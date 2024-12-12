# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## The Puzzle of Trying to Put an Object into a std::optional -- Raymond Chen
 - [https://isocpp.org//blog/2024/12/the-puzzle-of-trying-to-put-an-object-into-a-stdoptional-raymond-chen](https://isocpp.org//blog/2024/12/the-puzzle-of-trying-to-put-an-object-into-a-stdoptional-raymond-chen)
 - RSS feed: $source
 - date published: 2024-12-11T20:05:49+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />The <code>std::optional&lt;T&gt;</code> is a powerful tool for handling optional values, but assigning non-trivial types like <code>Doodad</code> to it can lead to unexpected compilation errors. This post explores why such assignments fail and unpacks the nuances of <code>std::optional</code> and type construction in modern C++.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20241113-00/?p=110516">The Puzzle of Trying to Put an Object into a std::optional</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		The C++ standard library template type&nbsp;<code>std::<wbr />optional&lt;T&gt;</code>&nbsp;has one of two states. It could be empty (not contain anything), or it could contain a&nbsp;<code>T</code>.</p>
	<p>
		Suppose you start with an empty&nbsp;<cod

