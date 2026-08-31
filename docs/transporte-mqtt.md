# MQTT

Protocolo pub-sub ligero (tópicos, QoS, broker central), diseñado para redes lentas o inestables.

**Ejemplos:**
1. Comando: `mosquitto_sub -h test.mosquitto.org -t sensores/temperatura`.
2. Comando: `mosquitto_pub -h test.mosquitto.org -t sensores/temperatura -m "23.5"`.
3. JavaScript: `mqtt.connect('mqtt://test.mosquitto.org').subscribe('sensores/temperatura')`.
