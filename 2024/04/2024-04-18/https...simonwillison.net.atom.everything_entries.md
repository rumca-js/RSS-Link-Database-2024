# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Andrej Karpathy's Llama 3 review
 - [https://simonwillison.net/2024/Apr/18/andrej-karpathys-llama-3-review/#atom-everything](https://simonwillison.net/2024/Apr/18/andrej-karpathys-llama-3-review/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-18T20:50:37+00:00

<p><a href="https://twitter.com/karpathy/status/1781028605709234613">Andrej Karpathy&#x27;s Llama 3 review</a></p>
<p>The most interesting coverage I&#x27;ve seen so far of Meta&#x27;s Llama 3 models (8b and 70b so far, 400b promised later).</p>

<p>Andrej notes that Llama 3 trained on 15 trillion tokens - up from 2 trillion for Llama 2 - and they used that many even for the smaller 8b model, 75x more than the chinchilla scaling laws would suggest.</p>

<p>The tokenizer has also changed - they now use 128,000 tokens, up from 32,000. This results in a 15% drop in the tokens needed to represent a string of text.</p>

<p>The one disappointment is the context length - just 8,192, 2x that of Llama 2 and 4x LLaMA 1 but still pretty small by today&#x27;s standards.</p>

<p>If early indications hold, the 400b model could be the first genuinely GPT-4 class openly licensed model. We&#x27;ll have to wait and see.</p>

## How cheap, outsourced labour in Africa is shaping AI English
 - [https://simonwillison.net/2024/Apr/18/delve/#atom-everything](https://simonwillison.net/2024/Apr/18/delve/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-18T16:04:12+00:00

<p><a href="https://www.theguardian.com/technology/2024/apr/16/techscape-ai-gadgest-humane-ai-pin-chatgpt">How cheap, outsourced labour in Africa is shaping AI English</a></p>
<p>The word &quot;delve&quot; has been getting a lot of attention recently as an example of something that might be an indicator of ChatGPT generated content.</p>

<p>One example: articles on medical research site PubMed now use ‚Äúdelve‚Äù 10 to 100 times more than a few years ago!</p>

<p>Nigerian Twitter took offense recently to Paul Graham&#x27;s suggestion that &quot;delve&quot; is a sign of bad writing. It turns out Nigerian formal writing has a subtly different vocabulary.</p>

<p>Alex Hern theorizes that the underlying cause may be related. Companies like OpenAI frequently outsource data annotation to countries like Nigeria that have excellent English skills and low wages. RLHF (reinforcement learning from human feedback) involves annotators comparing and voting on the &quot;best&quot; responses from the

## Quoting Meta AI bot, answering a question on a forum
 - [https://simonwillison.net/2024/Apr/18/meta-ai-bot/#atom-everything](https://simonwillison.net/2024/Apr/18/meta-ai-bot/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-18T03:34:15+00:00

<blockquote cite="https://twitter.com/korolova/status/1780450925028548821"><p>I have a child who is also 2e and has been part of the NYC G&amp;T program. We&#x27;ve had a positive experience with the citywide program, specifically with the program at The Anderson School.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/korolova/status/1780450925028548821">Meta AI bot, answering a question on a forum</a>

## llm-reka
 - [https://simonwillison.net/2024/Apr/18/llm-reka/#atom-everything](https://simonwillison.net/2024/Apr/18/llm-reka/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-18T03:17:03+00:00

<p><a href="https://github.com/simonw/llm-reka">llm-reka</a></p>
<p>My new plugin for running LLM prompts against the Reka family of API hosted LLM models: reka-core ($10 per million input), reka-flash (80c per million) and reka-edge (40c per million).</p>

<p>All three of those models are trained from scratch by a team that includes several Google Brain alumni.</p>

<p>Reka Core is their most powerful model, released on Monday 15th April and claiming benchmark scores competitive with GPT-4 and Claude 3 Opus.</p>

## mistralai/mistral-common
 - [https://simonwillison.net/2024/Apr/18/mistral-common/#atom-everything](https://simonwillison.net/2024/Apr/18/mistral-common/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-18T00:39:54+00:00

<p><a href="https://github.com/mistralai/mistral-common">mistralai/mistral-common</a></p>
<p>New from Mistral: mistral-common, an open source Python library providing &quot;a set of tools to help you work with Mistral models&quot;.</p>

<p>So far that means a tokenizer! This is similar to OpenAI&#x27;s tiktoken library in that it lets you run tokenization in your own code, which crucially means you can count the number of tokens that you are about to use - useful for cost estimates but also for cramming the maximum allowed tokens in the context window for things like RAG.</p>

<p>Mistral&#x27;s library is better than tiktoken though, in that it also includes logic for correctly calculating the tokens needed for conversation construction and tool definition. With OpenAI&#x27;s APIs you&#x27;re currently left guessing how many tokens are taken up by these advanced features.</p>

<p>Anthropic haven&#x27;t published any form of tokenizer at all - it&#x27;s the feature I&#x27;d most like t

## Quoting Alex Albert (Anthropic)
 - [https://simonwillison.net/2024/Apr/18/alex-albert/#atom-everything](https://simonwillison.net/2024/Apr/18/alex-albert/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-18T00:22:37+00:00

<blockquote cite="https://twitter.com/alexalbert__/status/1780707227130863674"><p>In mid-March, we added this line to our system prompt to prevent Claude from thinking it can open URLs:<br /><br />&quot;It cannot open URLs, links, or videos, so if it seems as though the interlocutor is expecting Claude to do so, it clarifies the situation and asks the human to paste the relevant text or image content directly into the conversation.&quot;</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/alexalbert__/status/1780707227130863674">Alex Albert (Anthropic)</a>

