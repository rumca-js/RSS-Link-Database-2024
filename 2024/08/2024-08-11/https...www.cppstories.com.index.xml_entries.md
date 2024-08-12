# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Boost File Scanning Speed: Query File Attributes on Windows 50x Faster
 - [https://www.cppstories.com/2024/cpp-query-file-attribs-faster](https://www.cppstories.com/2024/cpp-query-file-attribs-faster)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-08-11T00:00:00+00:00

<p>Imagine you&rsquo;re developing a tool that needs to scan for file changes across thousands of project files. Retrieving file attributes efficiently becomes critical for such scenarios. In this article, I&rsquo;ll demonstrate a technique to get file attributes that can achieve a surprising speedup of over 50+ times compared to standard Windows methods.</p>
<p>Let&rsquo;s dive in and explore how we can achieve this.</p>
<h2 id="inspiration--disclaimer">
Inspiration &amp; Disclaimer 
  
<a class="hash-link" href="#inspiration--disclaimer">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>The inspi

