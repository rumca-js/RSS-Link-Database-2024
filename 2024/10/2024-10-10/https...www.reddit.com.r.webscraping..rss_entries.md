# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Aliexpress product page API
 - [https://www.reddit.com/r/webscraping/comments/1g0t74r/aliexpress_product_page_api](https://www.reddit.com/r/webscraping/comments/1g0t74r/aliexpress_product_page_api)
 - RSS feed: $source
 - date published: 2024-10-10T21:04:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>i&#39;m trying to rebuild the API request from Aliexpress product page.</p> <p>can you tell me which parameters should be used to get the hash in the &#39;sign&#39; parameters please. i have tried every single combination of the following parameters without getting the same hash in &#39;sign&#39; </p> <pre><code>jsv=2.5.1 appKey=12574478 t=1728578918782 type=originaljsonp v=1.0 timeout=15000 dataType=originaljsonp callback=mtopjsonp1 sign=db1579946ca4c3b1410ad36386cc48b0 </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/smart_linux"> /u/smart_linux </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g0t74r/aliexpress_product_page_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g0t74r/aliexpress_product_page_api/">[comments]</a></span>

## How do websites know a request didn't originate from a browser?
 - [https://www.reddit.com/r/webscraping/comments/1g0sw75/how_do_websites_know_a_request_didnt_originate](https://www.reddit.com/r/webscraping/comments/1g0sw75/how_do_websites_know_a_request_didnt_originate)
 - RSS feed: $source
 - date published: 2024-10-10T20:51:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m poking around a certain website and noticed a weird thing of a post request working fine in browser but hanging and ultimately timing out if made from any other source (python scripts, thunder client, postman, etc.)</p> <p>The headers in requests are 1:1 copy and I&#39;m sending them from the same IP. I tried making several of those request from the browser by refreshing a bunch of times and there doesn&#39;t seem to be any rate limiting. It&#39;s just that it somehow knows I&#39;m not requesting from browser.</p> <p>What are some ways it can be checked? Something to do with insanely attentive TLS fingerprinting?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NightestOfTheOwls"> /u/NightestOfTheOwls </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g0sw75/how_do_websites_know_a_request_didnt_originate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/com

## Help Access Internal API UPS
 - [https://www.reddit.com/r/webscraping/comments/1g0re3s/help_access_internal_api_ups](https://www.reddit.com/r/webscraping/comments/1g0re3s/help_access_internal_api_ups)
 - RSS feed: $source
 - date published: 2024-10-10T19:46:14+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to craft some selenium code that will log into UPS navigate to the billing portal check the network requests looking for a specific endpoint `<a href="https://billing.ups.com/api/v1/bc/invoice/literals?language=EN%5C%60">https://billing.ups.com/api/v1/bc/invoice/literals?language=EN\`</a><br/> Then copy its request headers for a new request and its response header&#39;s csfr token as the csfr token in the new request to this endpoint `<a href="https://billing.ups.com/api/v1/bc/invoice/search%5C%60">https://billing.ups.com/api/v1/bc/invoice/search\`</a>. This is all so I can programmatically get back my billed rates on packages lol, since I can&#39;t seem to find a public api that does this.</p> <p>Copying the cURL for the <a href="https://billing.ups.com/api/v1/bc/invoice/literals?language=EN">https://billing.ups.com/api/v1/bc/invoice/literals?language=EN</a> request and replacing the csfr token with its repsonse csfr and calling the /i

## Pyppeteer Code Issue
 - [https://www.reddit.com/r/webscraping/comments/1g0qqx6/pyppeteer_code_issue](https://www.reddit.com/r/webscraping/comments/1g0qqx6/pyppeteer_code_issue)
 - RSS feed: $source
 - date published: 2024-10-10T19:17:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1g0qqx6/pyppeteer_code_issue/"> <img src="https://b.thumbs.redditmedia.com/JNUSkCABhgwHXCqgfn8PMPKXVRS1AXNLzjGnG6XdIDU.jpg" alt="Pyppeteer Code Issue" title="Pyppeteer Code Issue" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey everyone....</p> <p>I&#39;m trying pyppeteer for the first time. I usually use selenium. There is some issue with my code. It does not open browser when headless is False and gives this error</p> <p><a href="https://preview.redd.it/k5q7t112bztd1.png?width=1028&amp;format=png&amp;auto=webp&amp;s=aa90f4018668641f38840c24a03e534f2e64ac3a">https://preview.redd.it/k5q7t112bztd1.png?width=1028&amp;format=png&amp;auto=webp&amp;s=aa90f4018668641f38840c24a03e534f2e64ac3a</a></p> <p><strong>Code:</strong></p> <p><code>import asyncio</code></p> <p><code>from pyppeteer import launch</code></p> <p><code>async def main():</code></p> <p><code>browser = await launch({&quot;headless&quot;: False})</

## How to scrape emails | How to find specific emails
 - [https://www.reddit.com/r/webscraping/comments/1g0ilrg/how_to_scrape_emails_how_to_find_specific_emails](https://www.reddit.com/r/webscraping/comments/1g0ilrg/how_to_scrape_emails_how_to_find_specific_emails)
 - RSS feed: $source
 - date published: 2024-10-10T13:17:50+00:00

<!-- SC_OFF --><div class="md"><p>Learn how to find email addresses, verify them, and send personalized campaigns to boost your outreach efforts. Whether you&#39;re a marketer, entrepreneur, or business owner, <a href="http://Hunter.io">Hunter.io</a> can help you connect with your audience like never before.</p> <p><a href="https://www.youtube.com/watch?v=UFVPhY0r_Jw">https://www.youtube.com/watch?v=UFVPhY0r_Jw</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Terrible-Macaroon-95"> /u/Terrible-Macaroon-95 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g0ilrg/how_to_scrape_emails_how_to_find_specific_emails/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g0ilrg/how_to_scrape_emails_how_to_find_specific_emails/">[comments]</a></span>

## 500px Full Resolution - How is this done?
 - [https://www.reddit.com/r/webscraping/comments/1g0aeyh/500px_full_resolution_how_is_this_done](https://www.reddit.com/r/webscraping/comments/1g0aeyh/500px_full_resolution_how_is_this_done)
 - RSS feed: $source
 - date published: 2024-10-10T04:01:03+00:00

<!-- SC_OFF --><div class="md"><p>Per this post: <a href="https://old.reddit.com/r/DataHoarder/comments/1fznkim/how_is_this_one_particular_website_able_to_get/">https://old.reddit.com/r/DataHoarder/comments/1fznkim/how_is_this_one_particular_website_able_to_get/</a></p> <p>Does anyone know how <a href="https://www.savelink.info/">https://www.savelink.info/</a> is finding the full resolution link for photos on 500px? </p> <p>Example: <a href="https://500px.com/photo/47014798">https://500px.com/photo/47014798</a> I dug around in the source/inspect network, etc, but could only get the easily accessible [2048 x 1514].</p> <p><a href="https://www.savelink.info/">https://www.savelink.info/</a> gives the full resolution [6726 x 4972] - How?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/plunki"> /u/plunki </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g0aeyh/500px_full_resolution_how_is_this_done/">[link]</a></span> &#32; <spa

