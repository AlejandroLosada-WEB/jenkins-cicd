<p align="center">
  <a href="https://www.jenkins.io/" target="blank"><img src="https://www.jenkins.io/images/logos/jenkins/Jenkins-stop-the-war.svg" width="200" alt="Node Logo" /></a>
</p>

# Crear deployment

```
kubectl apply -f deployment.yaml
```

# Crear servicio

```
kubectl apply -f service.yaml
```

# Ver nodos de kubernetes

```
kubectl get nodes -o wide
```

# Poner url

```
External IP
<ip-nodo>:30000
```

# Instalación de node Jenkins

```
Instalar plugin node.
En tools poner node y version de node instalar
Crear pipeline con jenkins.pipeline.groovy
Automaticamente se instalará node
```

# Instalación de gitlab

```
Instalar plugin gitlab.
```

# Instalación de slack

```
Instalar plugin slack.
Secret text auth
```


# Instalación de Sonarqube

```
helm repo add sonarqube https://SonarSource.github.io/helm-chart-sonarqube
helm repo update
kubectl create namespace sonarqube
helm upgrade --install -n sonarqube sonarqube sonarqube/sonarqube

Cambiar en kubernettes en la edición del servicio el type ClusterIp por Nodeport y añadir nodeport y el puerto
pass admin admin
```


# Documentación

```
aHR0cHM6Ly93d3cueW91dHViZS5jb20vd2F0Y2g/dj0tc2FDLVk3WndxYw==


aHR0cHM6Ly93d3cueW91dHViZS5jb20vd2F0Y2g/dj1yNXpoVHU2OTRLYw==
```


## Alejandro Losada Martínez ANGULAR FRONTEND