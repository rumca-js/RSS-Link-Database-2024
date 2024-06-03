# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Andrej Karpathy
 - [https://simonwillison.net/2024/Jun/2/andrej-karpathy/#atom-everything](https://simonwillison.net/2024/Jun/2/andrej-karpathy/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-02T21:09:44+00:00

<blockquote cite="https://twitter.com/karpathy/status/1797313173449764933"><p>Turns out that LLMs learn a lot better and faster from educational content as well. This is partly because the average Common Crawl article (internet pages) is not of very high value and distracts the training, packing in too much irrelevant information. The average webpage on the internet is so random and terrible it&#x27;s not even clear how prior LLMs learn anything at all.</p></blockquote><p class="cite">&mdash; <a href="https://twitter.com/karpathy/status/1797313173449764933">Andrej Karpathy</a>

## Experimenting with local alt text generation in Firefox Nightly
 - [https://simonwillison.net/2024/Jun/2/experimenting-with-local-alt-text-generation-in-firefox-nightly/#atom-everything](https://simonwillison.net/2024/Jun/2/experimenting-with-local-alt-text-generation-in-firefox-nightly/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-02T13:12:44+00:00

<p><a href="https://hacks.mozilla.org/2024/05/experimenting-with-local-alt-text-generation-in-firefox-nightly/">Experimenting with local alt text generation in Firefox Nightly</a></p>
The PDF editor in Firefox (confession: I did not know Firefox ships with a PDF editor) is getting an experimental feature that can help suggest alt text for images for the human editor to then adapt and improve on.</p>
<p>This is a great application of AI, made all the more interesting here because Firefox will run a local model on-device for this, using a custom trained model they describe as "our 182M parameters model using a Distilled version of GPT-2 alongside a Vision Transformer (ViT) image encoder".</p>
<p>The model uses WebAssembly with ONNX running in <a href="https://huggingface.co/docs/transformers.js/en/index">Transfomers.js</a>, and will be downloaded the first time the feature is put to use.

    <p>Via <a href="https://twitter.com/mozhacks/status/1796774672639336804">@mozhacks</a></p>

