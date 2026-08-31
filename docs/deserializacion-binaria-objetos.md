# Deserialización binaria de objetos

Leer una secuencia de bytes (ver [serialización binaria de objetos](serializacion-binaria-objetos.md)) e interpretarla según el layout acordado — qué offset corresponde a qué campo del objeto, con qué tipo y tamaño — para reconstruir el objeto original. También llamado **binary decoding** o **decodificación de tramas**.

## Ejemplo de layout

| Offset | Tamaño  | Tipo           | Descripción                                                   |
|--------|---------|----------------|----------------------------------------------------------------|
| 0      | 2 bytes | uint16         | Separador / estado (siempre 00 00 en los primeros registros)   |
| 2      | 73 bytes| ASCII          | Descripción del ítem, rellenada con espacios                   |
| 75     | 5 bytes | ASCII          | Unidad (pza, hr, m, etc.)                                       |
| 80     | 8 bytes | Binario        | Reservado / flags (muchos registros tienen ceros)               |
| 88     | 4 bytes | uint32 o float | Identificador o referencia                                      |
| 92     | —       | —              | Inicio del siguiente registro                                   |
