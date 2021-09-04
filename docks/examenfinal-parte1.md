Examen Final – Parte 1  


Curso: Docker y Kubernetes Fecha: 03/09/2021  Profesor: Cedric Bardalez Hall  
  
Cree un archivo docker-compose.yaml con las siguientes especificaciones:  
1. El archivo deberá contener como mínimo la definición de 2 servicios – (3 puntos)  
2. El archivo deberá definir y montar un volumen como mínimo – (2 puntos)  
3. Deberá crear una network con driver bridge sobre la cual se lanzarán los contenedores  asociados a los servicios definidos anteriormente – (2 puntos)  
4. Deberá exponer al menos un puerto haciendo un mapeo con el host, de manera que el  servicio pueda ser consumido externamente – (1 puntos)  
5. Deberá especificar healthCheck o un script .sh para verificar que el otro servicio este  activo antes de lanzar el siguiente servicio – (3 puntos)  
6. Deberá especificar que se lance un contenedor estrictamente luego después de haber  lanzado el primero – (1 punto)  
7. Deberá asignar un profile a alguno de los servicios y el otro dejarlo como deafult – (1  punto)  
8. Deberá asignar a los contenedores una política de restart on-failure – (1 punto)  
9. Deberá subir sus imágenes a Docker-hub – (1 punto)  
10. Deberá pasar mínimo 2 variables de entorno a alguno de los contenedores – (1 punto)  
11. Deberá limitar los recursos, de CPU, Memory y Swap para cada uno de los contenedores  – (3 puntos)  
12. Adjuntar en el classroom archivos docker-compose.yaml y Dockerfiles de ser necesario.  También colocar el link de su repositorio en Docker-hub – (1 punto)  
  
Observación 1: Para más detalles sobre el método de calificación y el sistema de puntaje,  consultar:  
https://escaladenotas.cl/?nmin=1.0&nmax=7.0&napr=5.0&exig=73.0&pmax=100.0&paso=1.0 &orden=ascendente&fbclid=IwAR3Ee6W0cFxkGakSrf6Jn5jIvYTDM5tHWXf2Y7cH9uyzkWwW UdGf_AvULDk  
Observación 2: Tal y como fue acordado en clase, esta es la prueba 1 la cual consiste únicamente  de temas relacionados a Docker y corresponde a un 20% del puntaje total, posteriormente  tendemos una prueba 2 la cual contendrá temas exclusivamente relacionados a kubernetes y  representará el 80% del puntaje total.  