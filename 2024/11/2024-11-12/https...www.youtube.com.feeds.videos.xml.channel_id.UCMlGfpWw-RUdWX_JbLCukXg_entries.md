# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Message Handling with Boolean Algebra - Ben Deane - CppCon 2024
 - [https://www.youtube.com/watch?v=-q9Omkhl62I](https://www.youtube.com/watch?v=-q9Omkhl62I)
 - RSS feed: $source
 - date published: 2024-11-12T21:37:13+00:00

https://cppcon.org​
---

Message Handling with Boolean Algebra - Ben Deane - CppCon 2024
---

Message reception and dispatch is something common to many codebases. And deep down, we know that Boolean algebra underlies everything we do. But we seldom give it a second thought, or if we do, we probably dismiss it as trivial; something we learned in college and quickly outgrew.

This talk shows the unreasonable effectiveness of going back to basics and really understanding and unlocking the power of Boolean algebra in the design of a message handling library for embedded systems. We’ll talk about separating message layout and semantics, how to match against messages for dispatch, and particularly how to compose and simplify constraints at compile time, in order to do the least at runtime. We’ll also introduce Boolean implication and see a non-obvious application which is key to a generic approach. Finally we’ll see how message matchers can be generically transformed using compile-time in

