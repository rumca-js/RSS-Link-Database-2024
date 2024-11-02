# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## The Publish Pattern -- Lucian Radu Teodorescu
 - [https://isocpp.org//blog/2024/11/the-publish-pattern-lucian-radu-teodorescu](https://isocpp.org//blog/2024/11/the-publish-pattern-lucian-radu-teodorescu)
 - RSS feed: $source
 - date published: 2024-11-01T18:03:54+00:00

<p>
	<img alt="logo.png" src="https://isocpp.org/files/img/logo.png" style="width: 225px; margin: 10px; float: right;" />How do you minimise locking between producers and consumers? Lucian Radu Teodorescu describes a common, but currently undocumented, design pattern. Design patterns can help us reason about code. They are like algorithms that are vaguely defined in the code. Once we recognise a pattern, we can easily draw conclusions about the behaviour of the code without looking at all the parts. Patterns also help us when designing software; they are known solutions to common problems.</p>
<p>
	In this article, we describe a concurrency pattern that can&rsquo;t be found directly in any listing of concurrency patterns, and yet, it appears (in one way or another) in many codebases. It is useful when we have producers and consumers that run continuously, and we want to minimise the locking between them.</p>
<blockquote>
	<h3>
		<a href="https://accu.org/journals/overload/32/183/teod

