# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Hidden Overhead of a Function API - Oleksandr Bacherikov - CppCon 2024
 - [https://www.youtube.com/watch?v=PCP3ckEqYK8](https://www.youtube.com/watch?v=PCP3ckEqYK8)
 - RSS feed: $source
 - date published: 2024-11-26T15:07:03+00:00

https://cppcon.org​
---

Hidden Overhead of a Function API - Oleksandr Bacherikov - CppCon 2024
---

API design and code performance are some of the most discussed topics in the C++ community. However, surprisingly little is said about the fundamental element of programming where they meet: the function signature. As a result, overhead that can be incurred inside every function body and at every call site is not commonly recognized. Non-inlined function calls are places where the ABI specification comes into play, and its effect on the generated assembly doesn’t always match expectations, even on the common platforms.

In this talk, we’ll bridge the gap and provide a comprehensive list of performance pitfalls to be aware of when designing a function signature, including a compiler’s view on the frequently debated questions:

- returning by value or by output parameter;
- passing parameters by value or by reference;
- using abstractions that are commonly considered to have zero runtim

