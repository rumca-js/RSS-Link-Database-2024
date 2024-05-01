# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Adding State to the Update Notification Pattern, Part 1 -- Raymond Chen
 - [https://isocpp.org//blog/2024/04/adding-state-to-the-update-notification-pattern-part-1-raymond-chen](https://isocpp.org//blog/2024/04/adding-state-to-the-update-notification-pattern-part-1-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-04-30T19:37:12+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />In software development, handling notifications efficiently is pivotal, particularly in user interface scenarios. While traditional notification patterns inform handlers of changes, they often lack crucial state information. In this article, we explore the intricacies of managing stateful updates within the context of C++/WinRT, addressing challenges such as race conditions and ensuring that notification handlers operate on the most recent data for optimal user experience.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240417-00/?p=109679">Adding State to the Update Notification Pattern, Part 1</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Some time ago, we looked at the update notification pattern, but in those cases, the notification carried no 

