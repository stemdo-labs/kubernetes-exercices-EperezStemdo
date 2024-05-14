# Ejercicio 9

### Creación del deployment redis-master

![](./create-deploy.png)

### Creación del servicio redis-master
![](./create-service.png)

### Creación de deployment redis-slave

Se define la variabloe de entorno `` GET_HOSTS_FROM`` para determinar de dónde recupera la información de los hosts. Por defecto siempre utiliza DNS a no ser que se especifique otro valor.

![](./redis-slave-deploy.png)

### Creación del servicio redis-slave

![](./redis-slave-service.png)

### Creación del deployment FrontEnd PHP




