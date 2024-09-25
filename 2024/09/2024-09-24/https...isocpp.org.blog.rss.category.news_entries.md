# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Temporarily Dropping a Lock: The Anti-lock Pattern -- Raymond Chen
 - [https://isocpp.org//blog/2024/09/temporarily-dropping-a-lock-the-anti-lock-pattern-raymond-chen](https://isocpp.org//blog/2024/09/temporarily-dropping-a-lock-the-anti-lock-pattern-raymond-chen)
 - RSS feed: $source
 - date published: 2024-09-24T21:44:19+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />In C++, it&#39;s common to use RAII types like <code>std::lock_guard</code> to manage synchronization primitives, ensuring a lock is acquired at object creation and released at destruction. However, a less common but useful pattern is the "anti-lock," which temporarily releases a lock and reacquires it later, useful in scenarios where you need to drop a lock while performing certain operations, like calling out to other components to avoid deadlocks.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240814-00/?p=110129">Temporarily Dropping a Lock: The Anti-lock Pattern</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		There is a common pattern in C++ of using an RAII type to manage a synchronization primitive. There are different versions of this, but t

## CopperSpice: Template Design With Policy Classes
 - [https://isocpp.org//blog/2024/09/copperspice-template-design-with-policy-classes](https://isocpp.org//blog/2024/09/copperspice-template-design-with-policy-classes)
 - RSS feed: $source
 - date published: 2024-09-24T20:21:08+00:00

<p>
	New video on the CopperSpice YouTube Channel:</p>
<blockquote>
	<h3>
		<a href="https://www.youtube.com/watch?v=23iz4DTp7rY">Template Design With Policy Classes</a></h3>
</blockquote>
<blockquote>
	<p>
		by Barbara Geller and Ansel Sermersheim</p>
</blockquote>
<p>
	About the video:</p>
<blockquote>
	<p>
		We have a new C++ video which discusses Policy Based Design and compares it to other styles of programming. Do you know which design pattern policy based programming solves? Have you considered the benefits of a design which provides a solution at compile time versus run time? Are you using policies and maybe you had no idea they had a name?</p>
	<p>
		Please take a look and remember to subscribe.</p>
</blockquote>

