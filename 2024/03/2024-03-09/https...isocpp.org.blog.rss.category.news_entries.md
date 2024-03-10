# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Aggregates: C++17 vs. C++20 -- Andreas Fertig
 - [https://isocpp.org//blog/2024/03/aggregates-cpp17-vs.-c20-andreas-fertig1](https://isocpp.org//blog/2024/03/aggregates-cpp17-vs.-c20-andreas-fertig1)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-03-09T20:14:05+00:00

<p>
	<img alt="me.png" src="https://isocpp.org/files/img/me.png" style="width: 200px; margin: 10px; float: right; height: 200px;" />Sometimes the small changes between two C++ standards really bite you. Today's post is about when I got bitten by a change to aggregates in C++20.</p>
<blockquote>
	<h3>
		<a href="https://andreasfertig.blog/2024/02/aggregates-cpp17-vs-cpp20/">Aggregates: C++17 vs. C++20</a></h3>
	<p>
		by Andreas Fertig</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		<strong>A harmless example</strong></p>
	<p>
		Attendees of my training classes usually assume that I know everything. I can say sorry, but that's not the case. One day in the past, I showed the following example during a class:</p>
	<pre class="prettyprint lang-cpp">
struct Point {&#10;&nbsp; int x;&#10;&nbsp; int y;&#10;};&#10;&#10;Point pt{2, 3};</pre>
	<p>
		The class did cover C++17 and C++20. The code of&nbsp;<code>Point</code>&nbsp;is a reduced version for this post. We were 

