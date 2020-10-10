# When to use REST?

- Crosses a bounded Context
- Mostly domain
- Client is mobile, web, Distributed
- Client has common workflows
- If network caching is important
- If server defiend client-caching is important
- If reducing response payloads is not a priority
- If you dont care about reducing roundtrips and bandwidth

### REST PROS and CONS

|PROS|CONS|
|----|----|
|Decoupled cliend and server|No Single spec|
|API can evolve over time|Big payloads and "chattiness"|
|Reuses HTTP||

### **[REST vs RPC](./REST-vs-RPC.md)**
