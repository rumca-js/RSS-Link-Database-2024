# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## The GPT-4 barrier has finally been broken
 - [https://simonwillison.net/2024/Mar/8/gpt-4-barrier/#atom-everything](https://simonwillison.net/2024/Mar/8/gpt-4-barrier/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-08T18:02:39+00:00

<p>Four weeks ago, GPT-4 remained the undisputed champion: consistently at the top of every key benchmark, but more importantly the clear winner in terms of "vibes". Almost everyone investing serious time exploring LLMs agreed that it was the most capable default model for the majority of tasks - and had been for more than a year.</p>
<p>Today that barrier has finally been smashed. We have four new models, all released to the public in the last four weeks, that are benchmarking near or even above GPT-4. And the all-important vibes are good, too!</p>
<p>Those models come from four different vendors.</p>
<ul>
<li>
<a href="https://blog.google/technology/ai/google-gemini-next-generation-model-february-2024/">Google Gemini 1.5</a>, February 15th. I wrote about this <a href="https://simonwillison.net/2024/Feb/21/gemini-pro-video/">the other week</a>: the signature feature is an incredible one million long token context, nearly 8 times the length of GPT-4 Turbo. It can also process

## You can now train a 70b language model at home
 - [https://simonwillison.net/2024/Mar/8/you-can-now-train-a-70b-language-model-at-home/#atom-everything](https://simonwillison.net/2024/Mar/8/you-can-now-train-a-70b-language-model-at-home/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-08T10:47:53+00:00

<p><a href="https://www.answer.ai/posts/2024-03-06-fsdp-qlora.html">You can now train a 70b language model at home</a></p>
<p>Jeremy Howard and team: &quot;Today, we’re releasing Answer.AI’s first project: a fully open source system that, for the first time, can efficiently train a 70b large language model on a regular desktop computer with two or more standard gaming GPUs (RTX 3090 or 4090).&quot;</p>

<p>This is about fine-tuning an existing model, not necessarily training one from scratch.</p>

<p>There are two tricks at play here. The first is QLoRA, which can be used to train quantized models despite the reduced precision usually preventing gradient descent from working correctly.</p>

<p>QLoRA can bring the memory requirements for a 70b model down to 35GB, but gaming GPUs aren&#x27;t quite that big. The second trick is Meta&#x27;s Fully Sharded Data Parallel or FSDP library, which can shard a model across GPUs. Two consumer 24GB GPUs can then handle the 70b training run

## Become a Wikipedian in 30 minutes
 - [https://simonwillison.net/2024/Mar/8/become-a-wikipedian-in-30-minutes/#atom-everything](https://simonwillison.net/2024/Mar/8/become-a-wikipedian-in-30-minutes/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-08T09:47:48+00:00

<p><a href="https://blog.mollywhite.net/become-a-wikipedian-transcript/">Become a Wikipedian in 30 minutes</a></p>
<p>A characteristically informative and thoughtful guide to getting started with Wikipedia editing by Molly White - video accompanied by a full transcript.</p>

<p>I found the explanation of Reliable Sources particularly helpful, including why Wikipedia prefers secondary to primary sources.</p>

<p>&quot;The way we determine reliability is typically based on the reputation for editorial oversight, and for factchecking and corrections. For example, if you have a reference book that is published by a reputable publisher that has an editorial board and that has edited the book for accuracy, if you know of a newspaper that has, again, an editorial team that is reviewing articles and issuing corrections if there are any errors, those are probably reliable sources.&quot;</p>

    <p>Via <a href="https://www.metafilter.com/202817/a-Wikipedia-article-that-was-citing-an-A

## Eloquent JavaScript, 4th edition (2024)
 - [https://simonwillison.net/2024/Mar/8/eloquent-javascript-4th-edition/#atom-everything](https://simonwillison.net/2024/Mar/8/eloquent-javascript-4th-edition/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-08T04:07:12+00:00

<p><a href="https://eloquentjavascript.net/">Eloquent JavaScript, 4th edition (2024)</a></p>
<p>Marijn Haverbeke is the creator of both the CodeMirror JavaScript code editor library (used by Datasette and many other projects) and the ProseMirror rich-text editor. Eloquent JavaScript is his Creative Commons licensed book on JavaScript, first released in 2007 and now in its 4th edition.</p>

<p>I&#x27;ve only dipped into it myself but it has an excellent reputation.</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=39629044">Hacker News</a></p>

## Inflection-2.5: meet the world's best personal AI
 - [https://simonwillison.net/2024/Mar/8/inflection-25/#atom-everything](https://simonwillison.net/2024/Mar/8/inflection-25/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-08T00:51:11+00:00

<p><a href="https://inflection.ai/inflection-2-5">Inflection-2.5: meet the world&#x27;s best personal AI</a></p>
<p>I&#x27;ve not been paying much attention to Inflection&#x27;s Pi since it released last year, but yesterday they released a new version that they claim is competitive with GPT-4.</p>

<p>&quot;Inflection-2.5 approaches GPT-4’s performance, but used only 40% of the amount of compute for training.&quot;</p>

<p>(I wasn&#x27;t aware that the compute used to train GPT-4 was public knowledge.)</p>

<p>If this holds true, that means that the GPT-4 barrier has been well and truly smashed: we now have Claude 3 Opus, Gemini 1.5, Mistral Large and Inflection-2.5 in the same class as GPT-4, up from zero contenders just a month ago.</p>

    <p>Via <a href="https://twitter.com/emollick/status/1765886334076612830">Ethan Mollick</a></p>

## American Community Survey Data via FTP
 - [https://simonwillison.net/2024/Mar/8/american-community-survey-data-via-ftp/#atom-everything](https://simonwillison.net/2024/Mar/8/american-community-survey-data-via-ftp/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-08T00:25:11+00:00

<p><a href="https://www.census.gov/programs-surveys/acs/data/data-via-ftp.html">American Community Survey Data via FTP</a></p>
<p>I got talking to some people from the US Census at NICAR today and asked them if there was a way to download their data in bulk (in addition to their various APIs)... and there was!</p>

<p>I had heard of the American Community Survey but I hadn&#x27;t realized that it&#x27;s gathered on a yearly basis, as a 5% sample compared to the full every-ten-years census. It&#x27;s only been running for ten years, and there&#x27;s around a year long lead time on the survey becoming available.</p>

