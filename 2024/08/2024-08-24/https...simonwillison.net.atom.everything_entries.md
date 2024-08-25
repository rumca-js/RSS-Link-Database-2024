# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Andy Jassy, Amazon CEO
 - [https://simonwillison.net/2024/Aug/24/andy-jassy-amazon-ceo/#atom-everything](https://simonwillison.net/2024/Aug/24/andy-jassy-amazon-ceo/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-24T04:25:06+00:00

<blockquote cite="https://www.linkedin.com/posts/andy-jassy-8b1615_one-of-the-most-tedious-but-critical-tasks-activity-7232374162185461760-AdSz/"><p>[...] here’s what we found when we integrated [Amazon Q, GenAI assistant for software development] into our internal systems and applied it to our needed Java upgrades:</p>
<ul>
<li>The average time to upgrade an application to Java 17 plummeted from what’s typically 50 developer-days to just a few hours. We estimate this has saved us the equivalent of 4,500 developer-years of work (yes, that number is crazy but, real).</li>
<li>In under six months, we've been able to upgrade more than 50% of our production Java systems to modernized Java versions at a fraction of the usual time and effort. And, our developers shipped 79% of the auto-generated code reviews without any additional changes.</li>
</ul></blockquote><p class="cite">&mdash; <a href="https://www.linkedin.com/posts/andy-jassy-8b1615_one-of-the-most-tedious-but-critical-tasks-activ

## Musing about OAuth and LLMs on Mastodon
 - [https://simonwillison.net/2024/Aug/24/oauth-llms/#atom-everything](https://simonwillison.net/2024/Aug/24/oauth-llms/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-24T00:29:47+00:00

<p><strong><a href="https://fedi.simonwillison.net/@simon/113014147494012212">Musing about OAuth and LLMs on Mastodon</a></strong></p>
Lots of people are asking why Anthropic and OpenAI don't support OAuth, so you can bounce users through those providers to get a token that uses their API budget for your app.</p>
<p>My guess: they're worried malicious app developers would use it to trick people and obtain valid API keys.</p>
<p>Imagine a version of my dumb little <a href="https://tools.simonwillison.net/haiku">write a haiku about a photo you take</a> page which used OAuth, harvested API keys and then racked up hundreds of dollar bills against everyone who tried it out running illicit election interference campaigns or whatever.</p>
<p>I'm trying to think of an OAuth API that dishes out tokens which effectively let you <em>spend money on behalf of your users</em> and I can't think of any - OAuth is great for "grant this app access to data that I want to share", but "spend money on my b

