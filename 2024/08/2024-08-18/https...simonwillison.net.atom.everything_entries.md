# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Fix @covidsewage bot to handle a change to the underlying website
 - [https://simonwillison.net/2024/Aug/18/fix-covidsewage-bot/#atom-everything](https://simonwillison.net/2024/Aug/18/fix-covidsewage-bot/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-18T17:26:32+00:00

<p><strong><a href="https://github.com/simonw/covidsewage-bot/issues/6">Fix @covidsewage bot to handle a change to the underlying website</a></strong></p>
I've been running <a href="https://fedi.simonwillison.net/@covidsewage">@covidsewage</a> on Mastodon since February last year tweeting a daily screenshot of the Santa Clara County charts showing Covid levels in wastewater.</p>
<p>A few days ago the county changed their website, breaking the bot. The chart now lives on their new <a href="https://publichealth.santaclaracounty.gov/health-information/health-data/disease-data/covid-19/covid-19-wastewater">COVID in wastewater</a> page.</p>
<p>It's still a Microsoft Power BI dashboard in an <code>&lt;iframe&gt;</code>, but my initial attempts to scrape it didn't quite work. Eventually I realized that Cloudflare protection was blocking my attempts to access the page, but thankfully sending a Firefox user-agent fixed that problem.</p>
<p>The new recipe I'm using to screenshot the chart invol

## Reckoning
 - [https://simonwillison.net/2024/Aug/18/reckoning/#atom-everything](https://simonwillison.net/2024/Aug/18/reckoning/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-18T16:37:41+00:00

<p><strong><a href="https://infrequently.org/series/reckoning/">Reckoning</a></strong></p>
Alex Russell is a self-confessed <a href="https://en.wikipedia.org/wiki/Cassandra">Cassandra</a> - doomed to speak truth that the wider Web industry stubbornly ignores. With this latest series of posts he is <em>spitting fire</em>.</p>
<p>The series is an "investigation into JavaScript-first frontend culture and how it broke US public services", in four parts.</p>
<p>In <a href="https://infrequently.org/2024/08/object-lesson/">Part 2 — Object Lesson</a> Alex profiles <a href="https://benefitscal.com/">BenefitsCal</a>, the California state portal for accessing SNAP food benefits (aka "food stamps"). On a 9Mbps connection, as can be expected in rural parts of California with populations most likely to need these services, the site takes 29.5 seconds to become usefully interactive, fetching more than 20MB of JavaScript (which isn't even correctly compressed) for a giant SPA that incoroprates React,

## “The Door Problem”
 - [https://simonwillison.net/2024/Aug/18/the-door-problem/#atom-everything](https://simonwillison.net/2024/Aug/18/the-door-problem/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-18T03:50:27+00:00

<p><strong><a href="https://lizengland.com/blog/2014/04/the-door-problem/">“The Door Problem”</a></strong></p>
Delightful allegory from game designer Liz England showing how even the simplest sounding concepts in games - like a door - can raise dozens of design questions and create work for a huge variety of different roles.</p>
<blockquote>
<ul>
<li>Can doors be locked and unlocked?</li>
<li>What tells a player a door is locked and will open, as opposed to a door that they will never open?</li>
<li>Does a player know how to unlock a door? Do they need a key? To hack a console? To solve a puzzle? To wait until a story moment passes?</li>
</ul>
<p>[...]</p>
<p><strong>Gameplay Programmer</strong>: “This door asset now opens and closes based on proximity to the player. It can also be locked and unlocked through script.”<br />
<strong>AI Programmer</strong>: “Enemies and allies now know if a door is there and whether they can go through it.”<br />
<strong>Network Programmer</strong> : “D

