# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## OpenAI: Introducing Structured Outputs in the API
 - [https://simonwillison.net/2024/Aug/6/openai-structured-outputs/#atom-everything](https://simonwillison.net/2024/Aug/6/openai-structured-outputs/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-06T18:32:25+00:00

<p><strong><a href="https://openai.com/index/introducing-structured-outputs-in-the-api/">OpenAI: Introducing Structured Outputs in the API</a></strong></p>
OpenAI have offered structured outputs for a while now: you could specify <code>"response_format": {"type": "json_object"}}</code> to request a valid JSON object, or you could use the <a href="https://platform.openai.com/docs/guides/function-calling">function calling</a> mechanism to request responses that match a specific schema.</p>
<p>Neither of these modes were guaranteed to return valid JSON! In my experience they usually did, but there was always a chance that something could go wrong and the returned code could not match the schema, or even not be valid JSON at all.</p>
<p>Outside of OpenAI techniques like <a href="https://github.com/1rgs/jsonformer">jsonformer</a> and <a href="https://til.simonwillison.net/llms/llama-cpp-python-grammars">llama.cpp grammars</a> could provide those guarantees against open weights models, by i

## Weeknotes: a staging environment, a Datasette alpha and a bunch of new LLMs
 - [https://simonwillison.net/2024/Aug/6/staging/#atom-everything](https://simonwillison.net/2024/Aug/6/staging/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-06T15:41:14+00:00

<p>My big achievement for the last two weeks was finally wrapping up work on the Datasette Cloud staging environment. I also shipped a new Datasette 1.0 alpha and added support to the LLM ecosystem for a bunch of newly released models.</p>

<ul>
  <li><a href="#a-staging-environment-for-datasette-cloud">A staging environment for Datasette Cloud</a></li>
  <li><a href="#datasette-1-0a14">Datasette 1.0a14</a></li>
  <li><a href="#llama-3-1-ggufs-and-mistral-for-llm">Llama 3.1 GGUFs and Mistral for LLM</a></li>
  <li><a href="#weeknotes-aug-6-2024-blog-entries">Blog entries</a></li>
  <li><a href="#weeknotes-aug-6-2024-releases">Releases</a></li>
  <li><a href="#weeknotes-aug-6-2024-tils">TILs</a></li>
</ul>

<h4 id="a-staging-environment-for-datasette-cloud">A staging environment for Datasette Cloud</h4>
<p>I'm a big believer in investing in projects to help accelerate future work. Having a productive development environment is critical for me - it's why most of my projects start with t

## macOS 15.1 Beta 1: Apple Intelligence Backend Prompts
 - [https://simonwillison.net/2024/Aug/6/apple-intelligence-prompts/#atom-everything](https://simonwillison.net/2024/Aug/6/apple-intelligence-prompts/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-06T04:34:15+00:00

<p><strong><a href="https://www.reddit.com/r/MacOSBeta/comments/1ehivcp/macos_151_beta_1_apple_intelligence_backend/">macOS 15.1 Beta 1: Apple Intelligence Backend Prompts</a></strong></p>
Reddit user <a href="https://www.reddit.com/user/devanxd2000/">devanxd2000</a> found what look like the system prompts for various Apple Intelligence features in the <code>/System/Library/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels</code> folder on their installation of macOS 15.1 Beta 1.</p>
<p>I had incorrectly assumed that tasks like summarization were being handled by fine-tuned models - what Apple have been calling "adapters".</p>
<p>That appears not to be the case. Here's a prompt stored as <code>com.apple.textComposition.MailReplyLongFormRewrite</code>:</p>
<blockquote>
<p><code>{{ specialToken.chat.role.system }}You are an assistant which helps the user respond to their mails. Given a mail, a draft response is initially provided based on a short reply snippet. In order to make the

