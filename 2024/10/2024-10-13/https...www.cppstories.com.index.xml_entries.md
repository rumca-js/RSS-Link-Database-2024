# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## C++ String Conversion: Exploring std::from_chars in C++17 to C++26
 - [https://www.cppstories.com/2018/12/fromchars](https://www.cppstories.com/2018/12/fromchars)
 - RSS feed: $source
 - date published: 2024-10-13T00:00:00+00:00

<p>With the introduction of C++17, the C++ Standard Library expanded its capabilities for converting text to numbers with the addition of <code>std::from_chars</code>. This low-level, high-performance API offers significant advantages over previous methods, such as <code>atoi</code> and <code>stringstream</code>. In this article, we will explore the evolution of string conversion routines from C++17 through C++26, highlighting key improvements like <code>constexpr</code> support and enhanced error handling. Let&rsquo;s dive into the details and see how <code>std::from_chars</code> can transform your approach to string conversion.</p>
<p><strong>Updated in Oct 2024:</strong> Added notes from <code>constexpr</code> support in C++23, and C++26 improvements, plus more Compiler Explorer examples.</p>
<h2 id="before-c17">
Before C++17 
  
<a class="hash-link" href="#before-c17" aria-hidden="true">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width=

