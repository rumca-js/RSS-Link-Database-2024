# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Python 3.12 change results in Apple App Store rejection
 - [https://simonwillison.net/2024/Jun/27/python-312-app-store-rejection/#atom-everything](https://simonwillison.net/2024/Jun/27/python-312-app-store-rejection/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-27T23:17:15+00:00

<p><a href="https://github.com/python/cpython/issues/120522">Python 3.12 change results in Apple App Store rejection</a></p>
Such a frustrating demonstration of the very worst of Apple's opaque App Store review process. The Python 3.12 standard library <code>urllib</code> package includes the string <code>itms-services</code>, and after much investigation Eric Froemling managed to determine that Apple use a scanner and reject any app that has that string mentioned anywhere within their bundle.</p>
<p>Russell Keith-Magee has <a href="https://discuss.python.org/t/handling-incompatibilities-with-app-store-review-processes/56011">a thread</a> on the Python forum discussing solutions. He doesn't think appealing to Apple is likely to help:</p>
<blockquote>
<p>That definitely sounds appealing as an approach - but in this case, it’s going to be screaming into the void. There’s barely even an appeals process for app rejection on Apple’s App Store. We definitely don’t have any sort of channel t

## Open challenges for AI engineering
 - [https://simonwillison.net/2024/Jun/27/ai-worlds-fair/#atom-everything](https://simonwillison.net/2024/Jun/27/ai-worlds-fair/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-27T16:35:18+00:00

<p>I gave the opening keynote at the <a href="https://www.ai.engineer/worldsfair">AI Engineer World's Fair</a> yesterday. I was a late addition to the schedule: OpenAI pulled out of their slot at the last minute, and I was invited to put together a 20 minute talk with just under 24 hours notice!</p>
<p>I decided to focus on highlights of the LLM space since the previous AI Engineer Summit 8 months ago, and to discuss some open challenges for the space - a response to my <a href="https://simonwillison.net/2023/Oct/17/open-questions/">Open questions for AI engineering</a> talk at that earlier event.</p>
<p>A <em>lot</em> has happened in the last 8 months. Most notably, GPT-4 is no longer the undisputed champion of the space - a position it held for the best part of a year.</p>
<p>You can <a href="https://www.youtube.com/watch?v=5zE2sMka620&amp;t=2026s">watch the talk on YouTube</a>, or read the full annotated and extended version below.</p>

 
<p>Sections of this talk:</p>
<ul>
<li>
<a 

