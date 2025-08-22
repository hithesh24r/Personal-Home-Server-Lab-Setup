# VM Setup Notes

- **VM: Jellyfin**
  - Ubuntu 22.04
  - 2 vCPU, 4GB RAM
  - Docker + Compose installed
  - Storage mounted from `/mnt/shared/media`

- **VM: Immich**
  - Ubuntu 22.04
  - 2 vCPU, 4GB RAM
  - Storage mounted `/mnt/shared/photos`

- **VM: Servarr Stack**
  - Ubuntu 22.04
  - 2 vCPU, 4GB RAM
  - Connected to Gluetun VPN container

- **VM: Nextcloud**
  - Ubuntu 22.04
  - 2 vCPU, 4GB RAM
  - Storage mounted `/mnt/shared/data`

- **K3s Cluster**
  - Master: 2 vCPU, 2GB RAM
  - Worker-1: 2 vCPU, 2GB RAM
  - Worker-2: 2 vCPU, 2GB RAM
