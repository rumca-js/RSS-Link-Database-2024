# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Around the World in C++: Exploring Time Zones with std::chrono -- Bartlomiej Filipek
 - [https://isocpp.org//blog/2024/12/around-the-world-in-cpp-exploring-time-zones-with-stdchrono-bartlomiej-fili](https://isocpp.org//blog/2024/12/around-the-world-in-cpp-exploring-time-zones-with-stdchrono-bartlomiej-fili)
 - RSS feed: $source
 - date published: 2024-12-06T19:56:53+00:00

<p>
	<img alt="2024-11-21_12-55-09.png" src="https://isocpp.org/files/img/2024-11-21_12-55-09.png" style="width: 357px; margin: 10px; float: right;" />While most time zones use simple hour offsets from UTC, some regions have chosen unusual time differences. In this blog post, we&rsquo;ll explore how we can discover such zones using C++20&rsquo;s chrono library.</p>
<blockquote>
	<h3>
		<a href="https://www.cppstories.com/2024/zones_around_world_chrono/">Around the World in C++: Exploring Time Zones with std::chrono</a></h3>
	<p>
		by Bartlomiej Filipek</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		We&rsquo;ll use GCC 14.2 as it fully supports C++20 chrono and also&nbsp;<code>std::print</code>&nbsp;from C++23.</p>
	<p id="first-attempt-basic-zone-iteration">
		<strong>First Attempt: Basic Zone Iteration</strong></p>
	<p>
		C++20 introduced comprehensive time zone support through the&nbsp;<code>&lt;chrono&gt;</code>&nbsp;library. The implementation relies on the IANA

