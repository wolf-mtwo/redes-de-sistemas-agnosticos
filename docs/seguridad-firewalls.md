# Firewalls y control de acceso

Filtrar qué tráfico entra o sale de una red según reglas (puertos, IPs, protocolos).

**Ejemplos:**

1. Comando — permitir tráfico SSH
```bash
iptables -A INPUT -p tcp --dport 22 -j ACCEPT
```

2. Comando — abrir el puerto HTTPS en el firewall
```bash
ufw allow 443/tcp
```

3. Comando — abrir el puerto HTTP (Windows)
```bash
netsh advfirewall firewall add rule name="HTTP" dir=in action=allow protocol=TCP localport=80
```
