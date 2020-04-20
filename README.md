# Desafio 05
## Executando a API simpleweb com o Kubenetes

1. Faça a instalação do Minikube e Kubectl de acordo com o seu sistema operacional e seguindo a documentação do link: ```https://kubernetes.io/docs/tasks/tools/install-minikube/```

2. Copie os arquivos YAML para um diretório no servidor que está executando o Minikube

3. Execute o seguinte comando no diretório que contém os arquivos YAML: ```kubectl apply -f <diretorio>```

4. Por fim, abra seu navegador de preferência e digite: ```http://<ip-servidor-k8s:31515>```