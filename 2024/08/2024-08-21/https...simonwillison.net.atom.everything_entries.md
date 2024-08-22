# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Armin Ronacher
 - [https://simonwillison.net/2024/Aug/21/armin-ronacher/#atom-everything](https://simonwillison.net/2024/Aug/21/armin-ronacher/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-21T12:08:15+00:00

<blockquote cite="https://lucumr.pocoo.org/2024/8/21/harvest-season/"><p>There is an elephant in the room which is that Astral is a VC funded company. What does that mean for the future of these tools? Here is my take on this: for the community having someone pour money into it can create some challenges. For the PSF and the core Python project this is something that should be considered. However having seen the code and what uv is doing, even in the worst possible future this is a very forkable and maintainable thing. I believe that even in case Astral shuts down or were to do something incredibly dodgy licensing wise, the community would be better off than before uv existed.</p></blockquote><p class="cite">&mdash; <a href="https://lucumr.pocoo.org/2024/8/21/harvest-season/">Armin Ronacher</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/python">python</a>, <a href="https://simonwillison.net/tags/uv">uv</a>, <a href="https://simonwillison.net/tags/astral">astral</a>, <a 

## #!/usr/bin/env uv run
 - [https://simonwillison.net/2024/Aug/21/usrbinenv-uv-run/#atom-everything](https://simonwillison.net/2024/Aug/21/usrbinenv-uv-run/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-21T01:29:54+00:00

<p><strong><a href="https://github.com/alsuren/sixdofone/blob/3ed09b930b1bf6e553b382588ab41d0c43a52744/app.py#L1-L14">#!/usr/bin/env uv run</a></strong></p>
This is a really neat pattern. Start your Python script like this:</p>
<pre><code>#!/usr/bin/env uv run
# /// script
# requires-python = "&gt;=3.12"
# dependencies = [
#     "flask==3.*",
# ]
# ///
import flask
# ...
</code></pre>
<p>And now if you <code>chmod 755</code> it you can run it on <em>any machine</em> with the <code>uv</code> binary installed like this: <code>./app.py</code> - and it will automatically create its own isolated environment and run itself with the correct installed dependencies and even the correctly installed Python version.</p>
<p>All of that from putting <code>uv run</code> in the shebang line!</p>
<p>Code from <a href="https://github.com/alsuren/sixdofone/pull/8">this PR</a> by David Laban.

    <p><small></small>Via <a href="https://twitter.com/charliermarsh/status/1826008669131067757">@charliermarsh<

## The dangers of AI agents unfurling hyperlinks and what to do about it
 - [https://simonwillison.net/2024/Aug/21/dangers-of-ai-agents-unfurling/#atom-everything](https://simonwillison.net/2024/Aug/21/dangers-of-ai-agents-unfurling/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-21T00:58:24+00:00

<p><strong><a href="https://embracethered.com/blog/posts/2024/the-dangers-of-unfurling-and-what-you-can-do-about-it/">The dangers of AI agents unfurling hyperlinks and what to do about it</a></strong></p>
Here’s a prompt injection exfiltration vulnerability I hadn’t thought about before: chat systems such as Slack and Discord implement “unfurling”, where any URLs pasted into the chat are fetched in order to show a title and preview image.</p>
<p>If your chat environment includes a chatbot with access to private data and that’s vulnerable to prompt injection, a successful attack could paste a URL to an attacker’s server into the chat in such a way that the act of unfurling that link leaks private data embedded in that URL.</p>
<p>Johann Rehberger notes that apps posting messages to Slack can opt out of having their links unfurled by passing the <code>"unfurl_links": false, "unfurl_media": false</code> properties to the Slack messages API, which can help protect against this exfiltratio

