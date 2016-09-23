A major constraint in the rate of the fetch-decode-execute cycle is the main memory which has a speed far lower than that of the CPU.
Even if the clock rate is increased, speed of processing is limited by the speed of the memory. It is the weakest link in the chain.

A solution to this problem is to use very fast memory within CPU itself or very close to it.

This memory is used to store data that has been recently used or is likely to be frequently used. It is called a cache.

The CPU first checks the fast cache for the data it needs.  If it finds it doesn’t have to wait for it to be fetched from the much slower RAM.

As the cache memory becomes larger, the latency increases and so it becomes slower to find the required data.
The cache is therefore divided into different levels.  
The caches are located on the processor chip. The fastest is the Level 1 cache and is smaller than the Level 2 and Level 3 caches.
The L1 cache is checked first followed by the L2 and then L3 caches.

The diagram shows a processor with L1 and L2 caches.
The L1 cache is smaller and is within the CPU itself for faster data access.

![](.guides/img/cache.png)

Most CPUs have independent instruction and data caches. The data caches have to
be read and written to but the instruction caches just have to be read by the CPU.