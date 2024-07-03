# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Qt and Trivial Relocation (Part 3) -- Giuseppe D'Angelo
 - [https://isocpp.org//blog/2024/07/qt-and-trivial-relocation-part-3-giuseppe-dangelo](https://isocpp.org//blog/2024/07/qt-and-trivial-relocation-part-3-giuseppe-dangelo)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-07-02T22:07:21+00:00

<p>
	<img alt="kdab.png" src="https://isocpp.org/files/img/kdab.png" style="width: 140px; margin: 10px; float: right;" />In the last post of this series we started exploring how to erase an element from the middle of a vector.</p>
<blockquote>
	<h3>
		<a href="https://www.kdab.com/qt-and-trivial-relocation-part-3/">Qt and Trivial Relocation (Part 3)</a></h3>
	<p>
		by Giuseppe D'Angelo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		<strong>The reference semantics backstab</strong></p>
	<p>
		Let&rsquo;s start by analyzing&nbsp;<tt>erase()</tt>&lsquo;s behavior once more.</p>
	<p>
		Do you remember our claim that the specific strategy used does not really matter; that is, that they are all equivalent?&nbsp;Well, not so fast!&nbsp;It is actually&nbsp;<em>quite imprecise</em>&nbsp;to say that they are all equivalent.</p>
	<p>
		They may be, as long as we deal with types which have&nbsp;<em>value</em>&nbsp;semantics.&nbsp;If we instead use a type that has&nbsp;<em>refere

