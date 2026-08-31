# Codificación de caracteres

Cómo una secuencia de bytes se interpreta como texto (ASCII, UTF-8).

**Ejemplos:**
1. JavaScript: `Buffer.from('A').toString('hex')` → `"41"` (código ASCII de 'A' en hex).
2. Java: `"A".getBytes(StandardCharsets.UTF_8)` — obtener los bytes UTF-8 de un texto.
3. Comando: `iconv -f UTF-8 -t ASCII archivo.txt` — convertir la codificación de un archivo.
