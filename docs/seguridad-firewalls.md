# Firewalls y control de acceso

Filtrar qué tráfico entra o sale de una red según reglas (puertos, IPs, protocolos).

**Ejemplos:**
1. Comando: `iptables -A INPUT -p tcp --dport 22 -j ACCEPT` — permitir tráfico SSH.
2. Comando: `ufw allow 443/tcp` — abrir el puerto HTTPS en el firewall.
3. Comando: `netsh advfirewall firewall add rule name="HTTP" dir=in action=allow protocol=TCP localport=80` (Windows).
