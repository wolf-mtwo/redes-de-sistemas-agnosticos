# Ruta: de binario a serialización de objetos

Progresión de temas para llegar a entender la serialización binaria de objetos, partiendo desde los fundamentos de binario.

1. **¿Qué es binario?** — sistema numérico de base 2, compuesto solo por bits (0 y 1).
2. **Notación hexadecimal** — representación compacta de binario (base 16), 1 dígito hex = 4 bits.
3. **Bytes** — agrupación de 8 bits; unidad básica de almacenamiento y transmisión de datos.
4. **Operaciones a nivel de bits** — AND, OR, XOR, shifts; manipular datos directamente en su representación binaria.
5. **Endianness** — orden en que se almacenan los bytes de un valor multi-byte (big-endian / little-endian).
6. **Codificación de caracteres** — cómo una secuencia de bytes representa texto (ASCII, UTF-8).
7. **Buffers** — contenedores de bytes en memoria (Read/Write Buffers, ArrayBuffer/TypedArrays) donde se acumulan y leen los datos binarios.
8. **[Serialización de valores primitivos](serializacion-valores-primitivos.md)** — convertir un valor simple (`int`, `Date`) a su representación en texto.
9. **[Serialización binaria de objetos](serializacion-binaria-objetos.md)** — convertir un objeto completo a una secuencia de bytes con un layout definido (offsets, tamaños, tipos).
10. **[Deserialización binaria de objetos](deserializacion-binaria-objetos.md)** — leer esos bytes de vuelta e interpretar el objeto original.
