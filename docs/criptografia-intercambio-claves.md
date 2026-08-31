# Intercambio de claves (Diffie-Hellman)

Dos partes acuerdan una clave secreta compartida sin transmitirla nunca directamente por la red.

**Ejemplos:**
1. Java: `KeyAgreement.getInstance("DH")`.
2. C#: `ECDiffieHellman.Create()` — variante con curvas elípticas.
3. Comando: `openssl dhparam -out dhparams.pem 2048` — generar parámetros Diffie-Hellman.
