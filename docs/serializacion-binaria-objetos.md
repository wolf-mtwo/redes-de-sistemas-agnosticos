# Serialización binaria de objetos

Convertir un objeto (una estructura con varios campos) a una secuencia de bytes con un layout binario definido (offsets, tamaños y tipos fijos), en lugar de un formato de texto estructurado como JSON. Se usa cuando importa el tamaño y la velocidad (protocolos de red, IoT, formatos de archivo binario), a costa de perder la legibilidad humana que sí tienen JSON o XML.

Este proceso también se conoce como **parsing binario** o **binary encoding**: no es "estructuras de datos" (eso son formas de organizar datos en memoria, como listas o árboles), sino la codificación de un objeto como bytes según un layout acordado.

## Términos relacionados

- **Wire format / memory layout**: la definición de offsets, tamaños y tipos de un buffer binario.
- **Struct parsing / binary struct mapping**: mapear los campos de un objeto a bytes crudos (como un `struct` en C, o un `DataView`/`Buffer.writeUInt16BE` en JS).
- **Fixed-length record parsing**: cuando cada registro (objeto serializado) tiene un tamaño fijo y se repite.
- **TLV (Type-Length-Value)**: cuando el formato describe su propio tamaño/tipo dentro del buffer, en vez de offsets fijos.
- **Endianness / byte order**: relevante para escribir `uint16`/`uint32` correctamente (big-endian vs little-endian).
