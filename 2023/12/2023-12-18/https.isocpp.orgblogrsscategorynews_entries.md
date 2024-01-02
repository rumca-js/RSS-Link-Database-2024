# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## How Can I Prevent Myself From Using a Parameter After I’ve Extracted All Value? -- Raymond Chen
 - [https://isocpp.org//blog/2023/12/how-can-i-prevent-myself-from-using-a-parameter-after-ive-extracted-all-val](https://isocpp.org//blog/2023/12/how-can-i-prevent-myself-from-using-a-parameter-after-ive-extracted-all-val)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2023-12-18T23:28:29+00:00

<p>
	Imagine you have a function parameter that you want to protect from direct access, ensuring that all future interactions occur through a wrapper or transformation. This situation often arises in scenarios like implementing a logging wrapper for a class. In this discussion, we'll explore a clever technique known as "hide_name" to achieve this goal, allowing you to enforce the use of the wrapper and prevent direct access to the parameter.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20230915-00/?p=108775">How Can I Prevent Myself From Using a Parameter After I&rsquo;ve Extracted All Value From It?</a></h3>
	<p>
		By Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Suppose you have a function that takes a parameter that you want to transform in some way, and you want to require that all future access to the parameter be done through the transformed version. One example is a wrapper class that does logging.&sup1;</p>
	<pre

