# When to use GraphQL?

- Crosses a bounded Context
- Mostly domain
- Client is mobile, web, Distributed
- Client doesn't have common workflows
- If network caching is NOT important
- If server defiend client-caching is NOT important
- If reducing response payloads is a priority
- If care about reducing roundtrips and bandwidth

### GraphQL PROS and CONS

|PROS|CONS|
|----|----|
|Low network overhead|Complexity|
|Typed schema|Caching|
|Fits graph like data very well| Versioning|