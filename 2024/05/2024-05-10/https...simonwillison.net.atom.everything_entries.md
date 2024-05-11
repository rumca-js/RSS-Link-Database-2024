# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Exploring Hacker News by mapping and analyzing 40 million posts and comments for fun
 - [https://simonwillison.net/2024/May/10/exploring-hacker-news-by-mapping-and-analyzing-40-million-posts/#atom-everything](https://simonwillison.net/2024/May/10/exploring-hacker-news-by-mapping-and-analyzing-40-million-posts/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-10T16:42:55+00:00

<p><a href="https://blog.wilsonl.in/hackerverse/">Exploring Hacker News by mapping and analyzing 40 million posts and comments for fun</a></p>
A real tour de force of data engineering. Wilson Lin fetched 40 million posts and comments from the Hacker News API (using Node.js with a custom multi-process worker pool) and then ran them all through the <code>BGE-M3</code> embedding model using RunPod, which let him fire up ~150 GPU instances to get the whole run done in a few hours, using a custom RocksDB and Rust queue he built to save on Amazon SQS costs.</p>
<p>Then he crawled 4 million linked pages, embedded <em>that</em> content using the faster and cheaper <code>jina-embeddings-v2-small-en</code> model, ran UMAP dimensionality reduction to render a 2D map and did a whole lot of follow-on work to identify topic areas and make the map look good.</p>
<p>That's not even half the project - Wilson built several interactive features on top of the resulting data, and experimented with custom 

## uv pip install --exclude-newer example
 - [https://simonwillison.net/2024/May/10/uv-pip-install-exclude-newer/#atom-everything](https://simonwillison.net/2024/May/10/uv-pip-install-exclude-newer/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-10T16:35:40+00:00

<p><a href="https://github.com/hauntsaninja/typing_extensions/blob/f694a4e2effdd2179f76e886498ffd3446e96b0b/.github/workflows/third_party.yml#L111">uv pip install --exclude-newer example</a></p>
A neat new feature of the <code>uv pip install</code> command is the <code>--exclude-newer</code> option, which can be used to avoid installing any package versions released after the specified date.</p>
<p>Here's a clever example of that in use from the <code>typing_extensions</code> packages CI tests that run against some downstream packages:</p>
<p><code>uv pip install --system -r test-requirements.txt --exclude-newer $(git show -s --date=format:'%Y-%m-%dT%H:%M:%SZ' --format=%cd HEAD)</code></p>
<p>They use <code>git show</code> to get the date of the most recent commit (<code>%cd</code> means commit date) formatted as an ISO timestamp, then pass that to <code>--exclude-newer</code>.

    <p>Via <a href="https://twitter.com/hauntsaninja/status/1788848732437713171">@hauntsaninja</a></p>

