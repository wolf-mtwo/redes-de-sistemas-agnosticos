# MessagePack

Formato binario "como JSON pero más chico y rápido", sin esquema previo.

**Ejemplos:**

1. JavaScript
```javascript
const buf = require('msgpack-lite').encode({ nombre: "Ana" });
```

2. Java (librería msgpack-java)
```java
MessagePack.newDefaultPacker(out).packString("Ana").close();
```

3. Comando — inspeccionar un archivo MessagePack desde la terminal
```bash
msgpack-cli cat archivo.msgpack
```
