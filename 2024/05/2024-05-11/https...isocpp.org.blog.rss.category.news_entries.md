# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Adding State to the Update Notification Pattern, Part 4 -- Raymond Chen
 - [https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-4-raymond-chen](https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-4-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-05-11T00:37:08+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />In our previous discussion, we explored the intricacies of stateful but coalescing update notifications, shedding light on the pivotal role of the UI thread in implicit serialization. However, what if this luxury of implicit synchronization is absent? Delving into an alternate version of our solution, we confront the looming specter of race conditions and the necessity for meticulous thread management to ensure seamless operation. Join us as we navigate the complexities of thread synchronization and embark on a quest to refine our approach to asynchronous work handling. &nbsp;</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240422-00/?p=109693">Adding State to the Update Notification Pattern, Part 4</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Las

