# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Context caching for Google Gemini
 - [https://simonwillison.net/2024/May/14/context-caching-for-google-gemini/#atom-everything](https://simonwillison.net/2024/May/14/context-caching-for-google-gemini/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-14T20:42:33+00:00

<p><a href="https://ai.google.dev/gemini-api/docs/caching">Context caching for Google Gemini</a></p>
Another new Gemini feature announced today. Long context models enable answering questions against large chunks of text, but the price of those long prompts can be prohibitive—$3.50/million for Gemini Pro 1.5 up to 128,000 tokens and $7/million beyond that.</p>

<p>Context caching offers a price optimization, where the long prefix prompt can be reused between requests, halving the cost per prompt but at an additional cost of $4.50 / 1 million tokens per hour to keep that context cache warm.</p>

<p>Given that hourly extra charge this isn’t a default optimization for all cases, but certain high traffic applications might be able to save quite a bit on their longer prompt systems.</p>

<p>It will be interesting to see if other vendors such as OpenAI and Anthropic offer a similar optimization in the future.

    <p>Via <a href="https://twitter.com/officiallogank/status/1790454105539854648

## llm-gemini 0.1a4
 - [https://simonwillison.net/2024/May/14/llm-gemini-01a4/#atom-everything](https://simonwillison.net/2024/May/14/llm-gemini-01a4/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-14T20:32:35+00:00

<p><a href="https://github.com/simonw/llm-gemini/releases/tag/0.1a4">llm-gemini 0.1a4</a></p>
A new release of my <code>llm-gemini</code> plugin adding support for the <a href="https://deepmind.google/technologies/gemini/flash/">Gemini 1.5 Flash</a> model that was revealed this morning at Google I/O.</p>
<p>I'm excited about this new model because of its low price. Flash is $0.35 per 1 million tokens for prompts up to 128K token and $0.70 per 1 million tokens for longer prompts - up to a million tokens now and potentially two million at some point in the future. That's 1/10th of the price of Gemini Pro 1.5, cheaper than GPT 3.5 ($0.50/million) and only a little more expensive than Claude 3 Haiku ($0.35/million).

## How developers are using Gemini 1.5 Pro’s 1 million token context window
 - [https://simonwillison.net/2024/May/14/how-developers-are-using-gemini/#atom-everything](https://simonwillison.net/2024/May/14/how-developers-are-using-gemini/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-14T20:27:29+00:00

<p><a href="https://www.youtube.com/watch?v=cogrixfRvWw">How developers are using Gemini 1.5 Pro’s 1 million token context window</a></p>
I got to be a talking head for a few seconds in an intro video for today's Google I/O keynote, talking about how I used Gemini Pro 1.5 to <a href="https://simonwillison.net/2024/Feb/21/gemini-pro-video/">index my bookshelf</a> (and with a cameo from my squirrel nutcracker). I'm at <a href="https://www.youtube.com/watch?v=cogrixfRvWw&amp;t=1m25s">1m25s</a>.

## Why your voice assistant might be sexist
 - [https://simonwillison.net/2024/May/14/voice-assistant-might-be-sexist/#atom-everything](https://simonwillison.net/2024/May/14/voice-assistant-might-be-sexist/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-14T16:16:47+00:00

<p><a href="https://www.bbc.com/future/article/20220614-why-your-voice-assistant-might-be-sexist">Why your voice assistant might be sexist</a></p>
Given OpenAI's <a href="https://www.youtube.com/watch?si=jZ_jPYiVGuf-dvQD">demo yesterday</a> of a vocal chat assistant with a flirty, giggly female voice - and the new ability to be interrupted! - it's worth revisiting this piece by Chris Baraniuk from June 2022 about gender dynamics in voice assistants. Includes a link to <a href="https://www.youtube.com/watch?v=lvv6zYOQqm0">this example</a> of a synthesized non-binary voice.

    <p>Via <a href="https://www.metafilter.com/203709/Well-you-seem-like-a-person-but-youre-just-a-voice-in-a-computer#8560562">MetaFilter comment</a></p>

