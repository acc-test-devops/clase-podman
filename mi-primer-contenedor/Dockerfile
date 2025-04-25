# Imagen base de Nginx
FROM nginx:alpine

# Copiar nuestro archivo HTML al directorio público de Nginx
COPY index.html /usr/share/nginx/html/index.html

# Exponer el puerto 80
EXPOSE 80

# El contenedor ejecutara un comando al iniciar
CMD ["nginx", "-g", "daemon off;"]

