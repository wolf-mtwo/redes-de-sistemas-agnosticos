# Certificados digitales (PKI)

Un tercero de confianza (autoridad certificadora) garantiza que una clave pública pertenece a quien dice ser.

**Ejemplos:**
1. Comando: `openssl x509 -in certificado.pem -text -noout` — inspeccionar un certificado.
2. Java: `CertificateFactory.getInstance("X.509").generateCertificate(inputStream)`.
3. C#: `new X509Certificate2("certificado.pfx", "password")`.
