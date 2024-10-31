# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## I built a scraper for Hong Kong's #1 job platform JobsDB
 - [https://www.reddit.com/r/webscraping/comments/1gfy1pl/i_built_a_scraper_for_hong_kongs_1_job_platform](https://www.reddit.com/r/webscraping/comments/1gfy1pl/i_built_a_scraper_for_hong_kongs_1_job_platform)
 - RSS feed: $source
 - date published: 2024-10-30T21:37:31+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/krishgalani/jobsdb-scraper">https://github.com/krishgalani/jobsdb-scraper</a></p> <p>I&#39;ve seen similar projects online before but none of them work / are outdated with bad code.</p> <p>My scraper workers on all platforms, is consistent in its guarantee to scrape without being blocked, and is <em>relatively</em> fast (takes ~10 minutes to scrape the entire website)</p> <p><strong>What it does:</strong></p> <p>Scrapes the first n pages of jobs specified from JobsDB (there are 1k total). Saves to a JSON file locally.</p> <p><strong>How it works:</strong></p> <p>Uses the ulixee framework (github.com/ulixee), where each worker has a browser environment and goes page by page on its page chunk making GETS and POST fetches to the backend db. All workers have a shared page task queue. Can scrape up to 20 pages concurrently while staying lightweight and avoiding CF detection.</p> <p><strong>Further considerations:</strong></p> <

## Job: help me web scrape Aliexpress in Python
 - [https://www.reddit.com/r/webscraping/comments/1gfubwy/job_help_me_web_scrape_aliexpress_in_python](https://www.reddit.com/r/webscraping/comments/1gfubwy/job_help_me_web_scrape_aliexpress_in_python)
 - RSS feed: $source
 - date published: 2024-10-30T18:59:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m an experienced programmer but usually only use Julia for programming. Now I want to scrape in Python since Julia doesn&#39;t have good libs.</p> <p>Anyone willing to show me how this is best done in Python? I an pay of course.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stvaccount"> /u/stvaccount </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gfubwy/job_help_me_web_scrape_aliexpress_in_python/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gfubwy/job_help_me_web_scrape_aliexpress_in_python/">[comments]</a></span>

## 🚀 27.6% of the Top 10 Million Sites Are Dead
 - [https://www.reddit.com/r/webscraping/comments/1gfmadf/276_of_the_top_10_million_sites_are_dead](https://www.reddit.com/r/webscraping/comments/1gfmadf/276_of_the_top_10_million_sites_are_dead)
 - RSS feed: $source
 - date published: 2024-10-30T13:17:09+00:00

<!-- SC_OFF --><div class="md"><p>In a recent project, I ran a high-performance web scraper to analyze the top 10 million domains—and the results are surprising: over a quarter of these sites (27.6%) are inactive or inaccessible. This research dives into the infrastructure needed to process such a massive dataset, the technical approach to handling 16,667 requests per second, and the significance of &quot;dead&quot; sites in our rapidly shifting web landscape. Whether you&#39;re into large-scale scraping, Redis queue management, or DNS optimization, this deep dive has something for you. Check out the full write-up and leave your feedback here</p> <p>Full <a href="https://tonywang.io/blog/top-10-million-sites-27-percent-dead">article</a> &amp; <a href="https://github.com/tonywangcn/ten-million-domains">code</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/the_bigbang"> /u/the_bigbang </a> <br/> <span><a href="https://www.reddit.com/r/webscrapi

## Maxun: Open Source Self-Hosted No-Code Web Data Extraction Platform
 - [https://www.reddit.com/r/webscraping/comments/1gfhf4y/maxun_open_source_selfhosted_nocode_web_data](https://www.reddit.com/r/webscraping/comments/1gfhf4y/maxun_open_source_selfhosted_nocode_web_data)
 - RSS feed: $source
 - date published: 2024-10-30T08:03:47+00:00

<!-- SC_OFF --><div class="md"><p>Hey Everybody,</p> <p>We are thrilled to open source Maxun today.</p> <p>Maxun is an open-source no-code web data extraction platform. It lets you build custom robots for data scraping in just a few clicks.</p> <p>Github : <a href="https://github.com/getmaxun/maxun">https://github.com/getmaxun/maxun</a></p> <p>Maxun lets you create custom robots which emulate user actions and extract data, while handling dynamic parts like pagination and scrolling.</p> <p>Maxun also lets you turn websites to REST APIs and Spreadsheets. We also support a feature called BYOP (Bring Your Own Proxy) which lets you connect your own anti-bot infrastructure and save huge $$$.</p> <p>Would love to hear use-cases &amp; feedback.</p> <p>Thank you,<br/> Team Maxun</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/carishmaa"> /u/carishmaa </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gfhf4y/maxun_open_source_selfhos

## Queries on curl-cffi
 - [https://www.reddit.com/r/webscraping/comments/1gff9ck/queries_on_curlcffi](https://www.reddit.com/r/webscraping/comments/1gff9ck/queries_on_curlcffi)
 - RSS feed: $source
 - date published: 2024-10-30T05:17:48+00:00

<!-- SC_OFF --><div class="md"><p>Folks knowledgeable with curl-cffi, I have the following 2 questions:</p> <p>A) With some of the proxies I use to crawl a website using cffi solution, I quite frequently get 403s and 407s. The same proxies used with other crawl solutions work fine on the same website. Any known solution for this??</p> <p>B) I was trying to use cffi for mobile, but chrome99_android is the only version I see being supported for chrome for mobile. This implies I can use all mobile chrome versions (99, 100, 122 etc) with chrome99_android right? With a website that performs TLS fingerprinting, does it make sense to use chrome99_android with different chrome user-agent versions??</p> <p>Thank you in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/happyotaku35"> /u/happyotaku35 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gff9ck/queries_on_curlcffi/">[link]</a></span> &#32; <span><a href="https://ww

## What VPN best hides my IP when scrapping?
 - [https://www.reddit.com/r/webscraping/comments/1gfbs35/what_vpn_best_hides_my_ip_when_scrapping](https://www.reddit.com/r/webscraping/comments/1gfbs35/what_vpn_best_hides_my_ip_when_scrapping)
 - RSS feed: $source
 - date published: 2024-10-30T01:57:20+00:00

<!-- SC_OFF --><div class="md"><p>Trynna hide my ip when scraping site ... (NordVPN) got Recommended to me but I thought I&#39;d ask people who know better than me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PhaseOk_1"> /u/PhaseOk_1 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gfbs35/what_vpn_best_hides_my_ip_when_scrapping/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gfbs35/what_vpn_best_hides_my_ip_when_scrapping/">[comments]</a></span>

## Aliexpress sign hash reverse engineering
 - [https://www.reddit.com/r/webscraping/comments/1gfb6vh/aliexpress_sign_hash_reverse_engineering](https://www.reddit.com/r/webscraping/comments/1gfb6vh/aliexpress_sign_hash_reverse_engineering)
 - RSS feed: $source
 - date published: 2024-10-30T01:27:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello folks! I&#39;m trying to use AliExpress&#39;s private API to retrieve product data in a lightweight and captcha-proof way (ultimately, Python requests).</p> <p>The problem is that one of the payload&#39;s params is a hash, which goes by the name of &#39;sign&#39; and uses some obfuscated variables that I couldn&#39;t figure out just yet.</p> <p>If you go to any Aliexpress product page like https:/ /aliexpress.com/item/{product_id}.html, you can search for <code>c.prototype.__processRequestUrl</code> to find the definition of &quot;sign&quot;</p> <p>I replicated the hash function accurately, but I couldn&#39;t understand how to spoof the variables that they defined as <code>var n = this.param; o = this.options;</code></p> <p>If anyone could give a tip to the friend here I, it would be extremely appreciated. I just need to solve this part to make proper calls to their API 🙏🏻🙏🏻🙏🏻</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://w

