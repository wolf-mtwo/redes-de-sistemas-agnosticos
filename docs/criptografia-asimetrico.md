# Cifrado asimétrico (RSA, ECC)

Un par de claves: lo que cifra la pública solo lo descifra la privada (y viceversa para firmar).

**Ejemplos:**
1. Comando: `openssl genrsa -out clave_privada.pem 2048` — generar un par de claves RSA.
2. Java: `KeyPairGenerator.getInstance("RSA").generateKeyPair()`.
3. C#: `RSA.Create()` y `Encrypt(datos, RSAEncryptionPadding.OaepSHA256)`.
