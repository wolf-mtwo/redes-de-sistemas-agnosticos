# Capa de transporte

Entrega de datos entre procesos, con o sin garantía de orden y confiabilidad (TCP/UDP).

**Ejemplos:**

1. Java — conexión TCP
```java
Socket socket = new Socket(host, port);
```

2. C# — conexión UDP
```csharp
var udpClient = new UdpClient();
```

3. Comando — ver las conexiones activas por puerto
```bash
netstat -an
```
