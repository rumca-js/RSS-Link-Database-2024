# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Opaque Pointer Pattern in C++ -- Daniel Sieger
 - [https://isocpp.org//blog/2024/09/opaque-pointer-pattern-in-cpp-daniel-sieger](https://isocpp.org//blog/2024/09/opaque-pointer-pattern-in-cpp-daniel-sieger)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-09-05T20:56:09+00:00

<p>
	<img alt="sieger-opaquepattern.png" src="https://isocpp.org/files/img/sieger-opaquepattern.png" style="width: 389px; margin: 10px; float: right;" />After reading this article, you should understand the basics of the opaque pointer pattern and how you can implement it using&nbsp;<code>std::unique_ptr</code>. I also gave some hints on when it is appropriate to use it and when maybe not.</p>
<blockquote>
	<h3>
		<a href="https://danielsieger.com/blog/2024/08/02/cpp-opaque-pointer-pattern.html">Opaque Pointer Pattern in C++</a></h3>
	<p>
		by Daniel Sieger</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	The basic problem is that C++ class declarations expose private details of the class. Private member functions and data members need to be declared in the header. Here&rsquo;s an example for illustration:<br />
	<br />
	<span style="background-color: rgb(242, 242, 242);">// Point.h</span></blockquote>
<blockquote>
	<p>
		<br />
		class Point<br />
		{<br />
		public:<br />


