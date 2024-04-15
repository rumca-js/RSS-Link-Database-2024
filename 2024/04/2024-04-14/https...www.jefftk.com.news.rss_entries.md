# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Clipboard Filtering
 - [https://www.jefftk.com/p/clipboard-filtering](https://www.jefftk.com/p/clipboard-filtering)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2024-04-14T08:00:00+00:00

<p><span>

Here's a pattern I find pretty useful:

</span>

<p>

</p>

<pre>
pbpaste | some_command | pbcopy
</pre>



<p>

For example:

</p>

<ul>

<li><p>Converting spaces to tabs, for pasting into a spreadsheet
program: <code>pbpaste | tr ' ' '\t' | pbcopy</code>

</p></li>
<li><p>Converting tabs and newlines to html table formatting:
<code>pbpaste | sed 's/^/&lt;tr&gt;&lt;td&gt;/' | sed
's/\t/&lt;td&gt;/g' | pbcopy</code>

</p></li>
<li><p>Escape angle brackets and ampersands for html: <code>pbpaste |
sed 's/&amp;/\&amp;amp;/g; s/&lt;/\&amp;lt;/g; s/&gt;/\&amp;gt;/g;' |
pbcopy</code> (I used this on itself before pasting into this post.)

</p></li>
<li><p>Convert newlines-indicate-paragraphs text to html:
<code>pbpaste | sed 's/^/&lt;p&gt;/' | pbcopy</code> (I use this in
putting together the <a href="https://www.jefftk.com/news/kidsgroup">kids text posts</a>.)

</p></li>
<li><p>Any time I want to do find-and-replace when working with
software that doesn't support it well.

</p><

