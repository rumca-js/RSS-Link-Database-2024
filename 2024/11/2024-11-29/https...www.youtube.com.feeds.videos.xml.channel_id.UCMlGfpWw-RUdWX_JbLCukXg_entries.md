# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Back to Basics: Function Call Resolution in C++ - Ben Saks - CppCon 2024
 - [https://www.youtube.com/watch?v=ab_RzvGAS1Q](https://www.youtube.com/watch?v=ab_RzvGAS1Q)
 - RSS feed: $source
 - date published: 2024-11-29T15:07:03+00:00

https://cppcon.org​
---

Back to Basics: Function Call Resolution in C++ - Ben Saks - CppCon 2024
---

When a C++ compiler encounters an expression like f(x, y), it must consider several language mechanisms to decide which function f the program will call. These mechanisms include name lookup, overload resolution, default function arguments, and template processing. Having a firm understanding of these mechanisms and how they interact will help you write user-friendly interfaces for you and your team. 

This session begins by reviewing each of these mechanisms individually. It then examines how those mechanisms interact, focusing on situations that are most likely to occur in practice. Some of the questions that we’ll consider are:

  - How does the compiler resolve calls on overloaded functions with implicit conversions on multiple arguments?
  - Why does the compiler apply implicit conversions when resolving calls to overloaded functions, but not when making calls to function templ

