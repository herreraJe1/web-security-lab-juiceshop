# Configuración del Entorno – OWASP Juice Shop y ZAP

## 🧃 OWASP Juice Shop con Docker

1. Instalar Docker Desktop:  
   https://www.docker.com/products/docker-desktop

2. Descargar la imagen oficial desde terminal:
```bash
docker pull bkimminich/juice-shop

3. Ejecutar el contenedor:
```bash
docker run --rm -p 3000:3000 bkimminich/juice-shop

4. Abrir la aplicación en el navegador:
http://localhost:3000

 OWASP ZAP Setup
- Download OWASP ZAP:
https://www.zaproxy.org/download/
- Install Java SE 17 x64:
https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
- Launch ZAP and confirm Java is properly detected
