# Marshalling / Unmarshalling

Términos usados sobre todo en llamadas remotas (RPC) para "empaquetar" y "desempaquetar" datos entre procesos o lenguajes distintos.

**Ejemplos:**

1. Java (RMI) — el runtime hace *marshalling* automático de los argumentos al llamar un método remoto
```java
ServicioRemoto servicio = (ServicioRemoto) Naming.lookup("rmi://host/servicio");
servicio.metodoRemoto(argumento); // argumento se serializa automáticamente
```

2. C# — marshalling de una struct a memoria nativa
```csharp
Marshal.StructureToPtr(estructura, puntero, false);
```

3. Comando — llamar un servicio gRPC, que hace marshalling/unmarshalling de protobuf internamente
```bash
grpcurl -plaintext localhost:50051 Servicio/Metodo
```
