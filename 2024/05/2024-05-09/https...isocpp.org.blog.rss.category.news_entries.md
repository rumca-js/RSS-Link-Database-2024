# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Trip Report: Winter ISO C++ Meeting in Tokyo, Japan --  David Sankel
 - [https://isocpp.org//blog/2024/05/trip-report-winter-iso-cpp-meeting-in-tokyo-japan-david-sankel](https://isocpp.org//blog/2024/05/trip-report-winter-iso-cpp-meeting-in-tokyo-japan-david-sankel)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-05-09T21:39:06+00:00

<p>
	<img alt="tokyoreport.png" src="https://isocpp.org/files/img/tokyoreport.png" style="width: 400px; margin: 10px; float: right;" />Another meeting, another slew of potential changes to standard C++. In this recap, I&rsquo;ll summarize the working draft&rsquo;s most significant changes, spotlight my favorite proposal at the meeting, Member customization points for Senders and Receivers, and discuss a handful of notable developments.</p>
<blockquote>
	<h3>
		<a href="https://blog.developer.adobe.com/trip-report-winter-iso-c-standards-meeting-6d38b5bcec54">Trip Report: Winter ISO C++ Meeting in Tokyo, Japan</a></h3>
	<p>
		by David Sankel</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		<strong>What&rsquo;s new in the draft standard?</strong><br />
		<br />
		This snippet summarizes the notable changes:</p>
</blockquote>
<blockquote>
	<pre class="prettyprint lang-cpp">
&#10;&#9;// wg21.link/p2573r2&#10;&#10;&#9;void newapi();&#10;&#10;&#9;void oldapi() = delete(&ldquo

## Adding State to the Update Notification Pattern, Part 3 -- Raymond Chen
 - [https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-3-raymond-chen](https://isocpp.org//blog/2024/05/adding-state-to-the-update-notification-pattern-part-3-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-05-09T00:33:06+00:00

<div>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />In our continued exploration of efficient stateful update notifications, we delve into optimizing our existing solution to mitigate unnecessary background work. By introducing periodic checks for pending text and leveraging mutex protection, we aim to streamline the process and enhance performance. However, as we unravel these optimizations, we confront the complexities of managing thread safety and delve into the intricacies of background thread synchronization.</div>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240419-00/?p=109689">Adding State to the Update Notification Pattern, Part 3</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Last time, we developed&nbsp;<a href="https://devblogs.microsoft.com/oldnewthing/20240418-00/?p=109685" title="Addi

