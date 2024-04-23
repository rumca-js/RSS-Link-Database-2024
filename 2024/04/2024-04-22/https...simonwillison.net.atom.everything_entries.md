# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## timpaul/form-extractor-prototype
 - [https://simonwillison.net/2024/Apr/22/form-extractor-prototype/#atom-everything](https://simonwillison.net/2024/Apr/22/form-extractor-prototype/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-22T22:01:22+00:00

<p><a href="https://github.com/timpaul/form-extractor-prototype">timpaul/form-extractor-prototype</a></p>
<p>Tim Paul, Head of Interaction Design at the UK&#x27;s Government Digital Service, published this brilliant prototype built on top of Claude 3 Opus.</p>

<p>The video shows what it can do. Give it an image of a form and it will extract the form fields and use them to create a GDS-style multi-page interactive form, using their GOV.UK Forms design system and govuk-frontend npm package.</p>

<p>It works for both hand-drawn napkin illustrations and images of existing paper forms.</p>

<p>The bulk of the prompting logic is the schema definition in data/extract-form-questions.json</p>

<p>I&#x27;m always excited to see applications built on LLMs that go beyond the chatbot UI. This is a great example of exactly that.</p>

    <p>Via <a href="https://twitter.com/timpaul/status/1781184488485056777">@timpaul</a></p>

## No one buys books
 - [https://simonwillison.net/2024/Apr/22/no-one-buys-books/#atom-everything](https://simonwillison.net/2024/Apr/22/no-one-buys-books/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-22T21:55:04+00:00

<p><a href="https://www.elysian.press/p/no-one-buys-books">No one buys books</a></p>
<p>Fascinating insights into the book publishing industry gathered by Elle Griffin from details that came out during the Penguin vs. DOJ antitrust lawsuit.</p>

<p>Publishing turns out to be similar to VC investing: a tiny percentage of books are hits that cover the costs for the vast majority that didn&#x27;t sell well. The DOJ found that, of 58,000 books published in a year, &quot;90 percent of them sold fewer than 2,000 copies and 50 percent sold less than a dozen copies.&quot;</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=40119958">Hacker News</a></p>

## Options for accessing Llama 3 from the terminal using LLM
 - [https://simonwillison.net/2024/Apr/22/llama-3/#atom-everything](https://simonwillison.net/2024/Apr/22/llama-3/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-22T13:38:09+00:00

<p>Llama 3 was released <a href="https://llama.meta.com/llama3/">on Thursday</a>. Early indications are that it's now the best available openly licensed model - Llama 3 70b Instruct has taken joint 5th place on the <a href="https://chat.lmsys.org/?leaderboard">LMSYS arena leaderboard</a>, behind only Claude 3 Opus and some GPT-4s and sharing 5th place with Gemini Pro and Claude 3 Sonnet. But unlike those other models Llama 3 70b is weights available and can even be run on a (high end) laptop!</p>
<p>My <a href="https://llm.datasette.io/">LLM</a> command-line tool and Python library provides access to dozens of models via plugins. Here are several ways you can use it to access Llama 3, both hosted versions and running locally on your own hardware.</p>

<ul>
  <li><a href="https://simonwillison.net/2024/Apr/22/llama-3/#llama-3-8b-instruct-locally-with-llm-gpt4all">Llama-3-8B-Instruct locally with llm-gpt4all</a></li>
  <li><a href="https://simonwillison.net/2024/Apr/22/llama-3/#fast-api

