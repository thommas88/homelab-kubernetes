# Proxmox VM setup

## Base VM
- Name: k8s-base
- OS: Debian 12
- Machine: q35
- BIOS: SeaBIOS
- SCSI controller: VirtIO SCSI single
- Qemu agent: enabled

## Disk
- Storage: local-lvm
- Bus: SCSI
- Size: 32 GB
- Cache: Default (No cache)
- Discard: enabled
- IO thread: enabled
- SSD emulation: enabled

## CPU
- Type: host
- Sockets: 1
- Cores: 2
- vCPUs: 2

## Memory
- 4096 MiB
- Ballooning: disabled

## Network
- Bridge: vmbr0
- Model: VirtIO
- Firewall: disabled
