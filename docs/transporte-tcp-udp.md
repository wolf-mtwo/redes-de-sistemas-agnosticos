# Envío y recepción de datos por TCP/UDP

TCP garantiza orden y entrega; UDP es más rápido pero no garantiza nada.

**Ejemplos:**

1. Java — TCP vs UDP
```java
Socket tcp = new Socket(host, port);
DatagramSocket udp = new DatagramSocket();
```

2. C# — TCP vs UDP
```csharp
var tcp = new TcpClient(host, port);
var udp = new UdpClient();
```

3. Comando — enviar datos por UDP desde la terminal (netcat)
```bash
nc -u example.com 9000
```
