# Firmas digitales

Usar una clave privada para "firmar" un dato, y la pública para verificar que no fue alterado.

**Ejemplos:**

1. C#
```csharp
byte[] firma = rsa.SignData(datos, HashAlgorithmName.SHA256, RSASignaturePadding.Pkcs1);
```

2. Java
```java
Signature firma = Signature.getInstance("SHA256withRSA");
```

3. Comando
```bash
openssl dgst -sha256 -sign clave_privada.pem -out firma.sig archivo.txt
```
