# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Building search-based RAG using Claude, Datasette and Val.Town
 - [https://simonwillison.net/2024/Jun/21/search-based-rag/#atom-everything](https://simonwillison.net/2024/Jun/21/search-based-rag/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-21T20:44:24+00:00

<p>Retrieval Augmented Generation (RAG) is a technique for adding extra "knowledge" to systems built on LLMs, allowing them to answer questions against custom information not included in their training data. A common way to implement this is to take a question from a user, translate that into a set of search queries, run those against a search engine and then feed the results back into the LLM to generate an answer.</p>
<p>I built a basic version of this pattern against the brand new <a href="https://simonwillison.net/2024/Jun/20/claude-35-sonnet/">Claude 3.5 Sonnet</a> language model, using <a href="https://www.sqlite.org/fts5.html">SQLite full-text search</a> running in <a href="https://datasette.io/">Datasette</a> as the search backend and <a href="https://www.val.town/">Val Town</a> as the prototyping platform.</p>
<p>The implementation took just over an hour, during a live coding session with Val.Town founder Steve Krouse. I was the latest guest on Steve's <a href="https://www.yo

## Quoting Matt Levine
 - [https://simonwillison.net/2024/Jun/21/matt-levine/#atom-everything](https://simonwillison.net/2024/Jun/21/matt-levine/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-21T05:40:12+00:00

<blockquote cite="https://www.bloomberg.com/opinion/articles/2024-06-20/virgin-orbit-had-a-fake-takeover"><p>OpenAI was founded to build artificial general intelligence safely, free of outside commercial pressures. And now every once in a while it shoots out a new AI firm whose mission is to build artificial general intelligence safely, free of the commercial pressures at OpenAI.</p></blockquote><p class="cite">&mdash; <a href="https://www.bloomberg.com/opinion/articles/2024-06-20/virgin-orbit-had-a-fake-takeover">Matt Levine</a>

## Val Vibes: Semantic search in Val Town
 - [https://simonwillison.net/2024/Jun/21/semantic-search-in-val-town/#atom-everything](https://simonwillison.net/2024/Jun/21/semantic-search-in-val-town/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-21T02:16:10+00:00

<p><a href="https://blog.val.town/blog/val-vibes/">Val Vibes: Semantic search in Val Town</a></p>
A neat case-study by JP Posma on how Val Town's developers can use Val Town Vals to build prototypes of new features that later make it into Val Town core.</p>
<p>This one explores building out <a href="https://www.val.town/search?searchType=semantic">semantic search</a> against Vals using OpenAI embeddings and the PostgreSQL pgvector extension.

## Quoting Jeff Jarvis
 - [https://simonwillison.net/2024/Jun/21/jeff-jarvis/#atom-everything](https://simonwillison.net/2024/Jun/21/jeff-jarvis/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-21T02:04:22+00:00

<blockquote cite="https://www.oreilly.com/radar/how-to-fix-ais-original-sin/"><p>It is in the public good to have AI produce quality and credible (if ‘hallucinations’ can be overcome) output. It is in the public good that there be the creation of original quality, credible, and artistic content. It is not in the public good if quality, credible content is excluded from AI training and output OR if quality, credible content is not created.</p></blockquote><p class="cite">&mdash; <a href="https://www.oreilly.com/radar/how-to-fix-ais-original-sin/">Jeff Jarvis</a>

