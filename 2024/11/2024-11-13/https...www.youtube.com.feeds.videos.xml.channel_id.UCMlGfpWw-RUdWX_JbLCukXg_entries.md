# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## C++ Reflection Based Libraries to Look Forward To - Saksham Sharma - CppCon 2024
 - [https://www.youtube.com/watch?v=7I40gHiLpiE](https://www.youtube.com/watch?v=7I40gHiLpiE)
 - RSS feed: $source
 - date published: 2024-11-13T17:41:13+00:00

https://cppcon.org​
---

C++ Reflection Based Libraries to Look Forward To - Saksham Sharma - CppCon 2024
---

Our C++ code often contains violations of "Don't Repeat Yourself" (DRY). You write down enums, but then you also have to write their stringified version. You write down a class, but you have to expose every method / member in the class separately to be able to bind your class to a Python program (for example).

Reflection is (potentially / hopefully) showing up for C++26, having already been design approved by EWG, its chances are looking promising! This talk will discuss everything the basics of reflection, and we will lead up to three library ideas based on reflection, as a way to understand the massive impact this might have on the kind of libraries our ecosystem can provide, without relying on the core language to provide such abilities. The examples we will go through are:

Automatic python bindings
ABI hashing (hashing a type for efficient compatibility checking)
A bet

