## Kubernetes Quick Start 


### install and run the command:

```
	git clone https://github.com/kevsersrca/kubernetes-vagrant-ansible-deployment.git k8s
	cd k8s
	
```

```
	vagrant up
```
and 3 vm created !

### Connect master node

```
	vagrant ssh k8s-master
```

### list nodes

```
	kubectl get nodes
```

if not viewing nodes, firstly run the command master node

```
	 kubeadm token create --print-join-command
```

and this output run the nodes


