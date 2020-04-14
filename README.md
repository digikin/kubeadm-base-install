# kubeadm-base-install
Script to install docker, set ip tables, add kubernetes repo and install kubelet/kubeadm/kubectl

## Description:
Got tired of manually installing and setting everything for a kubeadm setup on ubuntu virtual machines.  Script will run the get-docker install script, configure ip tables and install the latest kubelet/kubeadm/kubectl.  This just gets all the manual tasks out of the way.

## Instructions:
```
git clone https://github.com/digikin/kubeadm-base-install
cd kubeadm-base-install
sudo chmod +x kubeadm-install.sh
sudo ./kubeadm-install.sh
```

## Post install
You will need to finish the rest on your own by issuing the `kubeadm init` or `kubeadm join` as root to finish the kubernetes setup.  

### Help
Please further this script to finish everything for both debian and centos based machines.  I would appreciate any help.  
