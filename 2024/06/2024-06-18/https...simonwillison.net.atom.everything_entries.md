# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Tags with descriptions
 - [https://simonwillison.net/2024/Jun/18/tags-with-descriptions/#atom-everything](https://simonwillison.net/2024/Jun/18/tags-with-descriptions/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-18T16:50:07+00:00

<p><a href="https://simonwillison.net/dashboard/tags-with-descriptions/">Tags with descriptions</a></p>
Tiny new feature on my blog: I can now add optional descriptions to my tag pages, for example on <a href="https://simonwillison.net/tags/datasette/">datasette</a> and <a href="https://simonwillison.net/tags/sqliteutils/">sqliteutils</a> and <a href="https://simonwillison.net/tags/promptinjection/">promptinjection</a>.</p>
<p>I built this feature on a live call this morning as an unplanned demonstration of GitHub's new <a href="https://githubnext.com/projects/copilot-workspace">Copilot Workspace</a> feature, where you can run a prompt against a repository and have it plan, implement and file a pull request implementing a change to the code.</p>
<p>My prompt was:</p>
<blockquote>
<p>Add a feature that lets me add a description to my tag pages, stored in the database table for tags and visible on the /tags/x/ page at the top</p>
</blockquote>
<p>It wasn't as compelling a demo as I expe

## Claude: Building evals and test cases
 - [https://simonwillison.net/2024/Jun/18/claude-evals/#atom-everything](https://simonwillison.net/2024/Jun/18/claude-evals/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-18T16:28:50+00:00

<p><a href="https://docs.anthropic.com/en/docs/build-with-claude/develop-tests">Claude: Building evals and test cases</a></p>
More documentation updates from Anthropic: this section on writing evals for Claude is new today and includes Python code examples for a number of different evaluation techniques.</p>
<p>Included are several examples of the LLM-as-judge pattern, plus an example using cosine similarity and another that uses the new-to-me <a href="https://pypi.org/project/rouge/">Rouge</a> Python library that implements the <a href="https://aclanthology.org/W04-1013/">ROUGE metric</a> for evaluating the quality of summarized text.

## Anthropic release notes
 - [https://simonwillison.net/2024/Jun/18/anthropic-release-notes/#atom-everything](https://simonwillison.net/2024/Jun/18/anthropic-release-notes/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-18T16:25:17+00:00

<p><a href="https://docs.anthropic.com/en/release-notes/overview">Anthropic release notes</a></p>
Anthropic have started publishing release notes! Currently available for <a href="https://docs.anthropic.com/en/release-notes/api">their API</a> and <a href="https://docs.anthropic.com/en/release-notes/claude-apps">their apps (mobile and web)</a>.</p>
<p>What I'd really like to see are release notes for the models themselves, though as far as I can tell there haven't been any updates to those since the Claude 3 models were first released (the Haiku model name in the API is still <code>claude-3-haiku-20240307</code> and Anthropic say they'll change that identifier after any updates to the model).

    <p>Via <a href="https://twitter.com/alexalbert__/status/1803099234775994702">Alex Albert</a></p>

