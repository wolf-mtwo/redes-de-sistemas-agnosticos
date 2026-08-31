# Certificados digitales (PKI)

Un tercero de confianza (autoridad certificadora) garantiza que una clave pública pertenece a quien dice ser.

**Ejemplos:**

1. Comando — inspeccionar un certificado
```bash
openssl x509 -in certificado.pem -text -noout
```

2. Java
```java
Certificate cert = CertificateFactory.getInstance("X.509").generateCertificate(inputStream);
```

3. C#
```csharp
var cert = new X509Certificate2("certificado.pfx", "password");
```
