# Construcción de protocolos que viajan por la red

Definir el formato de los mensajes propios que dos sistemas van a intercambiar sobre TCP/UDP.

**Ejemplos:**

1. C# — mensaje propio `[4 bytes longitud][N bytes payload]`
```csharp
int longitud = reader.ReadInt32();
byte[] payload = reader.ReadBytes(longitud);
```

2. Java — protocolo de líneas de texto terminadas en `\n`
```java
String linea = bufferedReader.readLine();
```

3. Comando — levantar un servidor simple para probar un protocolo de texto propio
```bash
nc -l 9000
```
