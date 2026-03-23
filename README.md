# homelab-kubernetes

This repository documents my Kubernetes homelab built on Proxmox using Debian 12 virtual machines.

## Goal
- Learn Kubernetes in practice
- Build a small multi-node lab
- Test deployments, services, ingress and storage
- Document the setup so it can be recreated later

## Current setup
- Hypervisor: Proxmox
- Base OS: Debian 12
- Platform: Virtual machines
- Planned cluster size: 3 nodes
- Kubernetes distribution: k3s

## Planned nodes
- k8s-cp1
- k8s-w1
- k8s-w2

## VM specs
- 2 vCPU
- 4 GB RAM
- 32 GB disk

## Status
- [x] Created base VM
- [x] Installed Debian 12
- [ ] Install qemu-guest-agent
- [ ] Clone VM into 3 nodes
- [ ] Install k3s
- [ ] Join worker nodes
- [ ] Deploy first workload
