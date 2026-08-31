# Ataques comunes (MITM, spoofing, DoS)

Conocer las amenazas típicas ayuda a diseñar defensas: interceptación (MITM), suplantación (spoofing) y saturación (DoS).

**Ejemplos:**
1. Herramienta: Wireshark para detectar tráfico ARP sospechoso (posible MITM/spoofing).
2. Comando: `dig example.com` y comparar con la IP esperada, para detectar DNS spoofing.
3. Comando: `curl -o /dev/null -s -w "%{http_code}\n" https://example.com` en un script de monitoreo, para notar caídas por un posible DoS.
