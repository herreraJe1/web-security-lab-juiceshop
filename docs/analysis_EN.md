# Vulnerability Analysis – OWASP ZAP

## 🔍 Scan Summary

| Risk | Example | Impact |
|------|---------|--------|
| High | SQL Injection | Data theft, session hijacking |
| Medium | CSP Header Not Set | XSS exposure |
| Medium | Session ID in URL | Session hijacking |
| Low | Private IP Disclosure | Control evasion |
| Low | Timestamp Disclosure | Pattern exploitation |
| Informative | Modern Web App | Informative marker only |

## 🔧 Recommended Remediation

| Vulnerability | Technical Action | Responsible |
|---------------|------------------|-------------|
| SQL Injection | Validate inputs, use prepared statements | Developer |
| Session ID in URL | Avoid session IDs in URLs | Developer |
| CSP Header Missing | Apply CSP on server | Administrator |
| Anti-clickjacking Header Missing | Add `X-Frame-Options: DENY` | Administrator |
