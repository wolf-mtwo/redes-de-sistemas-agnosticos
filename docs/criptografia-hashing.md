# Hashing (SHA-256, MD5)

Convertir un dato en una huella de tamaño fijo; no se puede revertir al dato original.

**Ejemplos:**

1. Java
```java
byte[] hash = MessageDigest.getInstance("SHA-256").digest(datos);
```

2. JavaScript (Node.js)
```javascript
const hash = crypto.createHash('sha256').update('hola').digest('hex');
```

3. Comando — obtener el hash SHA-256 de un archivo
```bash
sha256sum archivo.txt
```
