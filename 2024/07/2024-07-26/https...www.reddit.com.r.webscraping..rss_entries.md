# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## New to web scraping and have a question.
 - [https://www.reddit.com/r/webscraping/comments/1ectzpl/new_to_web_scraping_and_have_a_question](https://www.reddit.com/r/webscraping/comments/1ectzpl/new_to_web_scraping_and_have_a_question)
 - RSS feed: https://www.reddit.com/r/webscraping/.rss
 - date published: 2024-07-26T17:33:59+00:00

<!-- SC_OFF --><div class="md"><p>Legit new to the web scarping and I hope I am not breaking any rules. This is question is a bit about legal/ethical dilemma I am having. Sorry for trash english/grammer since I am nervous and shit. Anyway, so I am making an electron js app that is meant to serve as a reading list of manhwa/mangas/etc. The idea was to &quot;scrape&quot; the cover image of the books and such. Firstly, I am doing this project to enhance some js/html/css stuff; but also a list for myself since I do read some mangas. But the problem is, I don't know if its legal to use the images from google image search. And since I plan on putting it on github, I don't want to face any charges. So, I guess my overall question is, can I use images for google image search for my project? Let me know If i have to clarify more, I know I kind of rambled on, but I am nervous since I really dont want google to bring some doom bots and make me use chrome without any adblockers for the rest of my

## I'll need to cite a few tweets, so I created the script to get bibtex citation from url
 - [https://www.reddit.com/r/webscraping/comments/1eclsv5/ill_need_to_cite_a_few_tweets_so_i_created_the](https://www.reddit.com/r/webscraping/comments/1eclsv5/ill_need_to_cite_a_few_tweets_so_i_created_the)
 - RSS feed: https://www.reddit.com/r/webscraping/.rss
 - date published: 2024-07-26T11:32:41+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/Vulwsztyn/tweet-2-bibtex">https://github.com/Vulwsztyn/tweet-2-bibtex</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SwordInStone"> /u/SwordInStone </a> <br /> <span><a href="https://www.reddit.com/r/webscraping/comments/1eclsv5/ill_need_to_cite_a_few_tweets_so_i_created_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1eclsv5/ill_need_to_cite_a_few_tweets_so_i_created_the/">[comments]</a></span>

## Kohls webscrapper-help needed
 - [https://www.reddit.com/r/webscraping/comments/1eci4sc/kohls_webscrapperhelp_needed](https://www.reddit.com/r/webscraping/comments/1eci4sc/kohls_webscrapperhelp_needed)
 - RSS feed: https://www.reddit.com/r/webscraping/.rss
 - date published: 2024-07-26T07:29:10+00:00

<!-- SC_OFF --><div class="md"><p>Hey. I am trying to scrape the kohl's website. My code is this </p> <pre><code>if response.status_code == 200: # Parse the HTML content using BeautifulSoup soup = BeautifulSoup(response.content, 'html.parser') # Define kwargs for finding the &lt;script&gt; tag kwargs = { 'name': 'script', 'attrs': {'type': 'text/javascript'} } # Find the &lt;script&gt; tag within the &lt;head&gt; tag head_tag = soup.find('head') if head_tag: # Find the &lt;script&gt; tag within the &lt;head&gt; tag using kwargs script_tag = getattr(head_tag, 'find')(**kwargs) if script_tag: # Extract the src attribute of the &lt;script&gt; tag script_src = script_tag.get('src') print(f&quot;Script src: {script_src}&quot;) if script_src: # Fetch the external JavaScript file external_script_response = requests.get(script_src) if external_script_response.status_code == 200: # Print the content of the external JavaScript file print(&quot;External script content:&quot;) print(external_scri

## Pinduoduo app and website scraping
 - [https://www.reddit.com/r/webscraping/comments/1echvag/pinduoduo_app_and_website_scraping](https://www.reddit.com/r/webscraping/comments/1echvag/pinduoduo_app_and_website_scraping)
 - RSS feed: https://www.reddit.com/r/webscraping/.rss
 - date published: 2024-07-26T07:11:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi is any one know how to scrape pinduoduo app or mobile website mobile.pinduoduo.com. I am not able to get the product detail data from any of the sources above. When I try to use the python request to automate the detail data extraction I got blocked after 10-12 request. Any help will be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legitimate_Map7097"> /u/Legitimate_Map7097 </a> <br /> <span><a href="https://www.reddit.com/r/webscraping/comments/1echvag/pinduoduo_app_and_website_scraping/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1echvag/pinduoduo_app_and_website_scraping/">[comments]</a></span>

## Selenium Web Scraping on Google Maps: Clicking on all markers/points in view
 - [https://www.reddit.com/r/webscraping/comments/1ecgfn5/selenium_web_scraping_on_google_maps_clicking_on](https://www.reddit.com/r/webscraping/comments/1ecgfn5/selenium_web_scraping_on_google_maps_clicking_on)
 - RSS feed: https://www.reddit.com/r/webscraping/.rss
 - date published: 2024-07-26T05:39:26+00:00

<!-- SC_OFF --><div class="md"><p>I'm fairly new to Selenium and am looking to learn how to use it to click on all the markers or points on Google Maps in my view only. I’ve tried following some examples, but they either only work with pre-existing points in their database or rely on the Google Maps API. When I inspect Google Maps, I can only find the entire canvas element, not the individual points.</p> <p>Below is my code</p> <p>' ' '</p> <p>from selenium import webdriver from selenium.webdriver.chrome.options import Options from selenium.webdriver.chrome.service import Service from webdriver_manager.chrome import ChromeDriverManager from selenium.webdriver.common.by import By from selenium.webdriver.support.ui import WebDriverWait from selenium.webdriver.support import expected_conditions as EC</p> <p>options = Options() options.add_argument('--headless') options.add_argument('--no-sandbox') options.add_argument('--disable-dev-shm-usage') driver = webdriver.Chrome(service=Service(C

## Do you know puppeteer-extra-plugin-stealth alternatives?
 - [https://www.reddit.com/r/webscraping/comments/1ecczl1/do_you_know_puppeteerextrapluginstealth](https://www.reddit.com/r/webscraping/comments/1ecczl1/do_you_know_puppeteerextrapluginstealth)
 - RSS feed: https://www.reddit.com/r/webscraping/.rss
 - date published: 2024-07-26T02:26:15+00:00

<!-- SC_OFF --><div class="md"><p>Starting yesterday I think cloudflare did some update and now our scrapers for thesis purposes no longer works and flagged immediately. I used Playwright with NodeJS with the stealth plugin, Would like to know if there are new methods for this </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Snoo_4779"> /u/Snoo_4779 </a> <br /> <span><a href="https://www.reddit.com/r/webscraping/comments/1ecczl1/do_you_know_puppeteerextrapluginstealth/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1ecczl1/do_you_know_puppeteerextrapluginstealth/">[comments]</a></span>

