# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## When an Empty Destructor is Required -- Andreas Fertig
 - [https://isocpp.org//blog/2024/01/when-an-empty-destructor-is-required-andreas-fertig](https://isocpp.org//blog/2024/01/when-an-empty-destructor-is-required-andreas-fertig)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-01-02T11:47:19+00:00

<p>
	<img alt="me.png" src="https://isocpp.org/files/img/me.png" style="width: 350px; margin: 10px; float: right;" />In my previous post, "<a href="http://andreasfertig.blog/2023/11/why-you-shouldnt-provide-an-empty-destructor/">Why you shouldn't provide an empty destructor</a>," we discussed the importance of not providing an empty destructor in most cases. However, in this post, we'll explore a rare exception to this rule that arises when using the PImpl idiom to hide implementation details, specifically in situations where the <code>unique_ptr </code>encounters issues with incomplete types. Let's delve into this exception and learn when it's necessary to provide an empty destructor.</p>
<blockquote>
	<h3>
		<a href="https://andreasfertig.blog/2023/12/when-an-empty-destructor-is-required/"><strong>When an Empty Destructor is Required</strong></a></h3>
	<p>
		by Andreas Fertig</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		As you probably know from life, not only p

