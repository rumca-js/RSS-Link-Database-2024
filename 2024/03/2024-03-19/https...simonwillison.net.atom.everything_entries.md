# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting quora.com/robots.txt
 - [https://simonwillison.net/2024/Mar/19/quora-robots/#atom-everything](https://simonwillison.net/2024/Mar/19/quora-robots/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-19T23:09:31+00:00

<blockquote cite="https://www.quora.com/robots.txt"><p>People share a lot of sensitive material on Quora - controversial political views, workplace gossip and compensation, and negative opinions held of companies. Over many years, as they change jobs or change their views, it is important that they can delete or anonymize their previously-written answers.<br /><br />We opt out of the wayback machine because inclusion would allow people to discover the identity of authors who had written sensitive answers publicly and later had made them anonymous, and because it would prevent authors from being able to remove their content from the internet if they change their mind about publishing it.</p></blockquote><p class="cite">&mdash; <a href="https://www.quora.com/robots.txt">quora.com/robots.txt</a>

## DiskCache
 - [https://simonwillison.net/2024/Mar/19/diskcache/#atom-everything](https://simonwillison.net/2024/Mar/19/diskcache/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-19T15:43:18+00:00

<p><a href="https://github.com/grantjenks/python-diskcache">DiskCache</a></p>
<p>Grant Jenks built DiskCache as an alternative caching backend for Django (also usable without Django), using a SQLite database on disk. The performance numbers are impressive - it even beats memcached in microbenchmarks, due to avoiding the need to access the network.</p>

<p>The source code (particularly in core.py) is a great case-study in SQLite performance optimization, after five years of iteration on making it all run as fast as possible.</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=39750077#39754972">Hacker News comment</a></p>

## The Tokenizer Playground
 - [https://simonwillison.net/2024/Mar/19/the-tokenizer-playground/#atom-everything](https://simonwillison.net/2024/Mar/19/the-tokenizer-playground/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-19T02:18:59+00:00

<p><a href="https://huggingface.co/spaces/Xenova/the-tokenizer-playground">The Tokenizer Playground</a></p>
<p>I built a tool like this a while ago, but this one is much better: it provides an interface for experimenting with tokenizers from a wide range of model architectures, including Llama, Claude, Mistral and Grok-1 - all running in the browser using Transformers.js.</p>

    <p>Via <a href="https://twitter.com/xenovacom/status/1769546095871287423">@xenovacom</a></p>

