# Intercambio de claves (Diffie-Hellman)

Dos partes acuerdan una clave secreta compartida sin transmitirla nunca directamente por la red.

**Ejemplos:**

1. Java
```java
KeyAgreement acuerdo = KeyAgreement.getInstance("DH");
```

2. C# — variante con curvas elípticas
```csharp
using var ecdh = ECDiffieHellman.Create();
```

3. Comando — generar parámetros Diffie-Hellman
```bash
openssl dhparam -out dhparams.pem 2048
```
