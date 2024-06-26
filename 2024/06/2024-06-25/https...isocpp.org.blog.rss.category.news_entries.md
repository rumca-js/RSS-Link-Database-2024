# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Qt and Trivial Relocation (Part 2) -- Giuseppe D'Angelo
 - [https://isocpp.org//blog/2024/06/qt-and-trivial-relocation-part-2-giuseppe-dangelo](https://isocpp.org//blog/2024/06/qt-and-trivial-relocation-part-2-giuseppe-dangelo)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-06-25T22:09:14+00:00

<p>
	<img alt="kdab.png" src="https://isocpp.org/files/img/kdab.png" style="width: 140px; margin: 10px; float: right;" />In this installment we are going to explore the relationships between trivial relocation and move assignments.</p>
<blockquote>
	<h3>
		<a href="https://www.kdab.com/qt-and-trivial-relocation-part-2/">Qt and Trivial Relocation (Part 2)</a></h3>
	<p>
		by Giuseppe D'Angelo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Last time we started our investigation of trivial relocation by considering an important use-case: reallocating a vector. This happens when a vector reaches its capacity, but more storage is needed.</p>
	<p>
		Let&rsquo;s now consider a different operation: erasing an element from the middle of a QVector.</p>
	<p>
		How do we go about it?</p>
	<p>
		<img alt="isocpp-dangelo.png" src="https://isocpp.org/files/img/isocpp-dangelo.png" style="margin: 10px; float: left;" /></p>
</blockquote>

