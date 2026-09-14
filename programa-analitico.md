# Programa Analítico del Módulo

## 1. Información General

| # | Campo | Valor |
|---|-------|-------|
| 1 | Módulo | Redes de Sistemas Agnósticos |
| 2 | Gestión | Gestión II/2026 |
| 3 | Nota Mínima de Aprobación | 61/100 |
| 4 | Nombre del Profesor | Rolf Mamani Mamani |
| 5 | Fecha (Inicio - Final) | 20/07/2026 - 04/12/2026 |
| 6 | Hrs. de clase | 57 horas reloj (38 sesiones de 1.5 h, lunes y miércoles 07:30-09:00) |

## 2. Presentación

La asignatura Redes de Sistemas Agnósticos forma parte del plan de estudios de la Licenciatura en Ingeniería en Sistemas de la Universidad Adventista de Bolivia, y aborda los fundamentos y mecanismos que permiten la comunicación fiable entre sistemas de software independientes de la plataforma, el lenguaje de programación o la arquitectura de hardware en la que se ejecutan.

A lo largo del módulo, el estudiante recorre el problema de la comunicación agnóstica desde sus capas conceptuales (física, enlace, red, transporte, sesión, presentación, aplicación y usuario/negocio) hasta su implementación práctica: representación binaria y hexadecimal de la información, manejo de buffers y flujos de bytes, técnicas de serialización y deserialización (JSON, XML, Protocol Buffers, MessagePack, formatos binarios personalizados), diseño de protocolos de comunicación propios, transporte de datos en tiempo real (TCP/UDP, sockets IoT, MQTT) y los mecanismos de seguridad y criptografía que garantizan la integridad, confidencialidad y autenticidad de la información transmitida.

El enfoque del módulo es eminentemente práctico: cada tema se desarrolla con ejemplos de código en C#, JavaScript o Java, según la herramienta o el escenario más representativo, de modo que el estudiante egrese con la capacidad de diseñar e implementar soluciones de comunicación interoperables entre sistemas heterogéneos.

## 3. Breve Descripción del Módulo

Redes de Sistemas Agnósticos es un módulo teórico-práctico que estudia la comunicación entre sistemas independientes de plataforma y lenguaje, cubriendo el modelo de capas de comunicación, la representación binaria y hexadecimal de datos, el manejo de buffers, las técnicas de serialización y deserialización de objetos, el diseño de protocolos de comunicación, el transporte de datos en tiempo real y los mecanismos de seguridad y criptografía necesarios para proteger la información transmitida. Se desarrolla mediante ejemplos prácticos en C#, JavaScript y Java aplicados a escenarios reales de interoperabilidad entre sistemas.

## 4. Objetivo General

> Diseñar e implementar soluciones de comunicación de datos entre sistemas heterogéneos, independientes de plataforma y lenguaje, garantizando la interoperabilidad, la integridad y la seguridad de la información transmitida, aplicando modelos de capas de comunicación, técnicas de serialización, protocolos de transporte y mecanismos criptográficos, conforme a buenas prácticas de la industria.

## 5. Objetivos Específicos

1. Analizar el modelo de capas de comunicación (física, enlace, red, transporte, sesión, presentación, aplicación y usuario/negocio) para comprender el flujo de datos entre sistemas.
2. Interpretar y manipular representaciones binarias y hexadecimales de datos, incluyendo operaciones a nivel de bits, endianness y codificación de caracteres.
3. Gestionar buffers, flujos de bytes y mecanismos de backpressure en la lectura y escritura de datos entre sistemas.
4. Aplicar técnicas de serialización y deserialización de datos primitivos y objetos en formatos estándar (JSON, XML, Protocol Buffers, MessagePack) y formatos binarios personalizados.
5. Diseñar protocolos de comunicación propios para el intercambio de mensajes entre sistemas, incluyendo colas de mensajes y arquitecturas orientadas a eventos.
6. Implementar transporte de datos en tiempo real mediante sockets TCP/UDP, MQTT y arquitecturas orientadas a IoT.
7. Aplicar mecanismos de seguridad (autenticación, autorización, TLS/SSL, firewalls, validación de entradas) para proteger sistemas de comunicación frente a ataques comunes.
8. Emplear técnicas de criptografía (cifrado simétrico y asimétrico, hashing, firmas digitales, intercambio de claves y certificados digitales) para garantizar la confidencialidad e integridad de la información transmitida.

## 6. Competencias y Resultados de Aprendizaje

