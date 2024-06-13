# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Datasette 0.64.7
 - [https://simonwillison.net/2024/Jun/12/datasette-0647/#atom-everything](https://simonwillison.net/2024/Jun/12/datasette-0647/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-12T22:55:00+00:00

<p><a href="https://docs.datasette.io/en/stable/changelog.html#v0-64-7">Datasette 0.64.7</a></p>
A very minor dot-fix release for Datasette stable, addressing <a href="https://github.com/simonw/datasette/issues/2353">this bug</a> where Datasette running against the latest version of SQLite - 3.46.0 - threw an error on canned queries that included <code>:named</code> parameters in their SQL.</p>
<p>The root cause was Datasette using <a href="https://github.com/simonw/datasette/blob/7437d40e5dd4d614bb769e16c0c1b96c6c19647f/datasette/utils/__init__.py#L1137-L1150">a now invalid clever trick</a> I came up with against the undocumented and unstable opcodes returned by a SQLite <code>EXPLAIN</code> query.</p>
<p>I asked on the SQLite forum and learned that the feature I was using was removed in <a href="https://sqlite.org/src/info/dd5977c9a8a418be">this commit to SQLite</a>. D. Richard Hipp <a href="https://sqlite.org/forum/forumpost/1cafc721009cef7f">explains</a>:</p>
<blockquote>
<p>The P

## Quoting Ben Thompson
 - [https://simonwillison.net/2024/Jun/12/ben-thompson/#atom-everything](https://simonwillison.net/2024/Jun/12/ben-thompson/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-12T21:29:38+00:00

<blockquote><p>Contrast [Apple Intelligence] to what OpenAI is trying to accomplish with its GPT models, or Google with Gemini, or Anthropic with Claude: those large language models are trying to incorporate all of the available public knowledge to know everything; it’s a dramatically larger and more difficult problem space, which is why they get stuff wrong. There is also a lot of stuff that they don’t know because that information is locked away — like all of the information on an iPhone.</p></blockquote><p class="cite">&mdash; Ben Thompson

## A homepage redesign for my blog's 22nd birthday
 - [https://simonwillison.net/2024/Jun/12/homepage-redesign/#atom-everything](https://simonwillison.net/2024/Jun/12/homepage-redesign/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-12T19:59:17+00:00

<p>This blog is 22 years old today! I wrote up <a href="https://simonwillison.net/2022/Jun/12/twenty-years/">a whole bunch of higlights</a> for the 20th birthday a couple of years ago. Today I'm celebrating with something a bit smaller: I finally redesigned the homepage.</p>
<p>I publish three kinds of content on my blog: <a href="https://simonwillison.net/search/?type=entry">entries</a> (like this one), "<a href="https://simonwillison.net/search/?type=blogmark">blogmarks</a>" (aka annotated links) and <a href="https://simonwillison.net/search/?type=quotation">quotations</a>. Until recently the entries were the main feature on the (desktop) homepage, with blogmarks and quotations relegated to the sidebar.</p>
<p>Back in April I <a href="https://simonwillison.net/2024/Apr/25/blogmarks-that-use-markdown/">implemented Markdown support</a> for my blogmarks, allowing me to include additional links and quotations in the body of those descriptions.</p>
<p>I was inspired in this by <a href="h

## Generative AI Is Not Going To Build Your Engineering Team For You
 - [https://simonwillison.net/2024/Jun/12/generative-ai-is-not-going-to-build-your-engineering-team/#atom-everything](https://simonwillison.net/2024/Jun/12/generative-ai-is-not-going-to-build-your-engineering-team/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-12T15:11:25+00:00

<p><a href="https://stackoverflow.blog/2024/06/10/generative-ai-is-not-going-to-build-your-engineering-team-for-you/">Generative AI Is Not Going To Build Your Engineering Team For You</a></p>
This is a long read by Charity Majors, and I find myself wanting to quote almost every paragraph.</p>
<p>It thoroughly and passionately debunks the idea that generative AI means that teams no longer need to hire junior programmers.</p>
<p>This is for several key reasons. First is the familiar pipeline argument - we need juniors in order to grow new intermediate and senior engineers:</p>
<blockquote>
<p>Software is an apprenticeship industry. You can’t learn to be a software engineer by reading books. You can only learn by doing…and doing, and doing, and doing some more. No matter what your education consists of, most learning happens on the job—period. And it never ends! Learning and teaching are lifelong practices; they have to be, the industry changes so fast.</p>
<p>It takes a solid seven-plus

