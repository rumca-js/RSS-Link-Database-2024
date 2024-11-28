# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## An open-source tool for extracting data visually
 - [https://www.reddit.com/r/webscraping/comments/1h1fhy4/an_opensource_tool_for_extracting_data_visually](https://www.reddit.com/r/webscraping/comments/1h1fhy4/an_opensource_tool_for_extracting_data_visually)
 - RSS feed: $source
 - date published: 2024-11-27T21:30:26+00:00

<!-- SC_OFF --><div class="md"><p><strong>Analyzing website screenshots with AI</strong></p> <p>While building out a web browsing agent, I kept encountering the problem of &quot;reading&quot; and understanding a webpage without hardcoding it. </p> <p>I found Microsoft&#39;s OmniParser recently and think it&#39;s a game changer. It is a model trained to analyze UI/website screenshots and output bounding boxes for &quot;clickable&quot; elements. </p> <p>There was no easy way to deploy or self-host the model, so I created <a href="https://github.com/addy999/omniparser-api">this</a> API client that you can deploy and start tinkering with in your scraping projects.</p> <p>Just send a screenshot of your browser and you&#39;ll receive text descriptions of the important elements on the page, along with coordinates. </p> <p>Let me know if it&#39;s useful!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/spacespacespapce"> /u/spacespacespapce </a> <br/> <s

## Guide to using rebrowser patches on Playwright with Python
 - [https://www.reddit.com/r/webscraping/comments/1h1eniu/guide_to_using_rebrowser_patches_on_playwright](https://www.reddit.com/r/webscraping/comments/1h1eniu/guide_to_using_rebrowser_patches_on_playwright)
 - RSS feed: $source
 - date published: 2024-11-27T20:53:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone. I recently discovered the <a href="https://github.com/rebrowser">rebrowser patches</a> for Playwright but I&#39;m looking for a guide on how to use them for a python project. Most importantly there is a comment that says; </p> <p>&gt; &quot;Make sure to read: <a href="https://rebrowser.net/blog/how-to-access-main-context-objects-from-isolated-context-in-puppeteer-and-playwright-23741">How to Access Main Context Objects from Isolated Context</a>&quot;</p> <p>However that example is in Javascript. I would love to see a guide in how to set everything up in Python if that&#39;s possible. I&#39;m testing my script on <a href="https://bot-detector.rebrowser.net/">their bot checking site </a>and it keeps failing.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LordOfTheDips"> /u/LordOfTheDips </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1h1eniu/guide_to_using_rebrowser_patches_on

## Scraping archive(dot)org for images under specific search queries?
 - [https://www.reddit.com/r/webscraping/comments/1h1bhln/scraping_archivedotorg_for_images_under_specific](https://www.reddit.com/r/webscraping/comments/1h1bhln/scraping_archivedotorg_for_images_under_specific)
 - RSS feed: $source
 - date published: 2024-11-27T18:40:23+00:00

<!-- SC_OFF --><div class="md"><p>I need to download a few hundred images from archive(dot)org. I want to use broad search terms like &#39;nature&#39;, and then the scraper downloads as many relevant images from as possible from this search term.</p> <p>I am a complete noob. Any advice and help would be highly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/personanonymous"> /u/personanonymous </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1h1bhln/scraping_archivedotorg_for_images_under_specific/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1h1bhln/scraping_archivedotorg_for_images_under_specific/">[comments]</a></span>

## Scraping German mobile numbers
 - [https://www.reddit.com/r/webscraping/comments/1h1a8g4/scraping_german_mobile_numbers](https://www.reddit.com/r/webscraping/comments/1h1a8g4/scraping_german_mobile_numbers)
 - RSS feed: $source
 - date published: 2024-11-27T17:49:08+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys,</p> <p>I need to scrape a list of German phone number of small business owners that have at least one employee. Does somebody have an advice how to do that or can help?</p> <p>Best regards</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AreaComprehensive804"> /u/AreaComprehensive804 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1h1a8g4/scraping_german_mobile_numbers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1h1a8g4/scraping_german_mobile_numbers/">[comments]</a></span>

## How can I manipulate the request/thread pool on Scrapy?
 - [https://www.reddit.com/r/webscraping/comments/1h184bw/how_can_i_manipulate_the_requestthread_pool_on](https://www.reddit.com/r/webscraping/comments/1h184bw/how_can_i_manipulate_the_requestthread_pool_on)
 - RSS feed: $source
 - date published: 2024-11-27T16:20:48+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I could use some help with Scrapy and JWT authentication.</p> <p>I&#39;ve got a spider where I&#39;m using Playwright to log into a site, grab the cookies, then use Scrapy&#39;s JsonRequest for the API calls. The site uses JWT auth, and I want to store the token as an object attribute (like <code>self.jwt</code>) so I can easily update/access it. I&#39;m stuck on handling token expiration.</p> <p>What I&#39;m trying to figure out:</p> <p>When a request fails because the JWT expired, I need to pause everything, get a fresh token, update <code>self.jwt</code>, and then continue all the pending requests with the new token. Right now I&#39;m just getting a new token for every API call, which... yeah, probably not great. </p> <p>Anyone know if there&#39;s a way to handle this in Scrapy? Can I somehow:</p> <ol> <li>Catch the failed auth in middleware.</li> <li>Pause the request queue</li> <li>Get new JWT and update <code>self.jwt</code></li> 

## temporal.io + go-rod
 - [https://www.reddit.com/r/webscraping/comments/1h16h7l/temporalio_gorod](https://www.reddit.com/r/webscraping/comments/1h16h7l/temporalio_gorod)
 - RSS feed: $source
 - date published: 2024-11-27T15:10:06+00:00

<!-- SC_OFF --><div class="md"><p>Just deployed a pretty tricky setup using the workflow engine <a href="http://temporal.io">temporal.io</a> + the go based dev tools protocol <a href="https://go-rod.github.io/#/">go-rod</a>.</p> <p>I also run all of my ai assisted data curation on go/temporal so it was a natural extension.</p> <p>It&#39;s very scaleable and robust but I had to solve a bunch of problems and overcome many impediments.</p> <p>AMA I guess if you are interested in the approach</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mdausmann"> /u/mdausmann </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1h16h7l/temporalio_gorod/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1h16h7l/temporalio_gorod/">[comments]</a></span>

## Problems of proxy IPs with Cloudfare
 - [https://www.reddit.com/r/webscraping/comments/1h0zp0q/problems_of_proxy_ips_with_cloudfare](https://www.reddit.com/r/webscraping/comments/1h0zp0q/problems_of_proxy_ips_with_cloudfare)
 - RSS feed: $source
 - date published: 2024-11-27T08:25:56+00:00

<!-- SC_OFF --><div class="md"><p>I have tried multiple proxy IP providers (both residental IPs and non-residential IPs) but most of the time their IPs are detected and blocked by Cloudfare. I have tried Smartdata, smartproxy, oxylabs, nodemaven.</p> <p>Context: when i run the same code in my home network, it works 100% of the time but if i use proxy IPs it works only 10% of the time.</p> <p>Does anyone know how to solve this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ConsiderationLivid59"> /u/ConsiderationLivid59 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1h0zp0q/problems_of_proxy_ips_with_cloudfare/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1h0zp0q/problems_of_proxy_ips_with_cloudfare/">[comments]</a></span>

