# Serialización binaria personalizada

Definir tu propio layout de bytes cuando ningún formato estándar se ajusta (tamaño, hardware legado, protocolos propietarios).

**Ejemplos:**

1. C# — escribir campo a campo siguiendo un layout propio
```csharp
using var writer = new BinaryWriter(stream);
writer.Write(valor);
```

2. Java — escribir campos en un orden acordado
```java
DataOutputStream out = new DataOutputStream(stream);
out.writeInt(valor);
out.writeUTF(texto);
```

3. Comando — verificar byte a byte que el layout personalizado se escribió bien
```bash
xxd -g 1 archivo.bin
```
