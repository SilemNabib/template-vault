---
tags:
- structural-pattern
- 
---
**Proxy** is a structural design pattern that lets you provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.

![[Pasted image 20241031231912.png]]


## Problem

You have a massive object that consumes a vast amount of system resources. You need it from time to time, but not always.

![[Pasted image 20241031232011.png]]

_The proxy disguises itself as a database object. It can handle lazy initialization and result caching without the client or the real database object even knowing._