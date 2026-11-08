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

Diseñar e implementar la comunicación segura de datos entre sistemas agnósticos (independientes de plataforma y lenguaje), desde su representación binaria hasta su transporte en red, para resolver problemas de integración, IoT y tiempo real en la Ing. de Software y Redes, conforme a estándares y buenas prácticas de comunicación en red, con rigor técnico, seguridad por diseño, interoperabilidad entre plataformas y pertinencia a la realidad tecnológica boliviana.

| Verbo de desempeño | Objeto conceptual | Finalidad | Condición de referencia-calidad |
|---|---|---|---|
| Diseñar e implementar | La comunicación segura de datos entre sistemas agnósticos, desde su representación binaria hasta su transporte en red | Resolver problemas de integración, IoT y tiempo real en la Ing. de Software y Redes | Conforme a estándares y buenas prácticas de comunicación en red, con rigor técnico, seguridad por diseño, interoperabilidad entre plataformas y pertinencia a la realidad tecnológica boliviana |

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

## Contenido temático por tema

### TEMA 1. FUNDAMENTOS DE LA COMUNICACIÓN Y REPRESENTACIÓN DE DATOS

**Contenido temático**

El tema parte del modelo de capas de comunicación (OSI, con una octava capa informal de usuario/negocio), que explica cómo dos sistemas de distinto fabricante o lenguaje pueden entenderse dividiendo la comunicación en niveles independientes: física, enlace, red, transporte, sesión, presentación, aplicación y negocio. Cada capa se explora con herramientas reales como `ping`, `tracert` y Wireshark, de modo que el estudiante ubique en qué nivel ocurre cada problema de red.

Luego se baja al nivel más básico de los datos: el sistema binario y el hexadecimal, las operaciones a nivel de bits (AND, OR, XOR y desplazamientos), el orden de los bytes (endianness) y la codificación de texto en ASCII y UTF-8. Estos conceptos son la base para leer y construir cualquier mensaje que viaje por una red.

El tema cierra con los buffers: contenedores de bytes en memoria (`ByteBuffer`, `Buffer`, `ArrayBuffer`), los flujos de bytes (byte streams) y el control de velocidad entre quien produce y quien consume datos (backpressure). Todo se practica con ejercicios en C#, JavaScript y Java.

**Bibliografía**
- Tanenbaum, A. S. y Wetherall, D. J. *Redes de computadoras* (5.ª ed.). Pearson.
- Kurose, J. F. y Ross, K. W. *Redes de computadoras: un enfoque descendente* (7.ª ed.). Pearson, 2017.

### TEMA 2. SERIALIZACIÓN

**Contenido temático**

La serialización resuelve un problema central de la comunicación entre sistemas: convertir datos en memoria a una forma que pueda almacenarse o transmitirse, y reconstruirlos después en el otro extremo. El tema distingue dos niveles: los valores primitivos (por ejemplo un entero o una fecha convertidos a texto) y los objetos completos, que se codifican como una secuencia de bytes con un layout definido de offsets, tamaños y tipos.

Se estudian los formatos más usados: JSON y XML como formatos de texto legibles, y Protocol Buffers y MessagePack como formatos binarios compactos. Para cada uno se comparan sus ventajas, su tamaño y su costo de procesamiento, con ejemplos de serialización y deserialización en distintos lenguajes.

Finalmente se aborda el diseño de formatos binarios propios, útiles en protocolos y dispositivos con recursos limitados, y el marshalling, es decir, el empaquetado de datos entre procesos y lenguajes distintos, como ocurre en las llamadas remotas (RPC).

**Bibliografía**
- Kleppmann, M. *Designing Data-Intensive Applications*. O'Reilly, 2017.

### TEMA 3. PROTOCOLOS Y TRANSPORTE DE DATOS EN TIEMPO REAL

**Contenido temático**

Este tema muestra cómo dos computadoras se conectan a nivel de sistema mediante sockets y cómo se define un protocolo propio: el formato de los mensajes, el modo de marcar su fin y el manejo de errores. A partir de ahí se presentan los patrones de comunicación desacoplada, como las colas de mensajes (tipo SQS), la publicación/suscripción (pub-sub) y los event listeners, que permiten que emisores y receptores no dependan directamente unos de otros.

