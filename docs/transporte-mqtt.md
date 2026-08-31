# MQTT

Protocolo pub-sub ligero (tópicos, QoS, broker central), diseñado para redes lentas o inestables.

**Ejemplos:**

1. Comando — suscribirse a un tópico
```bash
mosquitto_sub -h test.mosquitto.org -t sensores/temperatura
```

2. Comando — publicar en un tópico
```bash
mosquitto_pub -h test.mosquitto.org -t sensores/temperatura -m "23.5"
```

3. JavaScript
```javascript
const client = mqtt.connect('mqtt://test.mosquitto.org');
client.subscribe('sensores/temperatura');
```
