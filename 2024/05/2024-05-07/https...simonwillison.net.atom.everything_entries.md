# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Weeknotes: more datasette-secrets, plus a mystery video project
 - [https://simonwillison.net/2024/May/7/datasette-secrets/#atom-everything](https://simonwillison.net/2024/May/7/datasette-secrets/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-07T19:49:02+00:00

<p>I introduced <code>datasette-secrets</code> <a href="https://simonwillison.net/2024/Apr/23/weeknotes/#datasette-secrets">two weeks ago</a>. The core idea is to provide a way for end-users to store secrets such as API keys in Datasette, allowing other plugins to access them.</p>
<p><a href="https://github.com/datasette/datasette-secrets/releases/tag/0.2">datasette-secrets 0.2</a> is the first non-alpha release of that project. The big new feature is that the plugin is <a href="https://github.com/datasette/datasette-secrets/issues/15">now compatible</a> with both the Datasette 1.0 alphas and the stable releases of Datasette (currently Datasette 0.64.6).</p>
<p>My policy at the moment is that a plugin that only works with the Datasette 1.0 alphas must itself be an alpha release. I've been feeling the weight of this as the number of plugins that depend on 1.0a has grown - on the one hand it's a great reason to push through to that 1.0 stable release, but it's painful to have so many fe

## Deterministic Quoting: Making LLMs Safe for Healthcare
 - [https://simonwillison.net/2024/May/7/deterministic-quoting/#atom-everything](https://simonwillison.net/2024/May/7/deterministic-quoting/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-07T19:08:04+00:00

<p><a href="https://mattyyeung.github.io/deterministic-quoting">Deterministic Quoting: Making LLMs Safe for Healthcare</a></p>
Matt Yeung introduces <strong>Deterministic Quoting</strong>, a technique to help reduce the risk of hallucinations while working with LLMs. The key idea is to have parts of the output that are copied directly from relevant source documents, with a different visual treatment to help indicate that they are exact quotes, not generated output.</p>
<blockquote>
<p>The AI chooses which section of source material to quote, but the retrieval of that text is a traditional non-AI database lookup. That’s the only way to guarantee that an LLM has not transformed text: don’t send it through the LLM in the first place.</p>
</blockquote>
<p>The LLM may still pick misleading quotes or include hallucinated details in the accompanying text, but this is still a useful improvement.</p>
<p>The implementation is straight-forward: retrieved chunks include a unique reference, and th

## Quoting @deepfates
 - [https://simonwillison.net/2024/May/7/deepfates/#atom-everything](https://simonwillison.net/2024/May/7/deepfates/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-07T15:59:47+00:00

<blockquote cite="https://twitter.com/deepfates/status/1787472784106639418"><p>Watching in real time as &quot;slop&quot; becomes a term of art. the way that &quot;spam&quot; became the term for unwanted emails, &quot;slop&quot; is going in the dictionary as the term for unwanted AI generated content</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/deepfates/status/1787472784106639418">@deepfates</a>

## OpenAI cookbook: How to get token usage data for streamed chat completion response
 - [https://simonwillison.net/2024/May/7/token-usage-data-for-streamed-chat/#atom-everything](https://simonwillison.net/2024/May/7/token-usage-data-for-streamed-chat/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-07T02:46:45+00:00

<p><a href="https://cookbook.openai.com/examples/how_to_stream_completions#4-how-to-get-token-usage-data-for-streamed-chat-completion-response">OpenAI cookbook: How to get token usage data for streamed chat completion response</a></p>
New feature in the OpenAI streaming API that I've been wanting for a long time: you can now set <code>stream_options={"include_usage": True}</code> to get back a <code>"usage"</code> block at the end of the stream showing how many input and output tokens were used.</p>
<p>This means you can now accurately account for the total cost of each streaming API call. Previously this information was only an available for non-streaming responses.

    <p>Via <a href="https://twitter.com/athyuttamre/status/1787600929040343420">@athyuttamre</a></p>

