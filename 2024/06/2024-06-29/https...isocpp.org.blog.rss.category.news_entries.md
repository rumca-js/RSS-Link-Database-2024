# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## More on Harmful Overuse of std::move -- Raymond Chen
 - [https://isocpp.org//blog/2024/06/more-on-harmful-overuse-of-stdmove-raymond-chen](https://isocpp.org//blog/2024/06/more-on-harmful-overuse-of-stdmove-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-06-29T21:46:18+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />In recent discussions around the use of std::move in C++, questions have arisen regarding its potential overuse and the compiler's treatment of its return values. Addressing concerns raised by developers like Jonathan Duncan, this article delves into the nuances of <code>std::move</code>, examining whether its current implementation aligns with compiler optimizations and proposing potential enhancements for more efficient code generation.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240603-00/?p=109842">More on harmful overuse of <code>std::move</code></a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Some time ago, I wrote about&nbsp;<a href="https://devblogs.microsoft.com/oldnewthing/20231124-00/?p=109059" title="On harmful overuse of std::move">h

