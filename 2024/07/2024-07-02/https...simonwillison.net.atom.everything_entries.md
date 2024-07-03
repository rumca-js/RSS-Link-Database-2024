# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Compare PDFs
 - [https://simonwillison.net/2024/Jul/2/compare-pdfs/#atom-everything](https://simonwillison.net/2024/Jul/2/compare-pdfs/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-02T19:54:30+00:00

<p><a href="https://tools.simonwillison.net/compare-pdfs">Compare PDFs</a></p>
Inspired by <a href="https://news.ycombinator.com/item?id=40854319">this thread</a> on Hacker News about the C++ <a href="http://vslavik.github.io/diff-pdf/">diff-pdf</a> tool I decided to see what it would take to produce a web-based PDF diff visualization tool using Claude 3.5 Sonnet.</p>
<p>It took two prompts:</p>
<blockquote>
<p>Build a tool where I can drag and drop on two PDF files and it uses PDF.js to turn each of their pages into canvas elements and then displays those pages side by side with a third image that highlights any differences between them, if any differences exist</p>
</blockquote>
<p>That give me a React app that didn't quite work, so I followed-up with this:</p>
<blockquote>
<p>rewrite that code to not use React at all</p>
</blockquote>
<p>Which gave me a working tool! You can see the full Claude transcript plus screenshots of the tool in action <a href="https://gist.github.com/simon

## Optimizing Large-Scale OpenStreetMap Data with SQLite
 - [https://simonwillison.net/2024/Jul/2/openstreetmap-data-sqlite/#atom-everything](https://simonwillison.net/2024/Jul/2/openstreetmap-data-sqlite/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-02T14:33:09+00:00

<p><a href="https://jtarchie.com/posts/2024-07-02-optimizing-large-scale-openstreetmap-data-with-sqlite">Optimizing Large-Scale OpenStreetMap Data with SQLite</a></p>
JT Archie describes his project to take 9GB of compressed OpenStreetMap protobufs data for the whole of the United States and load it into a queryable SQLite database.</p>
<p>OSM tags are key/value pairs. The trick used here for FTS-accelerated tag queries is really neat: build a SQLite FTS table containing the key/value pairs as space concatenated text, then run queries that look like this:</p>
<pre><code>SELECT
    id
FROM
    entries e
    JOIN search s ON s.rowid = e.id
WHERE
    -- use FTS index to find subset of possible results
    search MATCH 'amenity cafe'
    -- use the subset to find exact matches
    AND tags-&gt;&gt;'amenity' = 'cafe';
</code></pre>
<p>JT ended up building a custom SQLite Go extension, <a href="https://github.com/jtarchie/sqlitezstd">SQLiteZSTD</a>, to further accelerate things by supportin

## Quoting John Naughton
 - [https://simonwillison.net/2024/Jul/2/john-naughton/#atom-everything](https://simonwillison.net/2024/Jul/2/john-naughton/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-02T05:23:47+00:00

<blockquote cite="https://www.theguardian.com/commentisfree/2016/jan/03/visicalc-software-first-killer-app-john-naughton"><p>So VisiCalc came and went, but the software genre it pioneered – the spreadsheet – endured to become arguably the most influential type of code ever written, at least in the sense of touching the lives of millions of office workers. I’ve never worked in an organisation in which spreadsheet software was not at the heart of most accounting, budgeting and planning activities. I’ve even known professionals for whom it’s the only piece of PC software they’ve ever used: one elderly accountant of my acquaintance, for example, used Excel even for his correspondence; he simply widened column A to 80 characters, typed his text in descending cells and hit the “print” key.</p></blockquote><p class="cite">&mdash; <a href="https://www.theguardian.com/commentisfree/2016/jan/03/visicalc-software-first-killer-app-john-naughton">John Naughton</a>

## Weeknotes: a livestream, a surprise keynote and progress on Datasette Cloud billing
 - [https://simonwillison.net/2024/Jul/2/weeknotes/#atom-everything](https://simonwillison.net/2024/Jul/2/weeknotes/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-02T04:46:44+00:00

<p>My first YouTube livestream with Val Town, a keynote at the AI Engineer World's Fair and some work integrating Stripe with Datasette Cloud. Plus a bunch of upgrades to my blog.</p>
<h4 id="livestreaming-rag-with-steve-krouse-and-val-town">Livestreaming RAG with Steve Krouse and Val Town</h4>
<p><img alt="Screnshot of a What is Datasette? page created by Claude 3.5 Sonnet - it includes a Key Features section with four different cards arranged in a grid, for Explore Data, Publish Data, API Access and Extensible." src="https://static.simonwillison.net/static/2024/claude-rag/frame_011319.jpg" /></p>
<p>A couple of weeks ago I broadcast a livestream with Val Town founder Steve Krouse, which I then <a href="https://simonwillison.net/2024/Jun/21/search-based-rag/">turned into an annotated video write-up</a>.</p>
<p>Outside of a few minutes in the occasional workshop I haven't ever participated in an extended live coding session before. Steve has been running <a href="https://www.youtube.c

