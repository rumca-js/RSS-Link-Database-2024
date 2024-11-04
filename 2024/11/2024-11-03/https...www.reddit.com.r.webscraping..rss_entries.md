# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## 401 on internal API
 - [https://www.reddit.com/r/webscraping/comments/1gijgkj/401_on_internal_api](https://www.reddit.com/r/webscraping/comments/1gijgkj/401_on_internal_api)
 - RSS feed: $source
 - date published: 2024-11-03T09:54:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>fotmob.com contains football data. When you click on a page, fetch requests are made to their internal API to populate the page with data. For a while, it was possible to directly make requests to this in python and use the returned JSON. However, now this returns a 401 error.</p> <p>I tried using chromedriver to open the homepage initially, take the authenticated session cookie, and pass this to the next requests to the API and that worked for a day or so, but now it doesn’t and I can’t find a way around it.</p> <p>For context, the internal API call can’t be opened in your browser anymore (you could before), and even populating my headers directly from a real browsing session that is open and working in real time doesn’t seem to work now.</p> <p>Any ideas on what has been changed, and potential solutions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SJRussell23"> /u/SJRussell23 </a> <br/> <span><a

