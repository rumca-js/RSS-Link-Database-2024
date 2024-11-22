# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Building Cppcheck - What We Learned from 17 Years of Development - Daniel Marjamäki - CppCon 2024
 - [https://www.youtube.com/watch?v=ztyhiMhvrqA](https://www.youtube.com/watch?v=ztyhiMhvrqA)
 - RSS feed: $source
 - date published: 2024-11-21T16:00:06+00:00

https://cppcon.org​
---

Building Cppcheck - What We Learned from 17 Years of Development - Daniel Marjamäki - CppCon 2024
---

Cppcheck has been evolving for 17 years, guided by a clear philosophy: minimal false positives and ease of use. This presentation will share the insights we've gained during its development. Our approach to easy configuration is a double-edged sword, providing user-friendly setup while occasionally leading to lower recall. We maintain a strict definition of false positives, ensuring the tool does not warn about well-written, functional code. This principle, while challenging, drives us to fix rather than suppress false positives. A core philosophy of Cppcheck is to learn from mistakes. When an issue is identified, we strive to implement checkers to prevent similar mistakes in the future.

The open-source community plays a crucial role in Cppcheck's evolution. We collaborate to enhance the tool, scanning large codebases like Debian's source code to identify i

