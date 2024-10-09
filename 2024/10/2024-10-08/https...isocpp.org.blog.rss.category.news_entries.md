# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Constructing Nodes of a Hand-made Linked List, How Hard Can it Be? -- Raymond Chen
 - [https://isocpp.org//blog/2024/10/constructing-nodes-of-a-hand-made-linked-list-how-hard-can-it-be-raymond-ch](https://isocpp.org//blog/2024/10/constructing-nodes-of-a-hand-made-linked-list-how-hard-can-it-be-raymond-ch)
 - RSS feed: $source
 - date published: 2024-10-08T19:38:55+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />When designing a circular doubly-linked list, the initial challenge is determining how to manage the construction of new nodes in relation to existing ones. While constructors seem like a natural fit for placing nodes before or after a given node, overloading them can lead to ambiguity and poor design choices. Instead, using distinct tag types or factory methods provides clearer intent, ensuring flexibility while respecting the constraints of guaranteed copy elision for node addresses.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20240819-00/?p=110145">Constructing Nodes of a Hand-made Linked List, How Hard Can it Be?</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Suppose you are writing your own circular doubly-linked list structure.</p>
	<pre tab