**Competencia General:** Diseña e implementa mecanismos y protocolos de comunicación de datos entre sistemas agnósticos a la plataforma y al lenguaje de programación, para resolver problemas de interoperabilidad, integridad y seguridad de la información en entornos de red reales, utilizando modelos de capas de comunicación, técnicas de serialización, transporte en tiempo real y criptografía, con criterio ético y apego a estándares de la industria.

**Resultados de Aprendizaje.** Al finalizar el módulo, el estudiante:

1. Explica el flujo de datos entre sistemas aplicando el modelo de capas de comunicación.
2. Convierte y opera datos en representación binaria y hexadecimal, aplicando endianness y codificación de caracteres correctamente.
3. Implementa el manejo de buffers y flujos de bytes, controlando el backpressure en la transferencia de datos.
4. Serializa y deserializa objetos en formatos JSON, XML, Protocol Buffers, MessagePack y binarios personalizados, seleccionando el formato adecuado según el contexto.
5. Diseña protocolos de comunicación propios y arquitecturas de colas de mensajes/eventos para sistemas distribuidos.
6. Desarrolla soluciones de transporte de datos en tiempo real mediante TCP/UDP, sockets IoT y MQTT.
7. Protege sistemas de comunicación aplicando autenticación, TLS/SSL, firewalls y validación de entradas frente a ataques comunes.
8. Aplica algoritmos criptográficos (simétricos, asimétricos, hashing, firmas digitales, PKI) para garantizar la confidencialidad, integridad y autenticidad de la información.

## 7. Unidades de Aprendizaje

### I Unidad. Fundamentos de comunicación y representación de datos

| Fecha | Capacidades | Tema |
|---|---|---|
| 20/07/2026 | Identifica el objeto de estudio del módulo y el rol de las capas de comunicación | Presentación del módulo; Capas del modelo de comunicación (introducción) |
| 22/07/2026 | Describe los medios y señales de transmisión física de datos | Capa Física |
| 27/07/2026 | Explica el direccionamiento y control de acceso al medio | Capa de Enlace |
| 29/07/2026 | Explica el enrutamiento y direccionamiento lógico entre redes | Capa de Red |
| 03/08/2026 | Explica el control de flujo y la entrega confiable de datos | Capa de Transporte |
| 05/08/2026 | Distingue el establecimiento de sesiones y la representación/traducción de datos | Capas de Sesión y Presentación |
| 10/08/2026 | Relaciona los servicios de aplicación con las necesidades del negocio | Capa de Aplicación y Capa de Usuario/Negocio |
| 12/08/2026 | Reconoce la relación entre representación binaria y serialización de objetos | Binario y hexadecimal (introducción); Ruta: de binario a serialización |
| 17/08/2026 | Interpreta y construye representaciones binarias de datos | Representación binaria de datos |
| 19/08/2026 | Convierte valores entre notación binaria y hexadecimal | Notación hexadecimal |
| 24/08/2026 | Aplica operadores a nivel de bits y determina el orden de bytes de un sistema | Operaciones a nivel de bits; Endianness |
| 26/08/2026 | Aplica esquemas de codificación de caracteres; repasa la Unidad 1 | Codificación de caracteres; Repaso general |

### II Unidad. Buffers y Serialización

| Fecha | Capacidades | Tema |
|---|---|---|
| 31/08/2026 | Reconoce el rol de los buffers en la transferencia de datos | Buffers (introducción); Buffers de lectura/escritura |
| 02/09/2026 | Manipula buffers tipados en memoria | ArrayBuffer / TypedArrays |
| 07/09/2026 | Procesa flujos de datos como secuencias de bytes | Byte streams |
| 09/09/2026 | Controla el buffering y el backpressure en flujos de datos | Buffering y backpressure |
| 16/09/2026 | Reconoce la necesidad de serializar datos para su transmisión | Serialización (introducción); Serialización de valores primitivos |
| 21/09/2026 | Reconstruye valores primitivos a partir de datos serializados | Deserialización de valores primitivos |
| 23/09/2026 | Serializa objetos complejos en formato binario | Serialización binaria de objetos |
| 28/09/2026 | Reconstruye objetos complejos a partir de datos binarios | Deserialización binaria de objetos |
| 30/09/2026 | Aplica formatos de intercambio de datos basados en texto | JSON; XML |
| 05/10/2026 | Aplica formatos de serialización binaria estandarizados | Protocol Buffers (protobuf); MessagePack |
| 07/10/2026 | Diseña formatos de serialización binaria propios; repasa la Unidad 2 | Serialización binaria personalizada; Marshalling/Unmarshalling; Repaso general |

