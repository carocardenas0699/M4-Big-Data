## Reto 3 - Consultas Hive desde Docker

##### 1. Clonar el repositorio en el tienes el archivo de docker-compose

```
git clone https://github.com/carocardenas0699/M4-Big-Data.git
```

##### 2. Acceder a la carpeta donde se encuentra el docker-compose.ylm, hadoop-hive.env y hue-overrides.ini

```
cd M4-Big-Data
cd 'Reto 3'
```

##### 3. Levantar los contenedores

```
sudo docker-compose up -d
```

##### 4. Verificar que existan los contenedores

```
sudo docker ps
```

##### 5. Acceder al contenedor del servidor de Hive. Buscar en los contenedores el nombre del contenedor que tiene un hive-server en él (ej. reto3_hive-server_1)
```
sudo docker exec -it hive-server bash
```
##### 6. Inicializar Hive

```
hive
```
##### A partir de este momento se pueden realizar consultas desde la linea de comando!!
