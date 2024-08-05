# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Enum class improvements for C++17, C++20 and C++23
 - [https://www.cppstories.com/2024/enum-improvements](https://www.cppstories.com/2024/enum-improvements)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-08-04T00:00:00+00:00

<p>The evolution of the C++ language continues to bring powerful features that enhance code safety, readability, and maintainability. Among these improvements, we got changes and additions to <code>enum class</code> functionalities across C++17, C++20, and C++23. In this blog post, we&rsquo;ll explore these advancements, focusing on initialization improvements in C++17, the introduction of the <code>using enum</code> keyword in C++20, and the <code>std::to_underlying</code> utility in C++23.</p>
<p>Let&rsquo;s go.</p>
<h2 id="enum-class-recap">
Enum Class Recap 
  
<a class="hash-link" href="#enum-class-recap">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24

