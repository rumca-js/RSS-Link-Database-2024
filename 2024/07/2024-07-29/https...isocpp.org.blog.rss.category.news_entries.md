# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## What’s the point of std::monostate? You can’t do anything with it! -- Raymond Chen
 - [https://isocpp.org//blog/2024/07/whats-the-point-of-stdmonostate-you-cant-do-anything-with-it-raymond-chen](https://isocpp.org//blog/2024/07/whats-the-point-of-stdmonostate-you-cant-do-anything-with-it-raymond-chen)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-07-29T18:36:48+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />C++17 introduced <code>std::monostate</code>, a dummy type with no members and trivial functions, primarily used when no action is needed. Despite its simplicity, <code>std::monostate</code> plays a crucial role in scenarios like coroutines and <code>std::variant</code>, where a default-constructible placeholder type is required.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240708-00/?p=109959">What&rsquo;s the point of std::monostate? You can&rsquo;t do anything with it!</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		C++17 introduced&nbsp;<code>std::monostate</code>, and I used it&nbsp;<a href="https://devblogs.microsoft.com/oldnewthing/20240112-00/?p=109267" title="In C++/WinRT, how can I await multiple coroutines and capture the results?, part

## CppCon 2024 Creating a Sender/Receiver HTTP Server -- Dietmar Kuhl
 - [https://isocpp.org//blog/2024/07/cppcon-2024-creating-a-sender-receiver-http-server-dietmar-kuhl](https://isocpp.org//blog/2024/07/cppcon-2024-creating-a-sender-receiver-http-server-dietmar-kuhl)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-07-29T15:28:42+00:00

<p>
	<strong>Registration is now open for CppCon 2024!</strong> The conference starts on September 15 and will be held&nbsp;<a href="https://cppcon.org">in person in Aurora, CO</a>.&nbsp;To whet your appetite for this year&rsquo;s conference, we&rsquo;re posting some upcoming talks that you will be able to attend this year. Here&rsquo;s another CppCon future talk we hope you will enjoy &ndash; and&nbsp;<strong><a href="https://cppcon.org/registration/">register today</a> for CppCon 2024!</strong></p>
<blockquote>
	<h3>
		<a href="https://cppcon2024.sched.com/event/1gZeX/creating-a-senderreceiver-http-server">Creating a Sender/Receiver HTTP Server&nbsp;</a></h3>
	<p>
		Monday, September 16 &bull; 11:00am - 12:00pm MDT</p>
	<p>
		by Dietmar Kuhl</p>
</blockquote>
<p>
	Summary of the talk:</p>
<blockquote>
	<p>
		The sender/receiver framework for asynchronous operations in C++ is well on its way towards standardization in C++26. Previously, the theoretical background and implementation o

