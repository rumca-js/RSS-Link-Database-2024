# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Providing a stable memory address to an external API
 - [https://isocpp.org//blog/2024/03/providing-a-stable-memory-address-to-an-external-api](https://isocpp.org//blog/2024/03/providing-a-stable-memory-address-to-an-external-api)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-03-20T09:08:39+00:00

<p>
	A post on how to provide a pointer to a Qt Model/View or other APIs storing pointers to their data without using shared_ptr or unique_ptr for the actual object.</p>
<blockquote>
	<h2>
		<a href="https://meetingcpp.com/blog/items/Providing-a-stable-memory-address.html">Providing a stable memory address</a></h2>
	<p>
		by Jens Weller</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Some APIs allow you to store a pointer to your data element. This is used to access additional information from your types to display them in Model/View Architecture.</p>
	<p>
		A while ago I showed how you can implement a tree with shared_ptr and enable_shared_from_this and then display this in QTreeView. And when working on my current project I knew this problem would come around again. Maybe not for a tree and a tree view, but I'll clearly need to have some way to have ui panels display and edit my data classes and store a stable memory adress as a pointer in Qt models. Back i

