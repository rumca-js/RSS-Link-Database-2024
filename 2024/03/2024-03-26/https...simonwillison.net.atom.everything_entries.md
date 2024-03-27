# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## gchq.github.io/CyberChef
 - [https://simonwillison.net/2024/Mar/26/cyberchef/#atom-everything](https://simonwillison.net/2024/Mar/26/cyberchef/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-26T17:08:34+00:00

<p><a href="https://gchq.github.io/CyberChef/">gchq.github.io/CyberChef</a></p>
<p>CyberChef is &quot;the Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis&quot; - entirely client-side JavaScript with dozens of useful tools for working with different formats and encodings.</p>

<p>It&#x27;s maintained and released by GCHQ - the UK government&#x27;s signals intelligence security agency.</p>

<p>I didn&#x27;t know GCHQ had a presence on GitHub, and I find the URL to this tool absolutely delightful. They first released it back in 2016 and it has over 3,700 commits.</p>

<p>The top maintainers also have suitably anonymous usernames - great work, n1474335, j433866, d98762625 and n1073645.</p>

    <p>Via <a href="https://mastodon.social/@Jermolene/112161646718885929">Jeremy Ruston</a></p>

## llm cmd undo last git commit - a new plugin for LLM
 - [https://simonwillison.net/2024/Mar/26/llm-cmd/#atom-everything](https://simonwillison.net/2024/Mar/26/llm-cmd/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-26T15:37:24+00:00

<p>I just released a neat new plugin for my <a href="https://llm.datasette.io/">LLM</a> command-line tool: <a href="https://github.com/simonw/llm-cmd">llm-cmd</a>. It lets you run a command to to generate a further terminal command, review and edit that command, then hit <code>&lt;enter&gt;</code> to execute it or <code>&lt;ctrl-c&gt;</code> to cancel.</p>
<p>This is an alpha release. It's a <strong>very dangerous</strong> piece of software! Do not use this unless you are fluent in terminal and confident that you understand what it's doing for you and what could go wrong. I take no responsibility if you accidentally delete all of your files with this tool.</p>
<p>To try this out, you'll need my LLM tool installed:</p>
<div class="highlight highlight-source-shell"><pre>brew install llm <span class="pl-c"><span class="pl-c">#</span> 'pipx install llm' works too</span>
llm keys <span class="pl-c1">set</span> openai
<span class="pl-k">&lt;</span>paste <span class="pl-k">in</span>

## GGML GGUF File Format Vulnerabilities
 - [https://simonwillison.net/2024/Mar/26/ggml-gguf-file-format-vulnerabilities/#atom-everything](https://simonwillison.net/2024/Mar/26/ggml-gguf-file-format-vulnerabilities/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-26T06:47:17+00:00

<p><a href="https://www.databricks.com/blog/ggml-gguf-file-format-vulnerabilities">GGML GGUF File Format Vulnerabilities</a></p>
<p>The GGML and GGUF formats are used by llama.cpp to package and distribute model weights.</p>

<p>Neil Archibald: &quot;The GGML library performs insufficient validation on the input file and, therefore, contains a selection of potentially exploitable memory corruption vulnerabilities during parsing.&quot;</p>

<p>These vulnerabilities were shared with the library authors on 23rd January and patches landed on the 29th.</p>

<p>If you have a llama.cpp or llama-cpp-python installation that&#x27;s more than a month old you should upgrade ASAP.</p>

## Cohere int8 & binary Embeddings - Scale Your Vector Database to Large Datasets
 - [https://simonwillison.net/2024/Mar/26/cohere-int8-binary-embeddings/#atom-everything](https://simonwillison.net/2024/Mar/26/cohere-int8-binary-embeddings/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-26T06:19:30+00:00

<p><a href="https://txt.cohere.com/int8-binary-embeddings/">Cohere int8 &amp; binary Embeddings - Scale Your Vector Database to Large Datasets</a></p>
<p>Jo Kristian Bergum told me &quot;The accuracy retention [of binary embedding vectors] is sensitive to whether the model has been using this binarization as part of the loss function.&quot;</p>

<p>Cohere provide an API for embeddings, and last week added support for returning binary vectors specifically tuned in this way.</p>

<p>250M embeddings (Cohere provide a downloadable dataset of 250M embedded documents from Wikipedia) at float32 (4 bytes) is 954GB.</p>

<p>Cohere claim that reducing to 1 bit per dimension knocks that down to 30 GB (954/32) while keeping &quot;90-98% of the original search quality&quot;.</p>

    <p>Via <a href="https://twitter.com/jobergum/status/1772507515076415803">@jobergum</a></p>

## My binary vector search is better than your FP32 vectors
 - [https://simonwillison.net/2024/Mar/26/binary-vector-search/#atom-everything](https://simonwillison.net/2024/Mar/26/binary-vector-search/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-26T04:56:25+00:00

<p><a href="https://blog.pgvecto.rs/my-binary-vector-search-is-better-than-your-fp32-vectors">My binary vector search is better than your FP32 vectors</a></p>
<p>I&#x27;m still trying to get my head around this, but here&#x27;s what I understand so far.</p>

<p>Embedding vectors as calculated by models such as OpenAI text-embedding-3-small are arrays of floating point values, which look something like this:</p>

<p>[0.0051681744, 0.017187592, -0.018685209, -0.01855924, -0.04725188...] - 1356 elements long</p>

<p>Different embedding models have different lengths, but they tend to be hundreds up to low thousands of numbers. If each float is 32 bits that&#x27;s 4 bytes per float, which can add up to a lot of memory if you have millions of embedding vectors to compare.</p>

<p>If you look at those numbers you&#x27;ll note that they are all pretty small positive or negative numbers, close to 0.</p>

<p>Binary vector search is a trick where you take that sequence of floating point

## Semgrep: AutoFixes using LLMs
 - [https://simonwillison.net/2024/Mar/26/semgrep-autofixes-using-llms/#atom-everything](https://simonwillison.net/2024/Mar/26/semgrep-autofixes-using-llms/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-26T00:51:37+00:00

<p><a href="https://choly.ca/post/semgrep-autofix-llm/">Semgrep: AutoFixes using LLMs</a></p>
<p>semgrep is a really neat tool for semantic grep against source code - you can give it a pattern like &quot;log.$A(...)&quot; to match all forms of log.warning(...) / log.error(...) etc.</p>

<p>Ilia Choly built semgrepx -  xargs for semgrep - and here shows how it can be used along with my llm CLI tool to execute code replacements against matches by passing them through an LLM such as Claude 3 Opus.</p>

    <p>Via <a href="https://lobste.rs/s/qtokfw/semgrep_autofixes_using_llms">lobste.rs</a></p>

