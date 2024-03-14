# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## llm-claude-3 0.3
 - [https://simonwillison.net/2024/Mar/13/llm-claude-3-03/#atom-everything](https://simonwillison.net/2024/Mar/13/llm-claude-3-03/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-13T21:18:28+00:00

<p><a href="https://github.com/simonw/llm-claude-3/releases/tag/0.3">llm-claude-3 0.3</a></p>
<p>Anthropic released Claude 3 Haiku today, their least expensive model: $0.25/million tokens of input, $1.25/million of output (GPT-3.5 Turbo is $0.50/$1.50). Unlike GPT-3.5 Haiku also supports image inputs.</p>

<p>I just released a minor update to my llm-claude-3 LLM plugin adding support for the new model.</p>

## Berkeley Function-Calling Leaderboard
 - [https://simonwillison.net/2024/Mar/13/berkeley-function-calling-leaderboard/#atom-everything](https://simonwillison.net/2024/Mar/13/berkeley-function-calling-leaderboard/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-13T17:26:18+00:00

<p><a href="https://gorilla.cs.berkeley.edu/leaderboard.html">Berkeley Function-Calling Leaderboard</a></p>
<p>The team behind Berkeley&#x27;s Gorilla OpenFunctions model - an Apache 2 licensed LLM trained to provide OpenAI-style structured JSON functions - also maintain a leaderboard of different function-calling models. Their own Gorilla model is the only non-proprietary model in the top ten.</p>

## Quoting Phillip Carter
 - [https://simonwillison.net/2024/Mar/13/phillip-carter/#atom-everything](https://simonwillison.net/2024/Mar/13/phillip-carter/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-13T15:02:48+00:00

<blockquote cite="https://twitter.com/_cartermp/status/1767923038404985115"><p>The talk track I&#x27;ve been using is that LLMs are easy to take to market, but hard to keep in the market long-term. All the hard stuff comes when you move past the demo and get exposure to real users.<br /><br />And that&#x27;s where you find that all the nice little things you got neatly working fall apart. And you need to prompt differently, do different retrieval, consider fine-tuning, redesign interaction, etc. People will treat this stuff differently from &quot;normal&quot; products, creating unique challenges.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/_cartermp/status/1767923038404985115">Phillip Carter</a>

## pywebview 5
 - [https://simonwillison.net/2024/Mar/13/pywebview-5/#atom-everything](https://simonwillison.net/2024/Mar/13/pywebview-5/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-13T14:15:46+00:00

<p><a href="https://pywebview.flowrl.com/blog/pywebview5.html">pywebview 5</a></p>
<p>pywebview is a library for building desktop (and now Android) applications using Python, based on the idea of displaying windows that use the system default browser to display an interface to the user - styled such that the fact they run on HTML, CSS and JavaScript is mostly hidden from the end-user.</p>

<p>It&#x27;s a bit like a much simpler version of Electron. Unlike Electron it doesn&#x27;t bundle a full browser engine (Electron bundles Chromium), which reduces the size of the dependency a lot but does mean that cross-browser differences (quite rare these days) do come back into play.</p>

<p>I tried out their getting started example and it&#x27;s very pleasant to use - import webview, create a window and then start the application loop running to display it.</p>

<p>You can register JavaScript functions that call back to Python, and you can execute JavaScript in a window from your Pyth

## The Bing Cache thinks GPT-4.5 is coming
 - [https://simonwillison.net/2024/Mar/13/the-bing-cache-thinks-gpt-45-is-coming/#atom-everything](https://simonwillison.net/2024/Mar/13/the-bing-cache-thinks-gpt-45-is-coming/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-13T02:29:13+00:00

<p><a href="https://twitter.com/TheXeophon/status/1767586070047203680">The Bing Cache thinks GPT-4.5 is coming</a></p>
<p>I was able to replicate this myself: earlier today: searching Bing (or apparently Duck Duck Go) for &quot;openai announces gpt-4.5 turbo&quot; would return a link to a 404 page at openai.com/blog/gpt-4-5-turbo with a search result page snippet that announced 256,000 tokens and knowledge cut-off of June 2024</p>

<p>I thought the knowledge cut-off must have been a hallucination, but someone got a screenshot of it showing up in the search engine snippet which would suggest that it was real text that got captured in a cache somehow.</p>

<p>I guess this means we might see GPT 4.5 in June then? I have trouble believing that OpenAI would release a model in June with a June knowledge cut-off, given how much time they usually spend red-teaming their models before release.</p>

<p>Or maybe  it was one of those glitches like when a newspaper accidentally publishes 

