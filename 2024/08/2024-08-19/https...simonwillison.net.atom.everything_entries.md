# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Arvind Narayanan and Sayash Kapoor
 - [https://simonwillison.net/2024/Aug/19/arvind-narayanan-and-sayash-kapoor/#atom-everything](https://simonwillison.net/2024/Aug/19/arvind-narayanan-and-sayash-kapoor/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-19T23:04:19+00:00

<blockquote cite="https://www.aisnakeoil.com/p/ai-companies-are-pivoting-from-creating"><p>With statistical learning based systems, perfect accuracy is intrinsically hard to achieve. If you think about the success stories of machine learning, like ad targeting or fraud detection or, more recently, weather forecasting, perfect accuracy isn't the goal --- as long as the system is better than the state of the art, it is useful. Even in medical diagnosis and other healthcare applications, we <a href="https://www.himss.org/news/north-carolina-hospital-system-reduces-sepsis-cases-using-predictive-analytics">tolerate</a> a lot of error.</p>
<p>But when developers put AI in consumer products, people expect it to behave like software, which means that it needs to work deterministically.</p></blockquote><p class="cite">&mdash; <a href="https://www.aisnakeoil.com/p/ai-companies-are-pivoting-from-creating">Arvind Narayanan and Sayash Kapoor</a></p>

    <p>Tags: <a href="https://simonwillison.net

## Migrating Mess With DNS to use PowerDNS
 - [https://simonwillison.net/2024/Aug/19/migrating-mess-with-dns/#atom-everything](https://simonwillison.net/2024/Aug/19/migrating-mess-with-dns/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-19T22:12:07+00:00

<p><strong><a href="https://jvns.ca/blog/2024/08/19/migrating-mess-with-dns-to-use-powerdns/">Migrating Mess With DNS to use PowerDNS</a></strong></p>
Fascinating in-depth write-up from Julia Evans about how she upgraded her "mess with dns" playground application to use <a href="https://github.com/PowerDNS/pdns">PowerDNS</a>, an open source DNS server with a <a href="https://doc.powerdns.com/authoritative/http-api/index.html#working-with-the-api">comprehensive JSON API</a>.</p>
<p>If you haven't explored <a href="https://messwithdns.net/">mess with dns</a> it's absolutely worth checking out. No login required: when you visit the site it assigns you a random subdomain (I got <code>garlic299.messwithdns.com</code> just now) and then lets you start adding additional sub-subdomains with their own DNS records - A records, CNAME records and more.</p>
<p>The interface then shows a live (WebSocket-powered) log of incoming DNS requests and responses, providing instant feedback on how your conf

## llamafile v0.8.13 (and whisperfile)
 - [https://simonwillison.net/2024/Aug/19/whisperfile/#atom-everything](https://simonwillison.net/2024/Aug/19/whisperfile/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-19T20:08:59+00:00

<p><strong><a href="https://github.com/Mozilla-Ocho/llamafile/releases/tag/0.8.13">llamafile v0.8.13 (and whisperfile)</a></strong></p>
The latest release of <a href="https://github.com/Mozilla-Ocho/llamafile">llamafile</a> (<a href="https://simonwillison.net/2023/Nov/29/llamafile/">previously</a>) adds support for <a href="https://blog.google/technology/developers/gemma-open-models/">Gemma 2B</a> (pre-bundled <a href="https://huggingface.co/jartine/gemma-2-27b-it-llamafile/tree/main">llamafiles available here</a>), significant performance improvements and new support for the Whisper speech-to-text model, based on <a href="https://github.com/ggerganov/whisper.cpp">whisper.cpp</a>, Georgi Gerganov's C++ implementation of Whisper that pre-dates his work on <code>llama.cpp</code>.</p>
<p>I got <code>whisperfile</code> working locally by first downloading the cross-platform executable attached to <a href="https://github.com/Mozilla-Ocho/llamafile/releases/tag/0.8.13">the GitHub release</a

