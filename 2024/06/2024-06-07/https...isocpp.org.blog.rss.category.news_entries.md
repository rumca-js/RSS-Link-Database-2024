# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Understand Internals of std::expected -- Bartlomiej Filipek
 - [https://isocpp.org//blog/2024/06/understand-internals-of-stdexpected-bartlomiej-filipek](https://isocpp.org//blog/2024/06/understand-internals-of-stdexpected-bartlomiej-filipek)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-06-07T22:40:16+00:00

<p>
	<img alt="BartlomiejFilipek-expected.png" src="https://isocpp.org/files/img/BartlomiejFilipek-expected.png" style="width: 385px; margin: 10px; float: right;" />In the&nbsp;<a href="https://www.cppstories.com/2024/expected-cpp23/">article about&nbsp;<code>std::expected,</code></a>&nbsp;I introduced the type and showed some basic examples, and in this text, you&rsquo;ll learn how it is implemented.</p>
<blockquote>
	<h3>
		<a href="https://www.cppstories.com/2024/expected-cpp23-internals/">Understand Internals of std::expected</a></h3>
	<p>
		by Bartlomiej Filipek</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		In short,&nbsp;<code>std::expected</code>&nbsp;should contain two data members: the actual expected value and the unexpected error object. So, in theory, we could use a simple structure:</p>
	<div>
		<pre tabindex="0">
<code>template &lt;class _Ty, class _Err&gt; &#10;struct expected {  &#10;     /*... lots of code ... */  &#10;     _Ty _Value;  &#10;     _E

