# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Accidental GPT-4o voice preview
 - [https://simonwillison.net/2024/Jun/28/accidental-gpt-4o-voice-preview/#atom-everything](https://simonwillison.net/2024/Jun/28/accidental-gpt-4o-voice-preview/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-28T20:53:34+00:00

<p><a href="https://www.reddit.com/r/ChatGPT/comments/1dp1grs/comment/lakpmjb/">Accidental GPT-4o voice preview</a></p>
Reddit user RozziTheCreator was one of a small group who were accidentally granted access to the new multimodal GPT-4o audio voice feature. They captured this video of it telling them a spooky story, complete with thunder sound effects added to the background and in a very realistic voice that clearly wasn't the one from the 4o demo that sounded similar to Scarlet Johansson.</p>
<p>OpenAI provided a comment for <a href="https://www.tomsguide.com/ai/chatgpt/openai-accidentally-gave-some-users-advanced-voice-early-heres-what-happened">this Tom's Guide story</a> confirming the accidental rollout so I don't think this is a faked video.

    <p>Via <a href="https://www.tomsguide.com/ai/chatgpt/openai-accidentally-gave-some-users-advanced-voice-early-heres-what-happened">Tom&#x27;s Guide</a></p>

## Serving a billion web requests with boring code
 - [https://simonwillison.net/2024/Jun/28/boring-code/#atom-everything](https://simonwillison.net/2024/Jun/28/boring-code/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-28T16:22:45+00:00

<p><a href="https://notes.billmill.org/blog/2024/06/Serving_a_billion_web_requests_with_boring_code.html">Serving a billion web requests with boring code</a></p>
Bill Mill provides a deep retrospective from his work helping build a relaunch of the <a href="https://www.medicare.gov/plan-compare/">medicare.gov/plan-compare</a> site.</p>
<p>It's a fascinating case study of the <a href="https://boringtechnology.club/">choose boring technology</a> mantra put into action. The "boring" choices here were PostgreSQL, Go and React, all three of which are so widely used and understood at this point that you're very unlikely to stumble into surprises with them.</p>
<p>Key goals for the site were accessibility, in terms of users, devices and performance. Despite best efforts:</p>
<blockquote>
<p>The result fell prey after a few years to a common failure mode of react apps, and became quite heavy and loaded somewhat slowly.</p>
</blockquote>
<p>I've seen this pattern myself many times over, and I'd

## Django: Test for pending migrations
 - [https://simonwillison.net/2024/Jun/28/django-test-for-pending-migrations/#atom-everything](https://simonwillison.net/2024/Jun/28/django-test-for-pending-migrations/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-28T15:23:00+00:00

<p><a href="https://adamj.eu/tech/2024/06/23/django-test-pending-migrations/">Django: Test for pending migrations</a></p>
Neat recipe from Adam Johnson for adding an automated test to your Django test suite that runs <code>manage.py makemigrations --check</code> to ensure you don't accidentally land code that deploys with a missing migration and crashes your site. I've made this mistake before myself so I'll be adding this to my projects.

    <p>Via <a href="https://fosstodon.org/@adamchainz/112687118729636820">@adamchainz</a></p>

