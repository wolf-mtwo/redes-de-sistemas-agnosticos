# Buffering y backpressure

Controlar la velocidad de los datos cuando el productor es más rápido que el consumidor.

**Ejemplos:**
1. JavaScript (Node.js): `stream.write(chunk)` devuelve `false` cuando el buffer interno está lleno (backpressure).
2. Java: `BufferedOutputStream` con un tamaño de buffer fijo para no saturar el destino.
3. Comando: `pv archivo.bin | comando_lento` — ver y limitar el flujo de bytes entre dos procesos.
