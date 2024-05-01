# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Understand internals of std::expected
 - [https://www.cppstories.com/2024/expected-cpp23-internals](https://www.cppstories.com/2024/expected-cpp23-internals)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-04-30T00:00:00+00:00

<p>In the <a href="https://www.cppstories.com/2024/expected-cpp23/">article about <code>std::expected,</code></a> I introduced the type and showed some basic examples, and in this text, you&rsquo;ll learn how it is implemented.</p>
<h2 id="a-simple-idea-with-struct">
A simple idea with <code>struct</code> 
  
<a class="hash-link" href="#a-simple-idea-with-struct">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>In short, <code>std::expected</code> should contain two data members: the actual expected value and the unexpected error object. So, in theory, we could use a simple structure:</p>
<div cla

