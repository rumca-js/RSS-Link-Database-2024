# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Matt Webb
 - [https://simonwillison.net/2024/Jun/11/matt-webb/#atom-everything](https://simonwillison.net/2024/Jun/11/matt-webb/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-11T17:26:00+00:00

<blockquote cite="https://interconnected.org/home/2024/06/11/siri"><p>Apple’s terminology distinguishes between “personal intelligence,” on-device and under their control, and “world knowledge,” which is prone to hallucinations – but is also what consumers expect when they use AI, and it’s what may replace Google search as the “point of first intent” one day soon.<br /><br />It’s wise for them to keep world knowledge separate, behind a very clear gate, but still engage with it. Protects the brand and hedges their bets.</p></blockquote><p class="cite">&mdash; <a href="https://interconnected.org/home/2024/06/11/siri">Matt Webb</a>

## First Came ‘Spam.’ Now, With A.I., We’ve Got ‘Slop’
 - [https://simonwillison.net/2024/Jun/11/nytimes-slop/#atom-everything](https://simonwillison.net/2024/Jun/11/nytimes-slop/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-11T16:12:21+00:00

<p><a href="https://www.nytimes.com/2024/06/11/style/ai-search-slop.html">First Came ‘Spam.’ Now, With A.I., We’ve Got ‘Slop’</a></p>
First <a href="https://simonwillison.net/2024/May/19/spam-junk-slop-the-latest-wave-of-ai-behind-the-zombie-internet/">the Guardian</a>, now the NYT. I've apparently made a habit of getting quoted by journalists talking about slop!</p>
<p>I got the closing quote in this one:</p>
<blockquote>
<p>Society needs concise ways to talk about modern A.I. — both the positives and the negatives. ‘Ignore that email, it’s spam,’ and ‘Ignore that article, it’s slop,’ are both useful lessons.</p>
</blockquote>

## Introducing Apple’s On-Device and Server Foundation Models
 - [https://simonwillison.net/2024/Jun/11/apples-on-device-and-server-foundation-models/#atom-everything](https://simonwillison.net/2024/Jun/11/apples-on-device-and-server-foundation-models/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-11T15:44:31+00:00

<p><a href="https://machinelearning.apple.com/research/introducing-apple-foundation-models">Introducing Apple’s On-Device and Server Foundation Models</a></p>
Apple Intelligence uses both on-device and in-the-cloud models that were trained from scratch by Apple.</p>
<p>Their on-device model is a 3B model that "outperforms larger models including Phi-3-mini, Mistral-7B, and Gemma-7B", while the larger cloud model is comparable to GPT-3.5.</p>
<p>The language models were trained on unlicensed scraped data - I was hoping they might have managed to avoid that, but sadly not:</p>
<blockquote>
<p>We train our foundation models on licensed data, including data selected to enhance specific features, as well as publicly available data collected by our web-crawler, AppleBot.</p>
</blockquote>
<p>The most interesting thing here is the way they apply fine-tuning to the local model to specialize it for different tasks. Apple call these "adapters", and they use LoRA for this - a technique first pub

## Private Cloud Compute: A new frontier for AI privacy in the cloud
 - [https://simonwillison.net/2024/Jun/11/private-cloud-compute/#atom-everything](https://simonwillison.net/2024/Jun/11/private-cloud-compute/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-11T15:38:15+00:00

<p><a href="https://security.apple.com/blog/private-cloud-compute/">Private Cloud Compute: A new frontier for AI privacy in the cloud</a></p>
Here are the details about Apple's Private Cloud Compute infrastructure, and they are pretty extraordinary.</p>
<p>The goal with PCC is to allow Apple to run larger AI models that won't fit on a device, but in a way that guarantees that private data passed from the device to the cloud cannot leak in any way - not even to Apple engineers with SSH access who are debugging an outage.</p>
<p>This is an extremely challenging problem, and their proposed solution includes a wide range of new innovations in private computing.</p>
<p>The most impressive part is their approach to technically enforceable guarantees and verifiable transparency. How do you ensure that privacy isn't broken by a future code change? And how can you allow external experts to verify that the software running in your data center is the same software that they have independently au

