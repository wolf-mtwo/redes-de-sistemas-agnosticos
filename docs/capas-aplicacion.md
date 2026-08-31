# Capa de aplicación

Protocolos que usan directamente los programas: HTTP, MQTT, DNS, etc.

**Ejemplos:**

1. Comando — hablar HTTP (capa de aplicación)
```bash
curl https://example.com
```

2. JavaScript
```javascript
fetch('https://api.example.com');
```

3. Java — paquete `java.net.http`
```java
HttpClient.newHttpClient().send(request, BodyHandlers.ofString());
```
