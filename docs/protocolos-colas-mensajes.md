# Colas de mensajes / eventos (tipo SQS, pub-sub)

Desacoplar al que produce un mensaje del que lo consume, usando una cola o un tema intermedio.

**Ejemplos:**
1. Comando: `aws sqs send-message --queue-url <url> --message-body "hola"` — enviar un mensaje a una cola SQS.
2. JavaScript: `sqsClient.send(new SendMessageCommand({ QueueUrl, MessageBody: "hola" }))`.
3. Java: `producer.send(new ProducerRecord<>("topico", "hola"))` — publicar un evento en Kafka (patrón pub-sub).
