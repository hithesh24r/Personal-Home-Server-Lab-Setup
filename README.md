# 🏠 Home Server Lab

This repository documents my **self-hosted home server project** using **Proxmox, Docker, VPNs, and Kubernetes**.

---

## 🚀 Services
- Jellyfin (media server)
- Immich (photo backup)
- Servarr stack (Radarr, Sonarr, Prowlarr, Lidarr, Readarr)
- Nextcloud (personal cloud)
- Gluetun VPN
- Tailscale for remote access
- k3s cluster (Kubernetes playground)

---

## 📂 Repo Structure
docker/ # Docker Compose files
k3s/ # Kubernetes cluster setup
proxmox/ # Proxmox VM and LXC notes

---

## 🔒 Security
- All torrent-related services routed via **Gluetun VPN**  
- Remote access via **Tailscale** (no port forwarding needed)

---

## 🌟 Why This Project
This project gave me hands-on practice with:
- Proxmox virtualization
- Docker + Compose
- VPNs & Networking
- Kubernetes fundamentals

---

## 📌 Next Steps
- Monitoring (Prometheus + Grafana)
- Ansible/Terraform automation
- Expanding k3s workloads
