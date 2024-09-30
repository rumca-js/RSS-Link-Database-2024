# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## std::initializer_list in C++ 2/2 - Caveats and Improvements
 - [https://www.cppstories.com/2023/initializer_list_improvements](https://www.cppstories.com/2023/initializer_list_improvements)
 - RSS feed: $source
 - date published: 2024-09-29T00:00:00+00:00

<p>In this article, you&rsquo;ll learn why <code>std::initializer_list</code> has a bad reputation in C++. Is passing values using is as efficient as &ldquo;emplace&rdquo;, how can we use non-copyable types? You&rsquo;ll also see how to fix some of the problems.</p>
<p>Let&rsquo;s start with the issues first:</p>
<p><strong>Updated in Sept 2024:</strong> Added note about stack overflow and C++26 fixes.</p>
<h2 id="1-referencing-local-array">
1. Referencing local array 
  
<a class="hash-link" href="#1-referencing-local-array" aria-hidden="true">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;


