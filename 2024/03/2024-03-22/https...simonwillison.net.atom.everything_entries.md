# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Threads has entered the fediverse
 - [https://simonwillison.net/2024/Mar/22/threads-has-entered-the-fediverse/#atom-everything](https://simonwillison.net/2024/Mar/22/threads-has-entered-the-fediverse/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-22T20:15:20+00:00

<p><a href="https://engineering.fb.com/2024/03/21/networking-traffic/threads-has-entered-the-fediverse/">Threads has entered the fediverse</a></p>
<p>Threads users with public profiles in certain countries can now turn on a setting which makes their posts available in the fediverse - so users of ActivityPub systems such as Mastodon can follow their accounts to subscribe to their posts.</p>

<p>It&#x27;s only a partial integration at the moment: Threads users can&#x27;t themselves follow accounts from other providers yet, and their notifications will show them likes but not boosts or replies: &quot;For now, people who want to see replies on their posts on other fediverse servers will have to visit those servers directly.&quot;</p>

<p>Depending on how you count, Mastodon has around 9m user accounts of which 1m are active. Threads claims more than 130m active monthly users. The Threads team are developing these features cautiously which is reassuring to see - a clumsy or though

## Claude and ChatGPT for ad-hoc tasks
 - [https://simonwillison.net/2024/Mar/22/claude-and-chatgpt-case-study/#atom-everything](https://simonwillison.net/2024/Mar/22/claude-and-chatgpt-case-study/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-22T19:44:12+00:00

<p>Here is a short, illustrative example of one of the ways in which I use Claude and ChatGPT on a daily basis.</p>
<p>I recently learned that the <a href="https://en.wikipedia.org/wiki/Adirondack_Park">Adirondack Park</a> is the single largest park in the contiguous United States, taking up a fifth of the state of New York.</p>
<p>Naturally, my first thought was that it would be neat to have a GeoJSON file representing the boundary of the park.</p>
<p>A quick search landed me on the <a href="https://apa.ny.gov/gis/ApaData.html">Adirondack Park Agency GIS data page</a>, which offered me a shapefile of the "Outer boundary of the New York State Adirondack Park as described in Section 9-0101 of the New York Environmental Conservation Law". Sounds good!</p>
<p>I knew there were tools for converting shape files to GeoJSON, but I couldn't remember what they were. Since I had a terminal window open already, I typed the following:</p>
<div class="highlight highlight-source-shell"><pr

## The Dropflow Playground
 - [https://simonwillison.net/2024/Mar/22/the-dropflow-playground/#atom-everything](https://simonwillison.net/2024/Mar/22/the-dropflow-playground/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-22T01:33:44+00:00

<p><a href="https://chearon.github.io/dropflow/">The Dropflow Playground</a></p>
<p>Dropflow is a &quot;CSS layout engine&quot; written in TypeScript and taking advantage of the HarfBuzz text shaping engine (used by Chrome, Android, Firefox and more) compiled to WebAssembly to implement glyph layout.</p>

<p>This linked demo is fascinating: on the left hand side you can edit HTML with inline styles, and the right hand side then updates live to show that content rendered by Dropflow in a canvas element.</p>

<p>Why would you want this? It lets you generate images and PDFs with excellent performance using your existing knowledge HTML and CSS. It&#x27;s also just really cool!</p>

    <p>Via <a href="https://github.com/chearon/dropflow">chearon/dropflow</a></p>

