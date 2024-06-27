# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## picopilot
 - [https://simonwillison.net/2024/Jun/26/picopilot/#atom-everything](https://simonwillison.net/2024/Jun/26/picopilot/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-26T00:24:21+00:00

<p><a href="https://github.com/coder/picopilot">picopilot</a></p>
Kyle Carberry's "GitHub Copilot in 70 lines of JavaScript". The title is a little hyperbolic, but the code itself really does implement an OpenAI powered Visual Studio Code text completion extension in <a href="https://github.com/coder/picopilot/blob/f71c6ab4738d4159d18aa772b22f4b1d24c89899/extension.js">71 lines of code</a>. This is an excellent example for learning what a minimal VS Code extension looks like.</p>
<p>Here's the system prompt it uses:</p>
<p><code>You provide code completion results given a prefix and suffix. Respond with a JSON object with the key 'completion' containing a suggestion to place between the prefix and suffix. Follow existing code styles. Listen to comments at the end of the prefix. The language is "{language}".</code></p>
<p>Then it passes the prefix and suffix as two user messages, and uses the <code>"response_format": {"type": "json_object"}</code> option to enforce JSON output from the

