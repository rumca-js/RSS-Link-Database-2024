# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Character.AI
 - [https://simonwillison.net/2024/Aug/2/characterai/#atom-everything](https://simonwillison.net/2024/Aug/2/characterai/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-02T21:07:34+00:00

<blockquote cite="https://blog.character.ai/our-next-phase-of-growth/"><p>When Noam and Daniel started Character.AI, our goal of personalized superintelligence required a full stack approach. We had to pre-train models, post-train them to power the experiences that make Character.AI special, and build a product platform with the ability to reach users globally. Over the past two years, however, the landscape has shifted – many more pre-trained models are now available. Given these changes, we see an advantage in making greater use of third-party LLMs alongside our own. This allows us to devote even more resources to post-training and creating new product experiences for our growing user base.</p></blockquote><p class="cite">&mdash; <a href="https://blog.character.ai/our-next-phase-of-growth/">Character.AI</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/llms">llms</a>, <a href="https://simonwillison.net/tags/ai">ai</a>, <a href="https://simonwillison.net/tags/fine-tuning"

## Extracting Prompts by Inverting LLM Outputs
 - [https://simonwillison.net/2024/Aug/2/extracting-prompts-by-inverting-llm-outputs/#atom-everything](https://simonwillison.net/2024/Aug/2/extracting-prompts-by-inverting-llm-outputs/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-02T18:15:28+00:00

<p><strong><a href="https://arxiv.org/abs/2405.15012">Extracting Prompts by Inverting LLM Outputs</a></strong></p>
New paper from Meta research:</p>
<blockquote>
<p>We consider the problem of language model inversion: given outputs of a language model, we seek to extract the prompt that generated these outputs. We develop a new black-box method, output2prompt, that learns to extract prompts without access to the model's logits and without adversarial or jailbreaking queries. In contrast to previous work, output2prompt only needs outputs of normal user queries.</p>
</blockquote>
<p>This is a way of extracting the hidden prompt from an application build on an LLM <em>without</em> using prompt injection techniques.</p>
<p>The trick is to train a dedicated model for guessing hidden prompts based on public question/answer pairs.</p>
<p>They conclude:</p>
<blockquote>
<p>Our results demonstrate that many user and system prompts are intrinsically vulnerable to extraction.</p>
</blockquote>
<

