# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting David Hahn
 - [https://simonwillison.net/2024/Jul/3/david-hahn/#atom-everything](https://simonwillison.net/2024/Jul/3/david-hahn/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-03T20:49:06+00:00

<blockquote cite="https://www.sequoiacap.com/article/ais-600b-question/"><p>If you own the tracks between San Francisco and Los Angeles, you likely have some kind of monopolistic pricing power, because there can only be so many tracks laid between place A and place B. In the case of GPU data centers, there is much less pricing power. GPU computing is increasingly turning into a commodity, metered per hour. Unlike the CPU cloud, which became an oligopoly, new entrants building dedicated AI clouds continue to flood the market. Without a monopoly or oligopoly, high fixed cost + low marginal cost businesses almost always see prices competed down to marginal cost (e.g., airlines).</p></blockquote><p class="cite">&mdash; <a href="https://www.sequoiacap.com/article/ais-600b-question/">David Hahn</a>

## Chrome Prompt Playground
 - [https://simonwillison.net/2024/Jul/3/chrome-prompt-playground/#atom-everything](https://simonwillison.net/2024/Jul/3/chrome-prompt-playground/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-03T17:11:02+00:00

<p><a href="https://tools.simonwillison.net/chrome-prompt-playground">Chrome Prompt Playground</a></p>
Google Chrome Canary is currently shipping an experimental on-device LLM, in the form of Gemini Nano. You can access it via the new <code>window.ai</code> API, after first enabling the "Prompt API for Gemini Nano" experiment in <code>chrome://flags</code> (and then waiting an indeterminate amount of time for the ~1.7GB model file to download - I eventually spotted it in <code>~/Library/Application Support/Google/Chrome Canary/OptGuideOnDeviceModel</code>).</p>
<p>I got Claude 3.5 Sonnet to build me this playground interface for experimenting with the model. You can execute prompts, stream the responses and all previous prompts and responses are stored in <code>localStorage</code>.</p>
<p><img alt="Animated GIF demo. The prompt is Show two greetings each in French and Spanish - on clicking the button the result streams in:  French Bonjour! Bienvenue!, Spanish Hola!, Bienvenido! Scroll

