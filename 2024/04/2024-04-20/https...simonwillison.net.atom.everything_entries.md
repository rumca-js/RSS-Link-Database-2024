# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Tips on Adding JSON Output to Your CLI App
 - [https://simonwillison.net/2024/Apr/20/json-output-cli/#atom-everything](https://simonwillison.net/2024/Apr/20/json-output-cli/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-20T21:43:58+00:00

<p><a href="https://blog.kellybrazil.com/2021/12/03/tips-on-adding-json-output-to-your-cli-app/">Tips on Adding JSON Output to Your CLI App</a></p>
<p>Kelly Brazil - also the author of jc, the neat CLI tool that converts the output of common Unix utilities such as dig into JSON - provides some useful do&#x27;s and don&#x27;ts for adding JSON output as an option to a command-line tool.</p>

<p>Kelly recommends defaulting to arrays of flat objects - or newline-delimited objects - and suggests including an &quot;unbuffer&quot; option for streaming tools that discourages the OS from buffering output that is being sent through a pipe.</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=40098606">Hacker News</a></p>

## llm-gpt4all
 - [https://simonwillison.net/2024/Apr/20/llm-gpt4all/#atom-everything](https://simonwillison.net/2024/Apr/20/llm-gpt4all/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-20T17:58:25+00:00

<p><a href="https://github.com/simonw/llm-gpt4all/releases/tag/0.4">llm-gpt4all</a></p>
<p>New release of my LLM plugin which builds on Nomic&#x27;s excellent gpt4all Python library. I&#x27;ve upgraded to their latest version which adds support for Llama 3 8B Instruct, so after a 4.4GB model download this works:</p>

<p>llm -m Meta-Llama-3-8B-Instruct &quot;say hi in Spanish&quot;</p>

