# Fundamentos de Docker con Platzi

### Link del Curso
[Enlace aqui!](https://platzi.com/cursos/docker-fundamentos/)

### Primera Imagen del SitioWeb

Situarse en carpeta raiz y ejecutar comandos

```
# Construir imagen a partir del Dockerfile
docker build -t <nombre_imagen> .

# ---------------------------------

# Crear contenedor a partir de la imagen
docker run -it --rm -d -p 8080:80 --name <nombre_contenedor> <nombre_imagen>
```

* Para ver el resultado, podemos ir al http://localhost:8080/linktree.html y ver nuestra plantilla html. (Asegurarse de que nuestro contenedor este activo)