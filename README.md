# Pasos para levantar un WordPress

## 1. Buscamos información sobre WordPress
## 2. Buscamos la imagen de WordPress en Docker Hub.

- La página que deberemos de visitar es: [**Docker Hub**](https://hub.docker.com/_/wordpress)
- También podrémos visitar este [**Repositorio de Github**](https://github.com/docker/awesome-compose/tree/master/official-documentation-samples/wordpress/) en el cual podrémos encontrar más información

## 3. Buscamos la documentación de Docker
## 4. Creamos un Docker-Compose.yml

![img2](https://github.com/cristianmoreiraa/WordPress/blob/main/captura2.png)

- Breve explicación del código anterior:
    * Para almacenar la información usaremos `MariaDB`. Esta BDatos usa los puertos 3306 y 33060 para que el resto de los servicios se puedan comunicar con ella.
    * Usamos la imagen más actualizada de WordPress, plataforma que usaremos para la administración y creación de la página web.
    * WordPress usa el puerto 80.
## 5. Iniciamos el contenedor: `docker compose up -d`
- Tras iniciar el contenedor, abrimos nuestro buscador y bien escribimos `localhost` o `nuestra IP`, deberíamos de ver algo así

![img1](https://github.com/cristianmoreiraa/WordPress/blob/main/captura.png)