# Architecture Decisions

## Main Goals
- Support multiple OS (AIX, Linux, Windows)
- Combine fast local recovery and cheap long-term storage
- Ensure secure multi-site connectivity

## Chosen Stack
- Commvault: unified backup solution with legacy support
- Azure Blob + S3 Glacier: hybrid cloud for cost-effective tiering
- Ansible + Prometheus: automation and monitoring

## Justification
- Easy integration with existing infrastructure
- Scalable for multiple regions
- Enterprise-proven components
