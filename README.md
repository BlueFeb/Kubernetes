# Kubernetes
Install Kubernetes in Ubuntu, VirtualBox. (Following https://cla9.tistory.com/91?category=814452)

1. Install VirtualBox Ubuntu 
2. InstallDocker 
3. Setup Kubernetes Clusters  (Master, Work01, Work02)
4. Setup NFS
5. Install metallb
6. Install ingress-nginx 

1.1. Install VBox https://www.virtualbox.org/
1.2. Download Ubuntu https://ubuntu.com/#download
1.3. Setup Master Node
1.3.1 RAM > 2 GB
1.3.2 HDD > 20 GB
1.3.3 CPU > 2 cores (After setup, setting-> system -> processors)
1.3.4 Storage -> Controller IDE -> change to Ubuntu Image
1.3.5 Network -> Adapter 1 -> change to Bridge on the Adapter
1.3.6 Network -> Adapter 2 -> change to Host only adapter
1.4. Install Ubuntu on the Master node
