# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## C++23: Allocator Related Changes -- Sandor Dargo
 - [https://isocpp.org//blog/2024/03/cpp23-allocator-related-changes-sandor-dargo](https://isocpp.org//blog/2024/03/cpp23-allocator-related-changes-sandor-dargo)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-03-13T20:49:38+00:00

<p>
	<img alt="SANDOR_DARGO_ROUND.JPG" src="https://isocpp.org/files/img/SANDOR_DARGO_ROUND.JPG" style="width: 200px; margin: 10px; float: right; height: 204px;" />In this post, we are going to review two changes related to allocators in C++. One is about providing size information about the allocated memory and the other is about how CTAD should happen for containers with non-default allocators.</p>
<blockquote>
	<h3>
		<a href="https://www.sandordargo.com/blog/2024/01/10/cpp23-and-allocators">C++23: Allocator Related Changes</a></h3>
	<p>
		by Sandor Dargo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		<a href="https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2021/p0401r6.html">P0401R6</a>&nbsp;gives a new way to allocate memory on the heap to limit spurious reallocations.</p>
	<p>
		The new interface of&nbsp;<code>std::allocator</code>&nbsp;looks like this, but there is also a free function version of it.</p>
	<pre>
template&lt;class Pointer&gt;&#10;  

