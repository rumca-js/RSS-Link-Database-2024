# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Zed Decoded: Rope & SumTree
 - [https://simonwillison.net/2024/Apr/28/zed-decoded-rope-sumtree/#atom-everything](https://simonwillison.net/2024/Apr/28/zed-decoded-rope-sumtree/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-28T15:25:58+00:00

<p><a href="https://zed.dev/blog/zed-decoded-rope-sumtree">Zed Decoded: Rope &amp; SumTree</a></p>
Text editors like <a href="https://zed.dev/">Zed</a> need in-memory data structures that are optimized for handling large strings where text can be inserted or deleted at any point without needing to copy the whole string.</p>
<p><a href="https://en.m.wikipedia.org/wiki/Rope_(data_structure)">Ropes</a> are a classic, widely used data structure for this.</p>
<p>Zed have their own implementation of ropes in Rust, but it's backed by something even more interesting: a SumTree, described here as a thread-safe, snapshot-friendly, copy-on-write B+ tree where each leaf node contains multiple items and a Summary for each Item, and internal tree nodes contain a Summary of the items in its subtree.</p>
<p>These summaries allow for some very fast traversal tree operations, such as turning an offset in the file into a line and row coordinate and vice-versa. The summary itself can be anything, so each

