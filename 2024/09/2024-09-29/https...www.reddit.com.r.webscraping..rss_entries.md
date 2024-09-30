# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## I can't inspect a web page and open developer tools
 - [https://www.reddit.com/r/webscraping/comments/1fsdopa/i_cant_inspect_a_web_page_and_open_developer_tools](https://www.reddit.com/r/webscraping/comments/1fsdopa/i_cant_inspect_a_web_page_and_open_developer_tools)
 - RSS feed: $source
 - date published: 2024-09-29T20:18:05+00:00

<!-- SC_OFF --><div class="md"><p>It has never happened to me that I can&#39;t inspect a site. Are there any workarounds to inspect it anyway?</p> <p>The site is <a href="https://funkoeurope.com/">this one</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dekoalade"> /u/dekoalade </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fsdopa/i_cant_inspect_a_web_page_and_open_developer_tools/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fsdopa/i_cant_inspect_a_web_page_and_open_developer_tools/">[comments]</a></span>

## Could someone please help with Xpath code?
 - [https://www.reddit.com/r/webscraping/comments/1fsagw9/could_someone_please_help_with_xpath_code](https://www.reddit.com/r/webscraping/comments/1fsagw9/could_someone_please_help_with_xpath_code)
 - RSS feed: $source
 - date published: 2024-09-29T18:00:04+00:00

<!-- SC_OFF --><div class="md"><p>Guys hi</p> <p>I am trying to scape this page (FIRST NORTH GROWTH MARKET LISTINGS 2024)</p> <p><a href="https://www.nasdaqomxnordic.com/news/listings/firstnorth/2024">https://www.nasdaqomxnordic.com/news/listings/firstnorth/2024</a></p> <p>Xpath code i came up with</p> <p>$x(&quot;//html/body/section/div/div/div/section/div/article/div/p[position()&lt;3]/descendant-or-self::*/text()&quot;)</p> <p>But cause html of items is not consistent (sometimes company name is bold,</p> <p>&lt;p&gt;&lt;b&gt;Helsinki, September 17&lt;/b&gt;&lt;/p&gt;</p> <p>&lt;p&gt;Nasdaq welcomes &lt;b&gt;Canatu&lt;/b&gt;&lt;/p&gt;</p> <p>sometimes not)</p> <p>&lt;p&gt;&lt;b&gt;Helsinki, September 9&lt;/b&gt;&lt;/p&gt;</p> <p>&lt;p&gt;Nasdaq welcomes Solar Foods&lt;/p&gt;</p> <p>scraped item sometimes takes 3 lines, sometiems 2 lines</p> <p>0: #text &quot;Helsinki, September 17&quot;​</p> <p>1: #text &quot;Nasdaq welcomes &quot;​</p> <p>2: #text &quot;Canatu&quot;​</p> <p>-,</p> 

## Need guidance, Learning Request
 - [https://www.reddit.com/r/webscraping/comments/1fs8wpy/need_guidance_learning_request](https://www.reddit.com/r/webscraping/comments/1fs8wpy/need_guidance_learning_request)
 - RSS feed: $source
 - date published: 2024-09-29T16:52:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have always used Playwright or Selenium for scraping, but it&#39;s really slow, and I would like to learn how to work directly with the site&#39;s API to fetch the data. Do you have any YouTube video recommendations or step-by-step guidance on what to do?</p> <p>this is the website I would like to extract: <a href="https://www.sr1rv.com/rv-search">https://www.sr1rv.com/rv-search</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Complex-Branch-3003"> /u/Complex-Branch-3003 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1fs8wpy/need_guidance_learning_request/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1fs8wpy/need_guidance_learning_request/">[comments]</a></span>

## Can't send API post request with scrapy
 - [https://www.reddit.com/r/webscraping/comments/1fs7qwl/cant_send_api_post_request_with_scrapy](https://www.reddit.com/r/webscraping/comments/1fs7qwl/cant_send_api_post_request_with_scrapy)
 - RSS feed: $source
 - date published: 2024-09-29T16:02:24+00:00

<!-- SC_OFF --><div class="md"><pre><code>import scrapy class Tg(scrapy.Spider): name = &#39;tg&#39; url = &#39;https://api.telegram.org/botXXXXX/sendMessage&#39; handle_httpstatus_list = [400] def start_requests(self): body = &quot;{&#39;chat_id&#39;: &#39;X&#39;, &#39;text&#39;: &#39;message&#39;}&quot; yield scrapy.FormRequest(url=self.url, method=&#39;POST&#39;, body=body, callback=self.parse) def parse(self, response): if response.status == 200: print(&#39;Message sent successfully!&#39;) else: print(&#39;Failed to send message:&#39;, response.text) </code></pre> <p>This doesn&#39;t work. It returns that message text is empty.</p> <p>But when I use requests everything is fine. I&#39;ve tried formatting the body in all possible ways but none worked. Could you tell me where the problem might be?</p> <p>(I know I overcomplicate things using scrapy, I just want to figure out why it doesn&#39;t work).</p> <p>Traceback:</p> <pre><code>2024-09-29 17:51:15 [scrapy.core.engine] DEBUG: Cra

## Scraping only new data from html api return
 - [https://www.reddit.com/r/webscraping/comments/1fs0i1l/scraping_only_new_data_from_html_api_return](https://www.reddit.com/r/webscraping/comments/1fs0i1l/scraping_only_new_data_from_html_api_return)
 - RSS feed: $source
 - date published: 2024-09-29T09:25:29+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to create a web app that scrapes only the newest real estate listings in my country from multiple websites.</p> <p>The idea is to create an initial database from the lasts month listings and then automatically scrape (periodically) only the latest ones.</p> <p>The main issue is that one of the most popular websites for real estate listings( <a href="https://www.merrjep.al/">https://www.merrjep.al/</a> ) ,where I am also mostly interested in scraping data, offers payed listing refreshing periodically, and jumps a lot of old listings at the beginning.<br/> So even if you sort them by new,the refreshed listings will show first for quite some pages,as you will have agencies refreshing old posts in bulk so you will have to go 30-40 or even more pages back to actually get some new listings.<br/> The tricky part is that when the listings are listed they have a new date or the refreshed date thus making them appear as new but only when you open th

## Getting "Just a moment" when scapping forvo.com.
 - [https://www.reddit.com/r/webscraping/comments/1frym7d/getting_just_a_moment_when_scapping_forvocom](https://www.reddit.com/r/webscraping/comments/1frym7d/getting_just_a_moment_when_scapping_forvocom)
 - RSS feed: $source
 - date published: 2024-09-29T07:03:52+00:00

<!-- SC_OFF --><div class="md"><pre><code>import requests session = requests.Session() url = &quot;https://forvo.com/search/connect/#en_usa&quot; headers = { &#39;Cookie&#39;: &#39;PHPSESSID=64klf82sdpat03b84d305csir4; __cf_bm=7A_VP2Vbe0RWgWRoXIoSyMgiq8_05dyiSGNzIytDExs-1727592824-1.0.1.1-bU2kGo4tlWwGEtC7AGybYxw5dIqzh1YPZQoJYye14QLtWsl6u3sLH644Ro7Ilq_.gJ15imkTDKZNYnQRWF91TA&#39;, &#39;User-Agent&#39;: &#39;Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.110 Safari/537.3&#39; } response = session.get(url, headers=headers) print(response.status_code) print(response.text) </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ImmediateDentist7171"> /u/ImmediateDentist7171 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1frym7d/getting_just_a_moment_when_scapping_forvocom/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1frym7d/getting_j

