# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Golden Gate Claude
 - [https://simonwillison.net/2024/May/24/golden-gate-claude/#atom-everything](https://simonwillison.net/2024/May/24/golden-gate-claude/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-24T08:17:56+00:00

<p><a href="https://www.anthropic.com/news/golden-gate-claude">Golden Gate Claude</a></p>
This is absurdly fun and weird. Anthropic's recent <a href="https://simonwillison.net/2024/May/21/scaling-monosemanticity-extracting-interpretable-features-from-c/">LLM interpretability research</a> gave them the ability to locate features within the opaque blob of their Sonnet model and boost the weight of those features during inference.</p>
<p>For a limited time only they're serving a "Golden Gate Claude" model which has the feature for the Golden Gate Bridge boosted. No matter what question you ask it the Golden Gate Bridge is likely to be involved in the answer in some way. Click the little bridge icon in the Claude UI to give it a go.</p>
<p>I asked for names for a pet pelican and the first one it offered was this:</p>
<blockquote>
<p>Golden Gate - This iconic bridge name would be a fitting moniker for the pelican with its striking orange color and beautiful suspension cables.</p>
</blockqu

## Nilay Patel reports a hallucinated ChatGPT summary of his own article
 - [https://simonwillison.net/2024/May/24/nilay-patel-hallucinated-chatgpt/#atom-everything](https://simonwillison.net/2024/May/24/nilay-patel-hallucinated-chatgpt/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-24T06:38:50+00:00

<p><a href="https://www.threads.net/@reckless1280/post/C7MeXn6LOt_">Nilay Patel reports a hallucinated ChatGPT summary of his own article</a></p>
Here's a ChatGPT bug that's a new twist on the <a href="https://simonwillison.net/2023/Mar/10/chatgpt-internet-access/">old issue</a> where it would hallucinate the contents of a web page based on the URL.</p>
<p>The Verge editor Nilay Patel asked for a summary of one of his own articles, pasting in the URL.</p>
<p>ChatGPT 4o replied with an entirely invented summary full of hallucinated details.</p>
<p>It turns out The Verge blocks ChatGPT's browse mode from accessing their site in their <a href="https://www.theverge.com/robots.txt">robots.txt</a>:</p>
<pre><code>User-agent: ChatGPT-User
Disallow: /
</code></pre>
<p>Clearly ChatGPT should reply that it is unable to access the provided URL, rather than inventing a response that guesses at the contents!

    <p>Via <a href="https://www.computerworld.com/article/2117752/google-gemini-ai.html">

## Quoting Scott Jenson
 - [https://simonwillison.net/2024/May/24/scott-jenson/#atom-everything](https://simonwillison.net/2024/May/24/scott-jenson/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-24T06:33:50+00:00

<blockquote cite="https://www.linkedin.com/posts/scottjenson_this-years-google-io-was-the-most-boring-activity-7198073799051780096-0AmW"><p>I just left Google last month. The &quot;AI Projects&quot; I was working on were poorly motivated and driven by this panic that as long as it had &quot;AI&quot; in it, it would be great. This myopia is NOT something driven by a user need. It is a stone cold panic that they are getting left behind.<br /><br />The vision is that there will be a Tony Stark like Jarvis assistant in your phone that locks you into their ecosystem so hard that you&#x27;ll never leave. That vision is pure catnip. The fear is that they can&#x27;t afford to let someone else get there first.</p></blockquote><p class="cite">&mdash; <a href="https://www.linkedin.com/posts/scottjenson_this-years-google-io-was-the-most-boring-activity-7198073799051780096-0AmW">Scott Jenson</a>

## Quoting Nivia Henry
 - [https://simonwillison.net/2024/May/24/nivia-henry/#atom-everything](https://simonwillison.net/2024/May/24/nivia-henry/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-24T06:09:32+00:00

<blockquote cite="https://twitter.com/Lanooba/status/1753475620892295401"><p>The leader of a team - especially a senior one - is rarely ever the smartest, the most expert or even the most experienced. <br /><br />Often it’s the person who can best understand individuals’ motivations and galvanize them towards an outcome, all while helping them stay cohesive.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/Lanooba/status/1753475620892295401">Nivia Henry</a>

## Some goofy results from ‘AI Overviews’ in Google Search
 - [https://simonwillison.net/2024/May/24/some-goofy-results-from-ai-overviews-in-google-search/#atom-everything](https://simonwillison.net/2024/May/24/some-goofy-results-from-ai-overviews-in-google-search/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-24T05:33:41+00:00

<p><a href="https://daringfireball.net/linked/2024/05/23/goofy-ai-overviews">Some goofy results from ‘AI Overviews’ in Google Search</a></p>
John Gruber collects two of the best examples of Google’s new AI overviews going horribly wrong.</p>

<p>Gullibility is a fundamental trait of all LLMs, and Google’s new feature apparently doesn’t know not to parrot ideas it picked up from articles in the Onion, or jokes from Reddit.</p>

<p>I’ve heard that LLM providers internally talk about “screenshot attacks”—bugs where the biggest risk is that someone will take an embarrassing screenshot.</p>

<p>In Google search’s case this class of bug feels like a significant reputational threat.

## Quoting Molly White
 - [https://simonwillison.net/2024/May/24/molly-white/#atom-everything](https://simonwillison.net/2024/May/24/molly-white/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-24T01:19:01+00:00

<blockquote cite="https://www.citationneeded.news/tornado-cash/"><p>But increasingly, I’m worried that attempts to crack down on the cryptocurrency industry — scummy though it may be — may result in overall weakening of financial privacy, and may hurt vulnerable people the most. As they say, “hard cases make bad law”.</p></blockquote><p class="cite">&mdash; <a href="https://www.citationneeded.news/tornado-cash/">Molly White</a>

## A Grand Unified Theory of the AI Hype Cycle
 - [https://simonwillison.net/2024/May/24/a-grand-unified-theory-of-the-ai-hype-cycle/#atom-everything](https://simonwillison.net/2024/May/24/a-grand-unified-theory-of-the-ai-hype-cycle/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-24T00:26:19+00:00

<p><a href="https://blog.glyph.im/2024/05/grand-unified-ai-hype.html">A Grand Unified Theory of the AI Hype Cycle</a></p>
Glyph outlines the pattern of every AI hype cycle since the 1960s: a new, novel mechanism is discovered and named. People get excited, and non-practitioners start hyping it as the path to true “AI”. It eventually becomes apparent that this is not the case, even while practitioners quietly incorporate this new technology into useful applications while downplaying the “AI” branding. A new mechanism is discovered and the cycle repeats.

