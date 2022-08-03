# kube-news

<h3>Criando imagem<br></h3>
cd ./src<br>
docker build -t vtmolina011/kube-news:v1 .<br><br>
<h3>Criando K8S<br></h3>
cd ./src/k8s<br>
kubectl create -f deployment.yaml<br>
