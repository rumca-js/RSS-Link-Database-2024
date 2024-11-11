# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Around the World in C++: Exploring Time Zones with std::chrono
 - [https://www.cppstories.com/2024/zones_around_world_chrono](https://www.cppstories.com/2024/zones_around_world_chrono)
 - RSS feed: $source
 - date published: 2024-11-10T00:00:00+00:00

<p>While most time zones use simple hour offsets from UTC, some regions have chosen unusual time differences. In this blog post, we&rsquo;ll explore how we can discover such zones using C++20&rsquo;s chrono library.</p>
<p>We&rsquo;ll use GCC 14.2 as it fully supports C++20 chrono and also <code>std::print</code> from C++23.</p>
<h2 id="first-attempt-basic-zone-iteration">
First Attempt: Basic Zone Iteration 
  
<a class="hash-link" href="#first-attempt-basic-zone-iteration" aria-hidden="true">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>C++20 introduced comprehensive time 

