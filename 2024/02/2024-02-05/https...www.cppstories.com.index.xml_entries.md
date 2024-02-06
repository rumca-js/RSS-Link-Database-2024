# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Using std::expected from C++23
 - [https://www.cppstories.com/2024/expected-cpp23](https://www.cppstories.com/2024/expected-cpp23)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-02-05T00:00:00+00:00

<p>In this article, we&rsquo;ll go through a new vocabulary type introduced in C++23. <code>std::expected</code> is a type specifically designed to return results from a function, along with the extra error information.</p>
<h2 id="motivation">
Motivation 
  
<a class="hash-link" href="#motivation">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>Imagine you&rsquo;re expecting a certain result from a function, but oops&hellip; things don&rsquo;t always go as planned.</p>
<div class="highlight"><pre class="chroma" tabindex="0"><code class="language-cpp"><span class="line"><span class="cl">

