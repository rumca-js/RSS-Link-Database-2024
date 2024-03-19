# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## 900 Sites, 125 million accounts, 1 vulnerability
 - [https://simonwillison.net/2024/Mar/18/firebase/#atom-everything](https://simonwillison.net/2024/Mar/18/firebase/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-18T18:53:23+00:00

<p><a href="https://env.fail/posts/firewreck-1/">900 Sites, 125 million accounts, 1 vulnerability</a></p>
<p>Google&#x27;s Firebase development platform encourages building applications (mobile an web) which talk directly to the underlying data store, reading and writing from &quot;collections&quot; with access protected by Firebase Security Rules.</p>

<p>Unsurprisingly, a lot of development teams make mistakes with these.</p>

<p>This post describes how a security research team built a scanner that found over 124 million unprotected records across 900 different applications, including huge amounts of PII: 106 million email addresses, 20 million passwords (many in plaintext) and 27 million instances of &quot;Bank details, invoices, etc&quot;.</p>

<p>Most worrying of all, only 24% of the site owners they contacted shipped a fix for the misconfiguration.</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=39742422">Hacker News</a></p>

## Quoting Geoffrey Litt
 - [https://simonwillison.net/2024/Mar/18/geoffrey-litt/#atom-everything](https://simonwillison.net/2024/Mar/18/geoffrey-litt/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-18T18:16:09+00:00

<blockquote cite="https://twitter.com/geoffreylitt/status/1769471002755338553"><p>It&#x27;s hard to overstate the value of LLM support when coding for fun in an unfamiliar language. [...] This example is totally trivial in hindsight, but might have taken me a couple mins to figure out otherwise. This is a bigger deal than it seems! Papercuts add up fast and prevent flow. (A lot of being a senior engineer is just being proficient enough to avoid papercuts).</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/geoffreylitt/status/1769471002755338553">Geoffrey Litt</a>

