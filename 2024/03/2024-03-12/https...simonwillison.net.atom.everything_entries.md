# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Astro DB
 - [https://simonwillison.net/2024/Mar/12/astro-db/#atom-everything](https://simonwillison.net/2024/Mar/12/astro-db/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-12T18:02:13+00:00

<p><a href="https://astro.build/db/">Astro DB</a></p>
<p>A new scale-to-zero hosted SQLite offering, described as &quot;A fully-managed SQL database designed exclusively for Astro&quot;. It&#x27;s built on top of LibSQL, the SQLite fork maintained by the Turso database team.</p>

<p>Astro DB encourages defining your tables with TypeScript, and querying them via the Drizzle ORM.</p>

<p>Running Astro locally uses a local SQLite database. Deployed to Astro Cloud switches to their DB product, where the free tier currently includes 1GB of storage, one billion row reads per month and one million row writes per month.</p>

<p>Astro itself is a &quot;web framework for content-driven websites&quot; - so hosted SQLite is a bit of an unexpected product from them, though it does broadly fit the ecosystem they are building.</p>

<p>This approach reminds me of how Deno K/V works - another local SQLite storage solution that offers a proprietary cloud hosted option for deployment.</p>

## gh-116167: Allow disabling the GIL with PYTHON_GIL=0 or -X gil=0
 - [https://simonwillison.net/2024/Mar/12/allow-disabling-the-gil/#atom-everything](https://simonwillison.net/2024/Mar/12/allow-disabling-the-gil/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-12T05:40:41+00:00

<p><a href="https://github.com/python/cpython/pull/116338">gh-116167: Allow disabling the GIL with PYTHON_GIL=0 or -X gil=0</a></p>
<p>Merged into python:main 14 hours ago. Looks like the first phase of Sam Gross&#x27;s phenomenal effort to provide a GIL free Python (here via an explicit opt-in) will ship in Python 3.13.</p>

## Speedometer 3.0: The Best Way Yet to Measure Browser Performance
 - [https://simonwillison.net/2024/Mar/12/speedometer-30/#atom-everything](https://simonwillison.net/2024/Mar/12/speedometer-30/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-12T04:26:06+00:00

<p><a href="https://webkit.org/blog/15131/speedometer-3-0-the-best-way-yet-to-measure-browser-performance/">Speedometer 3.0: The Best Way Yet to Measure Browser Performance</a></p>
<p>The new browser performance testing suite, released as a collaboration between Blink, Gecko, and WebKit. It&#x27;s fun to run this in your browser and watch it rattle through 580 tests written using a wide variety of modern JavaScript frameworks and visualization libraries.</p>

