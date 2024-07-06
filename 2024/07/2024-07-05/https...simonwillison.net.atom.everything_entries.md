# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## interactive-feed
 - [https://simonwillison.net/2024/Jul/5/interactive-feed/#atom-everything](https://simonwillison.net/2024/Jul/5/interactive-feed/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-05T23:39:01+00:00

<p><a href="https://github.com/sammorrisdesign/interactive-feed">interactive-feed</a></p>
Sam Morris maintains this project which gathers interactive, graphic, and data visualization stories from various newsrooms around the world and publishes them on  <a href="https://twitter.com/InteractiveFeed">Twitter</a>, <a href="https://botsin.space/@Interactives">Mastodon</a> and <a href="https://staging.bsky.app/profile/interactives.bsky.social">Bluesky</a>.</p>
<p>It runs automatically using GitHub Actions, and gathers data using a number of different techniques - XML feeds, custom API integrations (for the NYT, Guardian and Washington Post) and in some cases by scraping index pages on news websites <a href="https://github.com/sammorrisdesign/interactive-feed/blob/1652b7b6a698ad97f88b542cfdd94a90be4f119c/src/fetchers.js#L221-L251">using CSS selectors and cheerio</a>.</p>
<p>The data it collects is archived as JSON in the <a href="https://github.com/sammorrisdesign/interactive-feed/tree/main

## UK Parliament election results, now with Datasette
 - [https://simonwillison.net/2024/Jul/5/uk-parliament-election/#atom-everything](https://simonwillison.net/2024/Jul/5/uk-parliament-election/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-05T23:36:18+00:00

<p><a href="https://electionresults.parliament.uk/">UK Parliament election results, now with Datasette</a></p>
The House of Commons Library maintains a website of UK parliamentary election results data, currently listing 2010 through 2019 and with 2024 results coming soon.</p>
<p>The site itself is <a href="https://github.com/ukparliament/psephology">a Rails and PostgreSQL app</a>, but I was delighted to learn today that they're also running <a href="https://psephology-datasette-f3e7b1b7eb77.herokuapp.com/">a Datasette instance</a> with the election results data, linked to from their homepage!</p>
<p><img alt="The data this website uses is available to query. as a Datasette endpoint. The database schema is published for reference. Mobile Safari screenshot on electionresults.parliament.uk" class="centered-image" src="https://static.simonwillison.net/static/2024/electionresults.jpg" width="400" /></p>
<p>The raw data is also available <a href="https://github.com/ukparliament/psephology/

## Tracking Fireworks Impact on Fourth of July AQI
 - [https://simonwillison.net/2024/Jul/5/tracking-fireworks/#atom-everything](https://simonwillison.net/2024/Jul/5/tracking-fireworks/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-05T22:52:51+00:00

<p><a href="https://danny.page/views/tracking-fireworks-on-july-4th">Tracking Fireworks Impact on Fourth of July AQI</a></p>
Danny Page ran <a href="https://shot-scraper.datasette.io/">shot-scraper</a> once per minute (using cron) against <a href="https://map.purpleair.com/1/mAQI/a10/p604800/cC0#8.45/37.764/-121.62">this Purple Air map</a> of the Bay Area and turned the captured screenshots into an animation using <code>ffmpeg</code>. The result shows the impact of 4th of July fireworks on air quality between 7pm and 7am.

    <p>Via <a href="https://twitter.com/DannyPage/status/1809331303386329194">@DannyPage</a></p>

## Quoting Marco Rogers
 - [https://simonwillison.net/2024/Jul/5/marco-rogers/#atom-everything](https://simonwillison.net/2024/Jul/5/marco-rogers/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-05T18:19:26+00:00

<blockquote cite="https://polotek.net/posts/the-frontend-treadmill/"><p>Product teams that are smart are getting off the treadmill. Whatever framework you currently have, start investing in getting to know it deeply. Learn the tools until they are not an impediment to your progress. That’s the only option. Replacing it with a shiny new tool is a trap.</p>
<p>[...]</p>
<p>Companies that want to reduce the cost of their frontend tech becoming obsoleted so often should be looking to get back to fundamentals. Your teams should be working closer to the web platform with a lot less complex abstractions. We need to relearn what the web is capable of and go back to that.</p></blockquote><p class="cite">&mdash; <a href="https://polotek.net/posts/the-frontend-treadmill/">Marco Rogers</a>

## jqjq: jq implementation of jq
 - [https://simonwillison.net/2024/Jul/5/jqjq/#atom-everything](https://simonwillison.net/2024/Jul/5/jqjq/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-05T15:23:14+00:00

<p><a href="https://github.com/wader/jqjq">jqjq: jq implementation of jq</a></p>
2,854 lines of jq that implements a full, working version of jq itself. “A great way to show that jq is a very expressive, capable and neat language!”

    <p>Via <a href="https://lobste.rs/s/eeqpis/jqjq_jq_implementation_jq">Lobste.rs</a></p>

