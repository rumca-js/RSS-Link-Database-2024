# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Practical C++17: Loop Unrolling with Lambdas and Fold Expressions
 - [https://www.cppstories.com/2024/unroll-templates-lambdas-and-fold](https://www.cppstories.com/2024/unroll-templates-lambdas-and-fold)
 - RSS feed: $source
 - date published: 2024-09-22T00:00:00+00:00

<p>In this blog post, we&rsquo;ll delve into the <code>unroll&lt;N&gt;()</code> template function for <strong>template unrolling</strong>, understand its mechanics, and see how it can improve your code. We&rsquo;ll look at lambdas, fold expressions, and integer sequences.</p>
<p>Let’s get started!</p>
<h2 id="a-little-background">
A little background 
  
<a class="hash-link" href="#a-little-background" aria-hidden="true">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>In a recent article <a href="https://aras-p.info/blog/2024/09/14/Vector-math-library-codegen-in-Debug/">Vector 

