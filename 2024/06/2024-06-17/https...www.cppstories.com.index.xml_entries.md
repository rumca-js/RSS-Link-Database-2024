# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Displaying File Time in C++: Finally fixed in C++20
 - [https://www.cppstories.com/2024/file-time-cpp20](https://www.cppstories.com/2024/file-time-cpp20)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-06-17T00:00:00+00:00

<p>In this blog post, we&rsquo;ll examine the potentially simple task of getting and displaying file time. Usually, we can depend on some library or OS-specific code to get that file property. Fortunately, since C++20, we have a reliable and simple technique from the <code>std::filesystem</code> and <code>std::chrono</code> components.</p>
<p>Let&rsquo;s jump in.</p>
<h2 id="before-c17">
Before C++17 
  
<a class="hash-link" href="#before-c17">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>In C++, working with files was usually reserved for OS APIs and third-party libraries. Here are two example

