# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Work Contracts - Rethinking Task Based Concurrency & Parallelism for Low Latency C++ - CppCon 2024
 - [https://www.youtube.com/watch?v=oj-_vpZNMVw](https://www.youtube.com/watch?v=oj-_vpZNMVw)
 - RSS feed: $source
 - date published: 2024-12-31T15:35:24+00:00

https://cppcon.org​
---

Work Contracts - Rethinking Task Based Concurrency and Parallelism for Low Latency C++ - Michael A Maniscalco - CppCon 2024
---

Task-based concurrency offers benefits in streamlining software and enhancing overall responsiveness. Numerous frameworks build upon this approach by furnishing abstractions that harness the capabilities of modern multi-core processors and distributed computing environments. These frameworks achieve this by facilitating the creation of task graphs, which simplify the management of task execution order and dependencies between tasks.

However, these frameworks are typically not well suited for use in low latency environments where every nanosecond matters, and any additional overhead introduced by managing task graphs can impact the system's ability to meet stringent latency requirements.

This presentation introduces Work Contracts, a novel approach specifically tailored for low-latency environments, which re-imagines both task-base

