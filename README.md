# Redes de Sistemas Agnósticos

Materia: Redes de Sistemas Agnósticos

> **Nota:** los ejemplos de cada tema están en C#, JavaScript o Java, dependiendo del ejemplo y la herramienta que se utilice.

## Contexto del curso

Materia que cubre la comunicación entre sistemas independientes de plataforma o lenguaje (agnósticos), a nivel de red y de datos.

## Introducción y definición de la asignatura

Redes de Sistemas Agnósticos es una asignatura que aborda cómo se comunican entre sí sistemas independientes de plataforma, fabricante o lenguaje de programación. Parte de los fundamentos de la representación de datos (binario, hexadecimal, buffers y serialización) y avanza por los protocolos de comunicación y el modelo de capas, hasta el transporte de datos en tiempo real mediante TCP/UDP, sockets para IoT y MQTT.

La asignatura incorpora la seguridad y la criptografía como componentes transversales de toda comunicación en red: autenticación, cifrado del canal, firmas digitales y certificados. Los ejercicios se desarrollan en C#, JavaScript y Java, y con herramientas de línea de comandos, de modo que el estudiante comprenda el principio de cada tecnología sin depender de una sola plataforma.

## Justificación respecto al perfil profesional

El ingeniero de software y de redes trabaja cada vez más en entornos donde conviven sistemas legados, servicios en la nube y dispositivos IoT de distintos fabricantes. Integrarlos exige dominar cómo viajan y se interpretan los datos entre ellos, una competencia que esta asignatura desarrolla de forma práctica y progresiva, desde el bit hasta el protocolo de aplicación.

En el contexto boliviano, donde instituciones públicas, bancos, cooperativas y sectores productivos como la minería y la agroindustria avanzan hacia la digitalización con infraestructura y conectividad heterogéneas, este perfil resulta especialmente necesario. La asignatura aporta al egresado la capacidad de diseñar soluciones de comunicación seguras, eficientes e interoperables, alineadas con las demandas reales del medio.

## Área profesional y su aporte en el contexto boliviano

Área de desempeño: **Ingeniería de Software / Redes**. Principales problemáticas que resuelve un profesional idóneo en esta área, en el contexto actual de Bolivia:

1. **Integración de sistemas aislados**: conectar bancos, cooperativas y gobiernos municipales con sistemas legados que no se hablan entre sí.
2. **Conectividad limitada**: mantener sistemas funcionando en zonas rurales con red inestable o de bajo ancho de banda.
3. **Seguridad en trámites digitales**: proteger datos de ciudadanos en servicios en línea (SIN, banca, municipios).
4. **IoT e industria**: integrar sensores y equipos de distintos fabricantes en minería, agroindustria y manufactura.

## Competencia central

Diseñar e implementar la comunicación segura de datos entre sistemas agnósticos (independientes de plataforma y lenguaje), desde su representación binaria hasta su transporte en red, para resolver problemas de integración, IoT y tiempo real en la Ing. de Software y Redes, con precisión técnica, seguridad y pertinencia al contexto profesional boliviano.

| Verbo de desempeño | Objeto conceptual | Finalidad | Condición de referencia-calidad |
|---|---|---|---|
| Diseñar e implementar | La comunicación segura de datos entre sistemas agnósticos, desde su representación binaria hasta su transporte en red | Resolver problemas de integración, IoT y tiempo real en la Ing. de Software y Redes | Con precisión técnica, seguridad y pertinencia al contexto profesional boliviano |

### Criterios (para el desempeño del estudiante)

- **C.1.-** Asimila e interpreta los fundamentos de binario, hexadecimal, buffers y serialización, para representar y leer datos entre sistemas distintos con precisión técnica.
- **C.2.-** Plantea y argumenta el diseño de un protocolo de comunicación sobre el modelo de capas, definiendo con coherencia el formato de sus mensajes y su transporte (TCP/UDP).
- **C.3.-** Crea o adapta una solución de transporte de datos en tiempo real (sockets, MQTT, eventos) para IoT, coherente con las condiciones de conectividad de su entorno.
- **C.4.-** Presenta y defiende un proyecto de comunicación entre sistemas agnósticos que integre seguridad y criptografía, mediante un trabajo de valor final.

### Evidencias (como se evalúa al estudiante)

- **E.1.-** Prueba diagnóstica (test) y ejercicios de conversión binario/hexadecimal y manejo de buffers.
- **E.2.-** Ejercicios de serialización y deserialización de valores y objetos (JSON, protobuf, binario personalizado).
- **E.3.-** Implementación funcional de un protocolo cliente-servidor y de un flujo en tiempo real (TCP/UDP, MQTT).
- **E.4.-** Registro de defensa del trabajo de valor final: proyecto con comunicación segura (TLS, cifrado, firmas) al 100%.

## Los 4 saberes

- **Ser:** actúa con ética y responsabilidad en el manejo de datos, comunicaciones y seguridad de las personas e instituciones.
- **Saber:** comprende binario, buffers, serialización, protocolos, el modelo de capas, transporte en tiempo real, seguridad y criptografía.
- **Hacer:** implementa comunicación entre sistemas en C#, JavaScript y Java, usando sockets, MQTT, formatos de serialización y cifrado.
- **Decidir:** elige y defiende el protocolo, formato y nivel de seguridad adecuados para cada problema de integración.

## Programa analítico (Redes de Sistemas Agnósticos)

### TEMA 1. FUNDAMENTOS DE LA COMUNICACIÓN Y REPRESENTACIÓN DE DATOS

**Contenido temático**
- 1.1. Capas del modelo de comunicación (8 capas)
- 1.2. Binario, hexadecimal y operaciones a nivel de bits
- 1.3. Endianness y codificación de caracteres
- 1.4. Buffers, byte streams y backpressure

### TEMA 2. SERIALIZACIÓN

**Contenido temático**
- 2.1. Serialización y deserialización de valores primitivos
- 2.2. Serialización y deserialización binaria de objetos
- 2.3. Formatos: JSON, XML, protobuf y MessagePack
- 2.4. Serialización personalizada y marshalling

### TEMA 3. PROTOCOLOS Y TRANSPORTE DE DATOS EN TIEMPO REAL

**Contenido temático**
- 3.1. Conexión entre sistemas y construcción de protocolos
- 3.2. Colas de mensajes, pub-sub y event listeners
- 3.3. TCP/UDP y sockets para IoT
- 3.4. MQTT y datos en tiempo real

### TEMA 4. SEGURIDAD Y CRIPTOGRAFÍA

**Contenido temático**
- 4.1. Autenticación, autorización y control de acceso
- 4.2. TLS/SSL, validación de entradas y ataques comunes
- 4.3. Cifrado simétrico y asimétrico, y hashing
- 4.4. Firmas digitales, intercambio de claves y certificados (PKI)

### Bibliografía (toda la materia)
- Tanenbaum, A. S. y Wetherall, D. J. *Redes de computadoras* (5.ª ed.). Pearson.
- Kurose, J. F. y Ross, K. W. *Redes de computadoras: un enfoque descendente* (7.ª ed.). Pearson, 2017.
- Kleppmann, M. *Designing Data-Intensive Applications*. O'Reilly, 2017.
- Stallings, W. *Cryptography and Network Security: Principles and Practice* (7.ª ed.). Pearson, 2017.

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

