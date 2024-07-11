# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Alex Albert (Anthropic)
 - [https://simonwillison.net/2024/Jul/10/alex-albert/#atom-everything](https://simonwillison.net/2024/Jul/10/alex-albert/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-10T18:56:40+00:00

<blockquote cite="https://twitter.com/alexalbert__/status/1811101055054402019"><p>Yeah, unfortunately vision prompting has been a tough nut to crack. We've found it's very challenging to improve Claude's actual "vision" through just text prompts, but we can of course improve its reasoning and thought process once it extracts info from an image. </p>
<p>In general, I think vision is still in its early days, although 3.5 Sonnet is noticeably better than older models.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/alexalbert__/status/1811101055054402019">Alex Albert (Anthropic)</a>

## Anthropic cookbook: multimodal
 - [https://simonwillison.net/2024/Jul/10/anthropic-cookbook-multimodal/#atom-everything](https://simonwillison.net/2024/Jul/10/anthropic-cookbook-multimodal/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-10T18:38:10+00:00

<p><a href="https://github.com/anthropics/anthropic-cookbook/tree/main/multimodal">Anthropic cookbook: multimodal</a></p>
I'm currently on the lookout for high quality sources of information about vision LLMs, including prompting tricks for getting the most out of them.</p>
<p>This set of Jupyter notebooks from Anthropic (published four months ago to accompany the original Claude 3 models) is the best I've found so far. <a href="https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/best_practices_for_vision.ipynb">Best practices for using vision with Claude</a> includes advice on multi-shot prompting with example, plus this interesting think step-by-step style prompt for improving Claude's ability to count the dogs in an image:</p>
<blockquote>
<p>You have perfect vision and pay great attention to detail which makes you an expert at counting objects in images. How many dogs are in this picture? Before providing the answer in <code>&lt;answer&gt;</code> tags, think step

## Vision language models are blind
 - [https://simonwillison.net/2024/Jul/10/vision-language-models-are-blind/#atom-everything](https://simonwillison.net/2024/Jul/10/vision-language-models-are-blind/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-10T18:17:14+00:00

<p><a href="https://vlmsareblind.github.io/">Vision language models are blind</a></p>
A new paper exploring vision LLMs, comparing GPT-4o, Gemini 1.5 Pro, Claude 3 Sonnet and Claude 3.5 Sonnet (I'm surprised they didn't include Claude 3 Opus and Haiku, which are more interesting than Claude 3 Sonnet in my opinion).</p>
<p>I don't like the title and framing of this paper. They describe seven tasks that vision models have trouble with - mainly geometric analysis like identifying intersecting shapes or counting things - and use those to support the following statement:</p>
<blockquote>
<p>The shockingly poor performance of four state-of-the-art VLMs suggests their vision is, at best, like of a person with myopia seeing fine details as blurry, and at worst, like an intelligent person that is blind making educated guesses.</p>
</blockquote>
<p>This is an interesting result. I've felt starved for information about the strengths and weaknesses of these vision LLMs since the good ones started

## Quoting Ryan Broderick
 - [https://simonwillison.net/2024/Jul/10/ryan-broderick/#atom-everything](https://simonwillison.net/2024/Jul/10/ryan-broderick/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-10T17:43:57+00:00

<blockquote cite="https://www.garbageday.email/p/slop-void"><p>Content slop has three important characteristics. The first being that, to the user, the viewer, the customer, it feels worthless. This might be because it was clearly generated in bulk by a machine or because of how much of that particular content is being created. The next important feature of slop is that feels forced upon us, whether by a corporation or an algorithm. It’s in the name. We’re the little piggies and it’s the gruel in the trough. But the last feature is the most crucial. It not only feels worthless and ubiquitous, it also feels optimized to be so. The Charli XCX “Brat summer” meme does not feel like slop, nor does Kendrick Lamar’s extremely long “Not Like Us” roll out. But Taylor Swift’s cascade of alternate versions of her songs does. The jury’s still out on Sabrina Carpenter. Similarly, last summer’s Barbenheimer phenomenon did not, to me, feel like slop. <em>Dune: Part Two</em> didn’t either. But <em>De

