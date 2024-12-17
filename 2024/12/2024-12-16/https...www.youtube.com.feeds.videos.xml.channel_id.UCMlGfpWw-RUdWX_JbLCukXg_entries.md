# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## LLVM's Realtime Safety Revolution: Tools for Modern Mission Critical Systems - CppCon 2024
 - [https://www.youtube.com/watch?v=KvhgNdxX6Uw](https://www.youtube.com/watch?v=KvhgNdxX6Uw)
 - RSS feed: $source
 - date published: 2024-12-16T15:07:05+00:00

https://cppcon.org​
---

LLVM's Realtime Safety Revolution: Tools for Modern Mission Critical Systems - Christopher Apple & David Trevelyan - CppCon 2024
---

"ERROR: RealtimeSanitizer: call to malloc detected during execution of realtime function MyAudioCallback::process!"

"Warning: MyAudioCallback::process must not call blocking fuction ‘SkectchyCall`"

Realtime programmers working on mission-critical audio, autonomous vehicle, and aerospace code are well-acquainted with the golden rule: “Thou shalt not call time-unbounded operations in your realtime thread.” Despite its importance, tools to enforce this rule have been non-existent—until now!

In the latest version of Clang, two new features help uphold realtime guarantees by preventing `malloc`, system calls, and user-defined "unsafe" functions. First, we introduce the Realtime Sanitizer, which detects calls to `malloc`, `pthread_mutex_lock`, and other problematic functions in your realtime code at runtime. Next, we explore the `

