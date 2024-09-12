# Source:ACCU Conference, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCJhay24LTpO1s4bIZxuIqKw, language:en

## An (In-)Complete Guide to C++ Object Lifetimes - Jonathan Müller - ACCU 2024
 - [https://www.youtube.com/watch?v=Lo-IlZxL8DU](https://www.youtube.com/watch?v=Lo-IlZxL8DU)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCJhay24LTpO1s4bIZxuIqKw
 - date published: 2024-09-11T12:00:07+00:00

ACCU Membership: https://tinyurl.com/ydnfkcyn
---

An (In-)Complete Guide to C++ Object Lifetimes - Jonathan Müller - ACCU 2024
---

A C++ program manipulate objects, but it is undefined behavior if you attempt to manipulate them while they are not alive.
So let's do a deep dive into object lifetime.

When are objects created and when are they destroyed?
How does temporary lifetime extension come into play and what changed there recently?
What happens when you std::malloc memory and just pretend objects are there without creating anything?
Or worse: You use mmap() to read shared memory.
How do unions interact with constructors, strict aliasing, or the "common initial sequence"?
What when you explicitly call the destructor and later re-use the same storage?
What's the deal with std::launder, std::bit_cast, and std::start_lifetime_as?

We'll answer all of those questions and much more.
We'll do that by looking at the C++ standard, old and new proposals, and compiler optimizations.

Slid

