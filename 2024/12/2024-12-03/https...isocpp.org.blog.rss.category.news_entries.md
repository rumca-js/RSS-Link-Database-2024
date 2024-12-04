# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Use std::span Instead of C-style Arrays -- Sandor Dargo
 - [https://isocpp.org//blog/2024/12/use-stdspan-instead-of-c-style-arrays-sandor-dargo](https://isocpp.org//blog/2024/12/use-stdspan-instead-of-c-style-arrays-sandor-dargo)
 - RSS feed: $source
 - date published: 2024-12-03T19:53:30+00:00

<p>
	<img alt="SANDOR_DARGO_ROUND.JPG" src="https://isocpp.org/files/img/SANDOR_DARGO_ROUND.JPG" style="width: 200px; margin: 10px; float: right; height: 200px;" />C-style arrays are still used, mostly when you have to deal with C-libraries. They come with significant limitations, particularly when passed to functions where array decay occurs, leading to the loss of size information.</p>
<blockquote>
	<h3>
		<a href="https://www.sandordargo.com/blog/2024/11/06/std-span">Use std::span Instead of C-style Arrays</a></h3>
	<p>
		by Sandor Dargo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		While reading the awesome book C++ Brain Teasers by Anders Schau Knatten, I realized it might be worth writing about spans.</p>
	<p>
		std::span is a class template that was added to the standard library in C++20 and you&rsquo;ll find it in the &lt;span&gt; header. A span is a non-owning object that refers to a contiguous sequence of objects with the first sequence element at positio

