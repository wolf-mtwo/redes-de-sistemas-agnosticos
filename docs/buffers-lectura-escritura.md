# Buffers de lectura/escritura

Contenedores de bytes usados para acumular datos antes de leerlos o escribirlos por completo.

**Ejemplos:**
1. JavaScript (Node.js): `const buf = Buffer.alloc(4); buf.writeUInt32BE(42, 0);`.
2. Java: `ByteBuffer buffer = ByteBuffer.allocate(4); buffer.putInt(42);`.
3. C#: `byte[] buffer = BitConverter.GetBytes(42);`.
