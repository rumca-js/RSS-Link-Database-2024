# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Lessons after a half-billion GPT tokens
 - [https://simonwillison.net/2024/Apr/13/lessons-after-a-half-billion-gpt-tokens/#atom-everything](https://simonwillison.net/2024/Apr/13/lessons-after-a-half-billion-gpt-tokens/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-13T20:54:34+00:00

<p><a href="https://kenkantzer.com/lessons-after-a-half-billion-gpt-tokens/">Lessons after a half-billion GPT tokens</a></p>
<p>Ken Kantzer presents some hard-won experience from shipping real features on top of OpenAI&#x27;s models.</p>

<p>They ended up settling on a very basic abstraction over the chat API - mainly to handle automatic retries on a 500 error. No complex wrappers, not even JSON mode or function calling or system prompts.</p>

<p>Rather than counting tokens they estimate tokens as 3 times the length in characters, which works well enough.</p>

<p>One challenge they highlight for structured data extraction (one of my favourite use-cases for LLMs): &quot;GPT really cannot give back more than 10 items. Trying to have it give you back 15 items? Maybe it does it 15% of the time.&quot;</p>

<p>(Several commenters on Hacker News report success in getting more items back by using numbered keys or sequence IDs in the returned JSON to help the model keep count.)</p>

    <p>Via

