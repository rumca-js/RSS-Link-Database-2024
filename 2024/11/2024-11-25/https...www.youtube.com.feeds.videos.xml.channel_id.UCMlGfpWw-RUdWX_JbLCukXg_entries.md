# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## C++ Coroutines and Structured Concurrency in Practice - Dmitry Prokoptsev - CppCon 2024
 - [https://www.youtube.com/watch?v=aPqMQ7SXSiw](https://www.youtube.com/watch?v=aPqMQ7SXSiw)
 - RSS feed: $source
 - date published: 2024-11-25T15:07:06+00:00

https://cppcon.org​
---

C++ Coroutines and Structured Concurrency in Practice - Dmitry Prokoptsev - CppCon 2024
---

C++20 coroutines present some exciting opportunities for organizing and simplifying concurrent logic, but they have proven challenging to integrate with production systems. Object lifetime and execution order issues can be difficult to manage, especially without guidance from well-established best practices. Practical use requires interoperability with existing event loops and with non-coroutine-aware components. While some experimental libraries have started to be released, the C++ “async ecosystem” is still young compared to many other languages.

We will describe our path through this thicket and introduce Corral, a new open-source concurrency framework for C++ that attempts to tame it. Corral is built around structured concurrency principles, so lifetimes and control flow are easier to reason about. It does not provide any opinionated I/O layer, so it can work wit

