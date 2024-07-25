# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Google is the only search engine that works on Reddit now thanks to AI deal
 - [https://simonwillison.net/2024/Jul/24/google-reddit/#atom-everything](https://simonwillison.net/2024/Jul/24/google-reddit/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-24T18:29:55+00:00

<p><strong><a href="https://www.404media.co/google-is-the-only-search-engine-that-works-on-reddit-now-thanks-to-ai-deal/">Google is the only search engine that works on Reddit now thanks to AI deal</a></strong></p>
This is depressing. As of around June 25th <a href="https://www.reddit.com/robots.txt">reddit.com/robots.txt</a> contains this:</p>
<pre><code>User-agent: *
Disallow: /
</code></pre>
<p>Along with a link to Reddit's <a href="https://support.reddithelp.com/hc/en-us/articles/26410290525844-Public-Content-Policy">Public Content Policy</a>.</p>
<p>Is this a direct result of Google's deal to license Reddit content for AI training, rumored <a href="https://www.reuters.com/technology/reddit-ai-content-licensing-deal-with-google-sources-say-2024-02-22/">at $60 million</a>? That's not been confirmed but it looks likely, especially since accessing that <code>robots.txt</code> using the <a href="https://search.google.com/test/rich-results">Google Rich Results testing tool</a> (hence p

## Mistral Large 2
 - [https://simonwillison.net/2024/Jul/24/mistral-large-2/#atom-everything](https://simonwillison.net/2024/Jul/24/mistral-large-2/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-24T15:56:23+00:00

<p><strong><a href="https://mistral.ai/news/mistral-large-2407/">Mistral Large 2</a></strong></p>
The second release of a GPT-4 class open weights model in two days, after yesterday's <a href="https://simonwillison.net/2024/Jul/23/introducing-llama-31/">Llama 3.1 405B</a>.</p>
<p>The weights for this one are under Mistral's <a href="https://mistral.ai/licenses/MRL-0.1.md">Research License</a>, which "allows usage and modification for research and non-commercial usages" - so not as open as Llama 3.1. You can use it commercially via the Mistral paid API.</p>
<p>Mistral Large 2 is 123 billion parameters, "designed for single-node inference" (on a very expensive single-node!) and has a 128,000 token context window, the same size as Llama 3.1.</p>
<p>Notably, according to Mistral's own benchmarks it out-performs the much larger Llama 3.1 405B on their code and math benchmarks. They trained on a lot of code:</p>
<blockquote>
<p>Following our experience with <a href="https://mistral.ai/news/

