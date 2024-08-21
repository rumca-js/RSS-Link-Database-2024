# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Data Exfiltration from Slack AI via indirect prompt injection
 - [https://simonwillison.net/2024/Aug/20/data-exfiltration-from-slack-ai/#atom-everything](https://simonwillison.net/2024/Aug/20/data-exfiltration-from-slack-ai/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-20T19:16:58+00:00

<p><strong><a href="https://promptarmor.substack.com/p/data-exfiltration-from-slack-ai-via">Data Exfiltration from Slack AI via indirect prompt injection</a></strong></p>
Today's prompt injection data exfiltration vulnerability affects Slack. <a href="https://slack.com/features/ai">Slack AI</a> implements a RAG-style chat search interface against public and private data that the user has access to, plus documents that have been uploaded to Slack. PromptArmor identified and reported a vulnerability where an attack can trick Slack into showing user's a Markdown link which, when clicked, passes private data to the attacker's server in the query string.</p>
<p>The attack described here is a little hard to follow. It assumes that a user has access to a private API key (here called "EldritchNexus") that has been shared with them in a private Slack channel.</p>
<p>Then, in a public Slack channel - or potentially in hidden text in a document that someone might have imported into Slack - the a

## Writing your pyproject.toml
 - [https://simonwillison.net/2024/Aug/20/writing-your-pyproject-toml/#atom-everything](https://simonwillison.net/2024/Aug/20/writing-your-pyproject-toml/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-20T00:12:21+00:00

<p><strong><a href="https://packaging.python.org/en/latest/guides/writing-pyproject-toml/">Writing your pyproject.toml</a></strong></p>
When I started <a href="https://til.simonwillison.net/python/pyproject">exploring pyproject.toml a year ago</a> I had trouble finding comprehensive documentation about what should go in that file.</p>
<p>Since then the <a href="https://packaging.python.org/">Python Packaging Guide</a> split out <a href="https://packaging.python.org/en/latest/guides/writing-pyproject-toml/">this page</a>, which is exactly what I was looking for back then.

    <p><small></small>Via <a href="https://github.com/simonw/click-app/pull/10">PR against click-app from @lonnen</a></small></p>


    <p>Tags: <a href="https://simonwillison.net/tags/packaging">packaging</a>, <a href="https://simonwillison.net/tags/python">python</a></p>

