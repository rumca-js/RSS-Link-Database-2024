# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Adding State to the Update Notification Pattern, Part 7 -- Raymond Chen
 - [https://isocpp.org//blog/2024/06/adding-state-to-the-update-notification-pattern-part-7-raymond-chen](https://isocpp.org//blog/2024/06/adding-state-to-the-update-notification-pattern-part-7-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-06-10T22:45:13+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />Last time, we refined our&nbsp;<a href="https://devblogs.microsoft.com/oldnewthing/20240424-00/?p=109700" title="Adding state to the update notification pattern, part 6">change counter-based stateful but coalescing update notification</a>. This version still relies on a UI thread to do two things: (1) make the final final change counter check and the subsequent callback atomic, and (2) to serialize the callbacks.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240425-00/?p=109702">Adding State to the Update Notification Pattern, Part 7</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		If we don&rsquo;t have a UI thread, then we open a race condition.</p>
	<div>
		&nbsp;</div>
	<pre tabindex="0">
class EditControl&#10;{&#10;    &#10214; ... existing cla

