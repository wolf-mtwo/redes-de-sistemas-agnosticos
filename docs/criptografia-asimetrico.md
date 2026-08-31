# Cifrado asimétrico (RSA, ECC)

Un par de claves: lo que cifra la pública solo lo descifra la privada (y viceversa para firmar).

**Ejemplos:**

1. Comando — generar un par de claves RSA
```bash
openssl genrsa -out clave_privada.pem 2048
```

2. Java
```java
KeyPair par = KeyPairGenerator.getInstance("RSA").generateKeyPair();
```

3. C#
```csharp
using var rsa = RSA.Create();
byte[] cifrado = rsa.Encrypt(datos, RSAEncryptionPadding.OaepSHA256);
```
