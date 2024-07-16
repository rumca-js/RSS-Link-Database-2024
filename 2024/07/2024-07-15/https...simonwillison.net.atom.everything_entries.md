# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Follow the Crypto
 - [https://simonwillison.net/2024/Jul/15/follow-the-crypto/#atom-everything](https://simonwillison.net/2024/Jul/15/follow-the-crypto/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-15T22:06:29+00:00

<p><a href="https://www.followthecrypto.org/">Follow the Crypto</a></p>
Very smart new site from Molly White tracking the huge increase in activity from Cryptocurrency-focused PACs this year. These PACs have already raised $203 million and spent $38 million influencing US elections in 2024.</p>
<p>Right now <a href="https://www.followthecrypto.org/committees/ranking/super">Molly's rankings show</a> that the "Fairshake" cryptocurrency PAC is second only to the Trump-supporting "Make America Great Again Inc" in money raised by Super PACs this year - though it's 9th in <a href="https://www.followthecrypto.org/committees/ranking/all">the list that includes other types of PAC</a>.</p>
<p>Molly's data comes from the FEC, and the code behind the site <a href="https://github.com/molly/follow-the-crypto">is all open source</a>.</p>
<p>There's lots more about the project in the latest edition of <a href="https://www.citationneeded.news/follow-the-crypto/">Molly's newsletter</a>:</p>
<blockquote

## Quoting Alex Albert
 - [https://simonwillison.net/2024/Jul/15/alex-albert/#atom-everything](https://simonwillison.net/2024/Jul/15/alex-albert/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-15T21:33:17+00:00

<blockquote cite="https://twitter.com/alexalbert__/status/1812921642143900036"><p>We've doubled the max output token limit for Claude 3.5 Sonnet from 4096 to 8192 in the Anthropic API.</p>
<p>Just add the header <code>"anthropic-beta": "max-tokens-3-5-sonnet-2024-07-15"</code> to your API calls.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/alexalbert__/status/1812921642143900036">Alex Albert</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/alex-albert">alex-albert</a>, <a href="https://simonwillison.net/tags/anthropic">anthropic</a>, <a href="https://simonwillison.net/tags/claude">claude</a>, <a href="https://simonwillison.net/tags/generative-ai">generative-ai</a>, <a href="https://simonwillison.net/tags/ai">ai</a>, <a href="https://simonwillison.net/tags/llms">llms</a></p>

## Facebook Is the 'Zombie Internet'
 - [https://simonwillison.net/2024/Jul/15/facebook-is-the-zombie-internet/#atom-everything](https://simonwillison.net/2024/Jul/15/facebook-is-the-zombie-internet/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-15T18:56:54+00:00

<p><a href="https://www.404media.co/email/24eb6cea-6fa6-4b98-a2d2-8c4ba33d6c04/">Facebook Is the &#x27;Zombie Internet&#x27;</a></p>
Ever since Facebook started to become infested with weird AI-generated images of shrimp Jesus - with thousands of comments and likes - I've been wondering how much of that activity is real humans as opposed to yet more bots.</p>
<p>Jason Koebler has been on the Facebook AI slop beat for a while. In this superb piece of online investigative reporting he dives deep into an attempt to answer that question, using multiple Facebook burner accounts and contacting more than 300 users who have commented on that kind of image.</p>
<blockquote>
<p>I endlessly tried to talk to people who commented on these images, but I had no luck at all. Over the course of several months, I messaged 300 people who commented on bizarre AI-generated images, which I could only do 20 or so at a time before Facebook stopped letting me send messages for several hours. I also commented 

## Hacker News homepage with links to comments ordered by most recent first
 - [https://simonwillison.net/2024/Jul/15/hacker-news-homepage-with-links/#atom-everything](https://simonwillison.net/2024/Jul/15/hacker-news-homepage-with-links/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-15T17:48:07+00:00

<p><a href="https://observablehq.com/@simonw/hacker-news-homepage">Hacker News homepage with links to comments ordered by most recent first</a></p>
Conversations on Hacker News are displayed as a tree, which can make it difficult to spot new comments added since the last time you viewed the thread.</p>
<p>There's a workaround for this using the <a href="https://hn.algolia.com/">Hacker News Algolia Search</a> interface: search for <code>story:STORYID</code>, select "comments" and the result will be a list of comments sorted by most recent first.</p>
<p>I got fed up of doing this manually so I built a quick tool in an Observable Notebook that documents the hack, provides a UI for pasting in a Hacker News URL to get back that search interface link and also shows the most recent items on the homepage with links to their most recently added comments.</p>
<p>See also my <a href="https://til.simonwillison.net/hacker-news/recent-comments">How to read Hacker News threads with most recent comme

