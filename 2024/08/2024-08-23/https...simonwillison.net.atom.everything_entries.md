# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Top companies ground Microsoft Copilot over data governance concerns
 - [https://simonwillison.net/2024/Aug/23/microsoft-copilot-data-governance/#atom-everything](https://simonwillison.net/2024/Aug/23/microsoft-copilot-data-governance/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-23T14:26:00+00:00

<p><strong><a href="https://www.theregister.com/2024/08/21/microsoft_ai_copilots/">Top companies ground Microsoft Copilot over data governance concerns</a></strong></p>
Microsoft’s use of the term “Copilot” is pretty confusing these days - this article appears to be about <a href="https://www.microsoft.com/en-us/microsoft-365/enterprise/copilot-for-microsoft-365">Microsoft 365 Copilot</a>, which is effectively an internal RAG chatbot with access to your company’s private data from tools like SharePoint.</p>
<p>The concern here isn’t the usual fear of data leaked to the model or prompt injection security concerns. It’s something much more banal: it turns out many companies don’t have the right privacy controls in place to safely enable these tools. Jack Berkowitz:</p>
<blockquote>
<p>Particularly around bigger companies that have complex permissions around their SharePoint or their Office 365 or things like that, where the Copilots are basically aggressively summarizing information tha

## Explain ACLs by showing me a SQLite table schema for implementing them
 - [https://simonwillison.net/2024/Aug/23/explain-acls/#atom-everything](https://simonwillison.net/2024/Aug/23/explain-acls/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-23T05:57:45+00:00

<p><strong><a href="https://gist.github.com/simonw/20b2e8c4d9d9d8d6dee327c221e57205">Explain ACLs by showing me a SQLite table schema for implementing them</a></strong></p>
Here’s an example transcript showing one of the common ways I use LLMs. I wanted to develop an understanding of ACLs - Access Control Lists - but I’ve found previous explanations <em>incredibly dry</em>. So I prompted Claude 3.5 Sonnet:</p>
<blockquote>
<p>Explain ACLs by showing me a SQLite table schema for implementing them</p>
</blockquote>
<p>Asking for explanations using the context of something I’m already fluent in is usually really effective, and an great way to take advantage of the weird abilities of frontier LLMs.</p>
<p>I exported the transcript to a Gist using my <a href="https://observablehq.com/@simonw/convert-claude-json-to-markdown">Convert Claude JSON to Markdown</a> tool, which I just upgraded to support syntax highlighting of code in artifacts.


    <p>Tags: <a href="https://simonwillison.net/t

## Claude's API now supports CORS requests, enabling client-side applications
 - [https://simonwillison.net/2024/Aug/23/anthropic-dangerous-direct-browser-access/#atom-everything](https://simonwillison.net/2024/Aug/23/anthropic-dangerous-direct-browser-access/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-23T02:29:08+00:00

<p>Anthropic have enabled CORS support for their JSON APIs, which means it's now possible to call the Claude LLMs directly from a user's browser.</p>

<p>This massively significant new feature is tucked away in this pull request: <a href="https://github.com/anthropics/anthropic-sdk-typescript/pull/504">anthropic-sdk-typescript: add support for browser usage</a>, via <a href="https://github.com/anthropics/anthropic-sdk-typescript/issues/248#issuecomment-2302791227" title="Add a dangerouslyAllowBrowser option to allow running in the browser">this issue</a>.</p>

<p>This change to the <a href="https://github.com/anthropics/anthropic-sdk-typescript">Anthropic TypeScript SDK</a> reveals the new JSON API feature, which I found <a href="https://github.com/anthropics/anthropic-sdk-typescript/blob/e400d2e8a54aa736717ed849ef8b44a3490fce68/src/index.ts#L151">by digging through the code</a>.</p>
<p>You can now add the following HTTP request header to enable CORS support for the Anthropic API, whi

