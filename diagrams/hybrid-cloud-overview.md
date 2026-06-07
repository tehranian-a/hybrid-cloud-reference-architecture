# Hybrid Cloud Overview Diagram

## Purpose

This diagram shows a sanitized hybrid cloud reference pattern connecting private cloud, Kubernetes operations, backup, observability, and public cloud governance concepts.

```mermaid
flowchart LR
    A["Private Cloud / VMware Cloud Foundation"] --> B["vSphere Clusters"]
    A --> C["NSX Network Segmentation"]
    A --> D["vSAN Storage"]

    B --> E["Kubernetes Platform"]
    E --> F["Application Workloads"]
    E --> G["Backup with Kasten"]

    D --> H["Backup Repository / Object Storage"]
    G --> H

    A --> I["Observability / AIOps"]
    E --> I
    F --> I

    J["Azure Landing Zone"] --> K["Identity and Governance"]
    J --> L["Policy and Cost Controls"]
    J --> M["Hybrid Connectivity"]

    M --> A
```

## Notes

This is a public reference diagram only.

It does not represent any specific production environment.