Después se analizan los protocolos de transporte TCP y UDP, sus diferencias en confiabilidad y velocidad, y su uso en sockets para dispositivos IoT con recursos limitados. Se practica el envío y la recepción de datos con comandos como `netcat` y con código en C# y Java.

El tema concluye con MQTT, un protocolo ligero de mensajería por tópicos con broker pensado para redes lentas o inestables, y con otros canales de datos en tiempo real como WebSocket y SignalR. Se relaciona con la realidad boliviana, donde la conectividad en zonas rurales e industriales suele ser limitada.

**Bibliografía**
- Kurose, J. F. y Ross, K. W. *Redes de computadoras: un enfoque descendente* (7.ª ed.). Pearson, 2017.
- Tanenbaum, A. S. y Wetherall, D. J. *Redes de computadoras* (5.ª ed.). Pearson.

### TEMA 4. SEGURIDAD Y CRIPTOGRAFÍA

**Contenido temático**

La seguridad se presenta como un componente transversal de toda comunicación en red. Se estudia cómo verificar quién es el usuario (autenticación) y qué puede hacer (autorización) mediante tokens y roles, cómo filtrar el tráfico con firewalls y cómo validar toda entrada externa para evitar inyecciones y corrupción de datos.

Se explica el cifrado del canal con TLS/SSL y las amenazas más comunes: interceptación (MITM), suplantación (spoofing) y saturación (DoS), junto con herramientas para inspeccionarlas, como `openssl` y Wireshark.

La parte de criptografía cubre el cifrado simétrico (AES), el asimétrico (RSA y curvas elípticas) y las funciones hash (SHA-256). Se complementa con firmas digitales, intercambio de claves (Diffie-Hellman) y certificados digitales (PKI), que garantizan la autoría, la integridad y la confianza entre las partes.

**Bibliografía**
- Stallings, W. *Cryptography and Network Security: Principles and Practice* (7.ª ed.). Pearson, 2017.
- Tanenbaum, A. S. y Wetherall, D. J. *Redes de computadoras* (5.ª ed.). Pearson.

## Planificación del Aprendizaje Basado en Problemas (ABP)

Cada tema se trabaja a partir de un problema real del contexto boliviano. Fases de cada problema: (1) presentación del problema, (2) qué sabemos y qué necesitamos saber, (3) investigación y práctica guiada, (4) construcción de la solución y (5) presentación y reflexión.

**Tema 1. Fundamentos y representación de datos.** Un sistema legado de una cooperativa entrega registros binarios sin documentación. La pregunta guía es cómo se leen los bytes y se reconstruyen los campos, aplicando capas, offsets, endianness y buffers. El producto es un lector de buffer y un informe del layout descubierto (E.1).

**Tema 2. Serialización.** Un banco y un municipio intercambian datos en formatos distintos y se pierde información. La pregunta guía es qué formato elegir (JSON, XML, protobuf) y cómo serializar sin perder datos. El producto es un serializador/deserializador con una comparación de tamaño entre formatos (E.2).

**Tema 3. Protocolos y transporte en tiempo real.** Una planta agroindustrial o minera debe monitorear sensores con conectividad inestable. La pregunta guía es qué protocolo y transporte (TCP/UDP, MQTT) resisten las caídas de red. El producto es un cliente-servidor y un flujo publicador/suscriptor MQTT, probados con cortes de red (E.3).

**Tema 4. Seguridad y criptografía.** Un trámite digital expone datos de ciudadanos al viajar por la red. La pregunta guía es cómo proteger el canal y garantizar la autoría y la integridad de los datos. El producto es un canal TLS, el hash o firma de mensajes y un informe de amenazas (E.3).

**Proyecto integrador.** Un sistema que combina los cuatro temas. La pregunta guía es cómo diseñar una comunicación segura entre sistemas agnósticos de punta a punta. El producto es el proyecto final y su defensa (E.4).

