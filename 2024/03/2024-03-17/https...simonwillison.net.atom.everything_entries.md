# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Grok-1 code and model weights release
 - [https://simonwillison.net/2024/Mar/17/grok-1/#atom-everything](https://simonwillison.net/2024/Mar/17/grok-1/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-17T20:20:13+00:00

<p><a href="https://github.com/xai-org/grok">Grok-1 code and model weights release</a></p>
<p>xAI have released their Grok-1 model under an Apache 2 license (for both weights and code). It&#x27;s distributed as a 318.24G torrent file and likely requires 320GB of VRAM to run, so needs some very hefty hardware.</p>

<p>The accompanying blog post (via link) says &quot;Trained from scratch by xAI using a custom training stack on top of JAX and Rust in October 2023&quot;, and describes it as a &quot;314B parameter Mixture-of-Experts model with 25% of the weights active on a given token&quot;.</p>

<p>Very little information on what it was actually trained on, all we know is that it was &quot;a large amount of text data, not fine-tuned for any particular task&quot;.</p>

    <p>Via <a href="https://x.ai/blog/grok-os">Open Release of Grok-1</a></p>

## Add ETag header for static responses
 - [https://simonwillison.net/2024/Mar/17/add-etag-header-for-static-responses/#atom-everything](https://simonwillison.net/2024/Mar/17/add-etag-header-for-static-responses/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-17T19:25:34+00:00

<p><a href="https://github.com/simonw/datasette/pull/2306">Add ETag header for static responses</a></p>
<p>I&#x27;ve been procrastinating on adding better caching headers for static assets (JavaScript and CSS) served by Datasette for several years, because I&#x27;ve been wanting to implement the perfect solution that sets far-future cache headers on every asset and ensures the URLs change when they are updated.</p>

<p>Agustin Bacigalup just submitted the best kind of pull request: he observed that adding ETag support for static assets would side-step the complexity while adding much of the benefit, and implemented it along with tests.</p>

<p>It&#x27;s a substantial performance improvement for any Datasette instance with a number of JavaScript plugins... like the ones we are building on Datasette Cloud. I&#x27;m just annoyed we didn&#x27;t ship something like this sooner!</p>

## How does SQLite store data?
 - [https://simonwillison.net/2024/Mar/17/how-does-sqlite-store-data/#atom-everything](https://simonwillison.net/2024/Mar/17/how-does-sqlite-store-data/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-17T18:47:53+00:00

<p><a href="https://michalpitr.substack.com/p/how-does-sqlite-store-data">How does SQLite store data?</a></p>
<p>Michal Pitr explores the design of the SQLite on-disk file format, as part of building an educational implementation of SQLite from scratch in Go.</p>

