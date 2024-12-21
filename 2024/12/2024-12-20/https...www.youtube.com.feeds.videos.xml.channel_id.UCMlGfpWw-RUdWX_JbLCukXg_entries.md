# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Guide to the C++ Filter View in C++ Programming - Nicolai Josuttis - CppCon 2024
 - [https://www.youtube.com/watch?v=c1gfbbE2zts](https://www.youtube.com/watch?v=c1gfbbE2zts)
 - RSS feed: $source
 - date published: 2024-12-20T15:07:04+00:00

https://cppcon.org​
---

Guide to the C++ Filter View in C++ Programming - Nicolai Josuttis - CppCon 2024
---

C++20 introduced "views" as easy-to-use building blocks for processing the elements and values of containers and ranges.
The filter view is one of the key views, because filtering collections of data to process only elements that satisfy a specific constraint or requirement is one of the most important use cases of dealing with ranges and views.

Unfortunately, the filter view is also one of the most surprising C++ standard views. Even for simple use cases, you can easily get: 
- Unexpected functional behavior 
- Surprising compile-time errors with cryptic error messages 
- Fatal runtime errors (without even noticing them)

There are reasons for the design of the filter view. For a successful filtering of elements you should know and understand the design and all of its consequences.

The talk will demonstrate all the issues with simple real-work examples and explain both th

