# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Optimizing the Unoptimizable: A Journey to Faster C++ Compile Times -- Victor Zverovich
 - [https://isocpp.org//blog/2024/02/optimizing-the-unoptimizable-a-journey-to-faster-cpp-compile-times](https://isocpp.org//blog/2024/02/optimizing-the-unoptimizable-a-journey-to-faster-cpp-compile-times)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-02-20T17:50:05+00:00

<p>
	<img alt="zverovich-compiletimes.jpg" src="https://isocpp.org/files/img/zverovich-compiletimes.jpg" style="width: 400px; margin: 10px; float: right;" />In this post, Victor talks about bringing compile times of the {fmt} library on par with the C standard I/O library (stdio).</p>
<blockquote>
	<h3>
		<a href="https://vitaut.net/posts/2024/faster-cpp-compile-times/">Optimizing the Unoptimizable: A Journey to Faster C++ Compile Times</a></h3>
	<p>
		by Victor Zverovich</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		First some background: {fmt} is a popular open-source formatting library for C++ that provides a better alternative to C++ iostreams and C stdio. It has already surpassed stdio in many areas:</p>
	<ul>
		<li>
			Type safety with&nbsp;<a href="https://vitaut.net/posts/2021/safe-formatting-api/">compile-time format string checks</a>&nbsp;available by default since C++20 and as an opt in for C++14/17. Runtime format strings are also safe to use in

