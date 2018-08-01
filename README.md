Kubernetes Local Services
=========================

Install various Kubernetes services on your local Kubernetes installation 

- Kubernetes Dashboard
- OpenFaaS
- More to come

Perquisites
-----------

Install Docker **Edge** version,
Follow instructions [here](https://store.docker.com/editions/community/docker-ce-desktop-mac) (MacOS), 
Enter Docker preferences, And make sure to activate Kubernetes.
![](docs/docker_kubernetes.png)

* The application assumes that file `~/.kube/config` created/appended is generated by Docker installation,
  If this is not the case and you have multiple kube config files,
  please make sure to copy relevant local configs to `~/.kube/config.local`

Installation
------------

Run
```bash
cp ~/.kube/config ~/.kube/config.local
./k8s-deployment.sh
```
