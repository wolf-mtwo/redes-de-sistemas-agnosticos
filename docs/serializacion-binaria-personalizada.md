# Serialización binaria personalizada

Definir tu propio layout de bytes cuando ningún formato estándar se ajusta (tamaño, hardware legado, protocolos propietarios).

**Ejemplos:**
1. C#: escribir campo a campo con `BinaryWriter.Write(valor)` siguiendo un layout propio.
2. Java: `DataOutputStream.writeInt(valor)` / `writeUTF(texto)` en un orden acordado.
3. Comando: `xxd -g 1 archivo.bin` — verificar byte a byte que el layout personalizado se escribió bien.
