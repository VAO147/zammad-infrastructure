# zammad-devops-project


A production-oriented DevOps project built around Zammad, evolving from a local containerized deployment into an automated, secure, observable and cloud-ready platform.

# Project Overview

This project demonstrates the design, deployment, automation and evolution of a modern DevOps platform using Zammad as the application workload.
The project is intentionally developed in incremental phases, starting with a simple and reproducible local deployment and progressively introducing:
- Containerization
- Linux infrastructure
- Git and GitHub
- CI/CD
- Container registries
- Infrastructure as Code
- Kubernetes
- Cloud infrastructure
- Security
- Monitoring and observability
- Production-oriented operational practices
The goal is not simply to deploy Zammad, but to demonstrate the engineering practices required to operate a modern application platform.


# Architecture Evolution

The platform is being developed through five major stages.

Phase 1
Local Linux + Docker Compose
        │
        ▼
Phase 2
Custom Docker Image + Private Registry
        │
        ▼
Phase 3
CI Pipeline
Build → Test → Scan → Push
        │
        ▼
Phase 4
CD Pipeline
Kubernetes + Deploy → Validate → Rollback
        │
        ▼
Phase 5
Production-oriented Platform
Cloud + Terraform
Security + Observability


The architecture is intentionally evolving rather than being designed as a single complex system from the beginning.
This approach allows each technological decision to be understood, tested and documented before introducing additional complexity.