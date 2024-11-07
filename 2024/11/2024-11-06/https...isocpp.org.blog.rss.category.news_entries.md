# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Implementing Trivial Relocation in Library -- Barry Revzin
 - [https://isocpp.org//blog/2024/11/implementing-trivial-relocation-in-library-barry-revzin](https://isocpp.org//blog/2024/11/implementing-trivial-relocation-in-library-barry-revzin)
 - RSS feed: $source
 - date published: 2024-11-06T18:06:32+00:00

<p>
	<img alt="TPWGDVRj_400x400.jpg" src="https://isocpp.org/files/img/TPWGDVRj_400x400.jpg" style="width: 240px; margin: 10px; float: right;" />One of the reasons that I&rsquo;m excited for Reflection in C++ is that it can permit you to implement, as a library, many things that previously required language features. In this post, I&rsquo;m going to walk through implementing P2786R8 (&ldquo;Trivial Relocatability For C++26&rdquo;).</p>
<blockquote>
	<h3>
		<a href="https://brevzin.github.io/c++/2024/10/21/trivial-relocation/">Implementing Trivial Relocation in Library</a></h3>
	<p>
		by Barry Revzin</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		The goal here is not to say that the design is right or wrong (although the syntax certainly is suspect), but rather to show the kinds of things that reflection can solve.</p>
	<p>
		We&rsquo;ll just go straight to the wording and translate it into code as we go:</p>
	<p id="trivially-relocatable-types">
		<strong>Trivially 

