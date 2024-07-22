# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## So you think you know box shadows?
 - [https://simonwillison.net/2024/Jul/21/so-you-think-you-know-box-shadows/#atom-everything](https://simonwillison.net/2024/Jul/21/so-you-think-you-know-box-shadows/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-21T16:23:39+00:00

<p><a href="https://dgerrells.com/blog/how-not-to-use-box-shadows">So you think you know box shadows?</a></p>
David Gerrells dives <em>deep</em> into CSS box shadows. How deep? Implementing a full ray tracer with them deep.

    <p>Via <a href="https://news.ycombinator.com/item?id=41024664">Hacker News</a></p>


    <p>Tags: <a href="https://simonwillison.net/tags/css">css</a>, <a href="https://simonwillison.net/tags/javascript">javascript</a></p>

## Quoting Chris Albon
 - [https://simonwillison.net/2024/Jul/21/chris-albon/#atom-everything](https://simonwillison.net/2024/Jul/21/chris-albon/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-21T15:08:31+00:00

<blockquote cite="https://twitter.com/chrisalbon/status/1814676689580139007"><p>I have a hard time describing the real value of consumer AI because it’s less some grand thing around AI agents or anything and more AI saving humans a hour of work on some random task, millions of times a day.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/chrisalbon/status/1814676689580139007">Chris Albon</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/ai">ai</a>, <a href="https://simonwillison.net/tags/llms">llms</a></p>

## pip install GPT
 - [https://simonwillison.net/2024/Jul/21/pip-install-gpt/#atom-everything](https://simonwillison.net/2024/Jul/21/pip-install-gpt/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-21T05:54:24+00:00

<p><a href="https://chatgpt.com/g/g-470NtUZER-pip-install">pip install GPT</a></p>
I've been uploading wheel files to ChatGPT in order to install them into Code Interpreter <a href="https://til.simonwillison.net/llms/code-interpreter-expansions">for a while now</a>. Nico Ritschel built a better way: this GPT can download wheels directly from PyPI and then install them.</p>
<p>I didn't think this was possible, since Code Interpreter is blocked from making outbound network requests.</p>
<p>Nico's trick uses a new-to-me feature of GPT Actions: you can <a href="https://platform.openai.com/docs/actions/sending-files/returning-files">return up to ten files</a> from an action call and ChatGPT will download those files to the same disk volume that Code Interpreter can access.</p>
<p>Nico wired up a Val Town endpoint that can divide a PyPI wheel into multiple 9.5MB files (if necessary) to fit the file size limit for files returned to a GPT, then uses prompts to tell ChatGPT to combine the resu

