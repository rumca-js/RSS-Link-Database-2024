# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Share Claude conversations by converting their JSON to Markdown
 - [https://simonwillison.net/2024/Aug/8/convert-claude-json-to-markdown/#atom-everything](https://simonwillison.net/2024/Aug/8/convert-claude-json-to-markdown/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-08T20:40:20+00:00

<p><strong><a href="https://observablehq.com/@simonw/convert-claude-json-to-markdown">Share Claude conversations by converting their JSON to Markdown</a></strong></p>
Anthropic's <a href="https://claude.ai/">Claude</a> is missing one key feature that I really appreciate in ChatGPT: the ability to create a public link to a full conversation transcript. You can publish individual artifacts from Claude, but I often find myself wanting to publish the whole conversation.</p>
<p>Before ChatGPT added that feature I solved it myself with <a href="https://observablehq.com/@simonw/chatgpt-json-transcript-to-markdown">this Observable notebook</a>. Today I built the same thing for Claude.</p>
<p>Here's how to use it:</p>
<p><img alt="Animated demo - starting on the Claude homepage, opening a conversation with the DevTools network panel open, searching for chat_ and then using Copy -&gt; Response to get the JSON, then switching tabs to the Observable notebook and pasting that JSON in to get Markdo

## django-http-debug, a new Django app mostly written by Claude
 - [https://simonwillison.net/2024/Aug/8/django-http-debug/#atom-everything](https://simonwillison.net/2024/Aug/8/django-http-debug/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-08T15:26:27+00:00

<p>Yesterday I finally developed something I’ve been casually thinking about building for a long time: <strong><a href="https://github.com/simonw/django-http-debug">django-http-debug</a></strong>. It’s a reusable Django app - something you can <code>pip install</code> into any Django project - which provides tools for quickly setting up a URL that returns a canned HTTP response and logs the full details of any incoming request to a database table.</p>
<p>This is ideal for any time you want to start developing against some external API that sends traffic to your own site - a webhooks provider <a href="https://docs.stripe.com/webhooks">like Stripe</a>, or an OAuth or OpenID connect integration (my task yesterday morning).</p>
<p>You can install it right now jn your own Django app: add <code>django-http-debug</code> to your requirements (or just <code>pip install django-http-debug</code>), then add the following to your <code>settings.py</code>:</p>
<pre><span class="pl-v">INSTALLED_APPS

## Quoting Andrej Karpathy
 - [https://simonwillison.net/2024/Aug/8/andrej-karpathy/#atom-everything](https://simonwillison.net/2024/Aug/8/andrej-karpathy/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-08T08:13:26+00:00

<blockquote cite="https://twitter.com/karpathy/status/1821277264996352246"><p>The RM [Reward Model] we train for LLMs is just a vibe check […] It gives high scores to the kinds of assistant responses that human raters statistically seem to like. It's not the "actual" objective of correctly solving problems, it's a proxy objective of what looks good to humans. Second, you can't even run RLHF for too long because your model quickly learns to respond in ways that game the reward model. […]</p>
<p>No production-grade <em>actual</em> RL on an LLM has so far been convincingly achieved and demonstrated in an open domain, at scale. And intuitively, this is because getting actual rewards (i.e. the equivalent of win the game) is really difficult in the open-ended problem solving tasks. […] But how do you give an objective reward for summarizing an article? Or answering a slightly ambiguous question about some pip install issue? Or telling a joke? Or re-writing some Java code to Python?</p></blo

