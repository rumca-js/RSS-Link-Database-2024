# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Benj Edwards
 - [https://simonwillison.net/2024/Jul/23/benj-edwards/#atom-everything](https://simonwillison.net/2024/Jul/23/benj-edwards/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-23T21:14:32+00:00

<blockquote cite="https://arstechnica.com/information-technology/2024/07/the-first-gpt-4-class-ai-model-anyone-can-download-has-arrived-llama-405b/"><p>As we've noted many times <a href="https://arstechnica.com/information-technology/2024/03/the-ai-wars-heat-up-with-claude-3-claimed-to-have-near-human-abilities/">since March</a>, these benchmarks aren't necessarily <a href="https://themarkup.org/artificial-intelligence/2024/07/17/everyone-is-judging-ai-by-these-tests-but-experts-say-theyre-close-to-meaningless">scientifically sound</a> and don't convey the subjective experience of interacting with AI language models. [...] We've instead found that measuring the subjective experience of using a conversational AI model (through what might be called "<strong>vibemarking</strong>") on A/B leaderboards like <a href="https://arstechnica.com/ai/2023/12/turing-test-on-steroids-chatbot-arena-crowdsources-ratings-for-45-ai-models/">Chatbot Arena</a> is a better way to judge new LLMs.</p></block

## Quoting Mark Zuckerberg
 - [https://simonwillison.net/2024/Jul/23/mark-zuckerberg/#atom-everything](https://simonwillison.net/2024/Jul/23/mark-zuckerberg/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-23T16:52:07+00:00

<blockquote cite="https://about.fb.com/news/2024/07/open-source-ai-is-the-path-forward/"><p>I believe the Llama 3.1 release will be an inflection point in the industry where most developers begin to primarily use open source, and I expect that approach to only grow from here.</p></blockquote><p class="cite">&mdash; <a href="https://about.fb.com/news/2024/07/open-source-ai-is-the-path-forward/">Mark Zuckerberg</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/meta">meta</a>, <a href="https://simonwillison.net/tags/open-source">open-source</a>, <a href="https://simonwillison.net/tags/generative-ai">generative-ai</a>, <a href="https://simonwillison.net/tags/facebook">facebook</a>, <a href="https://simonwillison.net/tags/mark-zuckerberg">mark-zuckerberg</a>, <a href="https://simonwillison.net/tags/ai">ai</a>, <a href="https://simonwillison.net/tags/llms">llms</a>, <a href="https://simonwillison.net/tags/llama">llama</a></p>

## Introducing Llama 3.1: Our most capable models to date
 - [https://simonwillison.net/2024/Jul/23/introducing-llama-31/#atom-everything](https://simonwillison.net/2024/Jul/23/introducing-llama-31/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-23T15:40:47+00:00

<p><a href="https://ai.meta.com/blog/meta-llama-3-1/">Introducing Llama 3.1: Our most capable models to date</a></p>
We've been waiting for the largest release of the Llama 3 model for a few months, and now we're getting a whole new model family instead.</p>
<p>Meta are calling Llama 3.1 405B "the first frontier-level open source AI model" and it really is benchmarking in that GPT-4+ class, competitive with both GPT-4o and Claude 3.5 Sonnet.</p>
<p>I'm equally excited by the new 8B and 70B 3.1 models - both of which now support a 128,000 token context and benchmark significantly higher than their Llama 3 equivalents. Same-sized models getting more powerful and capable a very reassuring trend. I expect the 8B model (or variants of it) to run comfortably on an array of consumer hardware, and I've run a 70B model on a 64GB M2 in the past.</p>
<p>The 405B model can at least be run on a single server-class node:</p>
<blockquote>
<p>To support large-scale production inference for a model at

## sqlite-jiff
 - [https://simonwillison.net/2024/Jul/23/sqlite-jiff/#atom-everything](https://simonwillison.net/2024/Jul/23/sqlite-jiff/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-23T03:53:52+00:00

<p><a href="https://github.com/asg017/sqlite-jiff">sqlite-jiff</a></p>
I linked to the brand new Jiff datetime library <a href="https://simonwillison.net/2024/Jul/22/jiff/">yesterday</a>. Alex Garcia has already used it for an experimental SQLite extension providing a timezone-aware <code>jiff_duration()</code> function - a useful new capability since SQLite's built in date functions don't handle timezones at all.</p>
<pre><code>select jiff_duration(
  '2024-11-02T01:59:59[America/Los_Angeles]',
  '2024-11-02T02:00:01[America/New_York]',
  'minutes'
) as result; -- returns 179.966
</code></pre>
<p>The implementation is <a href="https://github.com/asg017/sqlite-jiff/blob/e02d625757105a68f5a64954262bd1ef8683212e/src/lib.rs">65 lines of Rust</a>.

    <p>Via <a href="https://twitter.com/agarcia_me/status/1815517168366485619">@agarcia_me</a></p>


    <p>Tags: <a href="https://simonwillison.net/tags/timezones">timezones</a>, <a href="https://simonwillison.net/tags/rust">rust</a>, <a href=

