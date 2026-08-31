# Envío y recepción de datos por TCP/UDP

TCP garantiza orden y entrega; UDP es más rápido pero no garantiza nada.

**Ejemplos:**
1. Java: `Socket` para TCP vs `DatagramSocket` para UDP.
2. C#: `TcpClient` para TCP vs `UdpClient` para UDP.
3. Comando: `nc -u example.com 9000` — enviar datos por UDP desde la terminal (netcat).
