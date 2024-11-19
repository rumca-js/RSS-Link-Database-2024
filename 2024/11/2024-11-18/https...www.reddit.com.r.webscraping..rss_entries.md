# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Scraping images of clothing from online shops legally?
 - [https://www.reddit.com/r/webscraping/comments/1guivty/scraping_images_of_clothing_from_online_shops](https://www.reddit.com/r/webscraping/comments/1guivty/scraping_images_of_clothing_from_online_shops)
 - RSS feed: $source
 - date published: 2024-11-18T23:27:29+00:00

<!-- SC_OFF --><div class="md"><p>Today I thought it would be practical for OSINT if there was a searchable archive containing clothing items, the online shops they were sold in and corresponding time period when they were sold. However, I highly doubt this is legally possible due to two main reasons:</p> <ol> <li><p>The item&#39;s images might be copyrighted.</p></li> <li><p>You&#39;re basically copying the database of each shop by doing so.</p> <p>Does anybody know more about this and if there is a way do this legally in theory? Also there might be differences between countries that need to be researched in detail. (I know that a project like this would require a lot of work, difficulties and financial resources in practice, but I&#39;m just wondering about laws at the moment.)</p></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WonicTater"> /u/WonicTater </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1guivty/sc

## Website giving different results between headless and headful mode
 - [https://www.reddit.com/r/webscraping/comments/1guilzg/website_giving_different_results_between_headless](https://www.reddit.com/r/webscraping/comments/1guilzg/website_giving_different_results_between_headless)
 - RSS feed: $source
 - date published: 2024-11-18T23:14:55+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>I&#39;m trying to scrape <a href="https://www.nba.com/schedule">https://www.nba.com/schedule</a> but the website appears different in headless and headful mode. I&#39;m currently using python playwright.</p> <p>I&#39;ve tried all of GPT&#39;s suggestions but they aren&#39;t working.</p> <p>Here&#39;s my code:</p> <pre><code> with sync_playwright() as p: # Launch the browser (headless) browser = p.chromium.launch( headless=True, args=[ &#39;--disable-blink-features=AutomationControlled&#39;, &#39;--disable-blink-features&#39;, &#39;--disable-dev-shm-usage&#39;, &#39;--no-sandbox&#39;, &#39;--disable-gpu&#39;, &#39;--disable-infobars&#39;, &#39;--window-size=1920,1080&#39;, &#39;--start-maximized&#39; ] ) # Create a new browser context context = browser.new_context( user_agent=&quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64) &quot; &quot;AppleWebKit/537.36 (KHTML, like Gecko) &quot; &quot;Chrome/116.0.5845.96 Safari/537.36&quot;, viewpo

## Recommendation for tool to use.
 - [https://www.reddit.com/r/webscraping/comments/1guh91h/recommendation_for_tool_to_use](https://www.reddit.com/r/webscraping/comments/1guh91h/recommendation_for_tool_to_use)
 - RSS feed: $source
 - date published: 2024-11-18T22:16:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi I want to scrape prices from a website that I don’t have the login and password. I’d appreciate any recommendations. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Prudence_trans"> /u/Prudence_trans </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1guh91h/recommendation_for_tool_to_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1guh91h/recommendation_for_tool_to_use/">[comments]</a></span>

## Why CF don't subscribe to proxy companies and blacklist their ip's?
 - [https://www.reddit.com/r/webscraping/comments/1guh50d/why_cf_dont_subscribe_to_proxy_companies_and](https://www.reddit.com/r/webscraping/comments/1guh50d/why_cf_dont_subscribe_to_proxy_companies_and)
 - RSS feed: $source
 - date published: 2024-11-18T22:11:42+00:00

<!-- SC_OFF --><div class="md"><p>honest question. I don&#39;t really get how residential proxy provider companies survive and continue to run this model</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yyavuz"> /u/yyavuz </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1guh50d/why_cf_dont_subscribe_to_proxy_companies_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1guh50d/why_cf_dont_subscribe_to_proxy_companies_and/">[comments]</a></span>

## Best way to track CSV changes
 - [https://www.reddit.com/r/webscraping/comments/1gud5jt/best_way_to_track_csv_changes](https://www.reddit.com/r/webscraping/comments/1gud5jt/best_way_to_track_csv_changes)
 - RSS feed: $source
 - date published: 2024-11-18T19:26:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1gud5jt/best_way_to_track_csv_changes/"> <img src="https://b.thumbs.redditmedia.com/1aGmBqNXw3Z5BaWsSCgTmqGv-a4Gk4KYLl6bd_eSXmk.jpg" alt="Best way to track CSV changes" title="Best way to track CSV changes" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Do you have a better idea for tracking changes in a CSV file than Changedetection.io? It&#39;s a simple diff tool, but perhaps tracking individual lines would be more effective. The issue I&#39;m facing is that even if the order of products changes, it gets flagged as a change. I only want to track price changes.</p> <p><a href="https://preview.redd.it/p3rwm9xbop1e1.png?width=2602&amp;format=png&amp;auto=webp&amp;s=1b13978f9b6659655838ff2494450e42132a618a">https://preview.redd.it/p3rwm9xbop1e1.png?width=2602&amp;format=png&amp;auto=webp&amp;s=1b13978f9b6659655838ff2494450e42132a618a</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.re

## How to make sure I'm among the first on a web queue?
 - [https://www.reddit.com/r/webscraping/comments/1guafci/how_to_make_sure_im_among_the_first_on_a_web_queue](https://www.reddit.com/r/webscraping/comments/1guafci/how_to_make_sure_im_among_the_first_on_a_web_queue)
 - RSS feed: $source
 - date published: 2024-11-18T17:36:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1guafci/how_to_make_sure_im_among_the_first_on_a_web_queue/"> <img src="https://b.thumbs.redditmedia.com/WtGLczunEyegbtYxEg2mll8R1iza-3s5ttKM8FZyG6I.jpg" alt="How to make sure I'm among the first on a web queue?" title="How to make sure I'm among the first on a web queue?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>A store near me will be selling something and opened up a queue system via a Microsoft forms.<br/> The instructions are the following:</p> <blockquote> <p>At 10 a.m. tomorrow, Tuesday, November 19, the purchase notification opens. Here above you will find the link. It is <strong>first come, first</strong> served and your queue number is generated when you start the purchase notification by clicking on the link and the &quot;Start now&quot; button. After you click on the link, you have 20 minutes to fill in the form. </p> </blockquote> <p>The link right now shows the image bellow. I do not want

## Akamai 3.0 Help
 - [https://www.reddit.com/r/webscraping/comments/1gu98xi/akamai_30_help](https://www.reddit.com/r/webscraping/comments/1gu98xi/akamai_30_help)
 - RSS feed: $source
 - date published: 2024-11-18T16:50:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I need help bypassing akamai sensor data on v3. Can anyone point me to discords or communities where I can get help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Solitairee"> /u/Solitairee </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gu98xi/akamai_30_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gu98xi/akamai_30_help/">[comments]</a></span>

## How do you scrape a site in English? (When it's in another language)
 - [https://www.reddit.com/r/webscraping/comments/1gu7s2y/how_do_you_scrape_a_site_in_english_when_its_in](https://www.reddit.com/r/webscraping/comments/1gu7s2y/how_do_you_scrape_a_site_in_english_when_its_in)
 - RSS feed: $source
 - date published: 2024-11-18T15:49:19+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m in a situation where i could see translated content (from German) in a website so that i can easily scrape it in English, but when the automation browser (Chrome) opens it does not show the content in English, meaning it does not translate it, so i can&#39;t scrape it in English. The scraped data are all in German language.</p> <p>Could anyone please help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LocalConversation850"> /u/LocalConversation850 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gu7s2y/how_do_you_scrape_a_site_in_english_when_its_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gu7s2y/how_do_you_scrape_a_site_in_english_when_its_in/">[comments]</a></span>

## Weekly Discussion - 18 Nov 2024
 - [https://www.reddit.com/r/webscraping/comments/1gu6ohz/weekly_discussion_18_nov_2024](https://www.reddit.com/r/webscraping/comments/1gu6ohz/weekly_discussion_18_nov_2024)
 - RSS feed: $source
 - date published: 2024-11-18T15:01:39+00:00

<!-- SC_OFF --><div class="md"><p>Welcome to the weekly discussion thread! Whether you&#39;re a seasoned web scraper or just starting out, this is the perfect place to discuss topics that might not warrant a dedicated post, such as:</p> <ul> <li>Techniques for extracting data from popular sites like LinkedIn, Facebook, etc.</li> <li>Industry news, trends, and insights on the web scraping job market</li> <li>Challenges and strategies in marketing and monetizing your scraping projects</li> </ul> <p>Like our monthly <a href="https://reddit.com/r/webscraping/about/sticky?num=1">self-promotion</a> thread, mentions of paid services and tools are permitted 🤝. If you&#39;re new to web scraping, be sure to check out the <a href="https://webscraping.fyi">beginners guide</a> 🌱</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AutoModerator"> /u/AutoModerator </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gu6ohz/weekly_discussion_18_

## how can Reddit enjoy SEO & prevent AI from scraping its data?
 - [https://www.reddit.com/r/webscraping/comments/1gu27na/how_can_reddit_enjoy_seo_prevent_ai_from_scraping](https://www.reddit.com/r/webscraping/comments/1gu27na/how_can_reddit_enjoy_seo_prevent_ai_from_scraping)
 - RSS feed: $source
 - date published: 2024-11-18T11:00:18+00:00

<!-- SC_OFF --><div class="md"><p>how can a website like Reddit enjoy incredible SEO, but prevent AI from scraping its data to train LLMs?</p> <p>Reddit enjoys both amazing SEO &amp; SERP, while simultaneously monetizing our/their data here to sell or license to generative AI model builders? </p> <p>I don&#39;t think robots.txt, CAPTCHAs, Rate Limiting/IP Blocking, API Restrictions, etc can stop it - so how do they enforce exclusivity to their buyers, hence justifying the high double digit million price tags that the big players are all excited to pay? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stuffstart"> /u/stuffstart </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gu27na/how_can_reddit_enjoy_seo_prevent_ai_from_scraping/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gu27na/how_can_reddit_enjoy_seo_prevent_ai_from_scraping/">[comments]</a></span>

## Python requests library not returning all the html
 - [https://www.reddit.com/r/webscraping/comments/1gtzapb/python_requests_library_not_returning_all_the_html](https://www.reddit.com/r/webscraping/comments/1gtzapb/python_requests_library_not_returning_all_the_html)
 - RSS feed: $source
 - date published: 2024-11-18T07:17:46+00:00

<!-- SC_OFF --><div class="md"><p>I am making a get request to spotify websites just to get all the names of the artists for each song. But for some reason, it seems like the result is limited to 30 songs. Like only the first 30 songs are displayed. Is there a way to get the names of all the artists for all the songs given a url? Why is the html being limited? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/man_wif-waluigi-hed"> /u/man_wif-waluigi-hed </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gtzapb/python_requests_library_not_returning_all_the_html/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gtzapb/python_requests_library_not_returning_all_the_html/">[comments]</a></span>

