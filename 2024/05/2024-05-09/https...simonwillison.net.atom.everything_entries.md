# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Bullying in Open Source Software Is a Massive Security Vulnerability
 - [https://simonwillison.net/2024/May/9/bullying-in-open-source-software/#atom-everything](https://simonwillison.net/2024/May/9/bullying-in-open-source-software/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-09T22:26:43+00:00

<p><a href="https://www.404media.co/xz-backdoor-bullying-in-open-source-software-is-a-massive-security-vulnerability/">Bullying in Open Source Software Is a Massive Security Vulnerability</a></p>
The Xz story from <a href="https://simonwillison.net/2024/Apr/5/everything-i-know-about-the-xz-backdoor/">last month</a>, where a malicious contributor almost managed to ship a backdoor to a number of major Linux distributions, included a nasty detail where presumed collaborators with the attacker bullied the maintainer to make them more susceptible to accepting help.</p>
<p>Hans-Christoph Steiner from F-Droid <a href="https://social.librem.one/@eighthave/112194828562355097">reported a similar</a> attempt from a few years ago:</p>
<blockquote>
<p>A new contributor submitted a merge request to improve the search, which was oft requested but the maintainers hadn't found time to work on.  There was also pressure from other random accounts to merge it. In the end, it became clear that it added a 

## experimental-phi3-webgpu
 - [https://simonwillison.net/2024/May/9/experimental-phi3-webgpu/#atom-everything](https://simonwillison.net/2024/May/9/experimental-phi3-webgpu/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-09T22:21:48+00:00

<p><a href="https://huggingface.co/spaces/Xenova/experimental-phi3-webgpu">experimental-phi3-webgpu</a></p>
Run Microsoft’s excellent Phi-3 model directly in your browser, using WebGPU so didn’t work in Firefox for me, just in Chrome.</p>

<p>It fetches around 2.1GB of data into the browser cache on first run, but then gave me decent quality responses to my prompts running at an impressive 21 tokens a second (M2, 64GB).</p>

<p>I think Phi-3 is the highest quality model of this size, so it’s a really good fit for running in a browser like this.

    <p>Via <a href="https://twitter.com/xenovacom/status/1788664184487432679">@xenovacom</a></p>

## datasette-pins — a new Datasette plugin for pinning tables and queries
 - [https://simonwillison.net/2024/May/9/datasette-pins/#atom-everything](https://simonwillison.net/2024/May/9/datasette-pins/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-09T18:29:03+00:00

<p><a href="https://www.datasette.cloud/blog/2024/datasette-pins/">datasette-pins — a new Datasette plugin for pinning tables and queries</a></p>
Alex Garcia built this plugin for Datasette Cloud, and as with almost every Datasette Cloud features we're releasing it as <a href="https://github.com/datasette/datasette-pins">an open source package</a> as well.</p>
<p><code>datasette-pins</code> allows users with the right permission to "pin" tables, databases and queries to their homepage. It's a lightweight way to customize that homepage, especially useful as your Datasette instance grows to host dozens or even hundreds of tables.

