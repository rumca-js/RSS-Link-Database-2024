# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Can I scrape Ebay and use the data for my website ?
 - [https://www.reddit.com/r/webscraping/comments/1hkahlc/can_i_scrape_ebay_and_use_the_data_for_my_website](https://www.reddit.com/r/webscraping/comments/1hkahlc/can_i_scrape_ebay_and_use_the_data_for_my_website)
 - RSS feed: $source
 - date published: 2024-12-22T23:20:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I started scraping eBay because the only thing I was interested in was sold item data, and I couldn&#39;t find it in their API. I feel like their documentation is a bit all over the place, or maybe it&#39;s because English isn&#39;t my native language, Idk.</p> <p>Anyway, I started scraping data and storing it to bypass the 90-day limit on sold items. I built a website to display the data in a nice way, with charts and everything.</p> <p>Surprisingly, eBay hasn&#39;t blocked my IP, but I&#39;m wondering if it&#39;s legal. The website is not online yet, but I want to share it with the public.</p> <p>Can I do this, or will I get in trouble?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alk601"> /u/Alk601 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hkahlc/can_i_scrape_ebay_and_use_the_data_for_my_website/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webs

## I’m searching for a scraping tool that generates Scrapy code
 - [https://www.reddit.com/r/webscraping/comments/1hk9jku/im_searching_for_a_scraping_tool_that_generates](https://www.reddit.com/r/webscraping/comments/1hk9jku/im_searching_for_a_scraping_tool_that_generates)
 - RSS feed: $source
 - date published: 2024-12-22T22:33:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone. I’m in search of a platform or an open source project can take a url, analyse it using AI and a simple feedback from the developer generate the source code for scraping the website. It not really relevant whether it generates BS4, Scrapy, cheerio or any other framework or library specific code, as long as it can understand the context of the website and produce source code I can run on-prem. Another requirement is the generated code should not rely on a headless browser.</p> <p>Our issue with existing scraping platforms is they run as a black box and you are charged by usage. Our company’s use case is to generate scrapers for thousands of sources, if not tens of thousands and to scrape tens of millions of datapoints per month. Manually implementing scrapers for each source is unachievable in terms of human capital, while using a scraping service is not justifiable in terms of financial capital. The only solution for us is to have a pl

## How to infinite scroll with playwright on YouTube?
 - [https://www.reddit.com/r/webscraping/comments/1hk0ll5/how_to_infinite_scroll_with_playwright_on_youtube](https://www.reddit.com/r/webscraping/comments/1hk0ll5/how_to_infinite_scroll_with_playwright_on_youtube)
 - RSS feed: $source
 - date published: 2024-12-22T15:24:39+00:00

<!-- SC_OFF --><div class="md"><p>I was trying to apply the automation of infinite scroll on YouTube but It doesn&#39;t work. I tried with &quot;page.evaluate(&quot;window.scrollTo(0, &#39;document.body.scrollHeight&#39;)&quot;)</p> <p>But It doesn&#39;t do anything. Can anyone help me?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vinc__98"> /u/Vinc__98 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hk0ll5/how_to_infinite_scroll_with_playwright_on_youtube/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hk0ll5/how_to_infinite_scroll_with_playwright_on_youtube/">[comments]</a></span>

## help needed for my selenium code on UI.Vision
 - [https://www.reddit.com/r/webscraping/comments/1hk0l88/help_needed_for_my_selenium_code_on_uivision](https://www.reddit.com/r/webscraping/comments/1hk0l88/help_needed_for_my_selenium_code_on_uivision)
 - RSS feed: $source
 - date published: 2024-12-22T15:24:04+00:00

<!-- SC_OFF --><div class="md"><p>I created a functioning script that opens a page, selects options 1 and 2 from a.csv file, and submits; it then loops and repeats the process. Everything has been wonderful up to this point. Just one issue: it does not utilize row 2 from try number 2.</p> <p>So, for example, row one options 1 and 2 are orange and fruit, respectively, whereas row 2 options 1 and 2 are carrot and vegetable. However, when I execute the script, even if I loop it ten times, it will continue to publish orange and fruit rather than attempting 20 additional entries.CSV file.</p> <p>I&#39;m posting my basic code here in case someone can spot the problem and fix it so that I may attempt the loop with data from the following line on successive tries.</p> <p>thankyou</p> <blockquote> <p>{<br/> &quot;Name&quot;: &quot;document&quot;,<br/> &quot;CreationDate&quot;: &quot;2024-12-10&quot;,<br/> &quot;Commands&quot;: [<br/> {<br/> &quot;Command&quot;: &quot;store&quot;,<br/> &quot;T

## Current DOM saver
 - [https://www.reddit.com/r/webscraping/comments/1hk02un/current_dom_saver](https://www.reddit.com/r/webscraping/comments/1hk02un/current_dom_saver)
 - RSS feed: $source
 - date published: 2024-12-22T14:58:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi there, i need and advice: ideally i&#39;d like to navigate a webpage with my favorite browser and have something that every x seconds saves the DOM as it is in that specific moment, completely automated. </p> <p>I&#39;ve asked ChatGPT but gave me dumb or unrelated answer like unautomated solutions or browserless solutions. The best solution he gave is a script to put in the console of the browser, but every time i change page, even if in the same tab, the script disappears, so it&#39;s not the ideal solution.</p> <p>Just in case you&#39;re interested, here&#39;s the script:</p> <pre><code>setInterval(() =&gt; { const dom = document.documentElement.outerHTML; const blob = new Blob([dom], { type: &quot;text/html&quot; }); const a = document.createElement(&quot;a&quot;); a.href = URL.createObjectURL(blob); a.download = `snapshot_${Date.now()}.html`; a.click(); }, 2000); // Salva il DOM ogni 2 secondi </code></pre> <p>Any better idea? It should be the

## Why can't I Scape media posts of a subreddit?
 - [https://www.reddit.com/r/webscraping/comments/1hjzzav/why_cant_i_scape_media_posts_of_a_subreddit](https://www.reddit.com/r/webscraping/comments/1hjzzav/why_cant_i_scape_media_posts_of_a_subreddit)
 - RSS feed: $source
 - date published: 2024-12-22T14:53:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi, </p> <p>I&#39;m new to web scraping and was trying to develop a python script to download photos and videos from a subreddit. I was able to download the photos and videos from those of the single posts. But I&#39;m unable to read any post which has multiple media in it ( the gallery posts) ? I&#39;m seeing a HTTP Error 403: Forbidden error.</p> <p>Is there any API documentation related to accessing such a post&#39;s attribute?</p> <p>Has anyone encountered this? Any help is appreciated<br/> Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Evilredditur"> /u/Evilredditur </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hjzzav/why_cant_i_scape_media_posts_of_a_subreddit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hjzzav/why_cant_i_scape_media_posts_of_a_subreddit/">[comments]</a></span>

## web mining tutoriels
 - [https://www.reddit.com/r/webscraping/comments/1hjy8uf/web_mining_tutoriels](https://www.reddit.com/r/webscraping/comments/1hjy8uf/web_mining_tutoriels)
 - RSS feed: $source
 - date published: 2024-12-22T13:13:12+00:00

<!-- SC_OFF --><div class="md"><p>is their tutoriels or guide on how to start with web scraping and web automation ? guide , course , tutoriels anything would help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LahmeriMohamed"> /u/LahmeriMohamed </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hjy8uf/web_mining_tutoriels/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hjy8uf/web_mining_tutoriels/">[comments]</a></span>

## Your preferred method to scrape? Headless browser or private APIs
 - [https://www.reddit.com/r/webscraping/comments/1hjuan9/your_preferred_method_to_scrape_headless_browser](https://www.reddit.com/r/webscraping/comments/1hjuan9/your_preferred_method_to_scrape_headless_browser)
 - RSS feed: $source
 - date published: 2024-12-22T08:12:20+00:00

<!-- SC_OFF --><div class="md"><p>hi. i used to scrape via headless browser, but due to the drawbacks of high memory usage and high latency (also annoying code to write), i prefer to just use an HTTP client (favourite: node.js + axios + axios-cookiejar-support + cheerio libraries) and either get raw HTML or hit the private APIs (if it&#39;s a modern website they will have a JSON api to load the data).</p> <p>i&#39;ve never asked this of the community, but what&#39;s the breakdown of people who use headless browsers vs private APIs? i am 99%+ only private APIs - screw headless browsers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/skilbjo"> /u/skilbjo </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hjuan9/your_preferred_method_to_scrape_headless_browser/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hjuan9/your_preferred_method_to_scrape_headless_browser/">[comments]</a></span>

