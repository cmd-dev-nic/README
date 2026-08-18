 # High-Performance Systems Engineer | Low-Latency C++

✉️ nmfx555@gmail.com | 🔗 www.linkedin.com/in/nikhil-mahajan-a30972299 |

---

## 🚀 Professional Summary
High-Performance Systems Engineer with **11+ years** of expertise architecting deterministic, ultra-low-latency runtime systems, custom memory sub-systems, and hardware-conscious multithreaded pipelines. Proven track record of eliminating jitter, optimizing cache topologies, and maximizing CPU throughput under strict real-time constraints. Translating deep mastery of **modern C++ (C++11–20)**, x86-64 microarchitecture, Linux kernel tuning, and lock-free concurrency into cutting-edge trading infrastructure for quantitative finance.

---

## 🛠️ Core Competencies & Technical Stack

* **Languages & Paradigms:** C++11–20, Python, x86-64 Assembly, Template Metaprogramming, Data-Oriented Design (DOD)
* **Low-Level Systems:** Move semantics, Object lifetime, Custom arenas/allocators, ABI stability, Zero-copy parsing, `constexpr`
* **CPU & Microarchitecture:** L1–L3 cache optimization, Cache line alignment, TLB efficiency, Branch prediction, Out-of-order execution, SIMD (AVX2/AVX-512), NUMA topology, False sharing mitigation
* **Linux Kernel & Systems:** System calls, Real-Time CFS scheduling, CPU pinning & affinity, `isolcpus`, Huge Pages (`hugetlbfs`), `mmap`, `epoll`, `perf` profiling, Hardware performance counters
* **Concurrency & Synchronization:** Spinlocks, Compare-And-Swap (CAS), Acquire-Release & Relaxed memory ordering, SPSC/MPSC/MPMC lock-free queues, Wait-free algorithms, ABA mitigation
* **Networking & I/O:** TCP/UDP tuning, Multicast feeds, NIC offloading, RSS, Polling vs. Interrupts, Kernel bypass, DPDK
* **Quantitative Finance Domain:** Limit Order Books (LOB), Price-Time priority matching, Market data feed handlers, Order execution gateways, FIX/binary protocols, Hardware risk checks, Tail latency reduction

---

## 💼 Professional Experience

### Core Systems Engineer (Engine & Runtime)
*Freelance | Mumbai | 2025 – Present (1.5 Years)*
* Engineered high-throughput, deterministic core sub-systems for proprietary multi-threaded execution runtimes, translating real-time processing constraints directly to ultra-low-latency financial architecture requirements.
* Designed and implemented custom arena and pool memory allocators to completely eliminate dynamic heap allocation overheads (`malloc`/`free`) in hot execution loops, drastically reducing cache misses and garbage-collection-style pauses.
* Applied Data-Oriented Design (DOD) principles, leveraging template metaprogramming and aggressive function inlining to maximize Instruction Cache (ICache) locality and minimize instruction footprint.
* Profiled core event loops utilizing hardware performance counters (`perf`, `perf stat`), successfully eliminating pipeline stalls, branch mispredictions, and cache line bounces.

### High-Performance Systems & Graphics Pipeline Engineer
*Freelance | Mumbai | 2020 – 2024 (5 Years)*
* Developed deterministic, high-frequency compute and data processing pipelines operating under strict sub-millisecond deterministic budgets (sub-11ms end-to-end, sub-2ms compute passes).
* Maximized instruction throughput of parallel hardware components using explicit SIMD vectorization (AVX-512) and low-level thread-to-hardware synchronisation primitives.
* Managed complex resource lifecycles, memory mapping (`mmap`), and streaming allocations to eliminate latency jitter, mirroring the deterministic execution requirements of high-frequency order gateways.
* Analysed hardware utilization bottlenecks, resolving Translation Lookaside Buffer (TLB) misses and optimizing memory layouts to prevent false sharing across multi-core execution threads.

### Real-Time Distributed Systems Engineer
*Freelance | Mumbai | 2015 – 2019 (5 Years)*
* Built robust, multi-threaded simulation loops and high-throughput networking layers handling high-frequency state synchronization over custom binary transport streams.
* Implemented lock-free Single-Producer Single-Consumer (SPSC) and Multi-Producer Single-Consumer (MPSC) data structures utilizing CAS operations and strict memory ordering (acquire-release semantics) for ultra-low-latency cross-thread event dispatch.
* Tuned Linux kernel affinity and thread pinning (`isolcpus`, `pthread_setaffinity_np`) to isolate core execution loops from OS jitter, context switches, and hardware interrupt interference.
* Optimized packet serialization/deserialization routines using zero-copy custom binary protocols to minimize payload sizes and network traversal latency.

---

## 🎓 Education

* **Indian Institute of Technology, Roorkee**
  *Postgraduate Certification, Artificial Intelligence* | 2023 – 2025
* **Mumbai University**
  *Bachelor of Business Administration, General Management (Finance)* | 2009 - 2012
