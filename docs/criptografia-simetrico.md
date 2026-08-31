# Cifrado simétrico (AES)

Una sola clave cifra y descifra; rápido, pero hay que compartir la clave de forma segura.

**Ejemplos:**

1. C#
```csharp
using var aes = Aes.Create();
aes.GenerateKey();
aes.GenerateIV();
```

2. Java
```java
Cipher cipher = Cipher.getInstance("AES/GCM/NoPadding");
```

3. Comando
```bash
openssl enc -aes-256-cbc -in archivo.txt -out archivo.enc
```
