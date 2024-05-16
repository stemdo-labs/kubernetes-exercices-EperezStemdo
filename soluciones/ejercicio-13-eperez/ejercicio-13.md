# Ejercicio 13

### Crear congifMap

Utilizando el archivo ``service.yaml`` se crea el configMap con el comando 

```
kubectl apply -f service.yaml
```

![](./01-config-map-create.png)


### Crear Deployment

Utilizando el archivo ``deploy.yaml`` se crea el configMap con el comando 

```
kubectl apply -f deploy.yaml
```

![](./02-create-deploy.png)

### Crear servicio

Utilizando el archivo ``service.yaml`` se crea el configMap con el comando 

```
kubectl apply -f service.yaml
```

![](./03-create-svc.png)

### Verificar

Se verifica:

- Que el map se haya creado correctamente

![](./04-check-cm.png)

- Que el archivo index.html se encuentre dentro del pod
![](./check-volume.png)

- Que los endpoints del servicio coincidan con la ip del pod
![](./05-check-endpoints.png)

### Comprobar que funciona

![](06-minikube-service.png)

![](./07-it-works.png)