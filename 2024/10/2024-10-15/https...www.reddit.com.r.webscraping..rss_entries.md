# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Using Firecrawl?
 - [https://www.reddit.com/r/webscraping/comments/1g4ifgy/using_firecrawl](https://www.reddit.com/r/webscraping/comments/1g4ifgy/using_firecrawl)
 - RSS feed: $source
 - date published: 2024-10-15T21:05:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I have never coded in my life but I have a start up idea that&#39;s gotten some traction based on figma screens and customer discovery. I have a pilot and now I&#39;m in the process of trying to figure out my next steps. First and foremost I need to download about at least 500-1000 publicly available PDFs from different sites, plus the information about the site to use for a RAG model. Is firecrawl the place I can do this? if so, anyone willing to help walk me through some things?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/plumbusdischarge"> /u/plumbusdischarge </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g4ifgy/using_firecrawl/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g4ifgy/using_firecrawl/">[comments]</a></span>

## Scraping the used Web Analytics Tools
 - [https://www.reddit.com/r/webscraping/comments/1g4h89m/scraping_the_used_web_analytics_tools](https://www.reddit.com/r/webscraping/comments/1g4h89m/scraping_the_used_web_analytics_tools)
 - RSS feed: $source
 - date published: 2024-10-15T20:15:05+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone</p> <p>I&#39;m trying to scrape the biggest websites in Switzerland to see which web analytics tool is in use. </p> <p>For now, I have only built the code for Google Analytics. </p> <p>Unfortunately it only works partially. On various websites it shows that no GA is implemented, although it is available. I suspect that the problem is related to asynchronous loading. </p> <p>I would like to build the script without Selenium. Is it possible? </p> <p>Here is my current script: </p> <p><code>import requests</code></p> <p><code>from bs4 import BeautifulSoup</code></p> <p><code>from urllib.parse import urlparse</code></p> <p><code>def check_google_analytics(url):</code></p> <p><code>headers = {</code></p> <p><code>&#39;User-Agent&#39;: &#39;Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)&#39;</code></p> <p><code>}</code></p> <p><code>try:</code></p> <p><code>response = requests.get(url, headers=headers, timeout=10)</c

## Currently trying to scrape a large pdf but need good chunking strats
 - [https://www.reddit.com/r/webscraping/comments/1g4cnct/currently_trying_to_scrape_a_large_pdf_but_need](https://www.reddit.com/r/webscraping/comments/1g4cnct/currently_trying_to_scrape_a_large_pdf_but_need)
 - RSS feed: $source
 - date published: 2024-10-15T17:01:53+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to scrape a pdf using pymupdf but there is a lot of text contained in one file alone and I want to store information from pages in chunks - anybody have suggestions or alt ways i can do it</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EnvironmentBasic6030"> /u/EnvironmentBasic6030 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g4cnct/currently_trying_to_scrape_a_large_pdf_but_need/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g4cnct/currently_trying_to_scrape_a_large_pdf_but_need/">[comments]</a></span>

## Ethics issue
 - [https://www.reddit.com/r/webscraping/comments/1g4bv2s/ethics_issue](https://www.reddit.com/r/webscraping/comments/1g4bv2s/ethics_issue)
 - RSS feed: $source
 - date published: 2024-10-15T16:29:17+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I’m doing an NLP project in uni and I wanted to web scrape news articles so that I can extract the data and draw conclusions from it after doing some extra NLP stuff. Anyway, my advisor told me something along the lines of ‘since you’re scraping news articles it could be a potential ethics issue because some news publishers may not have given permission to scrape/copyright issues even if they’re publicly available’ so is there anything I can do? We’re in the UK btw. I’ve already begun my project over the summer so it’s a bummer if I have to do a different one unfortunately so I’ll take any suggestions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mindless-Drone-295"> /u/Mindless-Drone-295 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g4bv2s/ethics_issue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g4bv2s/ethics_issue/">[comment

## Pagination HELP
 - [https://www.reddit.com/r/webscraping/comments/1g49ahm/pagination_help](https://www.reddit.com/r/webscraping/comments/1g49ahm/pagination_help)
 - RSS feed: $source
 - date published: 2024-10-15T14:40:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello.</p> <p>I want to scrape this website (<a href="https://www.nexxon.ro/?page=product&amp;utiliz=PC&amp;fcat=TURISM&amp;ss=0&amp;sw=0&amp;sa=0">HERE</a>). I&#39;m interested in scraping all their products, with name and links. Now, I am using Octoparse to scrape all this data, but I have a pagination problem. This website doesn&#39;t have a parameter in the url for pagination, a &quot;Next Page&quot; or an &quot;Infinite Scroll&quot;. Instead, this website has a basic &quot;1,2,3,4xxxx&quot; page buttons. My problem is that, in Octoparse, whenever the scraper hits the 2nd page, it gets stuck and keeps scraping the same page over and over again.</p> <p>Can someone help and guide me on how to scrape all those products, please?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ResponsibleSpray8836"> /u/ResponsibleSpray8836 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g49ahm/pagination_h

## I scraped 50,000 jobs (grouped by level) into an excel spreadsheet
 - [https://www.reddit.com/r/webscraping/comments/1g41clm/i_scraped_50000_jobs_grouped_by_level_into_an](https://www.reddit.com/r/webscraping/comments/1g41clm/i_scraped_50000_jobs_grouped_by_level_into_an)
 - RSS feed: $source
 - date published: 2024-10-15T06:22:38+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1g41clm/i_scraped_50000_jobs_grouped_by_level_into_an/"> <img src="https://external-preview.redd.it/C1cZoSGK6At_Sz0suigVwI0KFUoTrCdxB6I_AoVOejg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f03ee2d572268d789bf0d9e033895866f41da87c" alt="I scraped 50,000 jobs (grouped by level) into an excel spreadsheet" title="I scraped 50,000 jobs (grouped by level) into an excel spreadsheet" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/marvythemantis"> /u/marvythemantis </a> <br/> <span><a href="https://docs.google.com/spreadsheets/d/1SoWhe2hAqw_9KpX7KXexH3Hi9Eo2FlWAVvLEPSNrk5M/edit?usp=sharing">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g41clm/i_scraped_50000_jobs_grouped_by_level_into_an/">[comments]</a></span> </td></tr></table>

## I made a Cloudflare-Bypass
 - [https://www.reddit.com/r/webscraping/comments/1g40qy2/i_made_a_cloudflarebypass](https://www.reddit.com/r/webscraping/comments/1g40qy2/i_made_a_cloudflarebypass)
 - RSS feed: $source
 - date published: 2024-10-15T05:39:41+00:00

<!-- SC_OFF --><div class="md"><p>This cloudflare bypass consists of accessing the site and obtaining the cf_clearance cookie</p> <p>And it works with any website. If anyone tries this and gets an error, let me know.</p> <p><a href="https://github.com/LOBYXLYX/Cloudflare-Bypass">https://github.com/LOBYXLYX/Cloudflare-Bypass</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dapper-Profession552"> /u/Dapper-Profession552 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g40qy2/i_made_a_cloudflarebypass/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g40qy2/i_made_a_cloudflarebypass/">[comments]</a></span>

## Any idea on how these bot likes on FB, insta made
 - [https://www.reddit.com/r/webscraping/comments/1g404uj/any_idea_on_how_these_bot_likes_on_fb_insta_made](https://www.reddit.com/r/webscraping/comments/1g404uj/any_idea_on_how_these_bot_likes_on_fb_insta_made)
 - RSS feed: $source
 - date published: 2024-10-15T04:58:46+00:00

<!-- SC_OFF --><div class="md"><p>Im web scraper and also doing web automations, i have bypassed many bot restiction challenges in my career, But i just wonder how these bots make thousands of likes and comments on FB and insta, any idea guys?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LocalConversation850"> /u/LocalConversation850 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g404uj/any_idea_on_how_these_bot_likes_on_fb_insta_made/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g404uj/any_idea_on_how_these_bot_likes_on_fb_insta_made/">[comments]</a></span>

## How to extract website info to combine & create single document
 - [https://www.reddit.com/r/webscraping/comments/1g3y2xz/how_to_extract_website_info_to_combine_create](https://www.reddit.com/r/webscraping/comments/1g3y2xz/how_to_extract_website_info_to_combine_create)
 - RSS feed: $source
 - date published: 2024-10-15T02:59:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1g3y2xz/how_to_extract_website_info_to_combine_create/"> <img src="https://b.thumbs.redditmedia.com/wSOytTVuuB68Mtr5KYvYRDz22B83BUl8g1Bm-pIIh7M.jpg" alt="How to extract website info to combine &amp; create single document" title="How to extract website info to combine &amp; create single document" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I was wondering if anyone could point me in the right direction of how to extract all of the information from these folders and sub-folders so that I can combine all of the information and create a single PDF file so that it is easier to read and search? Thanks in advance for any help, I have very limited knowledge on how to do something like this so all info is much appreciated...here is the link to the webpage if that makes things any easier... <a href="https://charm.li/Buick/2007/Lucerne%20V6-3.8L/">https://charm.li/Buick/2007/Lucerne%20V6-3.8L/</a></p> <p><a href="h

## New to selenium and webscraping
 - [https://www.reddit.com/r/webscraping/comments/1g3xrdr/new_to_selenium_and_webscraping](https://www.reddit.com/r/webscraping/comments/1g3xrdr/new_to_selenium_and_webscraping)
 - RSS feed: $source
 - date published: 2024-10-15T02:42:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m fairly new at this so I apologize if something is &quot;obvious&quot; and I&#39;m missing it. </p> <p>I&#39;m trying to scrape this website and parse through multiple pages. You also have to click on every individual person to be able to grab more items and I keep running into issues. </p> <pre><code>from selenium import webdriver from selenium.webdriver.common.by import By from selenium.webdriver.common.keys import Keys from selenium.webdriver.chrome.service import Service from webdriver_manager.chrome import ChromeDriverManager from selenium.webdriver.support.ui import WebDriverWait from selenium.webdriver.support import expected_conditions as EC import time import csv #Set up WebDriver driver = webdriver.Chrome(service=Service(ChromeDriverManager().install())) #Open the target website driver.get(&#39;https://proadvisor.intuit.com/app/accountant/search?location=CHICAGO,%20IL&amp;region=US&#39;) # Open a CSV file for writing with o

