# Mini Homelab Infrastructure

## Overview

This repository documents the design, configuration, deployment, and maintenance of my personal mini homelab.

The project is built around Debian Linux, OpenMediaVault, and Docker, with the goal of creating a centralized environment for network services, storage management, monitoring, and infrastructure experimentation.

## Infrastructure

| Component | Technology |
|---|---|
| Operating System | Debian Linux |
 OpenMediaVault |
| Containerization | Docker |
| Container Deployment | Docker Compose |
| DNS Filtering | Pi-hole |
| Network Monitoring |

## Architecture

The infrastructure is organized into three main layers:

1. **Operating System:** Debian provides the underlying Linux environment.
2. **Storage Management:** OpenMediaVault manages storage, filesystems, and network shares.
3. **Application Layer:** Docker runs containerized services such as Pi-hole and Uptime Kuma.

## Services

- Pi-hole: Network wide DNS filtering and ad blocking.
- Additional services will be documented as they are deployed.

## Documentation

- Hardware specifications
- Debian installation and configuration
- OpenMediaVault setup
- Docker installation and management
- Individual service deployments
- Network configuration
- Maintenance and troubleshooting

## Project Goals

- Develop practical Linux system administration skills.
- Gain experience with Docker and containerization.
- Understand network services and DNS management.
- Build experience with NAS and storage administration.
- Develop infrastructure monitoring and maintenance skills.
- Experiment with networking and cybersecurity technologies.