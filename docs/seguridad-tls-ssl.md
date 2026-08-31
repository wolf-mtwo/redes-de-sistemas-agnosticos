# TLS/SSL

Cifrar el canal de comunicación para que nadie en medio pueda leer o alterar los datos.

**Ejemplos:**

1. Comando — inspeccionar el certificado TLS de un servidor
```bash
openssl s_client -connect example.com:443
```

2. Java — valida automáticamente el certificado del servidor
```java
HttpsURLConnection conexion = (HttpsURLConnection) url.openConnection();
```

3. C#
```csharp
await sslStream.AuthenticateAsClientAsync("example.com");
```
