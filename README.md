# XSKY CSI 1.0.0

[Container Storage Interface (CSI)](https://github.com/container-storage-interface/) driver, provisioner, and attacher for XSKY ISCSI and NFS.

## Overview

XSKY CSI plugins implement an interface between CSI enabled Container Orchestrator (CO) and XSKY cluster. It allows dynamically provisioning XSKY volumes and attaching them to workloads. Current implementation of Xsky CSI plugins was tested in Kubernetes environment (requires Kubernetes 1.11+), but the code does not rely on any Kubernetes specific calls (WIP to make it k8s agnostic) and should be able to run with any CSI enabled CO.

For details about configuration and deployment of ISCSI and NFS CSI plugins, see documentation in `docs/`.

For example usage of ISCSI and NFS CSI plugins, see examples in `examples/`.
