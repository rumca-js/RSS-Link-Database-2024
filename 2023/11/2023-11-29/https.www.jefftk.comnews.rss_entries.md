# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Losing Metaphors: Zip and Paste
 - [https://www.jefftk.com/p/losing-metaphors-zip-and-paste](https://www.jefftk.com/p/losing-metaphors-zip-and-paste)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2023-11-29T08:00:00+00:00

<p><span>

In python (and several other languages) if I have two lists and want to
process corresponding elements together I can use </span>

<a href="https://en.wikipedia.org/wiki/Zipping_(computer_science)"><code>zip</code></a>:



<p>

</p>

<pre>
&gt;&gt;&gt; for number, letter in zip(
...    [1,2,3,4], ["a", "b", "c", "d"]):
...  print(number, letter)
...
1 a
2 b
3 c
4 d
</pre>



<p>

The metaphor is a zipper, taking the two sides and merging them
together.  It's not perfect, since a zipper interleaves instead of
matching pairs, but it's pretty good.

</p>

<p>

In unix, there's a command line tool, <code>paste</code> that does the
same thing:

</p>

<p>

</p>

<pre>
$ paste &lt;(echo 1 2 3 4 | tr ' ' '\n') \
        &lt;(echo a b c d | tr ' ' '\n')
1 a
2 b
3 c
4 d
</pre>



<p>

This time the metaphor is pasting: physically putting one column next
to another.

</p>

<p>


I found a <a href="https://news.ycombinator.com/item?id=29846318">discussion</a> on
the origin of these te

