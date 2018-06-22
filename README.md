![](./resources/freeOsRouting.jpg)
## What is it ?
Quagga is a free software routing suite that supports static and dynamic routing protocols.

The Quagga routing suite consists of 2 parts:

> zebra daemon

> routing processes (RIP,OSPF,BGP,IS-IS,Babel,OLSR,LDP,BFD)

The zebra daemon is a **abstraction layer** between the kernel and the running routing processes. Each routing protocol has its own specific daemon.

Quagga installed on a physical host acts as a dedicated router. Quagga updates the kernel routing table. It modifies interface IP addressing, sets static routes and enables dynamic routing.

## Installation

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```