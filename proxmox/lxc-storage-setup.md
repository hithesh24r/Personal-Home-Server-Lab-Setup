1. Create a new LXC container in Proxmox  
   - Ubuntu 22.04  
   - Attach large disk (1TB SSD in my case)  

2. Mount storage inside the LXC  
   mkdir /mnt/shared
   mount /dev/sdb /mnt/shared

3. Add entry to /etc/fstab:
/dev/sdb /mnt/shared ext4 defaults 0 0

4. Expose /mnt/shared as the common storage path for Docker services across VMs
---
