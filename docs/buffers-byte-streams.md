# Byte streams

Flujo continuo de bytes que se procesa por partes en vez de cargarlo todo en memoria.

**Ejemplos:**
1. Java: `InputStream in = Files.newInputStream(Path.of("archivo.bin"));`.
2. C#: `using var stream = File.OpenRead("archivo.bin");`.
3. Comando: `cat archivo.bin | xxd | head` — leer un stream de bytes por partes.
