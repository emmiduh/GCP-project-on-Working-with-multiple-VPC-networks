# GCP-project-on-Working-with-multiple-VPC-networks

In this project, I created several VPC networks and VM instances and test connectivity across the networks. Specifically, I created two custom mode networks (managementnet and privatenet) with firewall rules and VM instances, as shown in this network diagram:


![image](https://github.com/emmiduh/GCP-project-on-Working-with-multiple-VPC-networks/assets/35396053/fab5c61b-a91a-49ef-be0d-170c7248ac03)

## Objectives
In this lab, I performed the following tasks:

* Created custom mode VPC networks with firewall rules
* Created VM instances using Compute Engine
* Explored the connectivity for VM instances across VPC networks by pinging the internal and external IP addresses for mynet-eu-vm, managementnet-us-vm, and privatenet-us-vm from mynet-us-vm.
* Created a VM instance with multiple network interfaces in privatesubnet-us, managementsubnet-us, and mynetwork 
