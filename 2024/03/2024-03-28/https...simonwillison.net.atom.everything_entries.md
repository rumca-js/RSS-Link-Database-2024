# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Merge pull request #1757 from simonw/heic-heif
 - [https://simonwillison.net/2024/Mar/28/merge-pull-request/#atom-everything](https://simonwillison.net/2024/Mar/28/merge-pull-request/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-28T05:37:31+00:00

<p><a href="https://github.com/gchq/CyberChef/commit/674c8c7c87eff167f03ee42c998c7fff18da4fa3">Merge pull request #1757 from simonw/heic-heif</a></p>
<p>I got a PR into GCHQ&#x27;s CyberChef this morning! I added support for detecting heic/heif files to the Forensics -&gt; Detect File Type tool.</p>

<p>The change was landed by the delightfully mysterious a3957273.</p>

## Wrap text at specified width
 - [https://simonwillison.net/2024/Mar/28/wrap-text-at-specified-width/#atom-everything](https://simonwillison.net/2024/Mar/28/wrap-text-at-specified-width/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-28T03:36:01+00:00

<p><a href="https://observablehq.com/@simonw/wrap-text-at-specified-width">Wrap text at specified width</a></p>
<p>New Observable notebook. I built this with the help of Claude 3 Opus - it&#x27;s a text wrapping tool which lets you set the width and also lets you optionally add a four space indent.</p>

<p>The four space indent is handy for posting on forums such as Hacker News that treat a four space indent as a code block.</p>

## llm-gemini 0.1a1
 - [https://simonwillison.net/2024/Mar/28/llm-gemini-01a1/#atom-everything](https://simonwillison.net/2024/Mar/28/llm-gemini-01a1/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-28T03:32:15+00:00

<p><a href="https://github.com/simonw/llm-gemini/releases/tag/0.1a1">llm-gemini 0.1a1</a></p>
<p>I upgraded my llm-gemini plugin to add support for the new Google Gemini Pro 1.5 model, which is beginning to roll out in early access.</p>

<p>The 1.5 model supports 1,048,576 input tokens and generates up to 8,192 output tokens - a big step up from Gemini 1.0 Pro which handled 30,720 and 2,048 respectively.</p>

<p>The big missing feature from my LLM tool at the moment is image input - a fantastic way to take advantage of that huge context window. I have a branch for this which I really need to get into a useful state.</p>

