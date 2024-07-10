# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Qt and Trivial Relocation (Part 4) -- Giuseppe D'Angelo
 - [https://isocpp.org//blog/2024/07/qt-and-trivial-relocation-part-4-giuseppe-dangelo](https://isocpp.org//blog/2024/07/qt-and-trivial-relocation-part-4-giuseppe-dangelo)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-07-09T22:09:42+00:00

<p>
	<img alt="dangeloqt.png" src="https://isocpp.org/files/img/dangeloqt.png" style="width: 400px; margin: 10px; float: right;" />The conclusion of the last post was that we need to change something in our models: maybe&nbsp;<tt>std::vector</tt>&nbsp;should use a different strategy when erasing elements; maybe types like&nbsp;<tt>std::tuple&lt;int &amp;&gt;</tt>&nbsp;should not be allowed to be stored in a vector; maybe Qt should not be using&nbsp;<tt>memmove</tt>&nbsp;when erasing objects of trivially relocatable type (but it can still optimize the&nbsp;<em>reallocation</em>&nbsp;of a vector); maybe Qt&rsquo;s definition of trivial relocability does not match ours, and we need to fix our definitions. In this post we will explore these possibilities and reach some conclusions.</p>
<blockquote>
	<h3>
		<a href="https://www.kdab.com/qt-and-trivial-relocation-part-4/">Qt and Trivial Relocation (Part 4)</a></h3>
	<p>
		by Giuseppe D'Angelo</p>
</blockquote>
<p>
	From the article:</p>
<bl