### III Unidad. Protocolos, Transporte en Tiempo Real, Seguridad y Criptografía

| Fecha | Capacidades | Tema |
|---|---|---|
| 12/10/2026 | Reconoce los elementos de una conexión entre sistemas | Protocolos de comunicación (introducción); Conexión entre dos computadoras a nivel de sistema |
| 14/10/2026 | Diseña protocolos de comunicación propios para la red | Construcción de protocolos que viajan por la red; Colas de mensajes/eventos (SQS, pub-sub) |
| 19/10/2026 | Implementa manejadores de eventos; reconoce los requisitos de la comunicación en tiempo real | Event listeners; Transporte de datos en tiempo real (introducción) |
| 21/10/2026 | Implementa comunicación mediante sockets TCP/UDP | Envío y recepción de datos por TCP/UDP |
| 26/10/2026 | Implementa comunicación mediante sockets para IoT y el protocolo MQTT | Sockets para IoT; MQTT |
| 28/10/2026 | Diseña soluciones de datos en tiempo real; reconoce los principios de seguridad en redes | Datos en tiempo real; Seguridad (introducción) |
| 04/11/2026 | Implementa mecanismos de autenticación, autorización y cifrado de transporte | Autenticación y autorización; TLS/SSL |
| 09/11/2026 | Configura controles de acceso y validación de entradas | Firewalls y control de acceso; Validación de entradas |
| 11/11/2026 | Identifica y previene ataques comunes; reconoce el rol de la criptografía | Ataques comunes (MITM, spoofing, DoS); Criptografía (introducción); Cifrado simétrico (AES) |
| 16/11/2026 | Aplica algoritmos de cifrado asimétrico y funciones hash | Cifrado asimétrico (RSA, ECC); Hashing (SHA-256, MD5) |
| 18/11/2026 | Aplica firmas digitales, intercambio de claves e infraestructura de certificados; repasa la Unidad 3 | Firmas digitales; Intercambio de claves (Diffie-Hellman); Certificados digitales (PKI); Repaso general |

### IV Unidad. Cierre e Integración

| Fecha | Capacidades | Tema |
|---|---|---|
| 23/11/2026 | Integra los conocimientos del módulo en una solución de comunicación agnóstica end-to-end | Desarrollo del proyecto integrador |
| 25/11/2026 | Sustenta técnicamente las decisiones de diseño de su solución | Avance y asesoría del proyecto integrador |
| 30/11/2026 | Comunica de forma técnica y profesional los resultados de su proyecto | Exposición de proyectos integradores |
| 02/12/2026 | Reflexiona sobre su proceso de aprendizaje y cierra el módulo | Retroalimentación general y cierre del módulo |

Nota: los feriados 14/09/2026 (Aniversario de Cochabamba) y 02/11/2026 (Todos Santos) ya están excluidos de estas fechas.

## 8. Indicadores de Evaluación

| N° | Indicador de Evaluación | Relacionado con |
|---|---|---|
| 1 | Identifica correctamente la capa del modelo de comunicación involucrada en un escenario de red dado | RA1 |
| 2 | Convierte con exactitud valores entre representación binaria, hexadecimal y decimal, aplicando el endianness correcto | RA2 |
| 3 | Implementa el manejo de buffers y flujos de bytes sin pérdida ni corrupción de datos, controlando el backpressure | RA3 |
| 4 | Serializa y deserializa objetos correctamente en al menos dos formatos distintos (texto y binario), justificando la elección del formato | RA4 |
| 5 | Diseña un protocolo de comunicación propio que cumple con los requisitos funcionales planteados (mensajes, colas o eventos) | RA5 |
| 6 | Implementa una solución de transporte de datos en tiempo real funcional (TCP/UDP, sockets IoT o MQTT) | RA6 |
| 7 | Aplica al menos dos mecanismos de seguridad (autenticación, TLS/SSL, firewall o validación de entradas) para mitigar una vulnerabilidad concreta | RA7 |
| 8 | Aplica correctamente un algoritmo criptográfico (simétrico, asimétrico, hashing o firma digital) adecuado al escenario planteado, justificando su elección | RA8 |

## 9. Metodología

La metodología del módulo combina exposición docente con práctica guiada y autónoma en laboratorio de cómputo. Cada sesión se organiza en tres momentos:

