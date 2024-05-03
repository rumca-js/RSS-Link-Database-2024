# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Lightning Talk: Writing a Better std::move - Jonathan Müller - CppCon 2023
 - [https://www.youtube.com/watch?v=hvnl6T2MnUk](https://www.youtube.com/watch?v=hvnl6T2MnUk)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg
 - date published: 2024-05-02T15:04:10+00:00

https://cppcon.org/
---

Lightning Talk: Writing a Better std::move - Jonathan Müller - CppCon 2023
https://github.com/CppCon/CppCon2023

std::move allows the creation of const rvalue references, which is almost always wrong. It also allows moving out of lvalue references, which can be dangerous since you don't have real ownership over them and a caller might not expect the object to disappear. Let's fix those problems using macros, reflection, and more macros.
---

Jonathan Müller

Jonathan is a library developer at think-cell. In his spare time, he works on various C++ open source libraries for memory allocation, cache-friendly containers, or parsing. He also blogs at foonathan.net and is a member of the C++ standardization committee.
---

Videos Filmed & Edited by Bash Films: http://www.BashFilms.com
YouTube Channel Managed by Digital Medium Ltd: https://events.digital-medium.co.uk
---

Registration for CppCon: https://cppcon.org/registration/

#cppcon #cppprogramming #cpp

