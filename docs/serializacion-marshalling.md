# Marshalling / Unmarshalling

Términos usados sobre todo en llamadas remotas (RPC) para "empaquetar" y "desempaquetar" datos entre procesos o lenguajes distintos.

**Ejemplos:**
1. Java (RMI): el runtime hace *marshalling* automático de los argumentos al llamar un método remoto.
2. C#: `Marshal.StructureToPtr(struct, ptr, false)` — marshalling de una struct a memoria nativa.
3. Comando: `grpcurl` — llamar un servicio gRPC, que hace marshalling/unmarshalling de protobuf internamente.
