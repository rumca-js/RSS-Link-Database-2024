# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Pulling a Single Item From a C++ Parameter Pack by its Index --  Raymond Chen
 - [https://isocpp.org//blog/2024/06/pulling-a-single-item-from-a-cpp-parameter-pack-by-its-index-raymond-chen](https://isocpp.org//blog/2024/06/pulling-a-single-item-from-a-cpp-parameter-pack-by-its-index-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-06-21T21:22:57+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />This article explores techniques to access specific elements within a C++ parameter pack by index. It delves into the use of <code>std::tie</code> for creating a tuple of lvalue references and explains how <code>std::forward_as_tuple</code> can preserve the original reference categories of the parameters. Additionally, it highlights a proposed feature in C++26, Pack Indexing, which aims to simplify this process significantly.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240516-00/?p=109771">Pulling a Single Item From a C++ Parameter Pack by its Index</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Suppose you have a C++ parameter pack and you want to pluck out an item from it by index.</p>
	<pre class="prettyprint lang-cpp" tabindex="0">
template&

