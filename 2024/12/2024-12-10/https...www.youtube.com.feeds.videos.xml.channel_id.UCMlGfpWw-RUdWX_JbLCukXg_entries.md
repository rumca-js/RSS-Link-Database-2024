# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Introduction to Wait-free Algorithms in C++ Programming - Daniel Anderson - CppCon 2024
 - [https://www.youtube.com/watch?v=kPh8pod0-gk](https://www.youtube.com/watch?v=kPh8pod0-gk)
 - RSS feed: $source
 - date published: 2024-12-10T15:07:04+00:00

https://cppcon.org​
---

Introduction to Wait-free Algorithms in C++ Programming - Daniel Anderson - CppCon 2024
---

If you've attended any talks about concurrency, you've no doubt heard the term "lock-free programming" or "lock-free algorithms". Usually these talks will give you a slide that explains vaguely what this means, but you accept that is is approximately (but not quite exactly) equal to "just don't use locks". More formally, lock-freedom is about guaranteeing how much progress your algorithm will make in a given time. Specifically, a lock-free algorithm will always make some progress on at least one operation/thread. It does not guarantee however that all threads make progress. In a lock-free algorithm, a particular operation can still be blocked for an arbitrary long time because of the actions of other contending threads. What can we do in situations where this is unacceptable, such as when we want to guarantee low latency for every operation on our data structure rathe

