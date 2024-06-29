# Source:ACCU Conference, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCJhay24LTpO1s4bIZxuIqKw, language:en

## Narrow Contracts and `noexcept` are Inherently Incompatible in C++ - John Lakos - ACCU 2024
 - [https://www.youtube.com/watch?v=VCwC1cvP8i0](https://www.youtube.com/watch?v=VCwC1cvP8i0)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCJhay24LTpO1s4bIZxuIqKw
 - date published: 2024-06-28T12:00:35+00:00

ACCU Membership: https://tinyurl.com/ydnfkcyn
---

Narrow Contracts and `noexcept` are Inherently Incompatible in C++ - John Lakos - ACCU 2024
---

A contract is a plain-language specification of whatever essential behavior a given function promises to deliver when invoked in contract. A function that has at least one syntactically valid combination of state and input for which the behavior is undefined has a precondition and is therefore said to have a narrow contract. The Lakos Rule effectively prohibits placing the `noexcept` specifier (introduced in C++11) on any function that would otherwise have a narrow contract.

This talk begins with a reprise of contracts, essential behavior, and preconditions. We’ll then go on to contrast two classic software design principles, Design by Contract and Liskov Substitutability, and then use the latter to explain how both backward compatibility and wide implementations benefit from scrupulously adhering to The Lakos Rule. We conclude that best 

