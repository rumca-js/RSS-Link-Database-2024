# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## After 2 months learning scraping, I'm sharing what I learned!
 - [https://www.reddit.com/r/webscraping/comments/1flgwup/after_2_months_learning_scraping_im_sharing_what](https://www.reddit.com/r/webscraping/comments/1flgwup/after_2_months_learning_scraping_im_sharing_what)
 - RSS feed: $source
 - date published: 2024-09-20T16:59:51+00:00

<!-- SC_OFF --><div class="md"><ol> <li>Don&#39;t try putting scraping tools in Lambda. Just admit defeat!</li> <li>Selenium is cool and talked about a lot, but Playwright/Puppeteer/hrequests are new and better.</li> <li>Don&#39;t feel like you have to go with Python. The Node.JS scraping community is huge! And more modern advice than Selenium.</li> <li>AI will likely teach you old tricks because it&#39;s trained on a lot of old data. Use Medium/google search with timeframe &lt; 1 year.</li> <li>Scraping is about new tricks, as Cloudflare, etc block a lot of scraping tactics.</li> <li>Playwright is super cool! A lot of MS coders brought on from Puppeteer, from what I heard. The stealth plugin doesn&#39;t work, however (most stealth plugins don&#39;t, in fact!)</li> <li>Find out YOUR browser headers</li> <li>Don&#39;t worry about fancy proxies, etc if you&#39;re scraping lots of sites at scale. Worry if you&#39;re scraping lots of data from one site, or regular data scraping from one s

## Proxy Validation/Filtering Library
 - [https://www.reddit.com/r/webscraping/comments/1flg8yl/proxy_validationfiltering_library](https://www.reddit.com/r/webscraping/comments/1flg8yl/proxy_validationfiltering_library)
 - RSS feed: $source
 - date published: 2024-09-20T16:31:06+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks,</p> <p>TL;DR: Made a tool to check if proxies are alive to avoid server lockouts. Sharing in case it helps others! <a href="https://github.com/phileasme/ProxyFilter">-&gt; *Proxy Filtering Library* &lt;-</a></p> <p>Full story:</p> <ul> <li>On Monday my provider locked up my server&#39;s IP address and flagged the events as network abuse.</li> <li>The culprit? Making an overwhelmingly large number of calls to dead proxies (oops, my bad).</li> <li>I created a simple tool to prevent this from happening again. Check it out :) *it&#39;s free 💵</li> </ul> <p>What it does:</p> <ul> <li>Checks if addresses are alive</li> <li>Marks them as unrouted, behind Cloudflare, or invalid (likely unstable)</li> <li>Keeps track of everything, number of calls, providers, etc..</li> </ul> <p>This might be useful if you&#39;re:</p> <ul> <li>Using rotating proxies</li> <li>Pulling from multiple sources (like proxy lists)</li> </ul> <p>It&#39;s nothing fancy, it&#3

## Need Data Using Fetch Method
 - [https://www.reddit.com/r/webscraping/comments/1fl6imx/need_data_using_fetch_method](https://www.reddit.com/r/webscraping/comments/1fl6imx/need_data_using_fetch_method)
 - RSS feed: $source
 - date published: 2024-09-20T07:37:38+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I want to extract details from this page - <a href="https://www.menards.com/main/bath/bathroom-faucets/bathtub-shower-faucets/moen-reg-adler-trade-posi-temp-reg-one-handle-4-spray-shower-faucet/82604/p-1474478959890-c-5906.htm">https://www.menards.com/main/bath/bathroom-faucets/bathtub-shower-faucets/moen-reg-adler-trade-posi-temp-reg-one-handle-4-spray-shower-faucet/82604/p-1474478959890-c-5906.htm</a> using fetch request but not able to find any api. Can anyone help me on this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Minimum-Earth9509"> /u/Minimum-Earth9509 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fl6imx/need_data_using_fetch_method/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fl6imx/need_data_using_fetch_method/">[comments]</a></span>

