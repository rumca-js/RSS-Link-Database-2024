# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Transformer Explainer
 - [https://simonwillison.net/2024/Aug/11/transformer-explainer/#atom-everything](https://simonwillison.net/2024/Aug/11/transformer-explainer/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-11T22:56:33+00:00

<p><strong><a href="https://poloclub.github.io/transformer-explainer/">Transformer Explainer</a></strong></p>
This is a very neat interactive visualization (with accompanying essay and video - scroll down for those) that explains the Transformer architecture for LLMs, using a GPT-2 model running directly in the browser using the ONNX runtime and Andrej Karpathy's nanoGPT project.</p>
<p><img alt="Screenshot of the Transformer Explainer interface, running a prompt &quot;the sky is&quot; which returns &quot;blue&quot; as the most obvious next word." src="https://static.simonwillison.net/static/2024/transformer-explainer.jpg" />


    <p>Tags: <a href="https://simonwillison.net/tags/generative-ai">generative-ai</a>, <a href="https://simonwillison.net/tags/explorables">explorables</a>, <a href="https://simonwillison.net/tags/d3">d3</a>, <a href="https://simonwillison.net/tags/ai">ai</a>, <a href="https://simonwillison.net/tags/llms">llms</a></p>

## Ladybird set to adopt Swift
 - [https://simonwillison.net/2024/Aug/11/ladybird-set-to-adopt-swift/#atom-everything](https://simonwillison.net/2024/Aug/11/ladybird-set-to-adopt-swift/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-11T18:38:57+00:00

<p><strong><a href="https://twitter.com/awesomekling/status/1822236888188498031">Ladybird set to adopt Swift</a></strong></p>
Andreas Kling on the Ladybird browser project's search for a memory-safe language to use in conjunction with their existing C++ codebase:</p>
<blockquote>
<p>Over the last few months, I've asked a bunch of folks to pick some little part of our project and try rewriting it in the different languages we were evaluating. The feedback was very clear: everyone preferred Swift!</p>
</blockquote>
<p>Andreas previously worked for Apple on Safari, but this was still a surprising result given the current relative lack of widely adopted open source Swift projects outside of the Apple ecosystem.</p>
<p>This change is currently blocked on the upcoming Swift 6 release:</p>
<blockquote>
<p>We aren't able to start using it just yet, as the current release of Swift ships with a version of Clang that's too old to grok our existing C++ codebase. But when Swift 6 comes out of beta

## PEP 750 – Tag Strings For Writing Domain-Specific Languages
 - [https://simonwillison.net/2024/Aug/11/pep-750/#atom-everything](https://simonwillison.net/2024/Aug/11/pep-750/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-11T18:29:26+00:00

<p><strong><a href="https://peps.python.org/pep-0750/">PEP 750 – Tag Strings For Writing Domain-Specific Languages</a></strong></p>
A new PEP by Jim Baker, Guido van Rossum and Paul Everitt that proposes introducing a feature to Python inspired by JavaScript's <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals#tagged_templates">tagged template literals</a>.</p>
<p>F strings in Python already use a <code>f"f prefix"</code>, this proposes allowing any Python symbol in the current scope to be used as a string prefix as well.</p>
<p>I'm excited about this. Imagine being able to compose SQL queries like this:</p>
<pre><span class="pl-s1">query</span> <span class="pl-c1">=</span> <span class="pl-s">sql"select * from articles where id = <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">id</span><span class="pl-kos">}</span></span>"</span></pre>

<p>Where the <code>sql</code> tag ensures that the <code>{id}</code> value there is cor

## Using gpt-4o-mini as a reranker
 - [https://simonwillison.net/2024/Aug/11/using-gpt-4o-mini-as-a-reranker/#atom-everything](https://simonwillison.net/2024/Aug/11/using-gpt-4o-mini-as-a-reranker/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-11T18:06:19+00:00

<p><strong><a href="https://twitter.com/dzhng/status/1822380811372642378">Using gpt-4o-mini as a reranker</a></strong></p>
Tip from David Zhang: "using gpt-4-mini as a reranker gives you better results, and now with strict mode it's just as reliable as any other reranker model".</p>
<p>David's code here demonstrates the <a href="https://sdk.vercel.ai/">Vercel AI SDK</a> for TypeScript, and its support for <a href="https://sdk.vercel.ai/docs/ai-sdk-core/generating-structured-data">structured data</a> using <a href="https://zod.dev/">Zod schemas</a>.</p>
<div class="highlight highlight-source-ts"><pre><span class="pl-k">const</span> <span class="pl-s1">res</span> <span class="pl-c1">=</span> <span class="pl-k">await</span> <span class="pl-en">generateObject</span><span class="pl-kos">(</span><span class="pl-kos">{</span>
  <span class="pl-c1">model</span>: <span class="pl-s1">gpt4MiniModel</span><span class="pl-kos">,</span>
  <span class="pl-c1">prompt</span>: <span class="pl-s">`Given

