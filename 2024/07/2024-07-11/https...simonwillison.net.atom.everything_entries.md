# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Brian Grubb
 - [https://simonwillison.net/2024/Jul/11/brian-grubb/#atom-everything](https://simonwillison.net/2024/Jul/11/brian-grubb/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-11T21:11:55+00:00

<blockquote cite="https://briancgrubb.substack.com/p/the-five-spot-knives-out-more-like"><p>[On Paddington 3] If this movie is anywhere near as good as the second one, we are going to need to have an extremely serious conversation about this being one of the greatest film trilogies ever made.</p></blockquote><p class="cite">&mdash; <a href="https://briancgrubb.substack.com/p/the-five-spot-knives-out-more-like">Brian Grubb</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/brian-grubb">brian-grubb</a>, <a href="https://simonwillison.net/tags/film">film</a></p>

## The economics of a Postgres free tier
 - [https://simonwillison.net/2024/Jul/11/the-economics-of-a-postgres-free-tier/#atom-everything](https://simonwillison.net/2024/Jul/11/the-economics-of-a-postgres-free-tier/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-11T19:26:35+00:00

<p><a href="https://xata.io/blog/postgres-free-tier">The economics of a Postgres free tier</a></p>
<a href="https://xata.io/">Xata</a> offer a hosted PostgreSQL service with a generous free tier (15GB of volume). I'm very suspicious of free tiers that don't include a detailed breakdown of the unit economics... and in this post they've described exactly that, in great detail.</p>
<p>The trick is that they run their free tier on shared clusters - with each $630/month cluster supporting 2,000 free instances for $0.315 per instance per month. Then inactive databases get downgraded to even cheaper auto-scaling clusters that can host 20,000 databases for $180/month (less than 1c each).</p>
<p>They also cover the volume cost of $0.10/GB/month - so up to $1.50/month per free instance, but most instances only use a small portion of that space.</p>
<p>It's reassuring to see this spelled out in so much detail.

    <p>Via <a href="https://lobste.rs/s/qviw9h/economics_postgres_free_tier">lobste.r

## Quoting Jim Covello, Goldman Sachs
 - [https://simonwillison.net/2024/Jul/11/jim-covello/#atom-everything](https://simonwillison.net/2024/Jul/11/jim-covello/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-11T02:35:09+00:00

<blockquote cite="https://www.goldmansachs.com/intelligence/pages/gen-ai-too-much-spend-too-little-benefit.html"><p>My main concern is that the substantial cost to develop and run Al technology means that Al applications must solve extremely complex and important problems for enterprises to earn an appropriate return on investment.</p>
<p>We estimate that the Al infrastructure buildout will cost over $1tn in the next several years alone, which includes spending on data centers, utilities, and applications. So, the crucial question is: What $1tn problem will Al solve? Replacing low-wage jobs with tremendously costly technology is basically the polar opposite of the prior technology transitions I've witnessed in my thirty years of closely following the tech industry.</p></blockquote><p class="cite">&mdash; <a href="https://www.goldmansachs.com/intelligence/pages/gen-ai-too-much-spend-too-little-benefit.html">Jim Covello, Goldman Sachs</a></p>

    <p>Tags: <a href="https://simonwillison

