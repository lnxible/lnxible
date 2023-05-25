# lnxible

Automating the post-provisioning installation of a Linux workstation

## Prerequisites

### Grant user sudo-rights

`su root`
`/usr/sbin/usermod -aG sudo $USER`
`/usr/sbin/reboot`

### Install ansible from repo

#### Install Ansible
`sudo apt install -y ansible`
#### Create symbolic link to Python3 
`sudo ln -s /usr/bin/python3 /usr/bin/python`

## Machines

| Name | Brand | Type |
| --- | --- | --- |
| bookworm.lab.corp | VMware, Inc.| VMware Virtual Platform |
| desktop.lab.corp | Acer | Aspire M7811 |
| a1369.lab.home | Apple Inc. | MacBookAir4,2 |
| xps7590.lab.home | Dell Inc. | XPS 15 7590 |
