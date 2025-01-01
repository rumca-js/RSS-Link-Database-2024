# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## How to Ensure a Class is not Copyable or Movable -- Sandor Dargo
 - [https://isocpp.org//blog/2024/12/how-to-ensure-a-class-is-not-copyable-or-movable-sandor-dargo](https://isocpp.org//blog/2024/12/how-to-ensure-a-class-is-not-copyable-or-movable-sandor-dargo)
 - RSS feed: $source
 - date published: 2024-12-31T17:54:54+00:00

<p>
	<img alt="Dargo-classisnotcopyable.png" src="https://isocpp.org/files/img/Dargo-classisnotcopyable.png" style="width: 400px; margin: 10px; float: right;" />The topic of this post is to show different ways to ensure that a class is either non-moveable or non-copyable.</p>
<blockquote>
	<h3>
		<a href="https://www.sandordargo.com/blog/2024/11/27/non-movable-classes">How to Ensure a Class is not Copyable or Movable</a></h3>
	<p>
		by Sandor Dargo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		If we follow the classification proposed by&nbsp;<a href="https://meetingcpp.com/2024/Talks/items/Classes_Cpp23_style.html">Sebastian Theophil</a>, we can talk about 4 different class types:</p>
	<ul>
		<li>
			value classes</li>
		<li>
			container classes</li>
		<li>
			resource classes</li>
		<li>
			singleton classes</li>
	</ul>
	<p>
		While the first two should be regular classes offering both copy and move semantics, the latter two are different. One shouldn&rsquo;t be 

