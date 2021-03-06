# Cache

A hardware cache is usually implemented as static RAM (SRAM) that stores data so future requests for that data can be served faster. The data stored in a cache might be a result of an earlier computation, or the duplicate of data stored elsewhere.

A __cache hit__ occurs when the requested data can be found in a cache, while a __cache miss__ occurs when it cannot.

Cache hits are served by reading data from the cache, which is faster than recalculating the result or reading from a slower data store; thus, the more requests can be served from the cache, the faster the system performs.

A cache is an essential part of computing because data access patterns exhibit the __principle of locality__, also called __locality of reference__, which is a phenomenon when the same values, or the values in the related memory (storage) locations, are frequently accessed. There are two basic types of reference locality:
- __temporal locality__ refers to the reuse of specific data within a relatively small time duration: the data, that has been recently accessed, is requested again.
- __spatial locality__ refers to the use of data from within relatively close storage locations: the data, physically stored near the location of the previously accessed data, is requested.
- __sequential locality__ is a special case of spatial locality that occurs when data is arranged and accessed linearly, as in an array. Therefore, organizing data in an array-like structures results in the top performance.


There is an inherent trade-off between size and speed (given that a larger resource implies greater physical distances) but also a tradeoff between expensive, premium technologies (such as SRAM) vs cheaper, easily mass-produced commodities (such as DRAM or hard disks).

The buffering provided by a cache benefits both bandwidth and latency:

- Latency   
A larger resource incurs a significant latency for access – e.g. it can take hundreds of clock cycles for a modern 4 GHz processor to reach DRAM. This is mitigated by reading in large chunks, in the hope that subsequent reads will be from nearby locations. Prediction or explicit prefetching might also guess where future reads will come from and make requests ahead of time; if done correctly the latency is bypassed altogether.

- Throughput   
The use of a cache also allows for higher throughput from the underlying resource, by assembling multiple fine grain transfers into larger, more efficient requests. In the case of DRAM, this might be served by a wider bus. Imagine a program scanning bytes in a 32bit address space, but being served by a 128bit off chip data bus; individual uncached byte accesses would only allow 1/16th of the total bandwidth to be used, and 80% of the data movement would be addresses. Reading larger chunks reduces the fraction of bandwidth required for transmitting address information.