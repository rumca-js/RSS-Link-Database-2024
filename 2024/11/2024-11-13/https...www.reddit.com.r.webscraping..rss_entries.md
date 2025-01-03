# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Help using rvest and RSelenium on a dynamic table
 - [https://www.reddit.com/r/webscraping/comments/1gqp39k/help_using_rvest_and_rselenium_on_a_dynamic_table](https://www.reddit.com/r/webscraping/comments/1gqp39k/help_using_rvest_and_rselenium_on_a_dynamic_table)
 - RSS feed: $source
 - date published: 2024-11-13T22:10:25+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to scrape foreign drug inspection dates from Health Canada at this (public-facing) <a href="https://www.drug-inspections.canada.ca/gmp/searchResult-en.html?estName=&amp;ref=&amp;site=&amp;eType=0&amp;prov=&amp;rate=&amp;lic=&amp;licNum=&amp;act=&amp;actCat=&amp;term=&amp;startDate=&amp;endDate=&amp;lang=en&amp;cat=3">URL</a>. The table loads 10 observations at a time and has a total of 14000 or so entries. </p> <p>I&#39;ve figured out how to start a browser instance using RSelenium and page through each page of 10 observations. I&#39;m using a delay of a few seconds between website pings to give a chance for the data to load. I&#39;ve run the code but the resulting dataframe contains duplicate date values. For example, all other five columns will be correct, but the dates for all 14k observations will be repeats of the first ten observations or so. </p> <p>Code below. Any help appreciated: </p> <p>library(tidyverse)</p> <p>library(rvest)<

## Automated Scraping Infrastructure
 - [https://www.reddit.com/r/webscraping/comments/1gqnrwu/automated_scraping_infrastructure](https://www.reddit.com/r/webscraping/comments/1gqnrwu/automated_scraping_infrastructure)
 - RSS feed: $source
 - date published: 2024-11-13T21:14:51+00:00

<!-- SC_OFF --><div class="md"><p>TLDR: What cloud providers/Infrastructure do you use to run headful chrome consistently?</p> <p>Salutations.</p> <p>I currently have a scraping script that iterates through a few thousand urls, navigates to the site using nodriver, then executes some js to extract webpage data.</p> <p>On my local, it runs totally fine, but I&#39;ve had a brutal time trying to automate it on an EC2. I don&#39;t like running headless because that seems to get me detected more frequently. I downloaded Chrome, setup a virtual display with Xvfb, downloaded all the chrome dependencies, but I can never get nodriver to launch/connect to chrome.</p> <p>I was curious what stacks people use to automate their scraping jobs, as well as any resources people might have related to setting up headful automation in a VM environment.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/scoutingthehorizons"> /u/scoutingthehorizons </a> <br/> <span><a hr

## Cloudflare Reverse Engineering (help)
 - [https://www.reddit.com/r/webscraping/comments/1gqmfq4/cloudflare_reverse_engineering_help](https://www.reddit.com/r/webscraping/comments/1gqmfq4/cloudflare_reverse_engineering_help)
 - RSS feed: $source
 - date published: 2024-11-13T20:18:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1gqmfq4/cloudflare_reverse_engineering_help/"> <img src="https://b.thumbs.redditmedia.com/9Ehxp3jXCA2U1lz7m8vKG_xJHfvYpnEvI8WPFw-S6QQ.jpg" alt="Cloudflare Reverse Engineering (help)" title="Cloudflare Reverse Engineering (help)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;m doing a <strong><em>Cloudflare Turnstile Bypass</em></strong> (based on HTTP requests), I&#39;ve been analyzing the Cloudflare code and reversing it for about 15~20 days, I&#39;m 80~90% done with the project.</p> <p>The problem is sending the request to solve turnstile, basically it gives me <code>status_code: 400</code> when I try to bypass it, but if I send it from Devtools, it works</p> <p>I even used the <code>XMLHttpRequest</code> library which is the one Cloudflare uses to send requests, and it still gives 400 code</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dapper-Profession552"> 

## Does using a good VPN make your Scrapping intractable?
 - [https://www.reddit.com/r/webscraping/comments/1gqk8m1/does_using_a_good_vpn_make_your_scrapping](https://www.reddit.com/r/webscraping/comments/1gqk8m1/does_using_a_good_vpn_make_your_scrapping)
 - RSS feed: $source
 - date published: 2024-11-13T18:47:14+00:00

<!-- SC_OFF --><div class="md"><p>Will using a vpn really hide my IP ... &amp; my scrapping activity wont be traced back to me?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PhaseOk_1"> /u/PhaseOk_1 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gqk8m1/does_using_a_good_vpn_make_your_scrapping/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gqk8m1/does_using_a_good_vpn_make_your_scrapping/">[comments]</a></span>

## Dynamic Build IDs in URLs While Scraping Data from Next.js Websites
 - [https://www.reddit.com/r/webscraping/comments/1gqjo9t/dynamic_build_ids_in_urls_while_scraping_data](https://www.reddit.com/r/webscraping/comments/1gqjo9t/dynamic_build_ids_in_urls_while_scraping_data)
 - RSS feed: $source
 - date published: 2024-11-13T18:23:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to scrape product information from Whole Foods&#39; website, which is built with Next.js. Each product page has a JSON endpoint structured like this:</p> <p><a href="https://www.wholefoodsmarket.com/_next/data/%7Bbuild-id%7D/product/%7Bproduct-name%7D-%7Bproduct-id%7D.json?product-detail=%7Bproduct-name%7D-%7Bproduct-id%7D"><code>https://www.wholefoodsmarket.com/_next/data/{build-id}/product/{product-name}-{product-id}.json?product-detail={product-name}-{product-id}</code></a></p> <p>The problem is that {build-id} is a dynamic value that changes periodically. Whenever it changes, my scraper would break. So I built a quick workaround to dynamically fetch the build ID:</p> <pre><code>buildId = re.findall(r&#39;&quot;buildId&quot;:&quot;([^&quot;]+)&quot;&#39;, response.text)[0] </code></pre> <p>My questions are:</p> <ol> <li>Is there a more stable API endpoint that doesn’t use the build ID? I&#39;ve checked the Network tab in Chrome’s De

## Scrapling - Undetectable, Lightning-Fast, and Adaptive Web Scraping
 - [https://www.reddit.com/r/webscraping/comments/1gqiuk8/scrapling_undetectable_lightningfast_and_adaptive](https://www.reddit.com/r/webscraping/comments/1gqiuk8/scrapling_undetectable_lightningfast_and_adaptive)
 - RSS feed: $source
 - date published: 2024-11-13T17:50:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1gqiuk8/scrapling_undetectable_lightningfast_and_adaptive/"> <img src="https://external-preview.redd.it/fsrttsl7asqWYh-wJKwmxCMs6B4lHcDT7rXtPOvKRaI.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=06c6ace3f90f0c62a62e323c2459dec0ddb22f8d" alt="Scrapling - Undetectable, Lightning-Fast, and Adaptive Web Scraping" title="Scrapling - Undetectable, Lightning-Fast, and Adaptive Web Scraping" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello everyone, I have released version 0.2 of Scrapling with a lot of changes and am awaiting your feedback!</p> <p><a href="https://preview.redd.it/v4ahcniiip0e1.png?width=3227&amp;format=png&amp;auto=webp&amp;s=af555dd3492823c1da5184cf6a5758c36af2289c">https://preview.redd.it/v4ahcniiip0e1.png?width=3227&amp;format=png&amp;auto=webp&amp;s=af555dd3492823c1da5184cf6a5758c36af2289c</a></p> <p>New features include stuff like:</p> <ul> <li>Introducing the <code>Fetchers</code> featu

## GMB/Google Maps URL scraper?
 - [https://www.reddit.com/r/webscraping/comments/1gqh2op/gmbgoogle_maps_url_scraper](https://www.reddit.com/r/webscraping/comments/1gqh2op/gmbgoogle_maps_url_scraper)
 - RSS feed: $source
 - date published: 2024-11-13T16:37:15+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a scraper that I can feeds lists of Google Maps/GMB URLs (not a maps SERP) to pull data like review counts, averages, claim status, addresses etc. I already use phantombuster for the initial pull but am looking for a more convenient way to update the data rather than having to conduct new SERP scrapes and match the fields. My hunt for a solution has primarily returned scrapers just like phantombuster that pull SERP results rather than GMB URLs themselves. </p> <p>I’m tech savvy enough but not a coder by any means whatsoever so the more user friendly the better :) </p> <p>Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sm0llie"> /u/sm0llie </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gqh2op/gmbgoogle_maps_url_scraper/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gqh2op/gmbgoogle_maps_url_scraper/">[comments]</a></span>

## Cloudflare bypass
 - [https://www.reddit.com/r/webscraping/comments/1gqarxy/cloudflare_bypass](https://www.reddit.com/r/webscraping/comments/1gqarxy/cloudflare_bypass)
 - RSS feed: $source
 - date published: 2024-11-13T11:27:53+00:00

<!-- SC_OFF --><div class="md"><p>Im at my wits end man been up over 2 days. Ive been trying to find a reliable cloudflare bypass for turnstile. </p> <p>I have used Seleniumbase Drissionpage Curl.</p> <p>This is my current method that works on my main pc i bypass cloudflare get the header and cookies then do a http fetch it after constantly until the cookie wears off then at 401 failed refresh the cookies. </p> <p>I have tried so freaking hard so many hours to get this system working and i keep having issues. I got it mostly working on my main pc. Then when i switched to my vps with the exact same code it goes in endless cookie fetching. Please any help i have a huge app im shipping that requires this.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Djkid4lyfe"> /u/Djkid4lyfe </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gqarxy/cloudflare_bypass/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscrap

## Can anyone suggest me some free vpns or proxy ir any other methods
 - [https://www.reddit.com/r/webscraping/comments/1gq2olf/can_anyone_suggest_me_some_free_vpns_or_proxy_ir](https://www.reddit.com/r/webscraping/comments/1gq2olf/can_anyone_suggest_me_some_free_vpns_or_proxy_ir)
 - RSS feed: $source
 - date published: 2024-11-13T02:35:58+00:00

<!-- SC_OFF --><div class="md"><p>I am scraping medical details from 1mg.com and while scaling up and getting all the data i dont want my ip to get banned. The website doesn&#39;t have bot verification. Suggest how to do it with free resources.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/killerdrax2000"> /u/killerdrax2000 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gq2olf/can_anyone_suggest_me_some_free_vpns_or_proxy_ir/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gq2olf/can_anyone_suggest_me_some_free_vpns_or_proxy_ir/">[comments]</a></span>

