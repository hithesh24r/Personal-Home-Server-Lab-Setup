# K3s Cluster Setup (3 Nodes)

## Nodes
- Master: 2 vCPU, 2GB RAM
- Worker-1: 2 vCPU, 2GB RAM
- Worker-2: 2 vCPU, 2GB RAM

## Installation

### Master Node
curl -sfL https://get.k3s.io | sh -
#### Check status:
sudo kubectl get nodes

#### Get join token:
sudo cat /var/lib/rancher/k3s/server/node-token

### Worker Nodes:
curl -sfL https://get.k3s.io | K3S_URL=https://<MASTER_IP>:6443 K3S_TOKEN=<TOKEN> sh -

## Verify Cluster:
kubectl get nodes
