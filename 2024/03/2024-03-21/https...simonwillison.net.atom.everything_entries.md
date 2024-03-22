# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Ryan Broderick
 - [https://simonwillison.net/2024/Mar/21/ryan-broderick/#atom-everything](https://simonwillison.net/2024/Mar/21/ryan-broderick/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-21T21:49:43+00:00

<blockquote cite="https://www.garbageday.email/p/clout-world#a-is-impending-reputation-crisis"><p>At this point, I’m confident saying that 75% of what generative-AI text and image platforms can do is useless at best and, at worst, actively harmful. Which means that if AI companies want to onboard the millions of people they need as customers to fund themselves and bring about the great AI revolution, they’ll have to perpetually outrun the millions of pathetic losers hoping to use this tech to make a quick buck. Which is something crypto has never been able to do.<br /><br />In fact, we may have already reached a point where AI images have become synonymous with scams and fraud.</p></blockquote><p class="cite">&mdash; <a href="https://www.garbageday.email/p/clout-world#a-is-impending-reputation-crisis">Ryan Broderick</a>

## DuckDB as the New jq
 - [https://simonwillison.net/2024/Mar/21/duckdb-as-the-new-jq/#atom-everything](https://simonwillison.net/2024/Mar/21/duckdb-as-the-new-jq/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-21T20:36:20+00:00

<p><a href="https://www.pgrs.net/2024/03/21/duckdb-as-the-new-jq/">DuckDB as the New jq</a></p>
<p>The DuckDB CLI tool can query JSON files directly, making it a surprisingly effective replacement for jq. Paul Gross demonstrates the following query:</p>

<p>select license-&gt;&gt;&#x27;key&#x27; as license, count(*) from &#x27;repos.json&#x27; group by 1</p>

<p>repos.json contains an array of {&quot;license&quot;: {&quot;key&quot;: &quot;apache-2.0&quot;}..} objects. This example query shows counts for each of those licenses.</p>

    <p>Via <a href="https://lobste.rs/s/x5immj/duckdb_as_new_jq">lobste.rs</a></p>

## Redis Adopts Dual Source-Available Licensing
 - [https://simonwillison.net/2024/Mar/21/redis-adopts-dual-source-available-licensing/#atom-everything](https://simonwillison.net/2024/Mar/21/redis-adopts-dual-source-available-licensing/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-21T02:24:40+00:00

<p><a href="https://redis.com/blog/redis-adopts-dual-source-available-licensing/">Redis Adopts Dual Source-Available Licensing</a></p>
<p>Well this sucks: after fifteen years (and contributions from more than 700 people), Redis is dropping the 3-clause BSD license going forward, instead being &quot;dual-licensed under the Redis Source Available License (RSALv2) and Server Side Public License (SSPLv1)&quot; from Redis 7.4 onwards.</p>

    <p>Via <a href="https://mstdn.social/@msw/112130308202090850">@msw</a></p>

## Quoting Jacob Kaplan-Moss
 - [https://simonwillison.net/2024/Mar/21/jacob-kaplan-moss/#atom-everything](https://simonwillison.net/2024/Mar/21/jacob-kaplan-moss/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-21T00:45:47+00:00

<blockquote cite="https://jacobian.org/2024/mar/20/django-chat/"><p>I think most people have this naive idea of consensus meaning “everyone agrees”. That’s not what consensus means, as practiced by organizations that truly have a mature and well developed consensus driven process.<br /><br />Consensus is not “everyone agrees”, but [a model where] people are more aligned with the process than they are with any particular outcome, and they’ve all agreed on how decisions will be made.</p></blockquote><p class="cite">&mdash; <a href="https://jacobian.org/2024/mar/20/django-chat/">Jacob Kaplan-Moss</a>

## Talking about Django’s history and future on Django Chat
 - [https://simonwillison.net/2024/Mar/21/django-history-and-future/#atom-everything](https://simonwillison.net/2024/Mar/21/django-history-and-future/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-21T00:42:15+00:00

<p><a href="https://jacobian.org/2024/mar/20/django-chat/">Talking about Django’s history and future on Django Chat</a></p>
<p>Django co-creator Jacob Kaplan-Moss sat down with the Django Chat podcast team to talk about Django&#x27;s history, his recent return to the Django Software Foundation board and what he hopes to achieve there.</p>

<p>Here&#x27;s his post about it, where he used Whisper and Claude to extract some of his own highlights from the conversation.</p>

    <p>Via <a href="https://djangochat.com/episodes/djangos-evolution-jacob-kaplan-moss-6CswRTAf">Django Chat episodes</a></p>

