# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## 22 Common Filesystem Tasks in C++20
 - [https://www.cppstories.com/2024/common-filesystem-cpp20](https://www.cppstories.com/2024/common-filesystem-cpp20)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-07-14T00:00:00+00:00

<p>Working with the filesystem can be a daunting task, but it doesn&rsquo;t have to be. In this post, I&rsquo;ll walk you through some of the most common filesystem operations using the powerful features introduced in C++17, as well as some new enhancements in C++20/23. Whether you&rsquo;re creating directories, copying files, or managing permissions, these examples will help you understand and efficiently utilize the <code>std::filesystem</code> library.</p>
<p>Let&rsquo;s start.</p>
<h2 id="directory-operations">
Directory Operations 
  
<a class="hash-link" href="#directory-operations">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></p

