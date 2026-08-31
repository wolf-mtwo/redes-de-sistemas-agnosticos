# Protocol Buffers (protobuf)

Formato binario de Google, definido por un esquema `.proto`, mucho más compacto que JSON/XML.

**Ejemplos:**
1. Comando: `protoc --java_out=. persona.proto` — generar clases Java desde un esquema `.proto`.
2. Java: `PersonaProto.Persona.newBuilder().setNombre("Ana").build().toByteArray()`.
3. C#: `Persona.Parser.ParseFrom(bytes)` — deserializar bytes protobuf a un objeto.
