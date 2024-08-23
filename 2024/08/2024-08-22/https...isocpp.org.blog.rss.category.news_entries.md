# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## CppCon 2024 Building Safe and Reliable Surgical Robotics with C++ -- Milad Khaledyan
 - [https://isocpp.org//blog/2024/08/cppcon-2024-building-safe-and-reliable-surgical-robotics-with-cpp-milad-kha](https://isocpp.org//blog/2024/08/cppcon-2024-building-safe-and-reliable-surgical-robotics-with-cpp-milad-kha)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-08-22T19:46:04+00:00

<p>
	<strong><img alt="" src="https://avatars.sched.co/e/99/21223061/avatar.jpg?e44" style="width: 250px; height: 250px; float: right;" />Registration is now open for CppCon 2024!</strong> The conference starts on September 15 and will be held&nbsp;<a href="https://cppcon.org">in person in Aurora, CO</a>.&nbsp;To whet your appetite for this year&rsquo;s conference, we&rsquo;re posting some upcoming talks that you will be able to attend this year. Here&rsquo;s another CppCon future talk we hope you will enjoy &ndash; and&nbsp;<strong><a href="https://cppcon.org/registration/">register today</a> for CppCon 2024!</strong></p>
<blockquote>
	<h3>
		<a href="https://cppcon2024.sched.com/event/1gZgI/building-safe-and-reliable-surgical-robotics-with-c">Building Safe and Reliable Surgical Robotics with C++</a></h3>
	<p>
		Wednesday, September 18 15:15 - 16:15 MDT</p>
	<p>
		by Milad Khaledyan</p>
</blockquote>
<p>
	Summary of the talk:</p>
<blockquote>
	<p>
		This talk examines the use of C++ 

## What's so hard about constexpr allocation? -- Barry Revzin
 - [https://isocpp.org//blog/2024/08/whats-so-hard-about-constexpr-allocation-barry-revzin](https://isocpp.org//blog/2024/08/whats-so-hard-about-constexpr-allocation-barry-revzin)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-08-22T00:22:23+00:00

<p>
	Before C++20, constant evaluation couldn't handle allocations, causing any such attempts to fail. This changed with C++20, which introduced the ability to allocate memory during constant evaluation, although with strict limitations requiring deallocation during the same evaluation period. Despite these advancements, certain operations, such as declaring a <code>constexpr std::vector</code>, remain impossible, with the goal of this blog post being to explore why these limitations persist.</p>
<blockquote>
	<h3>
		<a href="https://brevzin.github.io/c++/2024/07/24/constexpr-alloc/">What's so hard about <code>constexpr</code> allocation?</a></h3>
	<p>
		by Barry Revzin</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Before C++20, we couldn&rsquo;t have any allocation during constant evaluation at all. Any attempt to do so would fail the evaluation &mdash; it would no longer be constant.</p>
	<p>
		In C++20, as a result of&nbsp;<a href="https://wg21.link/p0784">P0784R

