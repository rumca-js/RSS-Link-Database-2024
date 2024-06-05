# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Michal Zalewski
 - [https://simonwillison.net/2024/Jun/4/michal-zalewski/#atom-everything](https://simonwillison.net/2024/Jun/4/michal-zalewski/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-04T21:13:29+00:00

<blockquote cite="https://lcamtuf.substack.com/p/you-should-write-more"><p>You don’t need to be the world’s leading expert to write about a particular topic. Experts are often busy and struggle to explain concepts in an accessible way. You should be honest with yourself and with your readers about what you know and don’t know — but otherwise, it’s OK to write about what excites you, and to do it as you learn.</p></blockquote><p class="cite">&mdash; <a href="https://lcamtuf.substack.com/p/you-should-write-more">Michal Zalewski</a>

## Zoom CEO envisions AI deepfakes attending meetings in your place
 - [https://simonwillison.net/2024/Jun/4/zoom-ceo-ai-deepfakes/#atom-everything](https://simonwillison.net/2024/Jun/4/zoom-ceo-ai-deepfakes/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-04T19:28:56+00:00

<p><a href="https://arstechnica.com/information-technology/2024/06/zoom-ceo-envisions-ai-deepfakes-attending-meetings-in-your-place/">Zoom CEO envisions AI deepfakes attending meetings in your place</a></p>
I talked to Benj Edwards for this article about Zoom's terrible science-fiction concept to have "digital twins" attend meetings in your behalf:</p>
<blockquote>
<p>When we specifically asked Simon Willison about Yuan's comments about digital twins, he told Ars, "My fundamental problem with this whole idea is that it represents pure AI science fiction thinking—just because an LLM can do a passable impression of someone doesn't mean it can actually perform useful 'work' on behalf of that person. LLMs are useful tools for thought. They are terrible tools for delegating decision making to. That's currently my red line for using them: any time someone outsources actual decision making authority to an opaque random number generator is a recipe for disaster."</p>
</blockquote>

## Encryption At Rest: Whose Threat Model Is It Anyway?
 - [https://simonwillison.net/2024/Jun/4/encryption-at-rest/#atom-everything](https://simonwillison.net/2024/Jun/4/encryption-at-rest/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-04T13:17:34+00:00

<p><a href="https://scottarc.blog/2024/06/02/encryption-at-rest-whose-threat-model-is-it-anyway/">Encryption At Rest: Whose Threat Model Is It Anyway?</a></p>
Security engineer Scott Arciszewski talks through the challenges of building a useful encryption-at-rest system for hosted software. Encryption at rest on a hard drive protects against physical access to the powered-down disk and little else. To implement encryption at rest in a multi-tenant SaaS system - such that even individuals with insider access  (like access to the underlying database) are unable to read other user's data, is a whole lot more complicated.</p>
<p>Consider an attacker, Bob, with database access:</p>
<blockquote>
<p>Here’s the stupid simple attack that works in far too many cases: Bob copies Alice’s encrypted data, and overwrites his records in the database, then accesses the insurance provider’s web app [using his own account].</p>
</blockquote>
<p>The fix for this is to "use the AAD mechanism (part of the 

## How do I opt into full text search on Mastodon?
 - [https://simonwillison.net/2024/Jun/4/how-do-i-opt-into-full-text-search-on-mastodon/#atom-everything](https://simonwillison.net/2024/Jun/4/how-do-i-opt-into-full-text-search-on-mastodon/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-04T06:14:37+00:00

<p><a href="https://fedi.tips/how-do-i-opt-into-or-out-of-full-text-search-on-mastodon/">How do I opt into full text search on Mastodon?</a></p>
I missed this new Mastodon feature when it was released <a href="https://blog.joinmastodon.org/2023/09/mastodon-4.2/">in 4.2.0 last September</a>: you can now opt-in to a new setting which causes all of your future posts to be marked as allowed to be included in the Elasticsearch index provided by Mastodon instances that enable search.</p>
<p>It only applies to future posts because it works by adding an "indexable" flag to those posts, which can then be obeyed by other Mastodon instances that the post is syndicated to.</p>
<p>You can turn it on for your own account from the <code>/settings/privacy</code> page on your local instance.</p>
<p>The <a href="https://github.com/mastodon/mastodon/releases/tag/v4.2.0">release notes for 4.2.0</a> also mention new search operators:</p>
<blockquote>
<p><code>from:me</code>, <code>before:2022-11-01</code>

## A tip from Neal Stephenson
 - [https://simonwillison.net/2024/Jun/4/a-tip-from-neal-stephenson/#atom-everything](https://simonwillison.net/2024/Jun/4/a-tip-from-neal-stephenson/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-04T02:07:03+00:00

<p><a href="https://www.reddit.com/r/Fantasy/comments/vdt11/comment/c53o23x/">A tip from Neal Stephenson</a></p>
Twelve years ago on Reddit user bobbylox asked Neal Stephenson (in an AMA):</p>
<blockquote>
<p>My ultimate goal in life is to make the Primer real. Anything you want to make sure I get right?</p>
</blockquote>
<p>Referencing the Young Lady's Illustrated Primer from Neal's novel <a href="https://en.wikipedia.org/wiki/The_Diamond_Age">The Diamond Age</a>. Stephenson replied:</p>
<blockquote>
<p>Kids need to get answers from humans who love them.</p>
</blockquote>
<p>(A lot of people in the AI space are taking inspiration from the Primer right now.)

    <p>Via <a href="https://twitter.com/noahlt/status/1797488714433909175">@noahlt</a></p>

## Quoting Jon Christian
 - [https://simonwillison.net/2024/Jun/4/jon-christian/#atom-everything](https://simonwillison.net/2024/Jun/4/jon-christian/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-04T01:24:24+00:00

<blockquote cite="https://bsky.app/profile/jon-christian.bsky.social/post/3ktsxyw2pf423"><p>computer scientists: we have invented a virtual dumbass who is constantly wrong <br /><br />tech CEOs: let&#x27;s add it to every product</p></blockquote><p class="cite">&mdash; <a href="https://bsky.app/profile/jon-christian.bsky.social/post/3ktsxyw2pf423">Jon Christian</a>

