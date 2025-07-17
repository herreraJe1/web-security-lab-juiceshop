# Análisis de Vulnerabilidades – OWASP ZAP

## 🔍 Resultados del escaneo

| Riesgo | Ejemplo | Impacto |
|--------|---------|---------|
| Alto   | SQL Injection | Robo de datos, sesión comprometida |
| Medio  | CSP Header Not Set | Riesgo de XSS |
| Medio  | Session ID en URL | Secuestro de sesión |
| Bajo   | Private IP Disclosure | Evasión de controles |
| Bajo   | Timestamp Disclosure | Explotación de patrones |
| Informativo | Modern Web App | No requiere acción |

## 🔧 Remediación recomendada

| Vulnerabilidad | Acción técnica | Responsable |
|----------------|----------------|-------------|
| SQL Injection | Sentencias preparadas, validación | Programador |
| Session ID en URL | Evitar IDs en la URL | Programador |
| CSP Header Not Set | Implementar directiva CSP | Administrador |
| Anti-clickjacking Header | Añadir `X-Frame-Options: DENY` | Administrador |
