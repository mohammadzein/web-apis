# When to used gRPC?

- inside a bounded context
- between subdomains
- Mostly commands

### gRPC PROS and CONS

|PROS|CONS|
|----|----|
|Fast|Schema|
|One client library|Error handling|
|Progress feedback|No native browser support|
|H2 / protocol buffers|Timeouts|

### Why gRPC?
- Client Library: one client library for popular languages.
- Protocol: HTTP/2.
- Message Format: protocol buffers.
- Server Streaming.
- Client Streaming.
- Server-Client Streaming.
