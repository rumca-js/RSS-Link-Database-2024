# Source:InfoWorld, URL:http://www.infoworld.com/index.rss, language:en-us

## Rust stabilizes inline const expressions
 - [https://www.infoworld.com/article/3715660/rust-stabilizes-inline-const-expressions.html#tk.rss_all](https://www.infoworld.com/article/3715660/rust-stabilizes-inline-const-expressions.html#tk.rss_all)
 - RSS feed: http://www.infoworld.com/index.rss
 - date published: 2024-06-15T01:15:00+00:00

<article>
	<section class="page">
<p>The Rust Team has released Rust 1.79, an update to the <a href="https://www.infoworld.com/article/3218074/what-is-rust-safe-fast-and-easy-software-development.html">memory safe programming language</a> that stabilizes both inline <code>const</code> expressions and the associated item bounds syntax.</p><p><a href="https://blog.rust-lang.org/2024/06/13/Rust-1.79.0.html" rel="nofollow">Unveiled June 13</a>, Rust 1.79 can be installed by running <code>rustup update stable</code>.</p><p>With Rust 1.79, <code>const { … }</code> blocks now are stable in the expression position, thus permitting explicitly entering a const context without needing extra declarations. Unlike const items, inline consts can make use of in-scope generics and have their type inferred rather than explicitly written, making them particularly useful for inline code snippets. This improvement makes code more succinct and easier to read, the Rust Team said.</p><p class="jumpTag"><a hr

