# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Will Larson
 - [https://simonwillison.net/2024/May/31/will-larson/#atom-everything](https://simonwillison.net/2024/May/31/will-larson/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-31T19:53:59+00:00

<blockquote cite="https://review.firstround.com/unexpected-anti-patterns-for-engineering-leaders-lessons-from-stripe-uber-carta/"><p>Engineering leaders, especially at large companies, are managing a team of a couple hundred people. That team might cost $50 to 100 million in salary a year. So as a CEO, when you hear from your eng leaders that ‘Engineering is an art, and you can’t predict how it’s going to work,’ it’s frustrating. They’re sitting there thinking, ‘They’re telling me this is art, but I’m spending $100 million on this art each year.’ That’s not reassuring.</p></blockquote><p class="cite">&mdash; <a href="https://review.firstround.com/unexpected-anti-patterns-for-engineering-leaders-lessons-from-stripe-uber-carta/">Will Larson</a>

## Man caught in scam after AI told him fake Facebook customer support number was legitimate
 - [https://simonwillison.net/2024/May/31/caught-in-scam/#atom-everything](https://simonwillison.net/2024/May/31/caught-in-scam/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-31T16:53:33+00:00

<p><a href="https://www.cbc.ca/news/canada/manitoba/facebook-customer-support-scam-1.7219581">Man caught in scam after AI told him fake Facebook customer support number was legitimate</a></p>
This one illustrates a nasty edge-case if you ship any kind of chatbot with your company's name attached to it.</p>
<p>The scam victim here searches Google for a customer support phone number for Facebook, and came across a suspicious looking phone number.</p>
<p>He pasted that number into the Meta AI chatbot in Facebook Messenger and asked "is it a Facebook help line?" - and a Meta AI answered:</p>
<blockquote>
<p>The phone number 1-xxx-xxx-xxxx is indeed a legitimate Facebook support number. Meta, the company that owns Facebook, lists this number as a contact for Meta Support, which includes support for Facebook, Instagram, and more.</p>
</blockquote>
<p>This was a total hallucination, and the phone number was for a scammer who ran a classic "download this app so I can help you" attack.</p>
<p>

## Django Enhancement Proposal 14: Background Workers
 - [https://simonwillison.net/2024/May/31/django-background-workers/#atom-everything](https://simonwillison.net/2024/May/31/django-background-workers/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-31T08:44:37+00:00

<p><a href="https://www.djangoproject.com/weblog/2024/may/29/django-enhancement-proposal-14-background-workers/#top">Django Enhancement Proposal 14: Background Workers</a></p>
Jake Howard's DEP has been approved and is moving into the implementation stage.</p>
<blockquote>
<p>Django doesn't have a first-party solution for long-running tasks, however the ecosystem is filled with incredibly popular frameworks, all of which interact with Django in slightly different ways. Other frameworks such as Laravel have background workers built-in, allowing them to push tasks into the background to be processed at a later date, without requiring the end user to wait for them to occur. [...]</p>
<p>This proposal sets out to provide an interface and base implementation for long-running background tasks in Django.</p>
</blockquote>
<p>Jake has an illustrative reference implementation called <a href="https://github.com/RealOrangeOne/django-tasks">django-tasks</a>.

