# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## LLM 0.15
 - [https://simonwillison.net/2024/Jul/18/llm-015/#atom-everything](https://simonwillison.net/2024/Jul/18/llm-015/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-18T19:44:24+00:00

<p><a href="https://llm.datasette.io/en/stable/changelog.html#v0-15">LLM 0.15</a></p>
A new release of my <a href="https://llm.datasette.io/">LLM CLI tool</a> for interacting with Large Language Models from the terminal (see <a href="https://simonwillison.net/2024/Jun/17/cli-language-models/">this recent talk</a> for plenty of demos).</p>
<p>This release adds support for the brand new <a href="https://simonwillison.net/2024/Jul/18/gpt-4o-mini/">GPT-4o mini</a>:</p>
<pre><code>llm -m gpt-4o-mini "rave about pelicans in Spanish"
</code></pre>
<p>It also sets that model as the default used by the tool if no other model is specified. This replaces GPT-3.5 Turbo, the default since the first release of LLM. 4o-mini is both cheaper and <em>way</em> more capable than 3.5 Turbo.


    <p>Tags: <a href="https://simonwillison.net/tags/llm">llm</a>, <a href="https://simonwillison.net/tags/projects">projects</a>, <a href="https://simonwillison.net/tags/generative-ai">generative-ai</a>, <a href="ht

## GPT-4o mini
 - [https://simonwillison.net/2024/Jul/18/gpt-4o-mini/#atom-everything](https://simonwillison.net/2024/Jul/18/gpt-4o-mini/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-18T18:11:59+00:00

<p><a href="https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/">GPT-4o mini</a></p>
I've been complaining about how under-powered GPT 3.5 is for the price for a while now (I <a href="https://simonwillison.net/2024/Jun/27/ai-worlds-fair/#slide.011.jpeg">made fun of it</a> in a keynote a few weeks ago).</p>
<p>GPT-4o mini is <em>exactly</em> what I've been looking forward to.</p>
<p>It supports 128,000 input tokens (both images and text) and an impressive 16,000 output tokens. Most other models are still ~4,000, and Claude 3.5 Sonnet got an upgrade to 8,192 <a href="https://simonwillison.net/2024/Jul/15/alex-albert/">just a few days ago</a>. This makes it a good fit for translation and transformation tasks where the expected output more closely matches the size of the input.</p>
<p>OpenAI show benchmarks that have it out-performing Claude 3.5 Haiku and Gemini Flash, the two previous cheapest-best models.</p>
<p>GPT-4o mini is 15 cents per millions input tokens a

## Mistral NeMo
 - [https://simonwillison.net/2024/Jul/18/mistral-nemo/#atom-everything](https://simonwillison.net/2024/Jul/18/mistral-nemo/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-18T16:40:15+00:00

<p><a href="https://mistral.ai/news/mistral-nemo/">Mistral NeMo</a></p>
Released by Mistral today: "Our new best small model. A state-of-the-art 12B model with 128k context length, built in collaboration with NVIDIA, and released under the Apache 2.0 license."</p>
<p>Nice to see Mistral use Apache 2.0 for this, unlike their <a href="https://simonwillison.net/2024/May/30/codestral/">Codestral 22B release</a> - though Codestral Mamba was Apache 2.0 as well.</p>
<p>Mistral's own benchmarks but NeMo slightly ahead of the smaller (but same general weight class) Gemma 2 9B and Llama 3 8B models.</p>
<p>It's both multi-lingual and trained for tool usage:</p>
<blockquote>
<p>The model is designed for global, multilingual applications. It is trained on function calling, has a large context window, and is particularly strong in English, French, German, Spanish, Italian, Portuguese, Chinese, Japanese, Korean, Arabic, and Hindi.</p>
</blockquote>
<p>Part of this is down to the new Tekken tokenize

## Apple, Nvidia, Anthropic Used Thousands of Swiped YouTube Videos to Train AI
 - [https://simonwillison.net/2024/Jul/18/youtube-captions/#atom-everything](https://simonwillison.net/2024/Jul/18/youtube-captions/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-18T16:22:40+00:00

<p><a href="https://www.proofnews.org/apple-nvidia-anthropic-used-thousands-of-swiped-youtube-videos-to-train-ai/">Apple, Nvidia, Anthropic Used Thousands of Swiped YouTube Videos to Train AI</a></p>
This article has been getting a lot of attention over the past couple of days.</p>
<p>The story itself is nothing new: <a href="https://pile.eleuther.ai/">the Pile</a> is four years old now, and has been widely used for training LLMs since before anyone even cared what an LLM was. It turns out one of the components of the Pile is a set of ~170,000 YouTube video captions (just the captions, not the actual video) and this story by Annie Gilbertson and Alex Reisner highlights that and interviews some of the creators who were included in the data, as well as providing a <a href="https://www.proofnews.org/youtube-ai-search/">search tool</a> for seeing if a specific creator has content that was included.</p>
<p>What's notable is the response. Marques Brownlee (19m subscribers) <a href="https://

