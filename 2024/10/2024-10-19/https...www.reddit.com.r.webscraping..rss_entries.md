# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Is there a better way to do this?
 - [https://www.reddit.com/r/webscraping/comments/1g7g6ek/is_there_a_better_way_to_do_this](https://www.reddit.com/r/webscraping/comments/1g7g6ek/is_there_a_better_way_to_do_this)
 - RSS feed: $source
 - date published: 2024-10-19T19:07:43+00:00

<!-- SC_OFF --><div class="md"><p>We run a small website that tracks youtubers, but we don&#39;t have the youtube API quota to do this on a larger scale. So we’re trying to do this by scraping. </p> <p>We need get data on YouTube video and channel views for millions of records right now. Our current strategy is using AWS SQS to queue the URLs and have a bunch of Docker containers running Puppeteer clusters to process them.</p> <p>I was wondering if there&#39;s a more efficient way to scrape this data? I know Cheerio is faster, but it only scrapes the DOM, and the YouTube pages load dynamically with JavaScript.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GDTango"> /u/GDTango </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g7g6ek/is_there_a_better_way_to_do_this/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g7g6ek/is_there_a_better_way_to_do_this/">[comments]</a></span>

## Scraping AlgoliaSearch
 - [https://www.reddit.com/r/webscraping/comments/1g7f09f/scraping_algoliasearch](https://www.reddit.com/r/webscraping/comments/1g7f09f/scraping_algoliasearch)
 - RSS feed: $source
 - date published: 2024-10-19T18:14:06+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to scrape a website that uses AlgoliaSearch </p> <p>and i found the code used to init. the search and the index instances And I tried to mimic the request to get all the products But i faced some problems</p> <p>1- only the first 1000 items is returned in either the ui or by calling the index instance itself 2- using offset, length just returns the first 1000 only 3- browse and set settings methods are not allowed with the api key available so i think I&#39;m kinda stuck with search method</p> <p>My workaround was to make requests to algolia and put the item id as a filter And that was working well But they removed the itemid from the numeric attributes that can be used to filter </p> <p>So does anyone has any thoughts about what i can try ? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Same-Ad-8018"> /u/Same-Ad-8018 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g7f09f

## Help - WebScraping on Vinted
 - [https://www.reddit.com/r/webscraping/comments/1g7e7s9/help_webscraping_on_vinted](https://www.reddit.com/r/webscraping/comments/1g7e7s9/help_webscraping_on_vinted)
 - RSS feed: $source
 - date published: 2024-10-19T17:37:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;d like to create a bot (either for Telegram or Discord) to scrape Vinted listings.</p> <p>Here&#39;s how it should work: The user pastes a URL, and the bot continuously checks (e.g., every second) for new items added to that search result. When new items are uploaded, the bot sends notifications about them.</p> <p>For example: With this URL (<a href="https://www.vinted.it/catalog?time=1729358466&amp;brand_ids%5B%5D=53&amp;search_id=17960738370&amp;page=1">https://www.vinted.it/catalog?time=1729358466&amp;brand_ids[]=53&amp;search_id=17960738370&amp;page=1</a>), the bot should send a message whenever a new item appears.</p> <p>Are there any similar free bots available? If not, could someone help me create one? I&#39;ve never programmed a scraping bot before, but I&#39;m capable of learning.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mdmasa"> /u/mdmasa </a> <br/> <span><a href="https://www.reddit.com

## suggestion regarding bypassing captcha
 - [https://www.reddit.com/r/webscraping/comments/1g78ia8/suggestion_regarding_bypassing_captcha](https://www.reddit.com/r/webscraping/comments/1g78ia8/suggestion_regarding_bypassing_captcha)
 - RSS feed: $source
 - date published: 2024-10-19T13:05:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1g78ia8/suggestion_regarding_bypassing_captcha/"> <img src="https://b.thumbs.redditmedia.com/1Qf7sAQoa-6YW6-aYynuk0h38LUqz97DzA8WHUlc_sc.jpg" alt="suggestion regarding bypassing captcha" title="suggestion regarding bypassing captcha" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/hbyyb9opopvd1.png?width=359&amp;format=png&amp;auto=webp&amp;s=54137c47cba15ede52deb35de82a8883d5e0d6ad">https://preview.redd.it/hbyyb9opopvd1.png?width=359&amp;format=png&amp;auto=webp&amp;s=54137c47cba15ede52deb35de82a8883d5e0d6ad</a></p> <p>i am a a beginner in webscraping and would like to have suggestions on how to bypass these captchas, i tried using chatbots but they didnt gave the needed answers<br/> i want to scrape this website.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upper_Ad5011"> /u/Upper_Ad5011 </a> <br/> <span><a href="https://www.reddit.co

## its bonkerss to scrape dynamic sites
 - [https://www.reddit.com/r/webscraping/comments/1g74eum/its_bonkerss_to_scrape_dynamic_sites](https://www.reddit.com/r/webscraping/comments/1g74eum/its_bonkerss_to_scrape_dynamic_sites)
 - RSS feed: $source
 - date published: 2024-10-19T08:26:29+00:00

<!-- SC_OFF --><div class="md"><p>i tried 100 variations using coding llm (as a non-coder)</p> <p>i read somewhere in this forum Playwright is recommended </p> <p>But check this script:</p> <pre><code>import asyncio from playwright.async_api import Playwright, async_playwright import logging # Configure logging logging.basicConfig(level=logging.INFO) # URL of the webpage to scrape url = &quot;https://genius.com/One-direction-story-of-my-life-lyrics&quot; def tell_me_about_bad_math(): try: 1/0 except ZeroDivisionError: return &#39;oops!&#39; finally: print(&#39;you did bad math!&#39;) print(tell_me_about_bad_math()) async def main(): async with async_playwright() as p: browser = await p.chromium.launch() page = await browser.new_page() await page.goto(url) try: # Part 1: Extracting lyrics from the lyrics containers lyrics_containers = await page.query_selector_all(&#39;div[data-lyrics-container=&quot;true&quot;]&#39;) if not lyrics_containers: logging.warning(&quot;No lyrics containers

## How do I copy-paste these tables month-wise into an Excel sheet without manually copy-pasting and then changing the month every time?
 - [https://www.reddit.com/r/webscraping/comments/1g73msj/how_do_i_copypaste_these_tables_monthwise_into_an](https://www.reddit.com/r/webscraping/comments/1g73msj/how_do_i_copypaste_these_tables_monthwise_into_an)
 - RSS feed: $source
 - date published: 2024-10-19T07:25:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1g73msj/how_do_i_copypaste_these_tables_monthwise_into_an/"> <img src="https://preview.redd.it/sknpj8ikznvd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=0ac1204997bfdae02c08121064c88beab013ffab" alt="How do I copy-paste these tables month-wise into an Excel sheet without manually copy-pasting and then changing the month every time? " title="How do I copy-paste these tables month-wise into an Excel sheet without manually copy-pasting and then changing the month every time? " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/athex7"> /u/athex7 </a> <br/> <span><a href="https://i.redd.it/sknpj8ikznvd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g73msj/how_do_i_copypaste_these_tables_monthwise_into_an/">[comments]</a></span> </td></tr></table>

## Can anyone give a list of everything I need to know about webscraping
 - [https://www.reddit.com/r/webscraping/comments/1g7322v/can_anyone_give_a_list_of_everything_i_need_to](https://www.reddit.com/r/webscraping/comments/1g7322v/can_anyone_give_a_list_of_everything_i_need_to)
 - RSS feed: $source
 - date published: 2024-10-19T06:42:36+00:00

<!-- SC_OFF --><div class="md"><p>list of all concepts and technologies, please</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/piesany"> /u/piesany </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g7322v/can_anyone_give_a_list_of_everything_i_need_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g7322v/can_anyone_give_a_list_of_everything_i_need_to/">[comments]</a></span>

## Copyright regarding Scraping & Republishing content in my own app
 - [https://www.reddit.com/r/webscraping/comments/1g71dfo/copyright_regarding_scraping_republishing_content](https://www.reddit.com/r/webscraping/comments/1g71dfo/copyright_regarding_scraping_republishing_content)
 - RSS feed: $source
 - date published: 2024-10-19T04:44:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>Does anyone have experience scraping and republishing data (reviews) on their app? I scraped a bunch of reviews &amp; pictures from different stores in my city off Google Places and right now they are just sitting in my database. Am I even allowed to republish those images and reviews in my app? I read that somewhere these kinds of stuff belong to that user who posted it and will subjected to copyright laws. </p> <p>If this is not legal, what are some alternative ways we can pull images and reviews about a specific establishment onto our own apps? Is the only way paying for the google places apis (they don&#39;t allow caching so every time we need to call the API..)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Desperate-Editor-652"> /u/Desperate-Editor-652 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g71dfo/copyright_regarding_scraping_republishing_content/">[link]</a></s

