# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Lightning Talk: Un-Undefining Undefined Behavior in C++ - Jefferson Carpenter - CppCon 2023
 - [https://www.youtube.com/watch?v=S49fKs0Bv1Q](https://www.youtube.com/watch?v=S49fKs0Bv1Q)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg
 - date published: 2024-04-11T15:04:15+00:00

https://cppcon.org/
---

Lightning Talk: Un-Undefining Undefined Behavior in C++ - Jefferson Carpenter - CppCon 2023
https://github.com/CppCon/CppCon2023

Interpreting the C++ abstract machine in the context of the real machine that it runs on.  If your program contains UB, the compiler is allowed to emit any code whatsoever, and may optimize out any code paths leading to UB.  But what if you made it so the compiler had no way to tell that the behavior was undefined?  Then it would have to generate code such that, if the behavior was defined, the program would run correctly.  Then you can write all the UB you want!  In this undefined talk, I give a couple examples of UUB (un-undefined behavior).
---

Jefferson Carpenter

I spent my early life as a baby, but soon grew into a child. By college I had already graduated from high school, and now I'm extant.
---

Videos Filmed & Edited by Bash Films: http://www.BashFilms.com
YouTube Channel Managed by Digital Medium Ltd: https://events.digi

