# Cifrado simétrico (AES)

Una sola clave cifra y descifra; rápido, pero hay que compartir la clave de forma segura.

**Ejemplos:**
1. C#: `Aes.Create()` y `CreateEncryptor()` / `CreateDecryptor()`.
2. Java: `Cipher.getInstance("AES/GCM/NoPadding")`.
3. Comando: `openssl enc -aes-256-cbc -in archivo.txt -out archivo.enc`.
