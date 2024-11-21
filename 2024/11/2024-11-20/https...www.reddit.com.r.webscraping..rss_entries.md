# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Trying to grab elements from a site
 - [https://www.reddit.com/r/webscraping/comments/1gw1hck/trying_to_grab_elements_from_a_site](https://www.reddit.com/r/webscraping/comments/1gw1hck/trying_to_grab_elements_from_a_site)
 - RSS feed: $source
 - date published: 2024-11-20T23:13:20+00:00

<!-- SC_OFF --><div class="md"><p>i&#39;m relatively new at webscraping - so excuse my noobness</p> <p>trying to make a little bot that wants to scrape <a href="https://pump.fun/board">https://pump.fun/board</a> - what I see when I inspect in chrome is that the contract address for coins follow a simple pattern - its in a grid, then under the grid you&#39;ll see &lt;div id=contract address&gt; (this will be random but will almost always end with &#39;pump&#39; at the end)</p> <p>I&#39;ve tried extracting all the id= - but beautifulsoup will say that when it looks at the site, there&#39;s no elements where id=true.</p> <p>so then underneath, I noticed a &lt;a href=/coin/contractaddresspump&gt; so I tried getting it from there, modified the regex to handle anything that has /coin/ and pump but according to beautifulsoup there&#39;s only one URL and it&#39;s not what I am looking for.</p> <p>I then tried to use selenium and again, selenium just returns empty data and I am not too sure w

## Client side webscraping?
 - [https://www.reddit.com/r/webscraping/comments/1gw0gdb/client_side_webscraping](https://www.reddit.com/r/webscraping/comments/1gw0gdb/client_side_webscraping)
 - RSS feed: $source
 - date published: 2024-11-20T21:52:57+00:00

<!-- SC_OFF --><div class="md"><p>tl;dr: fetching other website and extracting its data directly from the browser</p> <p>A little backstory, I was working on my youtube player webapp, and I needed 2 main features which was to search and download videos. For this app, I didn&#39;t want to have a backend, because the idea for it to be PWA and offline first. The &quot;API&quot; in question for search was duckduckgo&#39;s and downloading videos is just calling youtube internal API.</p> <p>Major problem though, as you might expect it is not possible for the browser to fetch directly to other website due to same origin policy and the cors error. One way to solve this is to relay the request through your own backend to bypass the cors error, this is known as cors proxy. I did create my own cors proxy for this, but there are plenty of self hosting options. Having my request proxied through the cors proxy, I can directly call those websites in my browser.</p> <p>It made me think whether this 

## Rotating proxy provider with unlimited bandwidth
 - [https://www.reddit.com/r/webscraping/comments/1gvzhef/rotating_proxy_provider_with_unlimited_bandwidth](https://www.reddit.com/r/webscraping/comments/1gvzhef/rotating_proxy_provider_with_unlimited_bandwidth)
 - RSS feed: $source
 - date published: 2024-11-20T20:58:08+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a rotating proxy provider that offers unlimited bandwidth. The reason is that I need to scrape a large number of dynamic routes (like website.com/route/XXXXXX) which would require about 1TB of bandwidth.</p> <p>Key points:</p> <ul> <li>Need rotating proxies</li> <li>Require unlimited bandwidth</li> <li>Reasonable pricing Any tips on reputable providers that meet these criteria? Thanks!</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SimonFreedom"> /u/SimonFreedom </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvzhef/rotating_proxy_provider_with_unlimited_bandwidth/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gvzhef/rotating_proxy_provider_with_unlimited_bandwidth/">[comments]</a></span>

## Recommended proxy server after being blocked?
 - [https://www.reddit.com/r/webscraping/comments/1gvz8mb/recommended_proxy_server_after_being_blocked](https://www.reddit.com/r/webscraping/comments/1gvz8mb/recommended_proxy_server_after_being_blocked)
 - RSS feed: $source
 - date published: 2024-11-20T20:27:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m using fixed IP addresses from a datacenter for my proxy. I was switching between 5 different IPs, but now the entire group of these IPs is blocked. Here are the IPs:</p> <ol> <li>203.0.113.1</li> <li>203.0.113.2</li> <li>203.0.113.3</li> <li>203.0.113.4</li> <li>203.0.113.5</li> </ol> <p>My proxy provider told me that all these IPs are working fine, but some websites I&#39;m trying to access are giving a 406 error so they won&#39;t help me </p> <p>My question is<br/> 1. Can you recommend a proxy provider that provides this service? The ability to change the &quot;network portion&quot; (the first three octets) more easily?<br/> 2. Should I be using another proxy method instead of &quot;data center ip&quot; proxies?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LavishnessArtistic72"> /u/LavishnessArtistic72 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvz8mb/recommended_pr

## API calls
 - [https://www.reddit.com/r/webscraping/comments/1gvyufr/api_calls](https://www.reddit.com/r/webscraping/comments/1gvyufr/api_calls)
 - RSS feed: $source
 - date published: 2024-11-20T20:07:06+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to retrieve Zillow listings using an API call. For example, on this<a href="https://ulstercountyny.gov/maps/parcel-viewer/"> map viewer</a>, when I input something like 1.3-1-10, I get all the API responses. However, I’m missing the Zillow and Google Maps links in the results. If anyone could point me to where I can access these links via the API, it would be greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/albert_in_vine"> /u/albert_in_vine </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvyufr/api_calls/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gvyufr/api_calls/">[comments]</a></span>

## Having issue while clicking a button inside iFrame
 - [https://www.reddit.com/r/webscraping/comments/1gvy4wf/having_issue_while_clicking_a_button_inside_iframe](https://www.reddit.com/r/webscraping/comments/1gvy4wf/having_issue_while_clicking_a_button_inside_iframe)
 - RSS feed: $source
 - date published: 2024-11-20T19:38:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1gvy4wf/having_issue_while_clicking_a_button_inside_iframe/"> <img src="https://b.thumbs.redditmedia.com/3gqZdmpdTk1O-wnG1oSwc4Spv0kTr6TRYVnuuaelMyg.jpg" alt="Having issue while clicking a button inside iFrame" title="Having issue while clicking a button inside iFrame" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><strong>(Two images attached)</strong></p> <p>Please view both of the images, it actually catches the iFrame but not clicking the button inside it,</p> <p>Tried it in many way like XPath and Full path.</p> <p>ChatGPT says this : The <strong>SecurityError</strong> you encountered is due to the <strong>same-origin policy</strong>, which blocks JavaScript from accessing content inside an iframe if the iframe is loaded from a different origin than the parent page. In your case, the iframe is hosted on a different domain (<code>https://accounts.google.com</code>) than the actual page.</p> <p><a href="h

## Client side webscraping?
 - [https://www.reddit.com/r/webscraping/comments/1gvxmdt/client_side_webscraping](https://www.reddit.com/r/webscraping/comments/1gvxmdt/client_side_webscraping)
 - RSS feed: $source
 - date published: 2024-11-20T19:17:18+00:00

<!-- SC_OFF --><div class="md"><p>tl;dr: fetching other website and extracting its data directly from the browser</p> <p>A little backstory, I was working on my <a href="https://github.com/reynaldichernando/backtrack">youtube player webapp</a>, and I needed 2 main features which was to search and download videos. For this app, I didn&#39;t want to have a backend, because the idea for it to be PWA and offline first. The &quot;API&quot; in question for search was duckduckgo&#39;s and downloading videos is just calling youtube internal API.</p> <p>Major problem though, as you might expect it is not possible for the browser to fetch directly to other website due to same origin policy and the cors error. One way to solve this is to relay the request through your own backend to bypass the cors error, this is known as cors proxy. I did create my own <a href="https://corsfix.com">cors proxy</a> for this, but there are plenty of self hosting options. Having my request proxied through the cors

## What is the best product for market research?
 - [https://www.reddit.com/r/webscraping/comments/1gvr0wk/what_is_the_best_product_for_market_research](https://www.reddit.com/r/webscraping/comments/1gvr0wk/what_is_the_best_product_for_market_research)
 - RSS feed: $source
 - date published: 2024-11-20T14:42:40+00:00

<!-- SC_OFF --><div class="md"><p>The goal is to discover the number of certain kind of businesses in a market based on keywords / boolean equations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Eininho"> /u/Eininho </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvr0wk/what_is_the_best_product_for_market_research/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gvr0wk/what_is_the_best_product_for_market_research/">[comments]</a></span>

## Google LLC shows up when doing a DNS leak test
 - [https://www.reddit.com/r/webscraping/comments/1gvnq69/google_llc_shows_up_when_doing_a_dns_leak_test](https://www.reddit.com/r/webscraping/comments/1gvnq69/google_llc_shows_up_when_doing_a_dns_leak_test)
 - RSS feed: $source
 - date published: 2024-11-20T11:52:06+00:00

<!-- SC_OFF --><div class="md"><p>Is this a good or a bad thing?</p> <p>A fraud score is always lower when Google shows up with DNS leak test... but something tells me they have configured something wrong and no proxies routed through Google servers should be used.</p> <p>For example, the operator is Comcast Cable and the dns shows up as Google.</p> <p>We are talking about regular residential IPs (not mobile or ISP) </p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CryptoGoof"> /u/CryptoGoof </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvnq69/google_llc_shows_up_when_doing_a_dns_leak_test/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gvnq69/google_llc_shows_up_when_doing_a_dns_leak_test/">[comments]</a></span>

## Scraping a subreddit
 - [https://www.reddit.com/r/webscraping/comments/1gvl6eg/scraping_a_subreddit](https://www.reddit.com/r/webscraping/comments/1gvl6eg/scraping_a_subreddit)
 - RSS feed: $source
 - date published: 2024-11-20T08:45:30+00:00

<!-- SC_OFF --><div class="md"><p>Is there a way to scrape a sub for links to the YouTube videos on it? If it matters it&#39;s my sub. I was just going to have it be a small thing in the beginning but my ambition outgrew my ability to really be able to organize or handle it, so I want to make genre and artist specific playlists on my youtube channel and then link those here so I have some control over how things are layed out.</p> <p>Anyway I think I probably have between 500 to 750 videos linked in the sub. Any suggestions? If I do it manually at this point i can have grandkids finish it for me after I am long gone. Very painfully slow </p> <p>Do I need to set up special task with an app or api or is there something that exists already that does that? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/creative_name_idea"> /u/creative_name_idea </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvl6eg/scraping_a_subreddit/">[

## Scraping list of products with vba and selenium
 - [https://www.reddit.com/r/webscraping/comments/1gvkc77/scraping_list_of_products_with_vba_and_selenium](https://www.reddit.com/r/webscraping/comments/1gvkc77/scraping_list_of_products_with_vba_and_selenium)
 - RSS feed: $source
 - date published: 2024-11-20T07:41:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m trying to scrape a local web store using vba and selenium library. I want to get the name, the old and new prices of each item but I can&#39;t find a way to get through each element and get that information.</p> <pre><code>Option Explicit Dim ch As Selenium.ChromeDriver Sub ScrapeOffers() Set ch = New Selenium.ChromeDriver ch.Start ch.Get &quot;https://www.website.com./category/offers-november/&quot; Dim Element As Selenium.WebElement Set Element = ch.FindElementByClass(&quot;osf__sc-ukmfim-0&quot;) Debug.Print Element.Attribute(&quot;alt&quot;) Dim H4Headers As Selenium.WebElements Dim n As Long Set H4Headers = ch.FindElementsByTag(&quot;h4&quot;) For n = 1 To H4Headers.Count Debug.Print n &amp; &quot; - &quot; &amp; H4Headers(2).Text Next n End Sub </code></pre> <p>All the h4 elements have the same class: </p> <p>&lt;h4 class=&quot;ikm\_\_bn-3e68sgq-2 swCCom&quot;&gt;LAVABO BLANCO&lt;/h4&gt;</p> <p>&lt;h4 class=&quot;ikm\_\_bn-3e

## Why Xpass pro not working when i try to generate cookies
 - [https://www.reddit.com/r/webscraping/comments/1gvipjl/why_xpass_pro_not_working_when_i_try_to_generate](https://www.reddit.com/r/webscraping/comments/1gvipjl/why_xpass_pro_not_working_when_i_try_to_generate)
 - RSS feed: $source
 - date published: 2024-11-20T05:48:06+00:00

<!-- SC_OFF --><div class="md"><p>I have xpass pro, i try to generate cookies by an API call, before calling the API, need to set the header with API key. Which we can get from another API call with credentials.</p> <p>My issue: API key generation was successfull, but when i call the other API to generate cookies it returns 401.</p> <p>Note : My credits are in minus. But i suspect why it returns 401.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LocalConversation850"> /u/LocalConversation850 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvipjl/why_xpass_pro_not_working_when_i_try_to_generate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gvipjl/why_xpass_pro_not_working_when_i_try_to_generate/">[comments]</a></span>

## What happened to hCaptcha on AI solvers?
 - [https://www.reddit.com/r/webscraping/comments/1gvh8zj/what_happened_to_hcaptcha_on_ai_solvers](https://www.reddit.com/r/webscraping/comments/1gvh8zj/what_happened_to_hcaptcha_on_ai_solvers)
 - RSS feed: $source
 - date published: 2024-11-20T04:22:33+00:00

<!-- SC_OFF --><div class="md"><p>All major solving brands like capsolver &amp; capmonster stopped supporting. They’re never detailed about why they stop. Anybody know the details? I know funcaptcha arkose with a law suit. Is HCaptcha good or just same story?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Inevitable_Fortune66"> /u/Inevitable_Fortune66 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gvh8zj/what_happened_to_hcaptcha_on_ai_solvers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gvh8zj/what_happened_to_hcaptcha_on_ai_solvers/">[comments]</a></span>

## How to scrape an SVG element properly from an website?
 - [https://www.reddit.com/r/webscraping/comments/1gven4m/how_to_scrape_an_svg_element_properly_from_an](https://www.reddit.com/r/webscraping/comments/1gven4m/how_to_scrape_an_svg_element_properly_from_an)
 - RSS feed: $source
 - date published: 2024-11-20T02:06:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1gven4m/how_to_scrape_an_svg_element_properly_from_an/"> <img src="https://b.thumbs.redditmedia.com/xmk4i7i1zvpiVYKA5lFsmGFA8hbKtEhfK4TRh_YAV2k.jpg" alt="How to scrape an SVG element properly from an website?" title="How to scrape an SVG element properly from an website?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;m working on scraping the HEB (a Texas retailer) website, and I need to extract the SVG of their store map. Specifically, I&#39;m targeting the map that appears when you click on the &quot;View Store Map&quot; button on their product pages. Here&#39;s the URL for reference:</p> <p><a href="https://www.heb.com/product-detail/h-e-b-reduced-fat-2-milk-1-gal/314125">https://www.heb.com/product-detail/h-e-b-reduced-fat-2-milk-1-gal/314125</a>.</p> <p>What I&#39;ve Done So Far:</p> <p>I’m using BeautifulSoup with Selenium to scrape the webpage. After clicking the &quot;View

