## **Instrucciones**

*   Clonar este repositorio localmente
*   Abrir una shell y ejecutar el siguiente comando:

```plaintext
docker run --name nginx-ejercicio-1 -v //c/docker/nginx_ejercicio_1/html:/usr/share/nginx/html -d -p 8080:80 nginx:1.23.0
```

*   Se debe reemplazar el path "//c/docker/nginx\_ejercicio\_1/" por el path donde fue clonado este repositorio para que el mapeo se realice correctamente hacia el container.
*   Para probarlo ir al browser e ir a la URL localhost:8080