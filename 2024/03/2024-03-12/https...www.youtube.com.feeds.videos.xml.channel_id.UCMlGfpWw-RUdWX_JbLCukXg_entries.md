# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Iteration Revisited: A Safer Iteration Model for Cpp - Tristan Brindle - CppCon 2023
 - [https://www.youtube.com/watch?v=nDyjCMnTu7o](https://www.youtube.com/watch?v=nDyjCMnTu7o)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg
 - date published: 2024-03-12T16:04:18+00:00

https://cppcon.org/
---

Iteration Revisited: A Safer Iteration Model for Cpp - Tristan Brindle - CppCon 2023
https://github.com/CppCon/CppCon2023

“Safety” is the word on everyone’s lips at the moment. Unfortunately for C++ programmers, one of our most fundamental abstractions — iterators — are fraught with danger. Prone to out-of-bounds memory accesses, unexpected invalidation and dangling, iterators are a UB minefield in which even experts can find themselves in trouble.
Fortunately there is something we can do about it.

In this talk we’ll look at an alternative, safer abstraction for iterating over sequences and introduce Flux, a new C++20 library implementing these ideas. We’ll see how Flux retains all of the power and flexibility of the existing STL, but greatly reduces the potential for UB through careful design and implementation choices — all while offering compatibility with existing code. We’ll also take a look at performance and examine the cost of universal boun

