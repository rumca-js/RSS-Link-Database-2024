# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## C++23: More Small Changes -- Sandor Dargo
 - [https://isocpp.org//blog/2024/03/cpp23-more-small-changes-sandor-dargo](https://isocpp.org//blog/2024/03/cpp23-more-small-changes-sandor-dargo)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-03-18T20:55:16+00:00

<p>
	<img alt="SANDOR_DARGO_ROUND.JPG" src="https://isocpp.org/files/img/SANDOR_DARGO_ROUND.JPG" style="width: 200px; margin: 10px; float: right; height: 204px;" />In this post, we continue discovering the changes introduced by C++23. We are going to look into three (and a half) small changes, each affecting constructors of some standard library types. We&rsquo;re going to see how new constructors for container types, a new range constructor for&nbsp;<code>string_view</code>&nbsp;and some default template arguments for&nbsp;<code>pair</code>.</p>
<blockquote>
	<h3>
		<a href="https://www.sandordargo.com/blog/2024/02/07/cpp23-small-changes-2">C++23: More Small Changes</a></h3>
	<p>
		by Sandor Dargo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	As of C++20, almost all container-like objects (containers and container-adaptors) can be initialized with a pair of iterators.</blockquote>
<blockquote>
	<pre>
std::vector&lt;int&gt; v{42, 51, 66};&#10;std::list&lt;int&gt;

