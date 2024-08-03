# Source:ACCU Conference, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCJhay24LTpO1s4bIZxuIqKw, language:en

## C++ Exceptions Reduce Firmware Code Size - Khalil Estell - ACCU 2024
 - [https://www.youtube.com/watch?v=BGmzMuSDt-Y](https://www.youtube.com/watch?v=BGmzMuSDt-Y)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCJhay24LTpO1s4bIZxuIqKw
 - date published: 2024-08-02T12:00:07+00:00

ACCU Membership: https://tinyurl.com/ydnfkcyn
---

C++ Exceptions Reduce Firmware Code Size - Khalil Estell - ACCU 2024
---

Universally, exceptions are avoided in embedded systems C++ code, with a preference for error codes as out parameters, return values, or sum types like std::expected＜T,E＞. This avoidance stems from two main issues: the size of the exception handling runtime and the performance cost of throwing an exception versus returning a status code. But what if I were to tell you that exceptions are the better choice for producing smaller binaries than using the alternatives?

In this talk, I will explore the space cost of exceptions on a Cortex M4 microcontroller using the ARM GNU Toolchain, how to reduce the space cost, compare it to result types and identifying the point where result types become more costly in terms of code size than exceptions. I will delve into the performance of exceptions on the same Cortex M4 microcontroller, demonstrating how I managed to cut the 

