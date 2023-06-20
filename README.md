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


## Alejandro Losada Martínez ANGULAR FRONTEND