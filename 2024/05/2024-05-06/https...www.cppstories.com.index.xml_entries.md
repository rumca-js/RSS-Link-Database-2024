# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## std::expected - Monadic Extensions
 - [https://www.cppstories.com/2024/expected-cpp23-monadic](https://www.cppstories.com/2024/expected-cpp23-monadic)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-05-06T00:00:00+00:00

<p><code>std::expected</code> from C++23 not only serves as an error-handling mechanism but also introduces functional programming paradigms into the language. In this blog post, we&rsquo;ll have a look at functional/monadic extensions of <code>std::expected,</code> which allow us to chain operations elegantly, handling errors at the same time. The techniques are very similar to <code>std::optional</code> extensions - see <a href="https://www.cppstories.com/2023/monadic-optional-ops-cpp23/">How to Use Monadic Operations for `std::optional` in C++23 - C++ Stories</a>.</p>
<p>Here’s a brief overview of these functional capabilities:</p>
<h2 id="and_then">
<code>and_then()</code> 
  
<a class="hash-link" href="#and_then">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0

