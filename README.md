# Provisioning kubernetes testing env with Vagrant
Provisioning multiple VMs for install and configure multinode kubernetes cluster in virtualbox using Vagrant.

## Guide 

### Download and Install virtualbox

Download and install virtualbox using this [link](https://www.virtualbox.org/wiki/Downloads) 

### Installing Vagrant

Follow this [guide](https://www.vagrantup.com/docs/installation)

---

### Provision VMs

Open command prompet and run below commands to do appropiate task.

Provision/Start VMs
> vagrant up

Stop VMs
> vagrant halt

Delete VMs
> vagrant destroy -f

---
### Access VMs

You can use public key in keys folder to allow secure ssh for root user.


