# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Multiple urls with selenium
 - [https://www.reddit.com/r/webscraping/comments/1gdmtxq/multiple_urls_with_selenium](https://www.reddit.com/r/webscraping/comments/1gdmtxq/multiple_urls_with_selenium)
 - RSS feed: $source
 - date published: 2024-10-27T22:17:53+00:00

<!-- SC_OFF --><div class="md"><p>Hello i have thousands of URLs which should be fetched via selenium.I am running 40 parallel Python script but it is resouce hog. My cpu is always busy. How to make it effecient ? Selenium is my only option(company decision) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/parroschampel"> /u/parroschampel </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gdmtxq/multiple_urls_with_selenium/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gdmtxq/multiple_urls_with_selenium/">[comments]</a></span>

## Problems scraping NASDAQ.com for data
 - [https://www.reddit.com/r/webscraping/comments/1gdivlg/problems_scraping_nasdaqcom_for_data](https://www.reddit.com/r/webscraping/comments/1gdivlg/problems_scraping_nasdaqcom_for_data)
 - RSS feed: $source
 - date published: 2024-10-27T19:19:36+00:00

<!-- SC_OFF --><div class="md"><p>I used to be able to get intraday and pre/post (delayed) market data using the NASDAQ API and this URL: <a href="https://api.nasdaq.com/api/quote/gld/extended-trading?assetclass=etf&amp;markettype=pre">https://api.nasdaq.com/api/quote/gld/extended-trading?assetclass=etf&amp;markettype=pre</a></p> <p>The JSON result could then be imported into Google sheets with the regular IMPORTJSON function/script.</p> <p>Everything was fine up until a few days ago but doesn&#39;t work anymore...</p> <p>If I load the URL with my browser, I get a JSON file that looks OK. If I check the file online, the various validators say the file is properly formatted.</p> <p>But, ImportJSON times out systematically and when I check if the NASDAQ website is down, it does appear down. Although I can download the file with my browser !</p> <p>So I&#39;m pretty puzzled and can&#39;t figure out what the problem is and how to solve it...</p> <p>I tried to be smart and set up a &quot;

## web scrape booking.com to get winter hotels within the US
 - [https://www.reddit.com/r/webscraping/comments/1gdacnh/web_scrape_bookingcom_to_get_winter_hotels_within](https://www.reddit.com/r/webscraping/comments/1gdacnh/web_scrape_bookingcom_to_get_winter_hotels_within)
 - RSS feed: $source
 - date published: 2024-10-27T12:56:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi, Im a complete beginner to web scrapping I have this task I&#39;m trying to do where I web scrape booking .com to determine which states has the cheapest hotels in the US I have tried continously just cant seem to get anything i keep getting errors on python my code is below if anyone could help would be greatly appreciated </p> <pre><code>from selenium import webdriver from selenium.webdriver.chrome.service import Service from bs4 import BeautifulSoup import pandas as pd import time # Setup WebDriver service = Service(r&#39;C:\Users\elsht\Downloads\chromedriver-win64\chromedriver-win64\chromedriver.exe&#39;) options = webdriver.ChromeOptions() options.add_argument(&#39;--headless&#39;) # Run in headless mode options.add_argument(&#39;--no-sandbox&#39;) options.add_argument(&#39;--disable-dev-shm-usage&#39;) driver = webdriver.Chrome(service=service, options=options) def get_hotel_data(url): driver.get(url) time.sleep(5) # Wait for JavaScript to l

## Bypass custom X header checksum generation
 - [https://www.reddit.com/r/webscraping/comments/1gd9vtz/bypass_custom_x_header_checksum_generation](https://www.reddit.com/r/webscraping/comments/1gd9vtz/bypass_custom_x_header_checksum_generation)
 - RSS feed: $source
 - date published: 2024-10-27T12:30:53+00:00

<!-- SC_OFF --><div class="md"><p>I wonder if there is a way to simulate checksum generation without using tools like Selenium? What is the best way to scrape the website with custom headers? </p> <p><a href="https://www.pocketcomics.com/menu/all_comic/new_release?currentItemCode=comic">https://www.pocketcomics.com/menu/all_comic/new_release?currentItemCode=comic</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KayotaDakota"> /u/KayotaDakota </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gd9vtz/bypass_custom_x_header_checksum_generation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gd9vtz/bypass_custom_x_header_checksum_generation/">[comments]</a></span>

## Need help
 - [https://www.reddit.com/r/webscraping/comments/1gd4tlw/need_help](https://www.reddit.com/r/webscraping/comments/1gd4tlw/need_help)
 - RSS feed: $source
 - date published: 2024-10-27T06:30:06+00:00

<!-- SC_OFF --><div class="md"><p>Note: Not a developer , just been using Claude &amp; LLM Qwen2.5 Coder to fumble my way through. </p> <p>Being situated in Australia , I started with a Indeed &amp; Seek Job search to create a CSV which I go through once a week looking for local and remote work, then because I was defence orientated I started looking at the usual websites , Boeing , Lockheed etc and our smaller MSP defence companies ... which I&#39;ve figured out what works well for me and my job search. But for the life of me I cannot figure out the Raytheon site &quot;<a href="https://careers.rtx.com/global/en/raytheon-search-results">https://careers.rtx.com/global/en/raytheon-search-results</a>&quot;. I cant see where I am going wrong,,, but I also used the scrapemaster 4.0 which uses AI , and I managed to get the first page , so I know its possible, but want to learn. my opinion is that Im pretty sure it cant find the table that would be &quot;job_listings&quot; , but any advice 

## Mercari Cloudflare 403 Error
 - [https://www.reddit.com/r/webscraping/comments/1gd3vuy/mercari_cloudflare_403_error](https://www.reddit.com/r/webscraping/comments/1gd3vuy/mercari_cloudflare_403_error)
 - RSS feed: $source
 - date published: 2024-10-27T05:21:47+00:00

<!-- SC_OFF --><div class="md"><p>I am new to webscraping and would like to to scrape Mercari, but when I send a request with python using python I get the dreaded 403 error: &quot;Enable Javascript and cookies to continue&quot;. Are there any opensource packages to bypass this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/YS_OnTheBeat"> /u/YS_OnTheBeat </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gd3vuy/mercari_cloudflare_403_error/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gd3vuy/mercari_cloudflare_403_error/">[comments]</a></span>

## Bypassing DataDome
 - [https://www.reddit.com/r/webscraping/comments/1gczm5p/bypassing_datadome](https://www.reddit.com/r/webscraping/comments/1gczm5p/bypassing_datadome)
 - RSS feed: $source
 - date published: 2024-10-27T01:02:01+00:00

<!-- SC_OFF --><div class="md"><p>Until now, it&#39;s been quite easy to bypass DataDome by manipulating ciphers. It seems now they&#39;ve added a test for explicit JavaScript execution on some pages. The &quot;datadome&quot; cookie only gets set if you execute their JavaScript. With proper requests, this wasn&#39;t necessary before. Is there still a way to bypass DataDome without using a headless browser? </p> <p>PS. Maybe a few of us can make a separate private group to collaborate. This way we aren&#39;t stuck trying to reverse-engineer this ourselves every few months. Simultaneously, we aren&#39;t publicly disclosing our findings to DataDome employees 😂</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/netmillions"> /u/netmillions </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gczm5p/bypassing_datadome/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gczm5p/bypassing_datadome/">[

## Web scraping question.
 - [https://www.reddit.com/r/webscraping/comments/1gcyz9w/web_scraping_question](https://www.reddit.com/r/webscraping/comments/1gcyz9w/web_scraping_question)
 - RSS feed: $source
 - date published: 2024-10-27T00:27:27+00:00

<!-- SC_OFF --><div class="md"><p>I need to scrape this site for some data of the past 3 years. <a href="http://jaxepics.coj.net/Search/AdvancedSearch/">jaxepics.coj.net/Search/AdvancedSearch/</a></p> <p>I found the API that feeds the data but when I try to request it, I get a 500 error. </p> <p>What do I have to do to bypass this issue ? I am still pretty new to this. Any tips would be appreciated. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Concentrate_8732"> /u/Ok_Concentrate_8732 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gcyz9w/web_scraping_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gcyz9w/web_scraping_question/">[comments]</a></span>

