# Ataques comunes (MITM, spoofing, DoS)

Conocer las amenazas típicas ayuda a diseñar defensas: interceptación (MITM), suplantación (spoofing) y saturación (DoS).

**Ejemplos:**

1. Herramienta: Wireshark para detectar tráfico ARP sospechoso (posible MITM/spoofing).

2. Comando — comparar contra la IP esperada, para detectar DNS spoofing
```bash
dig example.com
```

3. Comando — monitorear caídas por un posible DoS
```bash
curl -o /dev/null -s -w "%{http_code}\n" https://example.com
```
