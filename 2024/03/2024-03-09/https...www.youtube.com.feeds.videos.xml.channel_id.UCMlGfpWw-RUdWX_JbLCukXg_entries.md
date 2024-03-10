# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## An Introduction to Tracy Profiler in C++ - Marcos Slomp - CppCon 2023
 - [https://www.youtube.com/watch?v=ghXk3Bk5F2U](https://www.youtube.com/watch?v=ghXk3Bk5F2U)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg
 - date published: 2024-03-09T16:55:09+00:00

https://cppcon.org/
---

An Introduction to Tracy Profiler in C++ - Marcos Slomp - CppCon 2023
https://github.com/CppCon/CppCon2023

Traditional profilers are prone to skew profiling results due to overhead and time resolution constraints. Moreover, results are commonly presented in some aggregated fashion (e.g., symbol tables, flame graphs, call graphs, etc.) which are unable to pin-point anomalies in a timeline. While insightful, this methodology obfuscates the "when and where" aspect of performance issues, which can lead to rabbit holes and your time wasted.

The Tracy profiler takes a different stance, putting the timeline in the front row. This helps on the identification of pathological cases, and on the performance analysis of specific portions of the program execution. Tracy also enables real-time performance analysis: you can interact with the profiler on-the-fly, as your program runs. While Tracy encourages manual code instrumentation through its minimally invasive,

