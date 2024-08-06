# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Datasette 1.0a14: The annotated release notes
 - [https://simonwillison.net/2024/Aug/5/datasette-1a14/#atom-everything](https://simonwillison.net/2024/Aug/5/datasette-1a14/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-05T23:20:01+00:00

<p>Released today: <a href="https://docs.datasette.io/en/1.0a14/changelog.html#a14-2024-08-05">Datasette 1.0a14</a>. This alpha includes significant contributions from <a href="https://alexgarcia.xyz/">Alex Garcia</a>, including some backwards-incompatible changes in the run-up to the 1.0 release.</p>

<ul>
  <li><a href="#metadata-now-lives-in-a-database">Metadata now lives in a database</a></li>
  <li><a href="#datasette-remote-metadata-0-2a0">datasette-remote-metadata 0.2a0</a></li>
  <li><a href="#sqlite-isolation-level-immediate-">SQLite isolation_level="IMMEDIATE"</a></li>
  <li><a href="#updating-the-urls">Updating the URLs</a></li>
  <li><a href="#everything-else">Everything else</a></li>
  <li><a href="#tricks-to-help-construct-the-release-notes">Tricks to help construct the release notes</a></li>
</ul>

<h4 id="metadata-now-lives-in-a-database">Metadata now lives in a database</h4>
<p>The biggest change in the alpha concerns how Datasette's <a href="https://docs.datasette.io

## Leaked Documents Show Nvidia Scraping ‘A Human Lifetime’ of Videos Per Day to Train AI
 - [https://simonwillison.net/2024/Aug/5/nvidia-scraping-videos/#atom-everything](https://simonwillison.net/2024/Aug/5/nvidia-scraping-videos/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-05T17:19:36+00:00

<p><strong><a href="https://www.404media.co/nvidia-ai-scraping-foundational-model-cosmos-project/">Leaked Documents Show Nvidia Scraping ‘A Human Lifetime’ of Videos Per Day to Train AI</a></strong></p>
Samantha Cole at 404 Media reports on a huge leak of internal NVIDIA communications - mainly from a Slack channel - revealing details of how they have been collecting video training data for a new video foundation model called Cosmos. The data is mostly from YouTube, downloaded via <code>yt-dlp</code> using a rotating set of AWS IP addresses and consisting of millions (maybe even hundreds of millions) of videos.</p>
<p>The fact that companies scrape unlicensed data to train models isn't at all surprising. This article still provides a fascinating insight into what model training teams care about, with details like this from a project update via email:</p>
<blockquote>
<p>As we measure against our desired distribution focus for the next week remains on cinematic, drone footage, egocentr

## How to Get or Create in PostgreSQL
 - [https://simonwillison.net/2024/Aug/5/how-to-get-or-create-in-postgresql/#atom-everything](https://simonwillison.net/2024/Aug/5/how-to-get-or-create-in-postgresql/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-05T15:15:30+00:00

<p><strong><a href="https://hakibenita.com/postgresql-get-or-create">How to Get or Create in PostgreSQL</a></strong></p>
Get or create - for example to retrieve an existing tag record from a database table if it already exists or insert it if it doesn’t - is a surprisingly difficult operation.</p>
<p>Haki Benita uses it to illustrate a variety of interesting PostgreSQL concepts.</p>
<p>New to me: a pattern that runs <code>INSERT INTO tags (name) VALUES (tag_name) RETURNING *;</code> and then catches the constraint violation and returns a record instead has a disadvantage at scale: “The table contains a dead tuple for every attempt to insert a tag that already existed” - so until vacuum runs you can end up with significant table bloat!</p>
<p>Haki’s conclusion is that the best solution relies on an upcoming feature <a href="https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=c649fa24a42ba89bf5460c7110e4fc8eeca65959">coming in PostgreSQL 17</a>: the ability to combine the

## Quoting Erich Gubler
 - [https://simonwillison.net/2024/Aug/5/erich-gubler/#atom-everything](https://simonwillison.net/2024/Aug/5/erich-gubler/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-05T02:26:40+00:00

<blockquote cite="https://news.ycombinator.com/item?id=41156872#41157602"><p>[On WebGPU in Firefox] There is a <em>lot</em> of work to do still to make sure we comply with the spec. in a way that's acceptable to ship in a browser. We're 90% of the way there in terms of functionality, but the last 10% of fixing up spec. changes in the last few years + being significantly more resourced-constrained (we have 3 full-time folks, Chrome has/had an order of magnitude more humans working on WebGPU) means we've got our work cut out for us. We're hoping to ship sometime in the next year, but I won't make promises here.</p></blockquote><p class="cite">&mdash; <a href="https://news.ycombinator.com/item?id=41156872#41157602">Erich Gubler</a></p>

    <p>Tags: <a href="https://simonwillison.net/tags/firefox">firefox</a>, <a href="https://simonwillison.net/tags/webgpu">webgpu</a></p>

