# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Releasing Common Corpus: the largest public domain dataset for training LLMs
 - [https://simonwillison.net/2024/Mar/20/releasing-common-corpus/#atom-everything](https://simonwillison.net/2024/Mar/20/releasing-common-corpus/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-20T19:34:00+00:00

<p><a href="https://huggingface.co/blog/Pclanglais/common-corpus">Releasing Common Corpus: the largest public domain dataset for training LLMs</a></p>
<p>Released today. 500 billion words from &quot;a wide diversity of cultural heritage initiatives&quot;. 180 billion words of English, 110 billion of French, 30 billion of German, then Dutch, Spanish and Italian.</p>

<p>Includes quite a lot of US public domain data - 21 million digitized out-of-copyright newspapers (or do they mean newspaper articles?)</p>

<p>&quot;This is only an initial part of what we have collected so far, in part due to the lengthy process of copyright duration verification. In the following weeks and months, we’ll continue to publish many additional datasets also coming from other open sources, such as open data or open science.&quot;</p>

<p>Coordinated by French AI startup Pleias and supported by the French Ministry of Culture, among others.</p>

<p>I can&#x27;t wait to try a model that&#x27;s been tr

## Skew protection in Vercel
 - [https://simonwillison.net/2024/Mar/20/skew-protection-in-vercel/#atom-everything](https://simonwillison.net/2024/Mar/20/skew-protection-in-vercel/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-20T14:06:38+00:00

<p><a href="https://vercel.com/docs/deployments/skew-protection">Skew protection in Vercel</a></p>
<p>Version skew is a name for the bug that occurs when your user loads a web application and then unintentionally keeps that browser tab open across a deployment of a new version of the app. If you&#x27;re unlucky this can lead to broken behaviour, where a client makes a call to a backend endpoint that has changed in an incompatible way.</p>

<p>Vercel have an ingenious solution to this problem. Their platform already makes it easy to deploy many different instances of an application. You can now turn on &quot;skew protection&quot; for a number of hours which will keep older versions of your backend deployed.</p>

<p>The application itself can then include its desired deployment ID in a x-deployment-id header, a __vdpl cookie or a ?dpl= query string parameter.</p>

    <p>Via <a href="https://twitter.com/vercel_changes/status/1770280131250286851">Vercel changes</a></p>

## Every dunder method in Python
 - [https://simonwillison.net/2024/Mar/20/every-dunder-method-in-python/#atom-everything](https://simonwillison.net/2024/Mar/20/every-dunder-method-in-python/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-20T03:45:58+00:00

<p><a href="https://www.pythonmorsels.com/every-dunder-method/">Every dunder method in Python</a></p>
<p>Trey Hunner: &quot;Python includes 103 &#x27;normal&#x27; dunder methods, 12 library-specific dunder methods, and at least 52 other dunder attributes of various types.&quot;</p>

<p>This cheat sheet doubles as a tour of many of the more obscure corners of the Python language and standard library.</p>

<p>I did not know that Python has over 100 dunder methods now! Quite a few of these were new to me, like __class_getitem__ which can be used to implement type annotations such as list[int].</p>

## AI Prompt Engineering Is Dead. Long live AI prompt engineering
 - [https://simonwillison.net/2024/Mar/20/prompt-engineering/#atom-everything](https://simonwillison.net/2024/Mar/20/prompt-engineering/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-20T03:22:18+00:00

<p><a href="https://spectrum.ieee.org/prompt-engineering-is-dead">AI Prompt Engineering Is Dead. Long live AI prompt engineering</a></p>
<p>Ignoring the clickbait in the title, this article summarizes research around the idea of using machine learning models to optimize prompts - as seen in tools such as Stanford&#x27;s DSPy and Google&#x27;s OPRO.</p>

<p>The article includes possibly the biggest abuse of the term &quot;just&quot; I have ever seen:</p>

<p>&quot;But that’s where hopefully this research will come in and say ‘don’t bother.’ Just develop a scoring metric so that the system itself can tell whether one prompt is better than another, and then just let the model optimize itself.&quot;</p>

<p>Developing a scoring metric to determine which prompt works better remains one of the hardest challenges generative AI!</p>

<p>Imagine if we had a discipline of engineers who could reliably solve that problem - who spent their time developing such metrics and then using them 

## Papa Parse
 - [https://simonwillison.net/2024/Mar/20/papa-parse/#atom-everything](https://simonwillison.net/2024/Mar/20/papa-parse/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-20T00:53:29+00:00

<p><a href="https://www.papaparse.com/">Papa Parse</a></p>
<p>I&#x27;ve been trying out this JavaScript library for parsing CSV and TSV data today and I&#x27;m very impressed. It&#x27;s extremely fast, has all of the advanced features I want (streaming support, optional web workers, automatically detecting delimiters and column types), has zero dependencies and weighs just 19KB minified - 6.8KB gzipped.</p>

<p>The project is 11 years old now. It was created by Matt Holt, who later went on to create the Caddy web server. Today it&#x27;s maintained by Sergi Almacellas Abellana.</p>

    <p>Via <a href="https://github.com/mholt/PapaParse">mholt/PapaParse</a></p>

