# Hybrid Cloud Reference Architecture

## About this repo

This repository contains sanitized reference architecture patterns for hybrid cloud, virtualization, Kubernetes, backup, and restricted enterprise environments.

It is designed to demonstrate architecture thinking, decision-making, trade-offs, and operational design patterns without exposing confidential enterprise information.

This is not a production environment export.
It does not contain real customer data, private IP addresses, hostnames, banking diagrams, internal screenshots, or confidential configuration.

## Purpose

The goal of this repository is to document practical architecture patterns based on enterprise infrastructure experience, including:

* VMware Cloud Foundation (VCF)
* VMware NSX network segmentation
* vSAN stretched cluster design
* Kubernetes platform operations
* Backup and recovery patterns
* Air-gapped registry and deployment patterns
* Azure landing zone and hybrid cloud governance concepts
* Observability and AIOps patterns

## Repository structure

```text
hybrid-cloud-reference-architecture/
  README.md
  adr/
    ADR-001-vsan-stretched-cluster.md
    ADR-002-nsx-network-segmentation.md
    ADR-003-backup-with-veeam-kasten-minio.md
    ADR-004-air-gapped-kubernetes-registry.md
    ADR-005-observability-aiops-pattern.md
  diagrams/
    hybrid-cloud-overview.md
  patterns/
    backup-and-recovery-pattern.md
    landing-zone-pattern.md
    restricted-environment-pattern.md
```

## What is an ADR?

An Architecture Decision Record (ADR) documents an important architecture decision, including:

* Context
* Decision
* Alternatives considered
* Trade-offs
* Consequences
* Operational notes

This format helps show not just what was built, but why it was designed that way.

## Important note

All content in this repository is public, sanitized, and generic.

The purpose is to demonstrate architecture capability, not to expose any real enterprise implementation.
