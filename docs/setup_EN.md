# Environment Setup – OWASP Juice Shop and ZAP

## 🧃 Juice Shop using Docker

1. Install Docker Desktop:  
   https://www.docker.com/products/docker-desktop

2. Pull the official Juice Shop image via terminal:
```bash
docker pull bkimminich/juice-shop

3. Run the container:
docker run --rm -p 3000:3000 bkimminich/juice-shop


4. Open the app in the browser:
http://localhost:3000

🔎 OWASP ZAP Setup
1. Download OWASP ZAP:
https://www.zaproxy.org/download/
2. Install Java SE 17 x64:
https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
3. Launch ZAP and confirm Java is properly detected
