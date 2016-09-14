Multi-core processors were introduced in 2006 to increase processing speed.
A multi-core processor has more than one CPU or core within the processor chip.

The diagram shows a dual-core processor but processors with more cores are available e.g.

| Number of cores | Common Name|
| :------: | :-----------: |
| 1 | Single-core |
| 2| Dual-core |
| 4| Quad-core|
| 5  |Penta-core|
| 8|Ocota(o)-core|
| 10 |Deca-core|

Multiple core processors can speed up processing because they allow:

- **Parallel processing** - the cores can work together on the same program.
- **Multitasking** - the cores can work on different programs at the same time.

However, not all programs will run twice as fast on a dual-core processor than on a single core one as the tasks required to be done may not be able to be carried out in parallel because they may be sequential so that one task requires output from a previous task and so the second task cannot start until the first one has finished.

In a multi-core processor the cores have their own L1 and L2 caches while the last level cache is usually shared by all the cores.