1. **Exposición conceptual** breve del tema por parte del docente, apoyada en ejemplos reales de la industria.
2. **Demostración en vivo (live coding)** de al menos un ejemplo práctico en C#, JavaScript o Java, según la herramienta más representativa del tema.
3. **Ejercicio guiado o práctica autónoma**, en la que el estudiante replica, modifica o extiende el ejemplo trabajado.

Se emplea además aprendizaje basado en proyectos: a partir de la III Unidad los estudiantes inician el diseño de un proyecto integrador de comunicación entre sistemas agnósticos, que consolidan y sustentan en la IV Unidad. Se promueve el trabajo colaborativo mediante la discusión de soluciones en pares o pequeños grupos, y el uso de herramientas de análisis de red (por ejemplo, Wireshark) para observar el comportamiento real de los protocolos estudiados. El uso de herramientas de inteligencia artificial (IA) es prioritario en el módulo: se promueve su uso responsable como apoyo al aprendizaje, la investigación y el desarrollo de las prácticas de programación.

## 10. Evaluación del Aprendizaje

| N° | Fecha | Estrategia - Descripción | Ponderado |
|---|---|---|---|
| 1 | Todas las sesiones | Asistencia y participación activa | 10.00 % |
| 2 | 27/08/2026 | Primer Parcial — Unidad 1 (Capas del modelo de comunicación; Binario y hexadecimal) | 20.00 % |
| 3 | 10/10/2026 | Segundo Parcial — Unidad 2 (Buffers; Serialización) | 20.00 % |
| 4 | 19/11/2026 | Examen Final — Unidad 3 (Protocolos; Transporte en tiempo real; Seguridad; Criptografía) | 25.00 % |
| 5 | 30/11/2026 | Proyecto Integrador — Unidad 4 (diseño, implementación y exposición de una solución de comunicación agnóstica) | 25.00 % |
| | | **Total** | **100.00 %** |

## 11. Referencias Bibliográficas

1. Kurose, J. F., y Ross, K. W. (2021). *Computer Networking: A Top-Down Approach* (8.ª ed.). Pearson.
2. Stevens, W. R., y Fall, K. R. (2011). *TCP/IP Illustrated, Volume 1: The Protocols* (2.ª ed.). Addison-Wesley.
3. Tanenbaum, A. S., y Wetherall, D. J. (2011). *Computer Networks* (5.ª ed.). Pearson.
4. Kleppmann, M. (2017). *Designing Data-Intensive Applications*. O'Reilly Media.
5. Stallings, W. (2020). *Cryptography and Network Security: Principles and Practice* (8.ª ed.). Pearson.
6. Schneier, B. (2015). *Applied Cryptography: Protocols, Algorithms, and Source Code in C* (20th anniversary ed.). Wiley.
7. Google. (s.f.). *Protocol Buffers Documentation*. https://protobuf.dev/
8. OASIS. (2019). *MQTT Version 5.0 Specification*. https://docs.oasis-open.org/mqtt/mqtt/v5.0/mqtt-v5.0.html
9. Internet Engineering Task Force. (1981-2018). *RFC 791 (Internet Protocol)*, *RFC 793 (TCP)*, *RFC 768 (UDP)*, *RFC 8446 (TLS 1.3)*. https://www.rfc-editor.org/
10. Mozilla Developer Network. (s.f.). *ArrayBuffer, TypedArray y JSON*. https://developer.mozilla.org/

## 12. Cláusula de Uso de Inteligencia Artificial (IA)

El uso de herramientas de inteligencia artificial (IA) es prioritario en el desarrollo del módulo. Se establecen los siguientes lineamientos para su uso responsable:

1. **Uso como apoyo prioritario:** las herramientas de IA (asistentes de código, chatbots, generadores de texto) se promueven activamente como apoyo al aprendizaje, la investigación y el desarrollo de las prácticas de programación en cada unidad del módulo.
2. **Comprensión exigida en clase:** dado que la metodología incluye demostración en vivo (live coding) y ejercicio guiado en cada sesión, el estudiante debe poder reproducir, modificar y justificar en clase cualquier solución que presente, haya usado o no asistencia de IA.
3. **Transparencia:** en el proyecto integrador (IV Unidad), el estudiante debe poder indicar qué partes de su solución se apoyaron en herramientas de IA y qué aportó él o ella al diseño.
4. **Responsabilidad sobre el resultado:** el estudiante es responsable de la corrección, seguridad y funcionamiento del código que entrega, independientemente de la herramienta usada para producirlo.
