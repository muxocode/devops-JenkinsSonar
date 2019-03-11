# Integración continua con JENKINS + SONARQUBE
![TITULO](imgs/title.png "Tree example")
## URLs y repositorios
### Eviroment
Se puedes configurar los puertos y volúmenes según el archivo .env
### Urls
- *Jenkins* está configurado para levantarse en el puerto 8080. Por lo que la URL sería <IPMáquina>:8080, es decir localhost:8080
- *SonarQube* está configurado para levantarse ne el puerto 9000. Por lo que la URL sería <IPMáquina>:9000, es decir localhost:9000
### Volúmenes
Para la persistencia de datos, se ha enlazado con volúmenes NFS(Windows), que se han situado en *C:/docker_volumes*, de no existir las carpetas, el proceso de arranque las crea.
## Para amantes de Windows :-)
### Arrancar
Para arrancar basta con ejecutar el scripr *Up.bat* de la carpeta raíz.
### Parar
Para parar el componente basta con ejecutar el scripr *down.bat* de la carpeta raíz