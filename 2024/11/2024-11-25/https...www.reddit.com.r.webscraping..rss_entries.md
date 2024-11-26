# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Hiring: Python developer with Playwright and Botasaurus Experience
 - [https://www.reddit.com/r/webscraping/comments/1gzscfp/hiring_python_developer_with_playwright_and](https://www.reddit.com/r/webscraping/comments/1gzscfp/hiring_python_developer_with_playwright_and)
 - RSS feed: $source
 - date published: 2024-11-25T20:04:26+00:00

<!-- SC_OFF --><div class="md"><p>We are looking to hire a freelancer for some projects that require playwright based browser automation and python sessions based automation. It would involve automating complex tasks such as authentication, payments etc.</p> <p>Experience with handling Cloudflare sites and having used Botasaurus would be a bonus. Please DM me in case you are interested and require more details.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/piyushnh"> /u/piyushnh </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gzscfp/hiring_python_developer_with_playwright_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gzscfp/hiring_python_developer_with_playwright_and/">[comments]</a></span>

## Scraping data from DEF 14A filings
 - [https://www.reddit.com/r/webscraping/comments/1gzqgf6/scraping_data_from_def_14a_filings](https://www.reddit.com/r/webscraping/comments/1gzqgf6/scraping_data_from_def_14a_filings)
 - RSS feed: $source
 - date published: 2024-11-25T18:48:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello, does anybody know an effective way of scraping data from SEC def14a filings using the edgar API? I haven&#39;t had much success. I want to scrape executive compensation from various filings. Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rezidual_"> /u/rezidual_ </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gzqgf6/scraping_data_from_def_14a_filings/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gzqgf6/scraping_data_from_def_14a_filings/">[comments]</a></span>

## Scraping Realtor.com Estimates
 - [https://www.reddit.com/r/webscraping/comments/1gzpndu/scraping_realtorcom_estimates](https://www.reddit.com/r/webscraping/comments/1gzpndu/scraping_realtorcom_estimates)
 - RSS feed: $source
 - date published: 2024-11-25T18:16:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1gzpndu/scraping_realtorcom_estimates/"> <img src="https://external-preview.redd.it/CR1o82xuTOQcWCO3w3nKo-rXG2xgTRKyAn-ki4hrUvI.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b6f9dd51064ad082e8489a1350f0fd15415bee9c" alt="Scraping Realtor.com Estimates" title="Scraping Realtor.com Estimates" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi all, I&#39;ve been beating my head against a wall on this problem. I&#39;ve built a wicked fast python scraper that can find properties based on city and state queries. Fantastic! Now I want to get the data for the charts in the screenshot below: </p> <p><a href="https://preview.redd.it/5rf3ekbk933e1.png?width=1902&amp;format=png&amp;auto=webp&amp;s=8eec223d25d56aab0dfd89f072d178959624ae7d">https://preview.redd.it/5rf3ekbk933e1.png?width=1902&amp;format=png&amp;auto=webp&amp;s=8eec223d25d56aab0dfd89f072d178959624ae7d</a></p> <p>I added a screenshot for the data I want. 

## Weekly Discussion - 25 Nov 2024
 - [https://www.reddit.com/r/webscraping/comments/1gzksia/weekly_discussion_25_nov_2024](https://www.reddit.com/r/webscraping/comments/1gzksia/weekly_discussion_25_nov_2024)
 - RSS feed: $source
 - date published: 2024-11-25T15:01:21+00:00

<!-- SC_OFF --><div class="md"><p>Welcome to the weekly discussion thread! Whether you&#39;re a seasoned web scraper or just starting out, this is the perfect place to discuss topics that might not warrant a dedicated post, such as:</p> <ul> <li>Techniques for extracting data from popular sites like LinkedIn, Facebook, etc.</li> <li>Industry news, trends, and insights on the web scraping job market</li> <li>Challenges and strategies in marketing and monetizing your scraping projects</li> </ul> <p>Like our monthly <a href="https://reddit.com/r/webscraping/about/sticky?num=1">self-promotion</a> thread, mentions of paid services and tools are permitted 🤝. If you&#39;re new to web scraping, be sure to check out the <a href="https://webscraping.fyi">beginners guide</a> 🌱</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AutoModerator"> /u/AutoModerator </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gzksia/weekly_discussion_25_

## Scraping jobs from Indeed
 - [https://www.reddit.com/r/webscraping/comments/1gziydl/scraping_jobs_from_indeed](https://www.reddit.com/r/webscraping/comments/1gziydl/scraping_jobs_from_indeed)
 - RSS feed: $source
 - date published: 2024-11-25T13:35:49+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>I would like to create a statistic, which shows that certain skills are commonly required for certain job types. For that I would like to make use of Indeed&#39;s jobs, but sadly they introduced some heavy bot protection recently. I&#39;m unable to get past it.</p> <p>I tried to use Playwright with the puppeteer-extra-plugin-stealth plugin, but without luck. Anyone got an idea on how to get some data from them?</p> <pre><code>import { chromium } from &quot;playwright-extra&quot;; import StealthPlugin from &quot;puppeteer-extra-plugin-stealth&quot;; chromium .use(StealthPlugin()) .launch({ headless: true }) .then(async (browser) =&gt; { const page = await browser.newPage(); await page.goto(&quot;https://indeed.com/jobs&quot;); await page.waitForTimeout(5000); await page.screenshot({ path: &quot;stealth.png&quot;, fullPage: true }); await browser.close(); }); </code></pre> <p>I&#39;m also failing the challenge at <a href="https://arh.antoin

## The most scrapable search engine?
 - [https://www.reddit.com/r/webscraping/comments/1gzega8/the_most_scrapable_search_engine](https://www.reddit.com/r/webscraping/comments/1gzega8/the_most_scrapable_search_engine)
 - RSS feed: $source
 - date published: 2024-11-25T08:42:39+00:00

<!-- SC_OFF --><div class="md"><p>Im working on a smaller scale and will be looking to scrape 100-1000 search results per day. Just the first ~5 or so links per search. What search engine do I go for scraping? Which wouldnt require a proxy or a VPN.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CaptTechno"> /u/CaptTechno </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gzega8/the_most_scrapable_search_engine/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gzega8/the_most_scrapable_search_engine/">[comments]</a></span>

## Is there a tool for downloading plaintext file of a web page?
 - [https://www.reddit.com/r/webscraping/comments/1gzbniz/is_there_a_tool_for_downloading_plaintext_file_of](https://www.reddit.com/r/webscraping/comments/1gzbniz/is_there_a_tool_for_downloading_plaintext_file_of)
 - RSS feed: $source
 - date published: 2024-11-25T05:29:29+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to search the content of all of the profiles on a matrimonial website. It&#39;s an extremely basic website and there&#39;s not search function. </p> <p>I&#39;m trying to find the best way to get all of the profiles (maybe two to three thousand) into a searchable form. I was wondering if there is any tool that I could use so that when I click a profile instead of opening a new tab, it just downloads the html to a folder for me. Once I click on all of the links, then I would just search the folder for keywords.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/semaf0r0"> /u/semaf0r0 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1gzbniz/is_there_a_tool_for_downloading_plaintext_file_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1gzbniz/is_there_a_tool_for_downloading_plaintext_file_of/">[comments]</a></span>

