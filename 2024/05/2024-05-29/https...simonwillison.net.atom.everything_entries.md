# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Jeremy Keith
 - [https://simonwillison.net/2024/May/29/jeremy-keith/#atom-everything](https://simonwillison.net/2024/May/29/jeremy-keith/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-29T11:06:14+00:00

<blockquote cite="https://adactio.com/journal/21160"><p>In their rush to cram in “AI” “features”, it seems to me that many companies don’t actually understand why people use their products. [...] Trust is a precious commodity. It takes a long time to build trust. It takes a short time to destroy it.</p></blockquote><p class="cite">&mdash; <a href="https://adactio.com/journal/21160">Jeremy Keith</a>

## Training is not the same as chatting: ChatGPT and other LLMs don't remember everything you say
 - [https://simonwillison.net/2024/May/29/training-not-chatting/#atom-everything](https://simonwillison.net/2024/May/29/training-not-chatting/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-29T10:51:56+00:00

<p>I'm beginning to suspect that one of the most common <a href="https://simonwillison.net/series/llm-misconceptions/">misconceptions about LLMs</a> such as ChatGPT involves how "training" works.</p>
<p>A common complaint I see about these tools is that people don't want to even try them out because they don't want to contribute to their training data.</p>
<p>This is by no means an irrational position to take, but it does often correspond to an incorrect mental model about how these tools work.</p>
<p>Short version: ChatGPT and other similar tools <strong>do not directly learn from and memorize everything that you say to them</strong>.</p>
<p>This can be quite unintuitive: these tools imitate a human conversational partner, and humans constantly update their knowledge based on what you say to to them. Computers have much better memory than humans, so surely ChatGPT would remember every detail of everything you ever say to it. Isn't that what "training" means?</p>
<p>That's not how the

## What We Learned from a Year of Building with LLMs (Part I)
 - [https://simonwillison.net/2024/May/29/a-year-of-building-with-llms/#atom-everything](https://simonwillison.net/2024/May/29/a-year-of-building-with-llms/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-29T08:59:25+00:00

<p><a href="https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/">What We Learned from a Year of Building with LLMs (Part I)</a></p>
Accumulated wisdom from six experienced LLM hackers. Lots of useful tips in here. On providing examples in a prompt:</p>
<blockquote>
<p>If n is too low, the model may over-anchor on those specific examples, hurting its ability to generalize. As a rule of thumb, aim for n ≥ 5. Don’t be afraid to go as high as a few dozen.</p>
</blockquote>
<p>There's a recommendation not to overlook keyword search when implementing RAG - tricks with embeddings can miss results for things like names or acronyms, and keyword search is much easier to debug.</p>
<p>Plus this tip on using the LLM-as-judge pattern for implementing automated evals:</p>
<blockquote>
<p>Instead of asking the LLM to score a single output on a Likert scale, present it with two options and ask it to select the better one. This tends to lead to more stable results.<

## Quoting Chris Perry
 - [https://simonwillison.net/2024/May/29/chris-perry/#atom-everything](https://simonwillison.net/2024/May/29/chris-perry/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-29T07:17:02+00:00

<blockquote cite="https://twitter.com/thechrisperry/status/1795661635602059664"><p>Sometimes the most creativity is found in enumerating the solution space. Design is the process of prioritizing tradeoffs in a high dimensional space. Understand that dimensionality.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/thechrisperry/status/1795661635602059664">Chris Perry</a>

