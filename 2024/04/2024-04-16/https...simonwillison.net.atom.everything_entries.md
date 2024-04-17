# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Google NotebookLM Data Exfiltration
 - [https://simonwillison.net/2024/Apr/16/google-notebooklm-data-exfiltration/#atom-everything](https://simonwillison.net/2024/Apr/16/google-notebooklm-data-exfiltration/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-16T21:28:39+00:00

<p><a href="https://embracethered.com/blog/posts/2024/google-notebook-ml-data-exfiltration/">Google NotebookLM Data Exfiltration</a></p>
<p>NotebookLM is a Google Labs product that lets you store information as sources (mainly text files in PDF) and then ask questions against those sources - effectively an interface for building your own custom RAG (Retrieval Augmented Generation) chatbots.</p>

<p>Unsurprisingly for anything that allows LLMs to interact with untrusted documents, it&#x27;s susceptible to prompt injection.</p>

<p>Johann Rehberger found some classic prompt injection exfiltration attacks: you can create source documents with instructions that cause the chatbot to load a Markdown image that leaks other private data to an external domain as data passed in the query string.</p>

<p>Johann reported this privately in the December but the problem has not yet been addressed.</p>

<p>A good rule of thumb is that any time you let LLMs see untrusted tokens there is a risk of an a

## Quoting wkirby on Hacker News
 - [https://simonwillison.net/2024/Apr/16/wkirby-on-hacker-news/#atom-everything](https://simonwillison.net/2024/Apr/16/wkirby-on-hacker-news/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-16T19:49:16+00:00

<blockquote cite="https://news.ycombinator.com/item?id=40052729#40054080"><p>Permissions have three moving parts, who wants to do it, what do they want to do, and on what object. Any good permission system has to be able to efficiently answer any permutation of those variables. Given this person and this object, what can they do? Given this object and this action, who can do it? Given this person and this action, which objects can they act upon?</p></blockquote><p class="cite">&mdash; <a href="https://news.ycombinator.com/item?id=40052729#40054080">wkirby on Hacker News</a>

## inline-snapshot
 - [https://simonwillison.net/2024/Apr/16/inline-snapshot/#atom-everything](https://simonwillison.net/2024/Apr/16/inline-snapshot/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-16T16:04:25+00:00

<p><a href="https://15r10nk.github.io/inline-snapshot/">inline-snapshot</a></p>
<p>I&#x27;m a big fan of snapshot testing, where expected values are captured the first time a test suite runs and then asserted against in future runs. It&#x27;s a very productive way to build a robust test suite.</p>

<p>inline-snapshot by Frank Hoffmann is a particularly neat implementation of the pattern. It defines a snapshot() function which you can use in your tests:</p>

<p>assert 1548 * 18489 == snapshot()</p>

<p>When you run that test using &quot;pytest --inline-snapshot=create&quot; the snapshot() function will be replaced in your code (using AST manipulation) with itself wrapping the repr() of the expected result:</p>

<p>assert 1548 * 18489 == snapshot(28620972)</p>

<p>If you modify the code and need to update the tests you can run &quot;pytest --inline-snapshot=fix&quot; to regenerate the recorded snapshot values.</p>

