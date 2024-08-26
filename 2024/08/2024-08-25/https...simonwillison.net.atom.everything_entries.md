# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## My @covidsewage bot now includes useful alt text
 - [https://simonwillison.net/2024/Aug/25/covidsewage-alt-text/#atom-everything](https://simonwillison.net/2024/Aug/25/covidsewage-alt-text/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-25T16:09:49+00:00

<p><strong><a href="https://fedi.simonwillison.net/@covidsewage/113023397159658020">My @covidsewage bot now includes useful alt text</a></strong></p>
I've been running a <a href="https://fedi.simonwillison.net/@covidsewage">@covidsewage</a> Mastodon bot for a while now, posting daily screenshots (taken with <a href="https://shot-scraper.datasette.io/">shot-scraper</a>) of the Santa Clara County <a href="https://publichealth.santaclaracounty.gov/health-information/health-data/disease-data/covid-19/covid-19-wastewater">COVID in wastewater</a> dashboard.</p>
<p>Prior to today the screenshot was accompanied by the decidedly unhelpful alt text "Screenshot of the latest Covid charts".</p>
<p>I finally fixed that today, closing <a href="https://github.com/simonw/covidsewage-bot/issues/2">issue #2</a> more than two years after I first opened it.</p>
<p>The screenshot is of a Microsoft Power BI dashboard. I hoped I could scrape the key information out of it using JavaScript, but the weirdness 

