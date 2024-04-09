# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Building files-to-prompt entirely using Claude 3 Opus
 - [https://simonwillison.net/2024/Apr/8/files-to-prompt/#atom-everything](https://simonwillison.net/2024/Apr/8/files-to-prompt/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-08T20:40:08+00:00

<p><a href="https://github.com/simonw/files-to-prompt">files-to-prompt</a> is a new tool I built to help me pipe several files at once into prompts to LLMs such as Claude and GPT-4.</p>
<p>When combined with my <a href="https://llm.datasette.io/">LLM</a> command-line tool it lets you do things like this:</p>
<div class="highlight highlight-source-shell"><pre>files-to-prompt README.md files_to_prompt <span class="pl-k">|</span> llm -m opus \
  --system <span class="pl-s"><span class="pl-pds">'</span>Update this README to reflect this functionality<span class="pl-pds">'</span></span></pre></div>
<p>I wrote <code>files-to-prompt</code> almost entirely using <a href="https://www.anthropic.com/news/claude-3-family">Claude 3 Opus</a>, <a href="https://github.com/simonw/llm-claude-3">llm-claude-3</a> and <code>files-to-prompt</code> itself, once it was functional enough to be useful.</p>
<h4 id="building-the-initial-tool">Building the initial tool</h4>
<p>I started with my <a href="https://g

## Introducing Enhance WASM
 - [https://simonwillison.net/2024/Apr/8/enhance-wasm/#atom-everything](https://simonwillison.net/2024/Apr/8/enhance-wasm/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-08T19:44:20+00:00

<p><a href="https://begin.com/blog/posts/2024-04-08-introducing-enhance-wasm">Introducing Enhance WASM</a></p>
<p>&quot;Backend agnostic server-side rendering (SSR) for Web Components&quot; - fascinating new project from Brian LeRoux and Begin.</p>

<p>The idea here is to provide server-side rendering of Web Components using WebAssembly that can run on any platform that is supported within the Extism WASM ecosystem.</p>

<p>The key is the enhance-ssr.wasm bundle, a 4.1MB WebAssembly version of the enhance-ssr JavaScript library, compiled using the Extism JavaScript PDK (Plugin Development Kit) which itself bundles a WebAssembly version of QuickJS.</p>

    <p>Via <a href="https://indieweb.social/@enhance_dev@fosstodon.org/112237109269781175">@enhance_dev@fosstodon.org</a></p>

## Quoting Julien Chaumond
 - [https://simonwillison.net/2024/Apr/8/julien-chaumond/#atom-everything](https://simonwillison.net/2024/Apr/8/julien-chaumond/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-08T18:35:30+00:00

<blockquote cite="https://twitter.com/julien_c/status/1777328846829679072"><p>in July 2023, we [Hugging Face] wanted to experiment with a custom license for this specific project [text-generation-inference] in order to protect our commercial solutions from companies with bigger means than we do, who would just host an exact copy of our cloud services.<br /><br />The experiment however wasn&#x27;t successful.<br /><br />It did not lead to licensing-specific incremental business opportunities by itself, while it did hamper or at least complicate the community contributions, given the legal uncertainty that arises as soon as you deviate from the standard licenses.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/julien_c/status/1777328846829679072">Julien Chaumond</a>

