# MessagePack

Formato binario "como JSON pero más chico y rápido", sin esquema previo.

**Ejemplos:**
1. JavaScript: `const buf = require('msgpack-lite').encode({nombre: "Ana"});`.
2. Java (librería msgpack-java): `MessagePack.newDefaultPacker(out).packString("Ana").close();`.
3. Comando: `msgpack-cli` o `mpv` para inspeccionar un archivo MessagePack desde la terminal.
