# Proxmox Homelab

Creating a data center for the web services project, so as to host it on-prem in my ubuntu server setup in an old Dell laptop.

## Steps involved

1. Setting up Proxmox
    - Flash proxmox VE
    - change the debian logind so that laptop doesn't turn off while lid close and proxmox is still working while laptop is sleeping
    - Make sure to update debian before creating any VMs.
    - Turn on the proxmox unstable updates for non production mode.
    - Turning disks into partition to make them RAID 10 zfs, for more redundancy.
    - 
