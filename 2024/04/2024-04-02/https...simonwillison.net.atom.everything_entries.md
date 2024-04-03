# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Cally: Accessibility statement
 - [https://simonwillison.net/2024/Apr/2/cally-accessibility-statement/#atom-everything](https://simonwillison.net/2024/Apr/2/cally-accessibility-statement/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-02T19:38:19+00:00

<p><a href="https://wicky.nillia.ms/cally/accessibility/">Cally: Accessibility statement</a></p>
<p>Cally is a neat new open source date (and date range) picker Web Component by Nick Williams.</p>

<p>It&#x27;s framework agnostic and weighs less than 9KB grilled, but the best feature is this detailed page of documentation covering its accessibility story, including how it was tested - in JAWS, NVDA and VoiceOver.</p>

<p>I&#x27;d love to see other open source JavaScript libraries follow this exanple.</p>

    <p>Via <a href="https://twitter.com/wickynilliams/status/1775208741392052299">@wickynilliams</a></p>

## Bringing Python to Workers using Pyodide and WebAssembly
 - [https://simonwillison.net/2024/Apr/2/cloudflare-python-workers/#atom-everything](https://simonwillison.net/2024/Apr/2/cloudflare-python-workers/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-02T16:09:57+00:00

<p><a href="https://blog.cloudflare.com/python-workers">Bringing Python to Workers using Pyodide and WebAssembly</a></p>
<p>Cloudflare Workers is Cloudflare&#x27;s serverless hosting tool for deploying server-side functions to edge locations in their CDN.</p>

<p>They just released Python support, accompanied by an extremely thorough technical explanation of how they got that to work. The details are fascinating.</p>

<p>Workers runs on V8 isolates, and the new Python support was implemented using Pyodide (CPython compiled to WebAssembly) running inside V8.</p>

<p>Getting this to work performantly and ergonomically took a huge amount of work.</p>

<p>There are too many details in here to effectively summarize, but my favorite detail is this one:</p>

<p>&quot;We scan the Worker’s code for import statements, execute them, and then take a snapshot of the Worker’s WebAssembly linear memory. Effectively, we perform the expensive work of importing packages at deploy time, rather than at r

## Quoting Alex Komoroske
 - [https://simonwillison.net/2024/Apr/2/alex-komoroske/#atom-everything](https://simonwillison.net/2024/Apr/2/alex-komoroske/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-02T15:19:39+00:00

<blockquote cite="https://docs.google.com/document/d/1ptHfoKWn0xbNSJgdkH8_3z4PHLC_f36MutFTTRf14I0/edit#bookmark=id.y7b1cw99raad"><p>LLMs are like a trained circus bear that can make you porridge in your kitchen. It&#x27;s a miracle that it&#x27;s able to do it at all, but watch out because no matter how well they can act like a human on some tasks, they&#x27;re still a wild animal. They might ransack your kitchen, and they could kill you, accidentally or intentionally!</p></blockquote><p class="cite">&mdash; <a href="https://docs.google.com/document/d/1ptHfoKWn0xbNSJgdkH8_3z4PHLC_f36MutFTTRf14I0/edit#bookmark=id.y7b1cw99raad">Alex Komoroske</a>

