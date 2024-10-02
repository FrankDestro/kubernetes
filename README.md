![icon](https://github.com/FrankDestro/Imagens-Readme/blob/main/icons8-kubernetes-48.png)

# kubernetes
Documentação do Curso Kubernetes Udemy 


## Instalação KubeCtl 

Install kubectl (terminal de linha de comando para manipular os cluster do kubernetes)

1. Open download folder
```js
cd Download
```
3. Download kubectl
```js
curl -LO https://dl.k8s.io/release/v1.24.2/bin/linux/amd64/kubectl
```
4. Install kubectl
```js
sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
```
6. Check installation
```js
kubectl version --client --output=yaml  
```

## Minikube 

Minikube é uma ferramenta que permite executar um cluster Kubernetes localmente, em um único nó, para facilitar o desenvolvimento e teste de aplicativos. É uma opção popular para desenvolvedores que estão aprendendo o Kubernetes ou precisam de um ambiente de desenvolvimento local.

Minikube install (Local Kubernetes cluster)

1. Open download folder
```js   
cd Download
```
3. Download minikube
```js
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd6
```
4. Set permission
```js
chmod +x minikube
```
4.Install minikube
```js
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64
```
5. Configure user group
```js
sudo usermod -aG docker $USER
```
6. Reboot Linux
```js
sudo reboot
```
7. Initialization
```js
minikube delete
```
```js
minikube start
```

### Orquestrador de container 


