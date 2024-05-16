# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Casey Newton
 - [https://simonwillison.net/2024/May/15/casey-newton/#atom-everything](https://simonwillison.net/2024/May/15/casey-newton/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T22:23:54+00:00

<blockquote cite="https://www.platformer.news/google-io-ai-search-sundar-pichai/"><p>But where the company once limited itself to gathering low-hanging fruit along the lines of “what time is the super bowl,” on Tuesday executives showcased generative AI tools that will someday plan an entire anniversary dinner, or cross-country-move, or trip abroad. A quarter-century into its existence, a company that once proudly served as an entry point to a web that it nourished with traffic and advertising revenue has begun to abstract that all away into an input for its large language models.</p></blockquote><p class="cite">&mdash; <a href="https://www.platformer.news/google-io-ai-search-sundar-pichai/">Casey Newton</a>

## PaliGemma model README
 - [https://simonwillison.net/2024/May/15/paligemma/#atom-everything](https://simonwillison.net/2024/May/15/paligemma/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T21:16:36+00:00

<p><a href="https://github.com/google-research/big_vision/blob/main/big_vision/configs/proj/paligemma/README.md?ref=blog.roboflow.com">PaliGemma model README</a></p>
One of the more over-looked announcements from Google I/O yesterday was PaliGemma, an openly licensed VLM (Vision Language Model) in the Gemma family of models.</p>
<p>The model accepts an image and a text prompt. It outputs text, but that text can include special tokens representing regions on the image. This means it can return both bounding boxes and fuzzier segment outlines of detected objects, behavior that can be triggered using a prompt such as "segment puffins".</p>
<p>You can try it out <a href="https://huggingface.co/spaces/google/paligemma">on Hugging Face</a>.</p>
<p>It's a 3B model, making it feasible to run on consumer hardware.

    <p>Via <a href="https://blog.roboflow.com/paligemma-multimodal-vision/">Roboflow: PaliGemma: Open Source Multimodal Model by Google</a></p>

## Managing your work in the API platform with Projects
 - [https://simonwillison.net/2024/May/15/openai-projects/#atom-everything](https://simonwillison.net/2024/May/15/openai-projects/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T19:18:19+00:00

<p><a href="https://platform.openai.com/settings/proj_0Z2W50LtkzHTIudyDCk7rzcR/limits">Managing your work in the API platform with Projects</a></p>
New OpenAI API feature: you can now create API keys for "projects" that can have a monthly spending cap. The UI for that limit says:</p>
<blockquote>
<p>If the project's usage exceeds this amount in a given calendar month (UTC), subsequent API requests will be rejected</p>
</blockquote>
<p>You can also set custom token-per-minute and request-per-minute rate limits for individual models.</p>
<p>I've been wanting this for ages: this means it's finally safe to ship a weird public demo on top of their various APIs without risk of accidental bankruptcy if the demo goes viral!

    <p>Via <a href="https://twitter.com/romainhuet/status/1790813142269976691">@romainhuet</a></p>

## ChatGPT in "4o" mode is not running the new features yet
 - [https://simonwillison.net/2024/May/15/chatgpt-in-4o-mode/#atom-everything](https://simonwillison.net/2024/May/15/chatgpt-in-4o-mode/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T18:25:07+00:00

<p>Monday's OpenAI <a href="https://openai.com/index/hello-gpt-4o/">announcement</a> of their new GPT-4o model included some intriguing new features:</p>
<ul>
<li>Creepily good improvements to the ability to both understand and produce voice (Sam Altman simply tweeted <a href="https://twitter.com/sama/status/1790075827666796666">"her"</a>), and to be interrupted mid-sentence</li>
<li>New image output capabilities that appear to leave existing models like DALL-E 3 in the dust - take a look <a href="https://openai.com/index/hello-gpt-4o/#_6NeEuZ7OcMDzk5E1elaK6i">at the examples</a>, they seem to have solved consistent character representation AND reliable text output!</li>
</ul>
<p>They also made the new 4o model available to paying ChatGPT Plus users, on the web and in their apps.</p>
<p>But, crucially, <strong>those big new features were not part of that release</strong>.</p>
<p>Here's the relevant section from the announcement post:</p>
<blockquote>
<p>We recognize that GPT-4o’s audi

## Quoting Arvind Narayanan
 - [https://simonwillison.net/2024/May/15/arvind-narayanan/#atom-everything](https://simonwillison.net/2024/May/15/arvind-narayanan/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T16:25:41+00:00

<blockquote cite="https://twitter.com/random_walker/status/1790702860595867972"><p>If we want LLMs to be less hype and more of a building block for creating useful everyday tools for people, AI companies&#x27; shift away from scaling and AGI dreams to acting like regular product companies that focus on cost and customer value proposition is a welcome development.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/random_walker/status/1790702860595867972">Arvind Narayanan</a>

## How to PyCon
 - [https://simonwillison.net/2024/May/15/how-to-pycon/#atom-everything](https://simonwillison.net/2024/May/15/how-to-pycon/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T15:29:08+00:00

<p><a href="https://blog.glyph.im/2024/05/how-to-pycon.html">How to PyCon</a></p>
Glyph’s tips on making the most out of PyCon. I particularly like his suggestion that “dinners are for old friends, but lunches are for new ones”.</p>

<p>I’m heading out to Pittsburgh tonight, and giving a keynote (!) on Saturday. If you see me there please come and say hi!

    <p>Via <a href="https://lobste.rs/s/scyvbr/how_pycon">Lobste.rs</a></p>

## Quoting Bruce Schneier
 - [https://simonwillison.net/2024/May/15/bruce-schneier/#atom-everything](https://simonwillison.net/2024/May/15/bruce-schneier/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T13:34:35+00:00

<blockquote cite="https://www.schneier.com/blog/archives/2024/05/llms-data-control-path-insecurity.html"><p>But unlike the phone system, we can’t separate an LLM’s data from its commands. One of the enormously powerful features of an LLM is that the data affects the code. We want the system to modify its operation when it gets new training data. We want it to change the way it works based on the commands we give it. The fact that LLMs self-modify based on their input data is a feature, not a bug. And it’s the very thing that enables prompt injection.</p></blockquote><p class="cite">&mdash; <a href="https://www.schneier.com/blog/archives/2024/05/llms-data-control-path-insecurity.html">Bruce Schneier</a>

## Quoting John Gruber
 - [https://simonwillison.net/2024/May/15/john-gruber/#atom-everything](https://simonwillison.net/2024/May/15/john-gruber/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-15T03:26:37+00:00

<blockquote cite="https://daringfireball.net/2024/05/the_m4_ipad_pros"><p>The MacBook Airs are Apple’s best-selling laptops; the iPad Pros are Apple’s least-selling iPads. I think it’s as simple as this: the current MacBook Airs have the M3, not the M4, because there isn’t yet sufficient supply of M4 chips to satisfy demand for MacBook Airs.</p></blockquote><p class="cite">&mdash; <a href="https://daringfireball.net/2024/05/the_m4_ipad_pros">John Gruber</a>

