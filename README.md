# Redes de Sistemas Agnósticos

Materia: Redes de Sistemas Agnósticos

> **Nota:** los ejemplos de cada tema están en C#, JavaScript o Java, dependiendo del ejemplo y la herramienta que se utilice.

## Contexto del curso

Materia que cubre la comunicación entre sistemas independientes de plataforma o lenguaje (agnósticos), a nivel de red y de datos.

## Temas y clases

### [Capas del modelo de comunicación](docs/capas-modelo-comunicacion.md)
- [Física](docs/capas-fisica.md)
- [Enlace](docs/capas-enlace.md)
- [Red](docs/capas-red.md)
- [Transporte](docs/capas-transporte.md)
- [Sesión](docs/capas-sesion.md)
- [Presentación](docs/capas-presentacion.md)
- [Aplicación](docs/capas-aplicacion.md)
- [Usuario / negocio](docs/capas-usuario-negocio.md)

### [Binario y hexadecimal](docs/binario-hexadecimal.md)
- [Ruta: de binario a serialización de objetos](docs/ruta-binario-a-serializacion.md)
- [Representación binaria de datos](docs/binario-representacion.md)
- [Notación hexadecimal](docs/hexadecimal-notacion.md)
- [Operaciones a nivel de bits](docs/binario-operaciones-bits.md)
- [Endianness](docs/binario-endianness.md)
- [Codificación de caracteres](docs/binario-codificacion-caracteres.md)

### [Buffers](docs/buffers.md)
- [Buffers de lectura/escritura](docs/buffers-lectura-escritura.md)
- [ArrayBuffer / TypedArrays](docs/buffers-arraybuffer-typedarrays.md)
- [Byte streams](docs/buffers-byte-streams.md)
- [Buffering y backpressure](docs/buffers-backpressure.md)

### [Serialización](docs/serializacion.md)
- [Serialización de valores primitivos](docs/serializacion-valores-primitivos.md)
- [Deserialización de valores primitivos](docs/deserializacion-valores-primitivos.md)
- [Serialización binaria de objetos](docs/serializacion-binaria-objetos.md)
- [Deserialización binaria de objetos](docs/deserializacion-binaria-objetos.md)
- [JSON](docs/serializacion-json.md)
- [XML](docs/serializacion-xml.md)
- [Protocol Buffers (protobuf)](docs/serializacion-protobuf.md)
- [MessagePack](docs/serializacion-messagepack.md)
- [Serialización binaria personalizada](docs/serializacion-binaria-personalizada.md)
- [Marshalling / Unmarshalling](docs/serializacion-marshalling.md)

### [Protocolos de comunicación](docs/protocolos-comunicacion.md)
- [Conexión entre dos computadoras a nivel de sistema](docs/protocolos-conexion-sistema.md)
- [Construcción de protocolos que viajan por la red](docs/protocolos-construccion.md)
- [Colas de mensajes / eventos (tipo SQS, pub-sub)](docs/protocolos-colas-mensajes.md)
- [Event listeners](docs/protocolos-event-listeners.md)

### [Transporte de datos en tiempo real](docs/transporte-tiempo-real.md)
- [Envío y recepción de datos por TCP/UDP](docs/transporte-tcp-udp.md)
- [Sockets para IoT](docs/transporte-sockets-iot.md)
- [MQTT](docs/transporte-mqtt.md)
- [Datos en tiempo real](docs/transporte-datos-tiempo-real.md)

### [Seguridad](docs/seguridad.md)
- [Autenticación y autorización](docs/seguridad-autenticacion-autorizacion.md)
- [TLS/SSL](docs/seguridad-tls-ssl.md)
- [Firewalls y control de acceso](docs/seguridad-firewalls.md)
- [Validación de entradas](docs/seguridad-validacion-entradas.md)
- [Ataques comunes (MITM, spoofing, DoS)](docs/seguridad-ataques-comunes.md)

### [Criptografía](docs/criptografia.md)
- [Cifrado simétrico (AES)](docs/criptografia-simetrico.md)
- [Cifrado asimétrico (RSA, ECC)](docs/criptografia-asimetrico.md)
- [Hashing (SHA-256, MD5)](docs/criptografia-hashing.md)
- [Firmas digitales](docs/criptografia-firmas-digitales.md)
- [Intercambio de claves (Diffie-Hellman)](docs/criptografia-intercambio-claves.md)
- [Certificados digitales (PKI)](docs/criptografia-certificados.md)
