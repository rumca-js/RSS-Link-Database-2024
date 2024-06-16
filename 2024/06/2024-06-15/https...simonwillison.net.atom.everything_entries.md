# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Notes on upgrading by blog's Heroku database plan
 - [https://simonwillison.net/2024/Jun/15/heroku-database-upgrade/#atom-everything](https://simonwillison.net/2024/Jun/15/heroku-database-upgrade/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-15T22:29:02+00:00

<p><a href="https://github.com/simonw/simonwillisonblog/issues/439">Notes on upgrading by blog&#x27;s Heroku database plan</a></p>
Heroku discontinued the “Basic” PostgreSQL plan I’ve been using for my blog, so I just upgraded to the new “essential-0” tier. Here are my notes as a GitHub issue—it was very straightforward, and I’m really only linking to it now to test that writes to the new database work correctly.</p>

<p>I try to create an issue like this any time I do even a minor ops task, mainly so I have somewhere to drop screenshots of any web UI interactions for future reference.

## Quoting Johanna Tarkela
 - [https://simonwillison.net/2024/Jun/15/johanna-tarkela/#atom-everything](https://simonwillison.net/2024/Jun/15/johanna-tarkela/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-15T15:28:17+00:00

<blockquote cite="https://twitter.com/johisart/status/1801751726694744155"><p>I understand people are upset about AI art making it to the final cut, but please try to also google artist names and compare to their portfolio before accusing them of using AI. I&#x27;m genuinely pretty upset to be accused of this. It&#x27;s no fun to work on your craft for decades and then be told by some &#x27;detection site&#x27; that your work is machine generated and people are spreading this around as a fact.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/johisart/status/1801751726694744155">Johanna Tarkela</a>

## Using DuckDB for Embeddings and Vector Search
 - [https://simonwillison.net/2024/Jun/15/duckdb-for-embeddings/#atom-everything](https://simonwillison.net/2024/Jun/15/duckdb-for-embeddings/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-15T14:39:18+00:00

<p><a href="https://blog.brunk.io/posts/similarity-search-with-duckdb/">Using DuckDB for Embeddings and Vector Search</a></p>
Sören Brunk's comprehensive tutorial combining DuckDB 1.0, a subset of German Wikipedia from Hugging Face (loaded using Parquet), the <a href="https://huggingface.co/BAAI/bge-m3">BGE M3</a> embedding model and DuckDB's <a href="https://duckdb.org/2024/05/03/vector-similarity-search-vss.html">new vss extension</a> for implementing an HNSW vector index.

    <p>Via <a href="https://twitter.com/soebrunk/status/1801631086386012453">@soebrunk</a></p>

