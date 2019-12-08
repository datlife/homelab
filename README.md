# Happy Garden HomeLab

🏡 - My garden for homegrown organic software projects. 🍇🍌🍈🍉🍊🍋.

## Motivation

* For fun.
* To understand Infrastructure behind my code.

## Overview

### Network Diagram

### Hardware

* ISP: Comcast - Xfiniti
* Router: 
* Switch:
* Physical Server:

### Software
* Soil (hypervisor): One of {Proxmox VE, VMWare ESXi, Hyper-V}.
* Equipments (automation tools): Ansible
* Seeds: K8s, Docker
* Fruits: juicy software products <3

## Setup

### Bare metal setup
* This is the fun, yet could-be-expensive part. I had to discipline my emotion to not overspend on latest flashy CPU / GPU. As of the end of 2019, here are the spec for my baremetal. It is indeed similar to a gaming PC. So what? It's my garden ;).
 
| Type      |Model                        |Spec                     | Comment                   |
|:----------|:----------------------------|:------------------------|:--------------------------|
| CPU       | AMD Ryzen 2700x             | 3.7 GHz 8-core 16-thread|                           |
| RAM       | Patriot 64GB DDR4           | 4x16GB DDR4 3200Hz      | ~~Upgrade to 64Gb if needed~~ <p color="red">Done</p> |
| DISK      | Samsung 970 EVO+ 512GB SSD  | Read/Write ~3GB/s       | Planning to use Ceph      |


### Software
* Install Proxmox.
* Automate config using Ansible
* 

## Build LOG(s)



## Reference:

1. This lab is awsome! https://github.com/bradfitz/homelab
2. Lab ideas : https://b3n.org/homelab-ideas/
3. Network Diagram: https://github.com/zimmertr/Network-Diagram
4. Hyper-converged Proxmox + Ceph Cluster : https://pve.proxmox.com/pve-docs/chapter-pveceph.html
5. Storage Option: https://chris-sanders.github.io/2018-01-29-single-node-ceph/
