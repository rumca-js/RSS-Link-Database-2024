# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Adding State to the Update Notification Pattern, Part 5 --  Raymond Chen
 - [https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-5-raymond-chen](https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-5-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-05-20T21:28:52+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />Managing stateful notifications is challenging when multiple requests arrive, and the goal is to only notify about the latest one. In the <code>EditControl</code> class, we use a counter to track the most recent request, updating it on the UI thread to ensure accurate ordering and prevent stale data from being processed. This approach works but is inefficient due to redundant calculations. Next time, we'll refine this strategy for greater efficiency.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240423-00/?p=109697">Adding State to the Update Notification Pattern, Part 5&nbsp;</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		We&rsquo;ve been looking at the problem of&nbsp;<a href="https://devblogs.microsoft.com/oldnewthing/20240417-00/?p=109679" tit

