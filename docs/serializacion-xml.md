# XML

Formato de texto basado en etiquetas anidadas, común en sistemas empresariales y SOAP.

**Ejemplos:**
1. Java: `JAXBContext.newInstance(Persona.class).createMarshaller().marshal(persona, writer)`.
2. C#: `new XmlSerializer(typeof(Persona)).Serialize(writer, persona)`.
3. Comando: `xmllint --format archivo.xml` — formatear y validar un XML.
