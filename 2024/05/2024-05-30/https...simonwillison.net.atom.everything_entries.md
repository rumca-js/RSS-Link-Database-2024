# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Why, after 6 years, I’m over GraphQL
 - [https://simonwillison.net/2024/May/30/why-after-6-years-im-over-graphql/#atom-everything](https://simonwillison.net/2024/May/30/why-after-6-years-im-over-graphql/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-30T10:36:53+00:00

<p><a href="https://bessey.dev/blog/2024/05/24/why-im-over-graphql/">Why, after 6 years, I’m over GraphQL</a></p>
I've seen many of these criticisms of GraphQL before - N+1 queries, the difficulty of protecting against deeply nested queries - but Matt Bessey collects them all in one place and adds an issue I hadn't considered before: the complexity of authorization, where each field in the query might involve extra permission checks:</p>
<blockquote>
<p>In my experience, this is actually <strong>the biggest source of performance issues</strong>. We would regularly find that our queries were spending more time authorising data than anything else.</p>
</blockquote>

    <p>Via <a href="https://news.ycombinator.com/item?id=40521518">Hacker News</a></p>

## What does the public in six countries think of generative AI in news?
 - [https://simonwillison.net/2024/May/30/ai-survey/#atom-everything](https://simonwillison.net/2024/May/30/ai-survey/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-30T07:38:29+00:00

<p><a href="https://reutersinstitute.politics.ox.ac.uk/what-does-public-six-countries-think-generative-ai-news">What does the public in six countries think of generative AI in news?</a></p>
Fascinating survey by the Reuters Institute for the Study of Journalism at Oxford that asked ~12,000 people across six countries for their opinions on AI usage in journalism.</p>

<p>It’s also being interpreted as evidence that few members of the general public actually use these tools, because the opening survey questions ask about personal usage.</p>

<p>I don’t think the numbers support that narrative, personally. For survey participants in the USA 7% used ChatGPT daily and 11% used it weekly, which is higher than I would expect for those frequencies. For the UK those were 2% daily and 7% weekly.</p>

<p>The 18-24 group were the heaviest users of these tools. Lots of other interesting figures to explore.

    <p>Via <a href="https://www.bbc.com/news/articles/c511x4g7x7jo.amp">BBC: AI products li

## Quoting Andrej Karpathy
 - [https://simonwillison.net/2024/May/30/andrej-karpathy/#atom-everything](https://simonwillison.net/2024/May/30/andrej-karpathy/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-30T07:27:57+00:00

<blockquote cite="https://twitter.com/karpathy/status/1795980744436932871"><p>The realization hit me [when the GPT-3 paper came out] that an important property of the field flipped. In ~2011, progress in AI felt constrained primarily by algorithms. We needed better ideas, better modeling, better approaches to make further progress. If you offered me a 10X bigger computer, I&#x27;m not sure what I would have even used it for. GPT-3 paper showed that there was this thing that would just become better on a large variety of practical tasks, if you only trained a bigger one. Better algorithms become a bonus, not a necessity for progress in AGI. Possibly not forever and going forward, but at least locally and for the time being, in a very practical sense. Today, if you gave me a 10X bigger computer I would know exactly what to do with it, and then I&#x27;d ask for more.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/karpathy/status/1795980744436932871">Andrej Karpathy<

## Codestral: Hello, World!
 - [https://simonwillison.net/2024/May/30/codestral/#atom-everything](https://simonwillison.net/2024/May/30/codestral/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-30T07:19:36+00:00

<p><a href="https://mistral.ai/news/codestral/">Codestral: Hello, World!</a></p>
Mistral's first code-specific model, trained to be "fluent" in 80 different programming languages.</p>
<p>The weights are released under a new <a href="https://mistral.ai/news/mistral-ai-non-production-license-mnpl/">Mistral AI Non-Production License</a>, which is extremely restrictive:</p>
<blockquote>
<p><strong>3.2. Usage Limitation</strong></p>
<ul>
<li>You shall only use the Mistral Models and Derivatives (whether or not created by Mistral AI) for testing, research, Personal, or evaluation purposes in Non-Production Environments; </li>
<li>Subject to the foregoing, You shall not supply the Mistral Models or Derivatives in the course of a commercial activity, whether in return for payment or free of charge, in any medium or form, including but not limited to through a hosted or managed service (e.g. SaaS, cloud instances, etc.), or behind a software layer.</li>
</ul>
</blockquote>
<p>To Mistral's cred

