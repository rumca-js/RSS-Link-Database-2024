# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## How to use std::span from C++20 -- Bartlomiej Filipek
 - [https://isocpp.org//blog/2023/12/how-to-use-stdspan-from-cpp20-bartlomiej-filipek](https://isocpp.org//blog/2023/12/how-to-use-stdspan-from-cpp20-bartlomiej-filipek)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2023-12-04T18:01:56+00:00

<p>
	<img alt="How_to_use_std_span_from_C++20.png" src="https://isocpp.org/files/img/How_to_use_std_span_from_C++20.png" style="width: 400px; margin: 10px; float: right;" />In this article, we&rsquo;ll look at&nbsp;<code>std::span</code>&nbsp;which is more generic than&nbsp;<code>string_view</code>&nbsp;and can help work with arbitrary contiguous collections.</p>
<blockquote>
	<h3>
		<a href="https://www.cppstories.com/2023/span-cpp20/">How to use std::span from C++20</a></h3>
	<p>
		by Bartlomiej Filipek</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Here&rsquo;s an example that illustrates the primary use case for&nbsp;<code>std::span</code>:</p>
	<p>
		In traditional C (or low-level C++), you&rsquo;d pass an array to a function using a pointer and a size like this:</p>
	<pre class="prettyprint lang-cpp">
void process_array(int* arr, std::size_t size) {&#10;&nbsp; for(std::size_t i = 0; i &lt; size; ++i) {&#10;&nbsp;&nbsp;&nbsp; // do something with arr[i]&#10;&nb

