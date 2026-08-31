# Redes de Sistemas Agnósticos

Materia: Redes de Sistemas Agnósticos

## Contexto del curso

Materia que cubre la comunicación entre sistemas independientes de plataforma o lenguaje (agnósticos), a nivel de red y de datos.

## Temas y clases

### Capas del modelo de comunicación
- Capas del modelo de comunicación (8 capas: física, enlace, red, transporte, sesión, presentación, aplicación, usuario/negocio)

### Binario y hexadecimal
- [Ruta: de binario a serialización de objetos](docs/ruta-binario-a-serializacion.md)
- Representación binaria de datos
- Notación hexadecimal
- Operaciones a nivel de bits (AND, OR, XOR, shifts)
- Endianness (Big-endian / Little-endian)
- Codificación de caracteres (ASCII, UTF-8)

### Buffers
- Buffers de lectura/escritura (Read/Write Buffers)
- ArrayBuffer / TypedArrays
- Byte streams
- Buffering y backpressure

### Serialización
- [Serialización de valores primitivos](docs/serializacion-valores-primitivos.md)
- [Deserialización de valores primitivos](docs/deserializacion-valores-primitivos.md)
- [Serialización binaria de objetos](docs/serializacion-binaria-objetos.md)
- [Deserialización binaria de objetos](docs/deserializacion-binaria-objetos.md)
- JSON
- XML
- Protocol Buffers (protobuf)
- MessagePack
- Serialización binaria personalizada
- Marshalling / Unmarshalling

### Protocolos de comunicación
- Conexión entre dos computadoras a nivel de sistema
- Construcción de protocolos que viajan por la red
- Colas de mensajes / eventos (tipo SQS, pub-sub)
- Event listeners

### Transporte de datos en tiempo real
- Envío y recepción de datos por TCP/UDP
- Sockets para IoT
- MQTT
- Datos en tiempo real

### Seguridad
- Autenticación y autorización
- TLS/SSL
- Firewalls y control de acceso
- Validación de entradas
- Ataques comunes (MITM, spoofing, DoS)

### Criptografía
- Cifrado simétrico (AES)
- Cifrado asimétrico (RSA, ECC)
- Hashing (SHA-256, MD5)
- Firmas digitales
- Intercambio de claves (Diffie-Hellman)
- Certificados digitales (PKI)
