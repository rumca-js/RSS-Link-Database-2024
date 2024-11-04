# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django list is not able to render through React app on mobile browser but works fine on PC
 - [https://www.reddit.com/r/django/comments/1giylso/django_list_is_not_able_to_render_through_react](https://www.reddit.com/r/django/comments/1giylso/django_list_is_not_able_to_render_through_react)
 - RSS feed: $source
 - date published: 2024-11-03T22:04:55+00:00

<!-- SC_OFF --><div class="md"><p>Django list is not appearing in my remote phone browser but it appears on pc</p> <p>So I have an app that uses Django as back end and react for front end. It works perfectly on my PC . But I wanted to try is out on my phone so I started both servers on 0.0.0.0, I went ahead to create inbound rules in my firewall.</p> <p>Now I can access the API URL and react page on my phone but the react page can not render the data from the Django API on the phone even though it&#39;s works fine on the pc. </p> <p>I have set cors to allow all origin. Looking at the Django server the react app is not able to make a request through the phone at all.</p> <p>I get failed to load resource error Uncought (in promise) type error, failed to fetch and ERR_CONNECTION_REFUSED</p> <p>what am I missing?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Realistic-Sector6793"> /u/Realistic-Sector6793 </a> <br/> <span><a href="https://www.reddi

## Trying to understand CRUD in Django
 - [https://www.reddit.com/r/django/comments/1giyin9/trying_to_understand_crud_in_django](https://www.reddit.com/r/django/comments/1giyin9/trying_to_understand_crud_in_django)
 - RSS feed: $source
 - date published: 2024-11-03T22:01:05+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I&#39;d like to get your opinion on this. Why is developing a CRUD in Django so popular? I&#39;ve worked on projects using Django, and I know it&#39;s a powerful framework that&#39;s easy to work with, but I&#39;ve mostly used it for building websites. I don’t quite understand why it’s so useful specifically for creating CRUD applications.</p> <p>For example, while browsing, I&#39;ve found many tutorials and courses on building CRUDs in Django with the Django Rest Framework. Could you explain or share your thoughts on this? Why are so many people using it in this way?</p> <p>Thank you for taking the time to read my message!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrNoodlesLearns"> /u/MrNoodlesLearns </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1giyin9/trying_to_understand_crud_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1

## Create Middleware to calculate the time it took to generate the view so it ca be passed as a variable to be used in render?
 - [https://www.reddit.com/r/django/comments/1gix15c/create_middleware_to_calculate_the_time_it_took](https://www.reddit.com/r/django/comments/1gix15c/create_middleware_to_calculate_the_time_it_took)
 - RSS feed: $source
 - date published: 2024-11-03T20:56:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m struggling with the logic to make a function which calculates the time to render a response to the frontend. When I&#39;m using the middleware, I&#39;m unable to pass the variable to the template (response.duration). </p> <p>I&#39;ve got below through chatgpt, but that doesn&#39;t really help in this case. What would be the logical approach to return the variable to be used in the template? </p> <pre><code>return render(request, &quot;index.html&quot;, context) </code></pre> <p>The only thing I can think of is seperating the render of the template and the return of the response?</p> <p>How can I add variable duration to request, after the view has been processed but before the response is returned?</p> <pre><code>class RenderTimeMiddleware(MiddlewareMixin): def process_request(self, request): # Store the start time request.start_time = time.time() def process_response(self, request, response): # Calculate the duration duration = time.time() -

## Has there ever been a poll on this subreddit about using Django solely for API vs. full SSR applications?
 - [https://www.reddit.com/r/django/comments/1givpge/has_there_ever_been_a_poll_on_this_subreddit](https://www.reddit.com/r/django/comments/1givpge/has_there_ever_been_a_poll_on_this_subreddit)
 - RSS feed: $source
 - date published: 2024-11-03T19:59:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! I&#39;m curious if there’s ever been a poll or discussion on this subreddit about how people use Django. Specifically, I’d love to know how many of you primarily use Django just for building APIs (e.g., with DRF) versus how many are building full SSR applications with Django only, using tools like DTL, Alpine.js, htmx, etc.</p> <p>I’m interested in seeing the breakdown in our community between those who go API-only and those who leverage Django as a complete SSR framework. Any insights or links to past discussions would be greatly appreciated. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/systemkwiat"> /u/systemkwiat </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1givpge/has_there_ever_been_a_poll_on_this_subreddit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1givpge/has_there_ever_been_a_poll_on_this_subreddit/">[comments

## Your Experience as Django developer.
 - [https://www.reddit.com/r/django/comments/1gis59h/your_experience_as_django_developer](https://www.reddit.com/r/django/comments/1gis59h/your_experience_as_django_developer)
 - RSS feed: $source
 - date published: 2024-11-03T17:27:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello Developers, </p> <p>I would love to know your experience as a Django developer and what are your day to day task as a dev.</p> <p>Like beside python, its important to know other languages like JavaScripts, CSS, MYSQL or just basic are fine?<br/> What makes a good developer in the eyes of a company?<br/> When you get stuck somewhere how you guys deal with it? </p> <p>I am asking because i am searching for job as a django developer, recently i have completed building few websites and course, buts its not easy to get a job. I am thinking to try for data science.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WildMarket6076"> /u/WildMarket6076 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gis59h/your_experience_as_django_developer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gis59h/your_experience_as_django_developer/">[comments]</a></span>

## Deploy Django to DigitalOcean Kubernetes
 - [https://www.reddit.com/r/django/comments/1gir6he/deploy_django_to_digitalocean_kubernetes](https://www.reddit.com/r/django/comments/1gir6he/deploy_django_to_digitalocean_kubernetes)
 - RSS feed: $source
 - date published: 2024-11-03T16:45:52+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/DilbertJunior"> /u/DilbertJunior </a> <br/> <span><a href="https://youtu.be/-md_6nmogNc">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gir6he/deploy_django_to_digitalocean_kubernetes/">[comments]</a></span>

## Setting Up a Project for Local Deployment
 - [https://www.reddit.com/r/django/comments/1gin0kk/setting_up_a_project_for_local_deployment](https://www.reddit.com/r/django/comments/1gin0kk/setting_up_a_project_for_local_deployment)
 - RSS feed: $source
 - date published: 2024-11-03T13:37:35+00:00

<!-- SC_OFF --><div class="md"><p>I am about to deploy my application to a local environment, it&#39;s going to be used internally within a company, what would be the best way to set it up? Should I use docker? Should I go with WhiteNoise for handling static files?</p> <p>What would be tips to properly set this up? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iEmerald"> /u/iEmerald </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gin0kk/setting_up_a_project_for_local_deployment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gin0kk/setting_up_a_project_for_local_deployment/">[comments]</a></span>

## Django Upload To S3 Using Presigned URLs tip
 - [https://www.reddit.com/r/django/comments/1gikw07/django_upload_to_s3_using_presigned_urls_tip](https://www.reddit.com/r/django/comments/1gikw07/django_upload_to_s3_using_presigned_urls_tip)
 - RSS feed: $source
 - date published: 2024-11-03T11:37:01+00:00

<!-- SC_OFF --><div class="md"><p>Create presigned urls on the server and then let users upload to that specific URL. AWS S3 has API endpoints for this. It&#39;s fairly easy to set up and takes the heavy lifting from your server.</p> <p>Please do not enter the credentials right into your settings files, but use something like django-environ to pull them from a .env file or environment variables.</p> <p>The class we just created will help us to easily call the boto3 code. We can now do S3().get_presigned_url(&#39;pictures/hello.png&#39;) to get an upload endpoint for pictures/hello.png. Note that it will overwrite items when you upload to the same url twice, so it&#39;s a good idea to add a unique identifier, such as the primairy key or a uuid. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://i.redd.it/pld5snmuaoyd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/com

## What features are missing in Django?
 - [https://www.reddit.com/r/django/comments/1gijjyw/what_features_are_missing_in_django](https://www.reddit.com/r/django/comments/1gijjyw/what_features_are_missing_in_django)
 - RSS feed: $source
 - date published: 2024-11-03T10:01:42+00:00

<!-- SC_OFF --><div class="md"><ol> <li><p>What features are missing in Django?</p></li> <li><p>Are you happy with the current state of Django? </p></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/The_Naveen"> /u/The_Naveen </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gijjyw/what_features_are_missing_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gijjyw/what_features_are_missing_in_django/">[comments]</a></span>

## Wants to make a full stack YouTube like application , here is confusion
 - [https://www.reddit.com/r/django/comments/1gih6yl/wants_to_make_a_full_stack_youtube_like](https://www.reddit.com/r/django/comments/1gih6yl/wants_to_make_a_full_stack_youtube_like)
 - RSS feed: $source
 - date published: 2024-11-03T06:57:30+00:00

<!-- SC_OFF --><div class="md"><p>so i have made this Youtube like full stack project in React &amp; node </p> <p>react on frontend and express on backend and yes frontend is alone.</p> <p>so main confusion is that i wanna built the same in django so should i use django-template with creatng html files and render or just make backend api on django and connect to frontend( as i have already made ).</p> <p>or should i use react as template and serve through django ( server side rendering)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/virgin_human"> /u/virgin_human </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gih6yl/wants_to_make_a_full_stack_youtube_like/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gih6yl/wants_to_make_a_full_stack_youtube_like/">[comments]</a></span>

## Hello everyone I'm a beginner in django I took help of youtube to start my project of advance finance tracker but I'm lost as there are so many ways could you guys help me out
 - [https://www.reddit.com/r/django/comments/1gif0rw/hello_everyone_im_a_beginner_in_django_i_took](https://www.reddit.com/r/django/comments/1gif0rw/hello_everyone_im_a_beginner_in_django_i_took)
 - RSS feed: $source
 - date published: 2024-11-03T04:25:55+00:00

<!-- SC_OFF --><div class="md"><p>For my final year main project our group thought of doing django with data science but as I&#39;m not a expert to be frank(I know only basics ) could you guys help me out 🙏 I&#39;ll be able to survive my last year</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/billjackz"> /u/billjackz </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gif0rw/hello_everyone_im_a_beginner_in_django_i_took/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gif0rw/hello_everyone_im_a_beginner_in_django_i_took/">[comments]</a></span>

