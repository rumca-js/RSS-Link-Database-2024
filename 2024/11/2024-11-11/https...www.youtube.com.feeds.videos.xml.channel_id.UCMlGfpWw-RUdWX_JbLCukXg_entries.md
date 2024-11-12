# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## What Volatile Means (and Doesn’t Mean) in C++ Programming - Ben Saks - CppCon 2024
 - [https://www.youtube.com/watch?v=GeblxEQIPFM](https://www.youtube.com/watch?v=GeblxEQIPFM)
 - RSS feed: $source
 - date published: 2024-11-11T18:19:01+00:00

https://cppcon.org​
---

What Volatile Means (and Doesn’t Mean) in C++ Programming - Ben Saks - CppCon 2024
---

Using the volatile keyword correctly is vital when accessing hardware devices in C++. Unfortunately, the volatile keyword is among the most misunderstood aspects of the language. If you don’t use volatile appropriately, you may find the compiler generating code that’s very different from what you intended.

This session will help you write more robust device drivers that avoid common mistakes surrounding volatile. Step by step, it explains:

  - Why volatile is necessary
  - How volatile affects the code that the compiler generates
  - How you should place volatile in object declarations
  - Which statements the compiler is and isn’t allowed to reorder around accesses to volatile objects
  - How to avoid misusing volatile 
  - How to avoid introducing inefficiencies when using volatile objects
---

Slides: https://github.com/CppCon/CppCon2024/blob/main/Presentations/What_V

