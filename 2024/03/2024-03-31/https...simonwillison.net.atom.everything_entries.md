# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Rumman Chowdhury
 - [https://simonwillison.net/2024/Mar/31/rumman-chowdhury/#atom-everything](https://simonwillison.net/2024/Mar/31/rumman-chowdhury/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-31T21:20:43+00:00

<blockquote cite="https://www.axios.com/2024/03/27/ai-chatbot-letdown-hype-reality"><p>No one wants to build a product on a model that makes things up. The core problem is that GenAI models are not information retrieval systems. They are synthesizing systems, with no ability to discern from the data it&#x27;s trained on unless significant guardrails are put in place.</p></blockquote><p class="cite">&mdash; <a href="https://www.axios.com/2024/03/27/ai-chatbot-letdown-hype-reality">Rumman Chowdhury</a>

## Optimizing SQLite for servers
 - [https://simonwillison.net/2024/Mar/31/optimizing-sqlite-for-servers/#atom-everything](https://simonwillison.net/2024/Mar/31/optimizing-sqlite-for-servers/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-31T20:16:23+00:00

<p><a href="https://kerkour.com/sqlite-for-servers">Optimizing SQLite for servers</a></p>
<p>Sylvain Kerkour&#x27;s comprehensive set of lessons learned running SQLite for server-based applications.</p>

<p>There&#x27;s a lot of useful stuff in here, including detailed coverage of the different recommended PRAGMA settings.</p>

<p>There was also a tip I haven&#x27;t seen before about &quot;BEGIN IMMEDIATE&quot; transactions:</p>

<p>&quot;By default, SQLite starts transactions in DEFERRED mode: they are considered read only. They are upgraded to a write transaction that requires a database lock in-flight, when query containing a write/update/delete statement is issued.</p>

<p>The problem is that by upgrading a transaction after it has started, SQLite will immediately return a SQLITE_BUSY error without respecting the busy_timeout previously mentioned, if the database is already locked by another connection.</p>

<p>This is why you should start your transactions with BEGIN IMMEDIATE in

## llm-nomic-api-embed
 - [https://simonwillison.net/2024/Mar/31/llm-nomic-api-embed/#atom-everything](https://simonwillison.net/2024/Mar/31/llm-nomic-api-embed/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-31T15:17:12+00:00

<p><a href="https://github.com/simonw/llm-nomic-api-embed">llm-nomic-api-embed</a></p>
<p>My new plugin for LLM which adds API access to the Nomic series of embedding models. Nomic models can be run locally too, which makes them a great long-term commitment as there&#x27;s no risk of the models being retired in a way that damages the value of your previously calculated embedding vectors.</p>

