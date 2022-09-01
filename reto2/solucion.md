# Solución del reto 2

1. Arrancar un contenedor que se llame `bbdd` y que ejecute una instancia de la imagen mariadb para que sea accesible desde el puerto 3306. Establecer variables de entorno.

        docker run --name bbdd 
        --env MARIADB_ROOT_PASSWORD=root 
        --env MARIADB_DATABASE=prueba 
        --env MARIADB_USER=invitado
        --env MARIADB_PASSWORD=invitado
        mariadb --port 3306

![Pantallazo_1](../reto2/img/pantallazo_1.png)