## Tabla de especificaciones

Cada competencia (criterio C.1–C.4) corresponde a un tema, subdividido en 4 sub-temas. La ponderación suma 100 puntos (25 por competencia).

- **C.1. Representación de datos:** interpretar y manipular datos binarios, hexadecimales y buffers, para leer y construir mensajes entre sistemas distintos, con precisión técnica y conforme al modelo de capas.
- **C.2. Serialización:** serializar y deserializar valores y objetos en formatos de texto y binarios, para intercambiar datos entre plataformas y lenguajes, con integridad y eficiencia en el tamaño de los mensajes.
- **C.3. Protocolos y transporte en tiempo real:** diseñar e implementar protocolos y flujos de datos en tiempo real (TCP/UDP, sockets, MQTT), para integrar sistemas e IoT, de forma confiable ante conectividad limitada.
- **C.4. Seguridad y criptografía:** proteger la comunicación entre sistemas mediante autenticación, TLS, cifrado, hashing y firmas digitales, para garantizar confidencialidad, integridad y autoría, siguiendo estándares y buenas prácticas.

| Competencia | Tema | Sub-tema | Nivel | Evidencia | Pond. (%) |
|---|---|---|---|---|---|
| C.1 | 1. Fundamentos y representación de datos | 1.1. Capas del modelo de comunicación | Comprender | E.1 | 6 |
| C.1 | | 1.2. Binario, hexadecimal y operaciones a nivel de bits | Aplicar | E.1 | 7 |
| C.1 | | 1.3. Endianness y codificación de caracteres | Aplicar | E.1 | 6 |
| C.1 | | 1.4. Buffers, byte streams y backpressure | Aplicar | E.1 | 6 |
| C.2 | 2. Serialización | 2.1. Valores primitivos | Aplicar | E.2 | 6 |
| C.2 | | 2.2. Objetos binarios | Aplicar | E.2 | 7 |
| C.2 | | 2.3. JSON, XML, protobuf y MessagePack | Analizar | E.2 | 6 |
| C.2 | | 2.4. Serialización personalizada y marshalling | Crear | E.2 | 6 |
| C.3 | 3. Protocolos y transporte en tiempo real | 3.1. Conexión entre sistemas y construcción de protocolos | Aplicar | E.3 | 6 |
| C.3 | | 3.2. Colas de mensajes, pub-sub y event listeners | Comprender | E.3 | 6 |
| C.3 | | 3.3. TCP/UDP y sockets para IoT | Aplicar | E.3 | 7 |
| C.3 | | 3.4. MQTT y datos en tiempo real | Crear | E.3 | 6 |
| C.4 | 4. Seguridad y criptografía | 4.1. Autenticación, autorización y control de acceso | Comprender | E.4 | 6 |
| C.4 | | 4.2. TLS/SSL, validación de entradas y ataques comunes | Analizar | E.4 | 6 |
| C.4 | | 4.3. Cifrado simétrico y asimétrico, y hashing | Aplicar | E.4 | 6 |
| C.4 | | 4.4. Firmas digitales, intercambio de claves y PKI | Crear | E.4 | 7 |
| | | **Total** | | | **100** |

### Distribución según nivel cognitivo

| Taxonomía | I (C.1) | II (C.2) | III (C.3) | IV (C.4) | Nº ítems |
|---|---|---|---|---|---|
| Recordar | 0 | 0 | 0 | 0 | 0 |
| Comprensión | 1 | 0 | 1 | 0 | 2 |
| Aplicar | 1 | 1 | 2 | 1 | 5 |
| Analizar | 0 | 1 | 0 | 1 | 2 |
| Evaluar | 0 | 0 | 0 | 0 | 0 |
| Crear | 0 | 0 | 1 | 0 | 1 |
| **Totales** | **2** | **2** | **4** | **2** | **10** |

## Perfil de referencia para el examen sumativo

Ver [Perfil de referencia para el examen sumativo](docs/perfil-referencia-examen-sumativo.md).

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

