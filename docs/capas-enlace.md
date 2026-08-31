# Capa de enlace

Direccionamiento por MAC address y entrega de tramas dentro de una misma red local.

**Ejemplos:**

1. Comando — ver la tabla de direcciones MAC de la red local
```bash
arp -a
```

2. Herramienta: Wireshark, filtrando por `eth.addr` para ver tramas Ethernet.

3. Java — leer la MAC address de una interfaz
```java
NetworkInterface.getByName("eth0").getHardwareAddress();
```
