# Sockets para IoT

Conexiones ligeras y de bajo consumo entre dispositivos con recursos limitados.

**Ejemplos:**

1. C# — enviar lecturas de un sensor (.NET nanoFramework)
```csharp
var udpClient = new UdpClient();
udpClient.Send(datos, datos.Length, "192.168.1.50", 9000);
```

2. Java — recibir datos de un dispositivo IoT en una app Android
```java
DatagramSocket socket = new DatagramSocket(9000);
socket.receive(paquete);
```

3. Comando — probar un socket UDP hacia un dispositivo IoT
```bash
socat - UDP:192.168.1.50:9000
```
