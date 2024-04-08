# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## The lifecycle of a code AI completion
 - [https://simonwillison.net/2024/Apr/7/the-lifecycle-of-a-code-ai-completion/#atom-everything](https://simonwillison.net/2024/Apr/7/the-lifecycle-of-a-code-ai-completion/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-07T19:37:24+00:00

<p><a href="https://sourcegraph.com/blog/the-lifecycle-of-a-code-ai-completion">The lifecycle of a code AI completion</a></p>
<p>Philipp Spiess provides a deep dive into how Sourcegraph&#x27;s Cody code completion assistant works. Lots of fascinating details in here:</p>

<p>&quot;One interesting learning was that if a user is willing to wait longer for a multi-line request, it usually is worth it to increase latency slightly in favor of quality. For our production setup this means we use a more complex language model for multi-line completions than we do for single-line completions.&quot;</p>

<p>This article is from October 2023 and talks about Claude Instant. The code for Cody is open source so I checked to see if they have switched to Haiku yet and found a commit from March 25th that adds Haiku as an A/B test.</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=39959380">Hacker News</a></p>

