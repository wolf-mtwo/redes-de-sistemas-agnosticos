# Construcción de protocolos que viajan por la red

Definir el formato de los mensajes propios que dos sistemas van a intercambiar sobre TCP/UDP.

**Ejemplos:**
1. C#: definir un mensaje propio como `[4 bytes longitud][N bytes payload]` y leerlo con `BinaryReader`.
2. Java: leer un protocolo de líneas de texto terminadas en `\n` con `BufferedReader.readLine()`.
3. Comando: `nc -l 9000` — levantar un servidor simple para probar un protocolo de texto propio.
