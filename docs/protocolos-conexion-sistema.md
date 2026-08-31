# Conexión entre dos computadoras a nivel de sistema

Establecer un canal de comunicación entre dos procesos usando el sistema operativo (sockets).

**Ejemplos:**

1. Java
```java
Socket socket = new Socket("example.com", 80);
```

2. C#
```csharp
using var cliente = new TcpClient("example.com", 80);
```

3. Comando — abrir una conexión TCP manual desde la terminal (netcat)
```bash
nc example.com 80
```
