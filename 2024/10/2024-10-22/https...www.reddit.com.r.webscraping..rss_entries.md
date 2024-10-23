# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Beautiful Soup - Goodreads Scraping - Performance Question
 - [https://www.reddit.com/r/webscraping/comments/1g9vads/beautiful_soup_goodreads_scraping_performance](https://www.reddit.com/r/webscraping/comments/1g9vads/beautiful_soup_goodreads_scraping_performance)
 - RSS feed: $source
 - date published: 2024-10-22T22:42:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! </p> <p>I&#39;m working on my first web scraping project to extract approximately 300 books from Goodreads and store them in a dataframe(for now). The following code is working as intended, but I can&#39;t help but think that a 7 minutes runtime is far too long for such a low volume of data (I want to do 4,000 eventually). When printing each book dictionary, I am seeing them arrive in about 1-2 seconds each. I added the runtime of the three parsers at the top of the script with lxml being the fastest so far.</p> <p>High level idea: Get list of genre urls from the &quot;most read&quot; page, then get list of book urls from each of the genre urls (100 for each genre), then scrape each book url using the book() function. </p> <p>Does anyone have any recommendations for optimization? Would an asynchronous approach make sense here? If I should provide any additional context, just let me know! Thanks!</p> <pre><code>import os import requests im

## How to automate google login?
 - [https://www.reddit.com/r/webscraping/comments/1g9ultx/how_to_automate_google_login](https://www.reddit.com/r/webscraping/comments/1g9ultx/how_to_automate_google_login)
 - RSS feed: $source
 - date published: 2024-10-22T22:11:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1g9ultx/how_to_automate_google_login/"> <img src="https://a.thumbs.redditmedia.com/mPpuMiyj0s7Jg5TPDF5JF9NVULjnIGgqi1RWCMrmmS8.jpg" alt="How to automate google login?" title="How to automate google login?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/gd57stlvsdwd1.png?width=1886&amp;format=png&amp;auto=webp&amp;s=9300dc274f401c96eea0ca1e097f2d53cbe8a727">https://preview.redd.it/gd57stlvsdwd1.png?width=1886&amp;format=png&amp;auto=webp&amp;s=9300dc274f401c96eea0ca1e097f2d53cbe8a727</a></p> <pre><code>from selenium import webdriver from selenium.webdriver.common.by import By from selenium.webdriver.common.keys import Keys username = &quot;username&quot; password = &quot;password&quot; driver = webdriver.Chrome() driver.get(&quot;https://accounts.google.com&quot;) username_field = driver.find_element(By.TAG_NAME, &#39;input&#39;); username_field.send_keys(username) username_fie

## Noob here. How to approach this?
 - [https://www.reddit.com/r/webscraping/comments/1g9t9j0/noob_here_how_to_approach_this](https://www.reddit.com/r/webscraping/comments/1g9t9j0/noob_here_how_to_approach_this)
 - RSS feed: $source
 - date published: 2024-10-22T21:12:49+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to scrape this list </p> <p>Nodejs</p> <p>Currently using a parser to get full text then sending to LLM for structured output</p> <p>But I struggle to get full entry back. Only some not full list parser </p> <p><a href="https://www.sanantonio.gov/acs/ACS_website_euth_capacity.pdf">https://www.sanantonio.gov/acs/ACS_website_euth_capacity.pdf</a></p> <p>Not to worry about the avatar images yet </p> <p>How would you approach it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mr_captcha"> /u/mr_captcha </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g9t9j0/noob_here_how_to_approach_this/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g9t9j0/noob_here_how_to_approach_this/">[comments]</a></span>

## Coding Help
 - [https://www.reddit.com/r/webscraping/comments/1g9jjf1/coding_help](https://www.reddit.com/r/webscraping/comments/1g9jjf1/coding_help)
 - RSS feed: $source
 - date published: 2024-10-22T14:30:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I need the help of someone who knows far more than I do.</p> <p>Full disclosure, I know almost nothing about coding/python/C/C++ or any of this. I tried following along with several tutorials etc but I&#39;ve found they either go through the simplest stuff with the finest of combs until I find myself scrolling through due to boredom, or they&#39;re opaque and I&#39;m not sure what they&#39;re telling me to do exactly.</p> <p>I don&#39;t have any other use for coding in my day to day life other than this very specific thing I&#39;m trying to do, and that makes it very challenging to go through the motions of actually learning what I&#39;m doing haha. As it is, I&#39;ve turned to the global idiot that is AI, and it has steered me wrong.</p> <p>Quick breakdown; I&#39;m trying to pull a specific section of data from the HTML on a website called <a href="http://Behindthename.com">Behindthename.com</a>, I have used their API to download a list of all

## Error on the school_page line.
 - [https://www.reddit.com/r/webscraping/comments/1g9jcok/error_on_the_school_page_line](https://www.reddit.com/r/webscraping/comments/1g9jcok/error_on_the_school_page_line)
 - RSS feed: $source
 - date published: 2024-10-22T14:22:56+00:00

<!-- SC_OFF --><div class="md"><p>d = {}</p> <p>For match in soup.find_all(‘td’): Link = match.find(“a”)</p> <p>If link: School_page = requests.get(<a href="https://schools.texastribune.org%E2%80%9D">https://schools.texastribune.org”</a> + link.href)</p> <p>School_soup = BeautifulSoup(school_page, “lxml”)</p> <p>Total<em>div = school_soup.find(“div”, class</em> = “metric”, text = “Total students”)</p> <p>If total_div: Amount = total_div.find(“p”, class_”metric-value”) d[link.text] = amount.text</p> <p>Print(d)</p> <p>——</p> <p>How do I fix that error? It says can only concaténate str (Not “NoneType”) to str.</p> <p>Im trying to get a list of student enrollment on the <a href="https://schools.texastribune.org/districts/">https://schools.texastribune.org/districts/</a> website.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Circa-Shootout"> /u/Circa-Shootout </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g9jcok/error_on_t

## Why scrape behind logins?
 - [https://www.reddit.com/r/webscraping/comments/1g9ikkp/why_scrape_behind_logins](https://www.reddit.com/r/webscraping/comments/1g9ikkp/why_scrape_behind_logins)
 - RSS feed: $source
 - date published: 2024-10-22T13:48:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks! 👋</p> <p>Been diving into web scraping lately and curious about your experiences with login-protected sites.</p> <p>What&#39;s your main reason for needing this data?</p> <ul> <li>Tracking competitors&#39; pricing?</li> <li>Building your own dataset?</li> <li>Monitoring changes?</li> <li>Market research?</li> <li>Something else?</li> </ul> <p>Share your experience!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/According_Visual_708"> /u/According_Visual_708 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g9ikkp/why_scrape_behind_logins/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g9ikkp/why_scrape_behind_logins/">[comments]</a></span>

## Nextdoor - Gold mine of local info
 - [https://www.reddit.com/r/webscraping/comments/1g9i1hn/nextdoor_gold_mine_of_local_info](https://www.reddit.com/r/webscraping/comments/1g9i1hn/nextdoor_gold_mine_of_local_info)
 - RSS feed: $source
 - date published: 2024-10-22T13:23:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been doing some web scraping on Nextdoor, seems to have minimal anti-scraping protection. While there&#39;s some throttling, the user base is relatively small, and there are limited posts, making it easy to gather a lot of information. Absolutely hilarious for a site with wild claims about privacy and local only info.</p> <ol> <li><p><strong>Profile Information</strong><br/> Each user profile can be accessed via:<br/> <code>https://nextdoor.com/profile/{integer id}</code></p> <p>The site uses integer IDs in the URL. You&#39;ll need to handle missing IDs, but you can start at 1 and increment upward. The profile page combines REST and GraphQL requests. A key request, <code>profileTopCard</code>, reveals detailed user information, including their neighborhood ID and name, along with the date they moved into the area.</p></li> <li><p><strong>Neighborhood Information</strong><br/> You can access neighborhood feeds via:<br/> <code>https://nextdoor.

## StarterSt0ry website - corrected
 - [https://www.reddit.com/r/webscraping/comments/1g9dywb/starterst0ry_website_corrected](https://www.reddit.com/r/webscraping/comments/1g9dywb/starterst0ry_website_corrected)
 - RSS feed: $source
 - date published: 2024-10-22T09:21:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying for days to get simple text from starterst0ry com using Claude and Chatgpt, but I cannot get it to work for some reason.<br/> (Added the full code so far below)</p> <p>Sample URL to scrape:<br/> h ttps://<a href="http://www.starterstory.com/ideas/sporting-goods-store/success-stories">www.starterstory.com/ideas/sporting-goods-store/success-stories</a></p> <p>We&#39;re having problems to get these:<br/> - $ / year<br/> - Starting Cost<br/> - People<br/> - Link (is next to &quot;How much money it makes:&quot;)</p> <p>The script saves the data in a csv, and these columns are showing N/A. </p> <p>The full code so far:<br/> <a href="https://pastebin.com/raw/RxTiUTFE">https://pastebin.com/raw/RxTiUTFE</a></p> <p>Note: when I asked Chatgpt to fetch the data from the URL, it does it without a problem.<br/> But the code it writes just doesn&#39;t work. </p> <p>Any ideas? I&#39;d really appreciate your help.</p> </div><!-- SC_ON --> &#32; su

## Scraping Netflix in Google Cloud Functions
 - [https://www.reddit.com/r/webscraping/comments/1g9cwc9/scraping_netflix_in_google_cloud_functions](https://www.reddit.com/r/webscraping/comments/1g9cwc9/scraping_netflix_in_google_cloud_functions)
 - RSS feed: $source
 - date published: 2024-10-22T08:00:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1g9cwc9/scraping_netflix_in_google_cloud_functions/"> <img src="https://b.thumbs.redditmedia.com/zmbQnQiVullSzx_t2gJ2DfyVctAsqnrbecOyyn3CAvk.jpg" alt="Scraping Netflix in Google Cloud Functions" title="Scraping Netflix in Google Cloud Functions" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://www.netflix.com/title/81663323">https://www.netflix.com/title/81663323</a></p> <p>I wrote scraping codes with Selenium and BeautifulSoup in Python to get a list of episodes for Netflix.<br/> I deployed them to Google Cloud Functions and ran, but the web page didn&#39;t show the Episodes part in the Cloud Functions environment in the first place.</p> <p>Does anyone know about the case of Netflix?<br/> Would a properly configured User Agent or something fix this?</p> <p>The first picture is the result ran in the local environment, and the second picture is in the Cloud Functions environment.<br/> The Videos

## Anyone have recommendation for Advanced Web Scraping Courses?
 - [https://www.reddit.com/r/webscraping/comments/1g9akts/anyone_have_recommendation_for_advanced_web](https://www.reddit.com/r/webscraping/comments/1g9akts/anyone_have_recommendation_for_advanced_web)
 - RSS feed: $source
 - date published: 2024-10-22T05:11:59+00:00

<!-- SC_OFF --><div class="md"><p>I already have some basic level of webscraping using playwright, bs4, selenium etc. Still need to learn about bypassing bot detection and web security though. Especially captcha and cloudflare.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FrostingEquivalent99"> /u/FrostingEquivalent99 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1g9akts/anyone_have_recommendation_for_advanced_web/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1g9akts/anyone_have_recommendation_for_advanced_web/">[comments]</a></span>

