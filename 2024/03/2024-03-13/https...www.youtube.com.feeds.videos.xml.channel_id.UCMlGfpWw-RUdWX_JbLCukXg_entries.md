# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Designing Fast and Efficient List-like Data Structures - Yannic Bonenberger - CppCon 2023
 - [https://www.youtube.com/watch?v=stfEry0zz5E](https://www.youtube.com/watch?v=stfEry0zz5E)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg
 - date published: 2024-03-13T16:04:26+00:00

https://cppcon.org/
---

Designing Fast and Efficient List-like Data Structures - Yannic Bonenberger - CppCon 2023
https://github.com/CppCon/CppCon2023

Ordered data structures like lists, queues, or stacks consume large shares of compute and memory footprints of many applications. However, the design of such containers, including the containers in the C++ STL, has mostly stayed the same in the past few decades. With computer architectures and performance shifting towards multi-core with multiple layers of caching in the past 10-15 years, these fundamental data structures designed for single-core architectures often become performance hot spots. This talk describes the process of designing an ordered, list-like data structure well suited for modern CPUs starting with the naive approach for a linked list and ending with a design optimized for today's computers, showing a drastic reduction in cache misses and thus showing 2+ times better performance compared to their STL equiva

