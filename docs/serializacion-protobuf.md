# Protocol Buffers (protobuf)

Formato binario de Google, definido por un esquema `.proto`, mucho más compacto que JSON/XML.

**Ejemplos:**

1. Comando — generar clases Java desde un esquema `.proto`
```bash
protoc --java_out=. persona.proto
```

2. Java
```java
PersonaProto.Persona.newBuilder().setNombre("Ana").build().toByteArray();
```

3. C# — deserializar bytes protobuf a un objeto
```csharp
Persona.Parser.ParseFrom(bytes);
```
