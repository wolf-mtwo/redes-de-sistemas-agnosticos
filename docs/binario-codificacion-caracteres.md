# Codificación de caracteres

Cómo una secuencia de bytes se interpreta como texto (ASCII, UTF-8).

**Ejemplos:**

1. JavaScript — código ASCII de 'A' en hex
```javascript
Buffer.from('A').toString('hex'); // "41"
```

2. Java — obtener los bytes UTF-8 de un texto
```java
byte[] bytes = "A".getBytes(StandardCharsets.UTF_8);
```

3. Comando — convertir la codificación de un archivo
```bash
iconv -f UTF-8 -t ASCII archivo.txt
```
