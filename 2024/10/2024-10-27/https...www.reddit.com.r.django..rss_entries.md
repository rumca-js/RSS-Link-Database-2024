# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Complex API causes Broken pipe from...
 - [https://www.reddit.com/r/django/comments/1gdjom2/complex_api_causes_broken_pipe_from](https://www.reddit.com/r/django/comments/1gdjom2/complex_api_causes_broken_pipe_from)
 - RSS feed: $source
 - date published: 2024-10-27T19:55:17+00:00

<!-- SC_OFF --><div class="md"><p>I face an issue with my API, it&#39;s quite complex, aggregates data from few different APIs and it takes quite some time till it&#39;s finished (about 30 sec).<br/> That&#39;s something I can live with, however when I use the API in my React app i can see in my logs there&#39;s &quot;Broken pipe from...&quot; even though I prevented users to move from one page to another and there was basically no action from user side.<br/> Is it something I shouldn&#39;t really stress about now or should I think how to fix it? (for update I&#39;m planning to setup Celery to not overload server with the API calls)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/imjustART"> /u/imjustART </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdjom2/complex_api_causes_broken_pipe_from/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdjom2/complex_api_causes_broken_pipe_from/">[comme

## Converting of web app into mobile application
 - [https://www.reddit.com/r/django/comments/1gdhpr9/converting_of_web_app_into_mobile_application](https://www.reddit.com/r/django/comments/1gdhpr9/converting_of_web_app_into_mobile_application)
 - RSS feed: $source
 - date published: 2024-10-27T18:30:23+00:00

<!-- SC_OFF --><div class="md"><p>As i am doing my project using django. I also want this project to be full fledged mobile application. I want my web app to be converted into mobile application. How to make it possible, what kind of languages or frameworks i need to use to make my django web app into mobile application. Can anyone would just give me the overview, how does this things really work?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Inside_Meet_4991"> /u/Inside_Meet_4991 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdhpr9/converting_of_web_app_into_mobile_application/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdhpr9/converting_of_web_app_into_mobile_application/">[comments]</a></span>

## Deployment Issues
 - [https://www.reddit.com/r/django/comments/1gdhm4e/deployment_issues](https://www.reddit.com/r/django/comments/1gdhm4e/deployment_issues)
 - RSS feed: $source
 - date published: 2024-10-27T18:25:58+00:00

<!-- SC_OFF --><div class="md"><p>I am doing a health related web app. And in this app i have like google OAuth to sign in, smtp email verification, news api and some other. So, the thing which is happening with me is that when i deploy my project in render none of them really works, it would only work on my local system. Do, there are so many issues with the links that need to be placed correctly for redirect as it is deployed on render.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Inside_Meet_4991"> /u/Inside_Meet_4991 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdhm4e/deployment_issues/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdhm4e/deployment_issues/">[comments]</a></span>

## Health Related Web App
 - [https://www.reddit.com/r/django/comments/1gdhiak/health_related_web_app](https://www.reddit.com/r/django/comments/1gdhiak/health_related_web_app)
 - RSS feed: $source
 - date published: 2024-10-27T18:21:23+00:00

<!-- SC_OFF --><div class="md"><p>I am building a web app which is related to health. And i only use html, css, js for frontend and django for backend. Some of them are telling we can also use django+react js. Can, anyone can help me with react js. How to use this react js in django project?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Inside_Meet_4991"> /u/Inside_Meet_4991 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdhiak/health_related_web_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdhiak/health_related_web_app/">[comments]</a></span>

## profile pic not showing
 - [https://www.reddit.com/r/django/comments/1gdbbd8/profile_pic_not_showing](https://www.reddit.com/r/django/comments/1gdbbd8/profile_pic_not_showing)
 - RSS feed: $source
 - date published: 2024-10-27T13:46:48+00:00

<!-- SC_OFF --><div class="md"><p>models.py:</p> <pre><code>class Profile(models.Model): user = models.OneToOneField(User,on_delete=models.CASCADE) user_image = models.ImageField(upload_to=&quot;user_pic/&quot;) def __str__(self): return self.user.username urls.py: from django.conf import settings from django.conf.urls.static import static urlpatterns += []+static(settings.MEDIA_URL, document_root=settings.MEDIA_ROOT) html template: &lt;img src=&quot;{{ user.profile.user_image.url }}&quot; alt=&quot;img&quot;&gt; error showing in terminal: Not Found: /picture/user_pic/10987982.jpg GET /picture/user_pic/10987982.jpg HTTP/1.1&quot; 404 2270 </code></pre> <p>the image stored in picture/user_pic/ but not rendered on html template but user name and first name is render in html template</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legal_Relief6756"> /u/Legal_Relief6756 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdbbd8/profi

## Trying Django {% url %} tag but not working as expected
 - [https://www.reddit.com/r/django/comments/1gdan1n/trying_django_url_tag_but_not_working_as_expected](https://www.reddit.com/r/django/comments/1gdan1n/trying_django_url_tag_but_not_working_as_expected)
 - RSS feed: $source
 - date published: 2024-10-27T13:11:45+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Devansh_Durgapal"> /u/Devansh_Durgapal </a> <br/> <span><a href="https://www.reddit.com/gallery/1gdan1n">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdan1n/trying_django_url_tag_but_not_working_as_expected/">[comments]</a></span>

## Please help me with my exam!
 - [https://www.reddit.com/r/django/comments/1gd7kki/please_help_me_with_my_exam](https://www.reddit.com/r/django/comments/1gd7kki/please_help_me_with_my_exam)
 - RSS feed: $source
 - date published: 2024-10-27T09:57:07+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://drive.google.com/drive/folders/1mtMEp6nDXBHwwAmqQYbrwMqkyzKJlLDK?usp=drive_link">https://drive.google.com/drive/folders/1mtMEp6nDXBHwwAmqQYbrwMqkyzKJlLDK?usp=drive_link</a></p> <p>Please i have 2 more hours</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkDare1485"> /u/OkDare1485 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gd7kki/please_help_me_with_my_exam/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gd7kki/please_help_me_with_my_exam/">[comments]</a></span>

## Looking for someone willing to join a call with me to review my code
 - [https://www.reddit.com/r/django/comments/1gd7jpy/looking_for_someone_willing_to_join_a_call_with](https://www.reddit.com/r/django/comments/1gd7jpy/looking_for_someone_willing_to_join_a_call_with)
 - RSS feed: $source
 - date published: 2024-10-27T09:55:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on Django Rest Framework and built REST API with MySQL workbench as database, I&#39;ve got most of the code done, but I&#39;m facing bugs in authentication that I&#39;ve been stuck on for a really long time and I can&#39;t move on with my project without fixing them, I really tried everything and I&#39;m trying this as a last option, I don&#39;t want anyone to write me code, I&#39;m suggesting if someone is willing to join a discord call with me where I can share my screen and they can review my code and maybe tell me what I&#39;ve been doing wrong. it&#39;s not a large project and I&#39;ll make sure I don&#39;t take much time, it&#39;ll be much appreciated, thanks for everyone in advance :) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mcphect"> /u/Mcphect </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gd7jpy/looking_for_someone_willing_to_join_a_call_with/">[link]</a></s

## Django and iOS/android apps?
 - [https://www.reddit.com/r/django/comments/1gd77ho/django_and_iosandroid_apps](https://www.reddit.com/r/django/comments/1gd77ho/django_and_iosandroid_apps)
 - RSS feed: $source
 - date published: 2024-10-27T09:29:57+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible to create one Django web app and also release iOS and android versions of that app without having to write in the native languages? It would be great to avoid having to learn/write in 3 frameworks but also is great for consistency/maintainability, only having to maintain the code in one place </p> <p>Of course, a Django web app can be used on mobile, but people always seem to say that users want to actually install an iOS/ android app instead. What is the best option here? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lebannax"> /u/lebannax </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gd77ho/django_and_iosandroid_apps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gd77ho/django_and_iosandroid_apps/">[comments]</a></span>

## How can I incorporate data science in Django project?
 - [https://www.reddit.com/r/django/comments/1gd0wms/how_can_i_incorporate_data_science_in_django](https://www.reddit.com/r/django/comments/1gd0wms/how_can_i_incorporate_data_science_in_django)
 - RSS feed: $source
 - date published: 2024-10-27T02:17:32+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I’m working on a data science project for academic research. I need to do some data analysis (I mean, data acquisition, pre-processing and data processing), specifically, it is about natural language processing so I also need to train a machine learning model I can get an output I can put in a map (a Google map).</p> <p>I’ve selected Django as the back-end framework I will use together with Flutter to develop my user interface for a mobile app in which I can deploy my map.</p> <p>So, my question is <strong>how can I handle my data analysis code into the Django project</strong> so I am able to map the output of my analysis into my geographic map, that is to say: where do I have to put my data analysis logic in the Django project considering I am planning to save the data I retrieve externally into a database based on my models? and, consequently how can I store the analysis into the database?</p> <p><strong>Somebody told me about using microser

