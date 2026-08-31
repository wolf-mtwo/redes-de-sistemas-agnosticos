# Endianness

Orden en que se almacenan los bytes de un valor de varios bytes (big-endian vs little-endian).

**Ejemplos:**
1. Java: `ByteBuffer.allocate(4).order(ByteOrder.BIG_ENDIAN).putInt(42)`.
2. C#: `BitConverter.IsLittleEndian` — verificar el orden de bytes del sistema.
3. Comando: `xxd -e archivo.bin` — mostrar los bytes de un archivo en formato little-endian.
