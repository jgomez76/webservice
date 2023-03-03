# webservice
Servicio web con: mysql 5.7, php 7-apache y phpmyadmin


```
Instalar docker
https://docs.docker.com/engine/install/

Instalar docker-compose
https://docs.docker.com/compose/install/

Ejecutar comando:
docker-compose up -d
```
La primera vez que ejecutemos el comando se descargarán las imagenes del mysql, php y phpmyadmin, y se crearan los 3 contenedores de docker. 
Para parar y eliminar los contenedores ejecutar: ```docker-compose down```

En la carpeta miweb tenemos un fichero de prueba index.php, que podemos sustituir por nuestro codigo web.

### Acceso página web: http://localhost/ 

### Acceso phpmyadmin: http://localhost:8080



