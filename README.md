# <p style="text-align: center">Vagrant VMs</p>

<div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 10px; text-align: center;">

  <img src="https://img.shields.io/badge/vagrant-%231563FF.svg?style=for-the-badge&logo=vagrant&logoColor=white" alt="Vagrant" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu" />
  <img src="https://img.shields.io/badge/cent%20os-002260?style=for-the-badge&logo=centos&logoColor=F0F0F0" alt="Cent OS" />

</div>

## Description

[Vagrant VMs](https://github.com/johanpham2711/vagrant-vms) with [Vagrant](https://developer.hashicorp.com/vagrant/)

by [Johan Pham](https://github.com/johanpham2711)

## Installation

Install Vagrant for Linux

```bash
$ sudo dnf update -y
$ sudo dnf config-manager --add-repo=https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
$ sudo dnf install vagrant -y
```

## Create the VMs

```bash
$ cd centos/

$ vagrant up
```

## Usage commands

```bash
# Check status
$ vagrant status
$ vagrant global-status

# SSH to VM
$ vagrant ssh

# Power off the VM
$ vagrant halt

# Reboot and apply new changes for the VM
$ vagrant reload

# Delete the VM
$ vagrant destroy

# Check list VM boxes
$ vagrant box list
```

