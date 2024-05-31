# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Adding State to the Update Notification Pattern, Part 6 -- Raymond Chen
 - [https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-6-raymond-chen](https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-6-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-05-30T22:32:23+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />Last time, we built a stateful but coalescing update notification using a change counter to identify which request is the latest one, but noted that it does unnecessary work. Let&rsquo;s see if we can avoid the unnecessary work.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240424-00/?p=109700">Adding State to the Update Notification Pattern, Part 6</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		We could add some early exits to abandon the work if we notice that we are no longer doing work on behalf of the most recent text change. It means that we have to switch the change counter variable to a&nbsp;<code>std::atomic</code>&nbsp;since we will be reading the variable from the background thread at the same time the UI thread may be modifying it.</p>

