# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Behavioral Modeling in HW/SW Co-design Using C++ Coroutines - Jeffrey Erickson, Sebastian Schoenberg
 - [https://www.youtube.com/watch?v=KmLunUoBcQk](https://www.youtube.com/watch?v=KmLunUoBcQk)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg
 - date published: 2024-03-28T16:04:15+00:00

https://cppcon.org/
---

Behavioral Modeling in HW/SW Co-design Using C++ Coroutines - Jeffrey Erickson & Sebastian Schoenberg - CppCon 2023
https://github.com/CppCon/CppCon2023

Faced with the challenge of modeling a hardware IP that is controlled by a processor running C code, we developed two key methodologies that we want to share with the C++ community. The first is “Register Hooking”, where we use the preprocessor to alter the behavior of primitive data type interactions to allow for a model interaction without extensive code alteration. The second methodology is the use of coroutines to define side effects through behavioral models, which constitutes the majority of this talk.

Coroutines have the advantage of representing the parallel nature of hardware in a syntactically friendly way. Using coroutines also avoids several potential synchronization problems that arise with multi-threaded approaches or extensive and nested use of async/future. Complex hardware interactions can b

