# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## C++ Relocation - How to Achieve Blazing Fast Save and Restore and More! - Eduardo Madrid - CppCon 24
 - [https://www.youtube.com/watch?v=LnGrrfBMotA](https://www.youtube.com/watch?v=LnGrrfBMotA)
 - RSS feed: $source
 - date published: 2024-11-18T16:00:03+00:00

https://cppcon.org​
---

C++ Relocation - How to Achieve Blazing Fast Save and Restore and More! - Eduardo Madrid - CppCon 2024
---

Programming normal C++ leads to the use of dynamic memory, pointer chasing, and other issues that zap performance. Because there haven’t been practical solutions to those problems we seldom discuss them, creating the impression that they are unavoidable. Fortunately, the same C++ that binds us frees us to devise techniques centered around the concept of “relocatability” to solve those issues. We will explain what relocatability is and how to achieve it.

Consider the example of runtime polymorphism. You may want to have interfaces and implementations of interfaces. If your object refers to a “polymorphic” member, it normally cannot be implemented as a concrete sub-object, only as a base class pointer that points to a dynamically allocated instance of a derived class. This leads to millions of small objects dispersed throughout memory, all referencing on

