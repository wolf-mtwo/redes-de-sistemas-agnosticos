# Colas de mensajes / eventos (tipo SQS, pub-sub)

Desacoplar al que produce un mensaje del que lo consume, usando una cola o un tema intermedio.

**Ejemplos:**

1. Comando — enviar un mensaje a una cola SQS
```bash
aws sqs send-message --queue-url <url> --message-body "hola"
```

2. JavaScript
```javascript
await sqsClient.send(new SendMessageCommand({ QueueUrl, MessageBody: "hola" }));
```

3. Java — publicar un evento en Kafka (patrón pub-sub)
```java
producer.send(new ProducerRecord<>("topico", "hola"));
```
