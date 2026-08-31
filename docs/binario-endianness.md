# Endianness

Orden en que se almacenan los bytes de un valor de varios bytes (big-endian vs little-endian).

**Ejemplos:**

1. Java
```java
ByteBuffer.allocate(4).order(ByteOrder.BIG_ENDIAN).putInt(42);
```

2. C# — verificar el orden de bytes del sistema
```csharp
bool esLittleEndian = BitConverter.IsLittleEndian;
```

3. Comando — mostrar los bytes de un archivo en formato little-endian
```bash
xxd -e archivo.bin
```
