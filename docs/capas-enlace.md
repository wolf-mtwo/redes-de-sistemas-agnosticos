# Capa de enlace

Direccionamiento por MAC address y entrega de tramas dentro de una misma red local.

**Ejemplos:**
1. Comando `arp -a` — ver la tabla de direcciones MAC de la red local.
2. Herramienta: Wireshark, filtrando por `eth.addr` para ver tramas Ethernet.
3. Java: `NetworkInterface.getByName("eth0").getHardwareAddress()` — leer la MAC address.
