# ArrayBuffer / TypedArrays

Buffers binarios de bajo nivel en JavaScript, con vistas tipadas sobre los mismos bytes.

**Ejemplos:**
1. JavaScript: `const ab = new ArrayBuffer(4); const view = new Uint32Array(ab);`.
2. JavaScript: `new DataView(ab).setInt32(0, 42);` — escribir con control de endianness.
3. Comando (Node.js REPL): `node -e "console.log(new Uint8Array(new ArrayBuffer(2)))"`.
