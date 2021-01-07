# Vagrant-Ansible Kubernetes cluster for HyperCloud test environment
## Prerequisites
* Vagrant
* Ansible

## Version info
* kubernetes 1.17.6
* calico 3.13

### Note
* 귀찮아서 crio 대신 docker 사용중
* 1 master, 2 worker
```
vagrant up #install
vagrant ssh master #master node
vagrant ssh node-1 #worker node-1
```
