# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## LLM 0.14, with support for GPT-4o
 - [https://simonwillison.net/2024/May/13/llm-014/#atom-everything](https://simonwillison.net/2024/May/13/llm-014/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-13T21:00:41+00:00

<p><a href="https://llm.datasette.io/en/stable/changelog.html#v0-14">LLM 0.14, with support for GPT-4o</a></p>
It's been a while since the last LLM release. This one adds support for OpenAI's new model:</p>
<pre><code>llm -m gpt-4o "fascinate me"
</code></pre>
<p>Also a new <code>llm logs -r</code> (or <code>--response</code>) option for getting back just the response from your last prompt, without wrapping it in Markdown that includes the prompt.</p>
<p>Plus nine new <a href="https://llm.datasette.io/en/stable/plugins/directory.html">plugins</a> since 0.13!

## Hello GPT-4o
 - [https://simonwillison.net/2024/May/13/gpt-4o/#atom-everything](https://simonwillison.net/2024/May/13/gpt-4o/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-13T19:09:49+00:00

<p><a href="https://openai.com/index/hello-gpt-4o/">Hello GPT-4o</a></p>
OpenAI announced a new model today: GPT-4o, where the o stands for "omni".</p>
<p>It looks like this is the <code>gpt2-chatbot</code> we've been <a href="https://simonwillison.net/2024/May/8/gpt2-chatbot-confirmed-as-openai/">seeing in the Chat Arena</a> the past few weeks.</p>
<p>GPT-4o doesn't seem to be a huge leap ahead of GPT-4 in terms of "intelligence" - whatever that might mean - but it has a bunch of interesting new characteristics.</p>
<p>First, it's multi-modal across text, images and audio as well. The audio demos from this morning's launch were extremely impressive.</p>
<p>ChatGPT's previous voice mode worked by passing audio through a speech-to-text model, then an LLM, then a text-to-speech for the output. GPT-4o does everything with the one model, reducing latency to the point where it can act as a live interpreter between people speaking in two different languages. It also has the ability to inter

## Quoting Tim Paul
 - [https://simonwillison.net/2024/May/13/tim-paul/#atom-everything](https://simonwillison.net/2024/May/13/tim-paul/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-13T14:35:56+00:00

<blockquote cite="https://www.timpaul.co.uk/posts/using-ai-to-generate-web-forms-from-pdfs/"><p>I’m no developer, but I got the AI part working in about an hour.<br /><br />What took longer was the other stuff: identifying the problem, designing and building the UI, setting up the templating, routes and data architecture.<br /><br />It reminded me that, in order to capitalise on the potential of AI technologies, we need to really invest in the other stuff too, especially data infrastructure.<br /><br />It would be ironic, and a huge shame, if AI hype sucked all the investment out of those things.</p></blockquote><p class="cite">&mdash; <a href="https://www.timpaul.co.uk/posts/using-ai-to-generate-web-forms-from-pdfs/">Tim Paul</a>

## GPUs Go Brrr
 - [https://simonwillison.net/2024/May/13/gpus-go-brrr/#atom-everything](https://simonwillison.net/2024/May/13/gpus-go-brrr/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-13T04:08:46+00:00

<p><a href="https://hazyresearch.stanford.edu/blog/2024-05-12-tk">GPUs Go Brrr</a></p>
Fascinating, detailed low-level notes on how to get the most out of NVIDIA's H100 GPUs (currently selling for around $40,000 a piece) from the research team at Stanford who created FlashAttention, among other things.</p>
<blockquote>
<p>The swizzled memory layouts are flat-out incorrectly documented, which took considerable time for us to figure out.</p>
</blockquote>

    <p>Via <a href="https://news.ycombinator.com/item?id=40337936">Hacker News</a></p>

