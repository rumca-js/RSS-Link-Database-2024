# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Tree.js interactive demo
 - [https://simonwillison.net/2024/Jun/8/treejs-interactive-demo/#atom-everything](https://simonwillison.net/2024/Jun/8/treejs-interactive-demo/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-08T21:43:22+00:00

<p><a href="https://dgreenheck.github.io/tree-js/">Tree.js interactive demo</a></p>
Daniel Greenheck's interactive demo of his procedural tree generator (as in vegetation) <a href="https://github.com/dgreenheck/tree-js">built with Three.js</a>. This is really fun to play with - there are 30+ tunable parameters and you can export your tree as a <code>.glb</code> file for import into tools like Blender or Unity.

    <p>Via <a href="https://twitter.com/dangreenheck/status/1798932111099105543">@dangreenheck</a></p>

## Claude's Character
 - [https://simonwillison.net/2024/Jun/8/claudes-character/#atom-everything](https://simonwillison.net/2024/Jun/8/claudes-character/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-08T21:41:27+00:00

<p><a href="https://www.anthropic.com/research/claude-character">Claude&#x27;s Character</a></p>
There's so much interesting stuff in this article from Anthropic on how they defined the personality for their Claude 3 model. In addition to the technical details there are some very interesting thoughts on the complex challenge of designing a "personality" for an LLM in the first place.</p>
<blockquote>
<p>Claude 3 was the first model where we added "character training" to our alignment finetuning process: the part of training that occurs after initial model training, and the part that turns it from a predictive text model into an AI assistant. The goal of character training is to make Claude begin to have more nuanced, richer traits like curiosity, open-mindedness, and thoughtfulness.</p>
</blockquote>
<p>But what other traits should it have? This is a very difficult set of decisions to make! The most obvious approaches are all flawed in different ways:</p>
<blockquote>
<p>Adopting the 

## Expanding on how Voice Engine works and our safety research
 - [https://simonwillison.net/2024/Jun/8/how-voice-engine-works/#atom-everything](https://simonwillison.net/2024/Jun/8/how-voice-engine-works/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-08T17:48:49+00:00

<p><a href="https://openai.com/index/expanding-on-how-voice-engine-works-and-our-safety-research/">Expanding on how Voice Engine works and our safety research</a></p>
Voice Engine is OpenAI's text-to-speech (TTS) model. It's not the same thing as the voice mode in the GPT-4o demo <a href="https://simonwillison.net/2024/May/15/chatgpt-in-4o-mode/">last month</a> - Voice Engine was first previewed <a href="https://openai.com/index/chatgpt-can-now-see-hear-and-speak/">on September 25 2023</a> as the engine used by the ChatGPT mobile apps. I also used the API version to build <a href="https://simonwillison.net/2023/Nov/7/ospeak/">my ospeak CLI tool</a>.</p>
<p>One detail in this new explanation of Voice Engine stood out to me:</p>
<blockquote>
<p>In November of 2023, we released a simple TTS API also powered by Voice Engine. We chose another limited release where we worked with professional voice actors to create 15-second audio samples to power each of the six preset voices in the API.</

