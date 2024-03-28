# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Writing Python Bindings for C++ Libraries: Easy-to-use Performance - Saksham Sharma - CppCon 2023
 - [https://www.youtube.com/watch?v=rB7c69Z5Kus](https://www.youtube.com/watch?v=rB7c69Z5Kus)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg
 - date published: 2024-03-27T16:04:11+00:00

https://cppcon.org/
---

Writing Python Bindings for C++ Libraries: Easy-to-use Performance - Saksham Sharma - CppCon 2023
https://github.com/CppCon/CppCon2023

The unix philosophy encourages writing small applications that compose well, and unix / linux / sh have provided us with nice chaining tools that let us achieve this. This works well enough, but chaining of processes makes it complicated to actually share memory space, library versions, and memory layouts of various objects. Working within a single programming language (Python for instance), we can script and keep local memory state and chain together things however we like. Think of numpy or pandas as examples.

In this talk we will discuss how we can use boost::python and friends to help us build our C++ libraries as dynamically linked libraries that can be exposed safely as python functions and objects in python programs. This will be done entirely in C++, with Python being the equivalent of a shell for us (helping

