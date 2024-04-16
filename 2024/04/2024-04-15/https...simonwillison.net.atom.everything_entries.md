# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## OpenAI Batch API
 - [https://simonwillison.net/2024/Apr/15/openai-batch-api/#atom-everything](https://simonwillison.net/2024/Apr/15/openai-batch-api/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-15T17:58:44+00:00

<p><a href="https://platform.openai.com/docs/api-reference/batch">OpenAI Batch API</a></p>
<p>OpenAI are now offering a 50% discount on batch chat completion API calls if you submit them in bulk and allow for up to 24 hours for them to be run.</p>

<p>Requests are sent as a newline-delimited JSON file, with each line looking something like this:</p>

<p>{&quot;custom_id&quot;: &quot;request-1&quot;, &quot;method&quot;: &quot;POST&quot;, &quot;url&quot;: &quot;/v1/chat/completions&quot;, &quot;body&quot;: {&quot;model&quot;: &quot;gpt-3.5-turbo&quot;, &quot;messages&quot;: [{&quot;role&quot;: &quot;system&quot;, &quot;content&quot;: &quot;You are a helpful assistant.&quot;}, {&quot;role&quot;: &quot;user&quot;, &quot;content&quot;: &quot;What is 2+2?&quot;}]}}</p>

<p>You upload a file for the batch, kick off a batch request and then poll for completion.</p>

<p>This makes GPT-3.5 Turbo cheaper than Claude 3 Opus - provided you&#x27;re willing to wait a few hours for your responses.</p

## Quoting Jason D. Clinton, Anthropic
 - [https://simonwillison.net/2024/Apr/15/jason-d-clinton/#atom-everything](https://simonwillison.net/2024/Apr/15/jason-d-clinton/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-15T01:27:38+00:00

<blockquote cite="https://www.reddit.com/r/ClaudeAI/comments/1c3f1yc/comment/kzj7n4s/"><p>[On complaints about Claude 3 reduction in quality since launch] The model is stored in a static file and loaded, continuously, across 10s of thousands of identical servers each of which serve each instance of the Claude model. The model file never changes and is immutable once loaded; every shard is loading the same model file running exactly the same software. We haven‚Äôt changed the temperature either. We don‚Äôt see anywhere where drift could happen. The files are exactly the same as at launch and loaded each time from a frozen pristine copy.</p></blockquote><p class="cite">&mdash; <a href="https://www.reddit.com/r/ClaudeAI/comments/1c3f1yc/comment/kzj7n4s/">Jason D. Clinton, Anthropic</a>

