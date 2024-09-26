# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Increase reliability of scraping
 - [https://www.reddit.com/r/webscraping/comments/1fph823/increase_reliability_of_scraping](https://www.reddit.com/r/webscraping/comments/1fph823/increase_reliability_of_scraping)
 - RSS feed: $source
 - date published: 2024-09-25T22:30:47+00:00

<!-- SC_OFF --><div class="md"><p>For my webscraping project (I use BeautifulSoup in python), I need to scrape this h3 element:</p> <p>&lt;h3 class=&quot;text-sm text-white font-medium&quot;&gt;...&lt;/h3&gt;</p> <p>However, the only way I know how to Identify it is through the class, but, since it is used for css, it changes from time to time, so its annoying to always have to update it. Is there a better way to go about scraping it? I&#39;ve already thought of finding a more reliable parent tag, but all the tags follow the same class scheme💀</p> <p>if it helps, this is the website I&#39;m scraping from and my goals are the chapter #&#39;s:</p> <p><a href="https://asuracomic.net/series/omniscient-readers-viewpoint-91ad8ed9">https://asuracomic.net/series/omniscient-readers-viewpoint-91ad8ed9</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/the_dawster"> /u/the_dawster </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fph

## Can anybody make an online Python-based SubscribeStar scraper?
 - [https://www.reddit.com/r/webscraping/comments/1fpgxax/can_anybody_make_an_online_pythonbased](https://www.reddit.com/r/webscraping/comments/1fpgxax/can_anybody_make_an_online_pythonbased)
 - RSS feed: $source
 - date published: 2024-09-25T22:17:01+00:00

<!-- SC_OFF --><div class="md"><p>Can anybody make an online Python/Scrapy-based SubscribeStar scraper (that actually shows unblocked/unblurred images) that&#39;s similar to FurArchiver? Kemono Party hasn&#39;t fixed the SubscribeStar importer for 2 years now due to SubscribeStar&#39;s anti-leak/anti-scrape system as well as SubscribeStar&#39;s admins automatically banning people who may be leaking stuff from their website.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/burai1992"> /u/burai1992 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fpgxax/can_anybody_make_an_online_pythonbased/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fpgxax/can_anybody_make_an_online_pythonbased/">[comments]</a></span>

## Scraping links on webpages, ideally with Python or Google Sheets.
 - [https://www.reddit.com/r/webscraping/comments/1fpglbc/scraping_links_on_webpages_ideally_with_python_or](https://www.reddit.com/r/webscraping/comments/1fpglbc/scraping_links_on_webpages_ideally_with_python_or)
 - RSS feed: $source
 - date published: 2024-09-25T22:01:43+00:00

<!-- SC_OFF --><div class="md"><p>I adapted the code below from <a href="https://docs.zyte.com/web-scraping/tutorial/setup.html">Scrapy</a>. My code returns a blank csv. I think the problems are the &quot;.next a&quot; and &quot;article a&quot;. I don&#39;t know how to identify them on the site I&#39;m trying to scrape.</p> <p>Heads-up: the links refer to sexual materials. from scrapy import Spider</p> <pre><code>class GBT(Spider): name = &quot;GBY&quot; start_urls = [ &quot;https://www.gayboystube.com/user/ABX#page1-videos,415652,1&quot; ] def parse(self, response): next_page_links = response.css(&quot;.next a&quot;) yield from response.follow_all(next_page_links) GBT_links = response.css(&quot;article a&quot;) yield from response.follow_all(GBT_links, callback=self.parse_GBT) def parse_GBT(self, response): yield { &quot;url&quot;: response.url, } </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ilovewacha3"> /u/ilovewacha3 </a> <br/> <

## How do you do concurrent requests in Python?
 - [https://www.reddit.com/r/webscraping/comments/1fpdhqk/how_do_you_do_concurrent_requests_in_python](https://www.reddit.com/r/webscraping/comments/1fpdhqk/how_do_you_do_concurrent_requests_in_python)
 - RSS feed: $source
 - date published: 2024-09-25T19:48:30+00:00

<!-- SC_OFF --><div class="md"><p>I am using requests + concurrent.futures, but it seems like the maximum concurrent requests I can do is 8. Is there a better way to do it so I can have more concurrent requests running? Like using other libraries/programs or something.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NopeNotHB"> /u/NopeNotHB </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fpdhqk/how_do_you_do_concurrent_requests_in_python/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fpdhqk/how_do_you_do_concurrent_requests_in_python/">[comments]</a></span>

## 500 requests/s in Python?
 - [https://www.reddit.com/r/webscraping/comments/1fpcy8p/500_requestss_in_python](https://www.reddit.com/r/webscraping/comments/1fpcy8p/500_requestss_in_python)
 - RSS feed: $source
 - date published: 2024-09-25T19:25:18+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I need to make a lot of requests to an api. I have rotating proxies and am using asynchronous programming, however my computer seems limited to something like 200 requests per second. It&#39;s not about bandwidth since it&#39;s not using more than 10% of it.</p> <p>How can I maximize the number of requests per second? Should I distribute the load among several workers? Or eventually use a faster language such as C++?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Due-Exercise6990"> /u/Due-Exercise6990 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fpcy8p/500_requestss_in_python/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fpcy8p/500_requestss_in_python/">[comments]</a></span>

## Intelligently skip irrelevant pages + do search and replace
 - [https://www.reddit.com/r/webscraping/comments/1fp9b9s/intelligently_skip_irrelevant_pages_do_search_and](https://www.reddit.com/r/webscraping/comments/1fp9b9s/intelligently_skip_irrelevant_pages_do_search_and)
 - RSS feed: $source
 - date published: 2024-09-25T16:53:53+00:00

<!-- SC_OFF --><div class="md"><p>I know how to scrape a website a dozen different ways, but does anyone know of a service or python script to do so in a way that makes it ready for ChatGPT Assistant to ingest, especially if it&#39;s from a third party&#39;s data?</p> <p>Example use case: I want a chatbot for a professional landscaper, and I want it to answer questions like &quot;do you agree with keeping the lawn longer or shorter?&quot; according to following the guidelines from trade association A instead of trade association B.</p> <p>I&#39;m imagining the following:</p> <ol> <li>type in a site URL (trade association A) and tell the scraper to only look for informational content (ideally on a specific topic like &quot;lawns&quot; but not &quot;trees&quot;) so that it intelligently skips pages like Terms, Contact Us, and Location-specific pages (yes, I know I could exclude specific URLs or URL patterns) - and also skips ones like &quot;best time of year to trim trees&quot; - but in

## Find emails of web users
 - [https://www.reddit.com/r/webscraping/comments/1fp934r/find_emails_of_web_users](https://www.reddit.com/r/webscraping/comments/1fp934r/find_emails_of_web_users)
 - RSS feed: $source
 - date published: 2024-09-25T16:44:38+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible to scrape emails of a website users or people who log in to a website? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/InkalimevaII"> /u/InkalimevaII </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fp934r/find_emails_of_web_users/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fp934r/find_emails_of_web_users/">[comments]</a></span>

## A good software that helps me scrape data of schools in the USA
 - [https://www.reddit.com/r/webscraping/comments/1fp85mn/a_good_software_that_helps_me_scrape_data_of](https://www.reddit.com/r/webscraping/comments/1fp85mn/a_good_software_that_helps_me_scrape_data_of)
 - RSS feed: $source
 - date published: 2024-09-25T16:05:56+00:00

<!-- SC_OFF --><div class="md"><p>Just like in the title, I badly need a software that could help me speed up the search. Thanks in advance! P.S. I don&#39;t mind paying for the software.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/blackbrandy"> /u/blackbrandy </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fp85mn/a_good_software_that_helps_me_scrape_data_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fp85mn/a_good_software_that_helps_me_scrape_data_of/">[comments]</a></span>

## Is this achievable? Scraping 1000 jobs daily from a job board
 - [https://www.reddit.com/r/webscraping/comments/1fp34xi/is_this_achievable_scraping_1000_jobs_daily_from](https://www.reddit.com/r/webscraping/comments/1fp34xi/is_this_achievable_scraping_1000_jobs_daily_from)
 - RSS feed: $source
 - date published: 2024-09-25T12:25:24+00:00

<!-- SC_OFF --><div class="md"><p>Beginner here.</p> <p>I did some reaserach on this topic on the subreddit but could&#39;nt come to a definitive answer, so here I am.</p> <p>I&#39;m diving into a large and complex ML project. The first step is obviously data acquisition, and this is such a huge subject on its own. I considered using paid solutions first, as I didn&#39;t want to spend too much time on this part (there are other complex ML-related parts ahead), but they&#39;re really expensive.</p> <p>I&#39;m wondering if I should dive into web scraping first, and if it will be worth it. Scraping job boards seems like an endless struggle. For now, I&#39;ve used the free tier of Octoparse to manually extract data from the microsoft-owned job board, but it comes with many limits (no automation, for example).</p> <p>What makes me think I could write my own scripts is:</p> <ul> <li>I&#39;m extracting a really small amount of data (1000 jobs)</li> <li>I don&#39;t have to log in since most j

## How do I scrape this site?
 - [https://www.reddit.com/r/webscraping/comments/1fp2d3c/how_do_i_scrape_this_site](https://www.reddit.com/r/webscraping/comments/1fp2d3c/how_do_i_scrape_this_site)
 - RSS feed: $source
 - date published: 2024-09-25T11:43:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>New to all this, wanted some guidance on how I can scrape this site:</p> <p><a href="https://www.wowhead.com/guide/classes/death-knight/frost/overview-pve-dps">https://www.wowhead.com/guide/classes/death-knight/frost/overview-pve-dps</a></p> <p>Not just this page, but this entire &quot;guide&quot;, ex sub links, side navigation, hyperlinks, etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Emphesis"> /u/Emphesis </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fp2d3c/how_do_i_scrape_this_site/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fp2d3c/how_do_i_scrape_this_site/">[comments]</a></span>

