# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## What is std::ref? -- Sandor Dargo
 - [https://isocpp.org//blog/2024/10/what-is-stdref-sandor-dargo](https://isocpp.org//blog/2024/10/what-is-stdref-sandor-dargo)
 - RSS feed: $source
 - date published: 2024-10-11T17:07:06+00:00

<p>
	<img alt="SANDOR_DARGO_ROUND.JPG" src="https://isocpp.org/files/img/SANDOR_DARGO_ROUND.JPG" style="width: 200px; margin: 10px; float: right; height: 200px;" />When working with C++ standard containers and functions, handling references can sometimes lead to unexpected behavior, particularly with copy semantics. This is where <code>std::ref</code> and <code>std::cref</code> come into play, allowing you to store references in containers and pass them safely to template functions like <code>std::bind</code> or <code>std::thread</code>.</p>
<blockquote>
	<h3>
		<a href="https://www.sandordargo.com/blog/2024/08/21/std-ref">What is std::ref?</a></h3>
	<p>
		by Sandor Dargo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Have you heard about&nbsp;<code>std::ref</code>&nbsp;and&nbsp;<code>std::cref</code>? The helper functions that generate objects of type&nbsp;<code>std::reference_wrapper</code>? The answer is probably yes. In that case, this article is probably not for

