# Buffering y backpressure

Controlar la velocidad de los datos cuando el productor es más rápido que el consumidor.

**Ejemplos:**

1. JavaScript (Node.js) — `stream.write(chunk)` devuelve `false` cuando el buffer interno está lleno
```javascript
const puedeSeguir = stream.write(chunk);
if (!puedeSeguir) stream.once('drain', continuar);
```

2. Java — buffer de salida con tamaño fijo
```java
BufferedOutputStream out = new BufferedOutputStream(destino, 8192);
```

3. Comando — ver y limitar el flujo de bytes entre dos procesos
```bash
pv archivo.bin | comando_lento
```
