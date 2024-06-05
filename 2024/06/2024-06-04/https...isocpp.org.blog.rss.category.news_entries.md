# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Qt and Trivial Relocation (Part 1) -- Giuseppe D'Angelo
 - [https://isocpp.org//blog/2024/06/qt-and-trivial-relocation-part-1-giuseppe-dangelo](https://isocpp.org//blog/2024/06/qt-and-trivial-relocation-part-1-giuseppe-dangelo)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-06-04T22:34:21+00:00

<p>
	<img alt="sso1.png" src="https://isocpp.org/files/img/sso1.png" style="width: 298px; margin: 10px; float: right;" />In Qt 4, container classes like QVector introduced an optimization that transformed certain operations on contained objects into efficient byte-level manipulations. By identifying types that can be safely moved via a simple memory copy, Qt was able to streamline reallocations for specific data types like <code>int</code> and <code>QString</code>. This article explores the concept of trivial relocation, how Qt leverages it for optimized data manipulation, and the implications for different container structures and data types.</p>
<blockquote>
	<h3>
		<a href="https://www.kdab.com/qt-and-trivial-relocation-part-1/">Qt and Trivial Relocation (Part 1)</a></h3>
	<p>
		by Giuseppe D'Angelo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		The container classes introduced in Qt 4 (<em>Tulip</em>, for the aficionados) had an interesting optimization: the abil

