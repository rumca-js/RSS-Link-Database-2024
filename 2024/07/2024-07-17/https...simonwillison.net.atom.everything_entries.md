# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## An example running DuckDB in ChatGPT Code Interpreter
 - [https://simonwillison.net/2024/Jul/17/duckdb-in-chatgpt-code-interpreter/#atom-everything](https://simonwillison.net/2024/Jul/17/duckdb-in-chatgpt-code-interpreter/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-17T21:04:27+00:00

<p><a href="https://chatgpt.com/share/de75e15e-d990-4c4e-b168-9f0390516dbe">An example running DuckDB in ChatGPT Code Interpreter</a></p>
I confirmed today that DuckDB can indeed be run inside ChatGPT Code Interpreter (aka "data analysis"), provided you upload the correct wheel file for it to install. The wheel file it needs is currently <code>duckdb-1.0.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl</code> from the <a href="https://pypi.org/project/duckdb/#files">PyPI releases page</a> - I asked ChatGPT to identify its platform, and it said that it needs <code>manylinux2014_x86_64.whl</code> wheels.</p>
<p>Once the wheel in installed ChatGPT already knows enough of the DuckDB API to start performing useful operations with it - and any brand new features in 1.0 will work if you tell it how to use them.

    <p>Via <a href="https://twitter.com/simonw/status/1813678487573852594">@simonw</a></p>


    <p>Tags: <a href="https://simonwillison.net/tags/duckdb">duckdb</a>, <a h

## Introducing Llama-3-Groq-Tool-Use Models
 - [https://simonwillison.net/2024/Jul/17/llama-3-groq-tool-use-models/#atom-everything](https://simonwillison.net/2024/Jul/17/llama-3-groq-tool-use-models/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-17T20:32:50+00:00

<p><a href="https://wow.groq.com/introducing-llama-3-groq-tool-use-models/">Introducing Llama-3-Groq-Tool-Use Models</a></p>
New from <a href="https://groq.com/">Groq</a>: two custom fine-tuned Llama 3 models specifically designed for tool use. Hugging Face model links:</p>
<ul>
<li><a href="https://huggingface.co/Groq/Llama-3-Groq-8B-Tool-Use">Groq/Llama-3-Groq-8B-Tool-Use</a></li>
<li><a href="https://huggingface.co/Groq/Llama-3-Groq-70B-Tool-Use">Groq/Llama-3-Groq-70B-Tool-Use</a></li>
</ul>
<p>Groq's own internal benchmarks put their 70B model at the top of the <a href="https://gorilla.cs.berkeley.edu/leaderboard.html">Berkeley Function-Calling Leaderboard</a> with a score of 90.76 (and 89.06 for their 8B model, which would put it at #3). For comparison, Claude 3.5 Sonnet scores 90.18 and GPT-4-0124 scores 88.29.</p>
<p>The two new Groq models are also available through their screamingly-fast (fastest in the business?) API, running at 330 tokens/s and 1050 tokens/s respectively.</

## AI Tooling for Software Engineers in 2024
 - [https://simonwillison.net/2024/Jul/17/ai-tooling/#atom-everything](https://simonwillison.net/2024/Jul/17/ai-tooling/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-17T17:19:49+00:00

<p><a href="https://newsletter.pragmaticengineer.com/p/ai-tooling-2024">AI Tooling for Software Engineers in 2024</a></p>
Gergely Orosz reports back on the survey he ran of 211 tech professionals concerning their use of generative AI. One interesting result:</p>
<blockquote>
<p>The responses reveal that as many professionals are using <em>both</em> ChatGPT and GitHub Copilot as all other tools combined!</p>
</blockquote>


    <p>Tags: <a href="https://simonwillison.net/tags/generative-ai">generative-ai</a>, <a href="https://simonwillison.net/tags/chatgpt">chatgpt</a>, <a href="https://simonwillison.net/tags/github-copilot">github-copilot</a>, <a href="https://simonwillison.net/tags/ai">ai</a>, <a href="https://simonwillison.net/tags/llms">llms</a>, <a href="https://simonwillison.net/tags/gergely-orosz">gergely-orosz</a></p>

## Announcing our DjangoCon US 2024 Talks!
 - [https://simonwillison.net/2024/Jul/17/djangocon-us-2024-talks/#atom-everything](https://simonwillison.net/2024/Jul/17/djangocon-us-2024-talks/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-17T03:20:57+00:00

<p><a href="https://2024.djangocon.us/news/announcing-lineup/">Announcing our DjangoCon US 2024 Talks!</a></p>
I'm speaking at DjangoCon in Durham, NC in September.</p>
<p>My accepted talk title was <strong>How to design and implement extensible software with plugins</strong>. Here's my abstract:</p>
<blockquote>
<p>Plugins offer a powerful way to extend software packages. Tools that support a plugin architecture include WordPress, Jupyter, VS Code and pytest - each of which benefits from an enormous array of plugins adding all kinds of new features and expanded capabilities.</p>
<p>Adding plugin support to an open source project can greatly reduce the friction involved in attracting new contributors. Users can work independently and even package and publish their work without needing to directly coordinate with the project's core maintainers. As a maintainer this means you can wake up one morning and your software grew new features without you even having to review a pull request!</p

## Quoting Lattice (HR platform)
 - [https://simonwillison.net/2024/Jul/17/lattice-hr-platform/#atom-everything](https://simonwillison.net/2024/Jul/17/lattice-hr-platform/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-17T03:08:02+00:00

<blockquote cite="https://lattice.com/blog/leading-the-way-in-responsible-ai-employment"><p>Update, July 12: This innovation sparked a lot of conversation and questions that have no answers yet. We look forward to continuing to work with our customers on the responsible use of AI, but will not further pursue digital workers in the product.</p></blockquote><p class="cite">&mdash; <a href="https://lattice.com/blog/leading-the-way-in-responsible-ai-employment">Lattice (HR platform)</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/ai">ai</a>, <a href="https://simonwillison.net/tags/ethics">ethics</a></p>

