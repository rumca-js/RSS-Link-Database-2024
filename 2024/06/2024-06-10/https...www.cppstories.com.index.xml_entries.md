# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## C++17 in Detail: Filesystem in The Standard Library
 - [https://www.cppstories.com/2017/08/cpp17-details-filesystem](https://www.cppstories.com/2017/08/cpp17-details-filesystem)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-06-10T00:00:00+00:00

<p>Although C++ is an old programming language, its Standard Library misses a few basic things. Features that Java or .NET had for years were/are not available in STL. With C++17 there’s a nice improvement: for example, we now have the standard filesystem!</p>
<p>Traversing a path, even recursively, is so simple now!</p>
<blockquote class="hint note">

  This article was initially written in 2017, but it&rsquo;s now updated. Main changes: updated compiler notes and C++20/23 changes, consistent tags, Compiler Explorer examples, layout.
</blockquote>
<h2 id="intro">
Intro 
  
<a class="hash-link" href="#intro">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5

