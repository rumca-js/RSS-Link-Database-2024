# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## I'm scraping 3000+ social media profiles and it's taking 1hr to run.
 - [https://www.reddit.com/r/webscraping/comments/1g1l5fk/im_scraping_3000_social_media_profiles_and_its](https://www.reddit.com/r/webscraping/comments/1g1l5fk/im_scraping_3000_social_media_profiles_and_its)
 - RSS feed: $source
 - date published: 2024-10-11T21:54:07+00:00

<!-- SC_OFF --><div class="md"><p>Is this normal?</p> <p>Currently, I am using requests + multiprocessing library. One part of my scraper requires me to make a quick headless playwright call that takes a few seconds because there&#39;s a certain token I need to grab which I couldn&#39;t manage to do with requests.</p> <p>Also weirdly, doing this for 3000 accounts is taking 1 hour but if I run it for 12000 accounts, I would expect it to be 4x slower (so 4h runtime) but the runtime actually goes above 12 hours. So it get&#39;s exponentially slower.</p> <p>What would be the solution for this? Currently I&#39;ve been looking at using external servers. I tried celery but it had too many issues on windows. I&#39;m now wrapping my head around using Dask for this.</p> <p>Any help appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Salt-Page1396"> /u/Salt-Page1396 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g1l5fk/im_

## rvest 403 error, set_cookies() or user_agent() or add_headers()?
 - [https://www.reddit.com/r/webscraping/comments/1g192qa/rvest_403_error_set_cookies_or_user_agent_or_add](https://www.reddit.com/r/webscraping/comments/1g192qa/rvest_403_error_set_cookies_or_user_agent_or_add)
 - RSS feed: $source
 - date published: 2024-10-11T12:53:34+00:00

<!-- SC_OFF --><div class="md"><p>I have used rvest and httr before to bypass a 403 by inspecting the page in Chrome and collecting those values.</p> <p>The issue is that I forgot how I actually did it, deleted that code chunk, and am having trouble replicating that solution.</p> <p>I am fairly sure that I inspected the page in Chrome, found the cookies, and passed them through either set_cookies() or user_agent() or add_headers().</p> <p>Does anyone have a good resource to help remind me how to troubleshoot this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pivottables"> /u/pivottables </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g192qa/rvest_403_error_set_cookies_or_user_agent_or_add/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g192qa/rvest_403_error_set_cookies_or_user_agent_or_add/">[comments]</a></span>

## How to bypass GoDaddy bot detection
 - [https://www.reddit.com/r/webscraping/comments/1g12y14/how_to_bypass_godaddy_bot_detection](https://www.reddit.com/r/webscraping/comments/1g12y14/how_to_bypass_godaddy_bot_detection)
 - RSS feed: $source
 - date published: 2024-10-11T05:49:35+00:00

<!-- SC_OFF --><div class="md"><p>GoDaddy seems to be detecting my bot only when the browser goes out of focus. I had 2 versions of this script: one version where I have to press enter for each character (shown in the video linked in this post), and one version where it puts a random delay between inputting each character. In the version shown in the video (where I have to press a key for each character), it detects the bot each time the browser window goes out of focus. In the version where the bot autonomously enters all the characters, GoDaddy detects the bot even when the browser window <em>is</em> in focus. Any tips on how to get around this?</p> <p><a href="https://youtu.be/8yPF66LVlgk">https://youtu.be/8yPF66LVlgk</a></p> <pre><code>from seleniumbase import Driver import random driver = Driver(uc=True) godaddyLogin = &quot;https://sso.godaddy.com/?realm=idp&amp;app=cart&amp;path=%2Fcheckoutapi%2Fv1%2Fredirects%2Flogin&quot; pixelScan = &quot;https://pixelscan.net&quot; username

## Help with JavaScript heavy site
 - [https://www.reddit.com/r/webscraping/comments/1g0x86y/help_with_javascript_heavy_site](https://www.reddit.com/r/webscraping/comments/1g0x86y/help_with_javascript_heavy_site)
 - RSS feed: $source
 - date published: 2024-10-11T00:18:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys I’m fairly new to Pycharm and setting up spiders. ChatGPT has been my tutor so far and am getting stuck on the below website. Ultimately I’d like to grab the product title as text, the image url, price - currently 3 selectors I think whole number decimal point and the price cents, product page url. </p> <p>I tried using splash but that didn’t work out. The next attempts are trying scrapy playwright. It’s hitting the site but having trouble with the right selectors among some other issues. </p> <p>Could someone please do a test and see if you can get any information or is this using anti scraping measures?</p> <p>I have another competitor site that works fine but it’s easier to setup, starts at the brand page and goes into each sub category then scrapes product listings. </p> <p><a href="https://sydneytools.com.au/category/by-brand/milwaukee/milwaukee-m18-combo-kits">https://sydneytools.com.au/category/by-brand/milwaukee/milwaukee-m18-combo-kit

