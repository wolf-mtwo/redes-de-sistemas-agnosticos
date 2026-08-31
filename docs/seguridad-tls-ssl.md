# TLS/SSL

Cifrar el canal de comunicación para que nadie en medio pueda leer o alterar los datos.

**Ejemplos:**
1. Comando: `openssl s_client -connect example.com:443` — inspeccionar el certificado TLS.
2. Java: `HttpsURLConnection` valida automáticamente el certificado del servidor.
3. C#: `SslStream.AuthenticateAsClient("example.com")`.
