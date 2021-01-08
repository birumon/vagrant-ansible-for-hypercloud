# Vagrant-Ansible for HyperCloud
## Kubernetes test environment for HyperCloud using Vagrant & Ansible

## Prerequisites
1. VirtualBox
```
$ apt install virtualbox
```
2. Vagrant
```
$ wget https://releases.hashicorp.com/vagrant/2.2.7/vagrant_2.2.7_x86_64.deb
$ dpkg -i vagrant_2.2.7_x86_64.deb
```
3. Ansible
```
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```

## Version info
* Ubuntu-18.04
* Kubernetes-1.17.6
* Calico-3.13

### Note
* Using docker instead of crio 
* 1 master, 2 worker
```
vagrant up #install
vagrant ssh master #master node
vagrant ssh node-1 #worker node-1
```
