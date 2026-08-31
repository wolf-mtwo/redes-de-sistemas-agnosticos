# XML

Formato de texto basado en etiquetas anidadas, común en sistemas empresariales y SOAP.

**Ejemplos:**

1. Java
```java
JAXBContext.newInstance(Persona.class).createMarshaller().marshal(persona, writer);
```

2. C#
```csharp
new XmlSerializer(typeof(Persona)).Serialize(writer, persona);
```

3. Comando — formatear y validar un XML
```bash
xmllint --format archivo.xml
```
