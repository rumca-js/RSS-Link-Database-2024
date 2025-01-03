# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django Ninja & Authentication
 - [https://www.reddit.com/r/django/comments/1gef0pq/django_ninja_authentication](https://www.reddit.com/r/django/comments/1gef0pq/django_ninja_authentication)
 - RSS feed: $source
 - date published: 2024-10-28T22:23:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to create a login/logout/register page for my NextJS frontend and have it POST to my django-ninja backend....I wanted thoughts about how to handle creating a new user. Is it as simple as just saving a new model? I already have JWTs setup for existing users. </p> <p>```python</p> <h1>api.py</h1> <p>from django.contrib.auth.models import User from django.contrib.auth.hashers import make_password from ninja import Router from ninja.errors import HttpError from .schemas import UserCreateSchema</p> <p>@api.post(&quot;/signup&quot;) def signup(request, payload: UserCreateSchema): # Check if user already exists if User.objects.filter(username=payload.username).exists(): raise HttpError(400, &quot;Username is already taken&quot;)</p> <pre><code># assume all fields have been validated </code></pre> <p># Create new user with hashed password user = User( username=payload.username, email=payload.email, password=make_password(payload.password) ) us

## django.contrib.sitemaps is creating a <script/> tag in sitemap.xml
 - [https://www.reddit.com/r/django/comments/1gedbci/djangocontribsitemaps_is_creating_a_script_tag_in](https://www.reddit.com/r/django/comments/1gedbci/djangocontribsitemaps_is_creating_a_script_tag_in)
 - RSS feed: $source
 - date published: 2024-10-28T21:10:59+00:00

<!-- SC_OFF --><div class="md"><p>So I switched to a hard-coded sitemap.xml and the script tag is still there. So some middleware or something is injecting it. Any ideas what to check?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AGrimmInPortland"> /u/AGrimmInPortland </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gedbci/djangocontribsitemaps_is_creating_a_script_tag_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gedbci/djangocontribsitemaps_is_creating_a_script_tag_in/">[comments]</a></span>

## How can I handle data analysis in a Django project?
 - [https://www.reddit.com/r/django/comments/1geco8a/how_can_i_handle_data_analysis_in_a_django_project](https://www.reddit.com/r/django/comments/1geco8a/how_can_i_handle_data_analysis_in_a_django_project)
 - RSS feed: $source
 - date published: 2024-10-28T20:44:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I’m working on a data science project for academic research. I need to do some data analysis (I mean, data acquisition, pre-processing and data processing), specifically, it is about natural language processing so I also need to train a machine learning model I can get an output I can put in a map (a Google map).</p> <p>I’ve selected Django as the back-end framework I will use together with Flutter to develop my user interface for a mobile app in which I can deploy my map.</p> <p>So, <strong>how can I handle my data analysis code into the Django project</strong> so I am able to map the output of my analysis into my geographic map, that is to say: where do I have to put my data analysis logic in the Django project considering I am planning to save the data I retrieve externally into a database based on my models? and, consequently how can I store the analysis into the database?</p> <p><strong>Somebody told me about using microservices</strong> 

## Comment section like reddit multi-threaded
 - [https://www.reddit.com/r/django/comments/1ge6o4b/comment_section_like_reddit_multithreaded](https://www.reddit.com/r/django/comments/1ge6o4b/comment_section_like_reddit_multithreaded)
 - RSS feed: $source
 - date published: 2024-10-28T16:39:32+00:00

<!-- SC_OFF --><div class="md"><p>I am facing difficulties creating multi threaded comment section like reddit in django . It just keep moving to the left like a slanted line . Please refer me some repo or module or any Github link or video </p> <p>If you have any idea , what could be possible reason just tell me every possible chances.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Speech2842"> /u/No-Speech2842 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ge6o4b/comment_section_like_reddit_multithreaded/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ge6o4b/comment_section_like_reddit_multithreaded/">[comments]</a></span>

## Help Finding Emoji Picker Widget
 - [https://www.reddit.com/r/django/comments/1ge3tgw/help_finding_emoji_picker_widget](https://www.reddit.com/r/django/comments/1ge3tgw/help_finding_emoji_picker_widget)
 - RSS feed: $source
 - date published: 2024-10-28T14:45:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m building a blog web app using HTML, CSS (with Bootstrap), and plain JS served using Django. What I would like to do is add a emoji widget next to the text input and text area widgets like you&#39;d find on Instagram or Discord so users can search for and select which emoji they&#39;d like to input as the next character in their post/comment. The only problem is that the django-emoji-picker (URL: <a href="https://github.com/wdr-data/django-emoji-picker">https://github.com/wdr-data/django-emoji-picker</a>) clashes with my project&#39;s CSS due to its use of an &lt;svg&gt; as the widget, plus it&#39;s been abandonware for years now at this point.</p> <p>Google searches have turned up iOS, Linux, and NPM dependencies (which I am not using in my project at the moment). Given that this is a relatively common use case, is there any dependency I can use for my project to insert a emoji picker next to the text inputs of my project?</p> <p>T

## How would you handle limits for Free Users without involving stripe?
 - [https://www.reddit.com/r/django/comments/1gdza2x/how_would_you_handle_limits_for_free_users](https://www.reddit.com/r/django/comments/1gdza2x/how_would_you_handle_limits_for_free_users)
 - RSS feed: $source
 - date published: 2024-10-28T11:03:59+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m building the user functionality for my app and want to offer a free tier option with limited capabilities. What&#39;s the best way to implement usage restrictions for free users without involving payment processing?</p> <p>The goals are to:</p> <ul> <li>Allow free users to upload up to 3 photos per month and view up to 10 pages per day</li> <li>Avoid requiring credit card information upfront, as that may deter signups</li> <li>Track each free user&#39;s usage to enforce the limits</li> </ul> <p>Some options I&#39;ve considered:</p> <ul> <li>Create a &quot;Free&quot; subscription plan with the desired limits, but set the price to $0. However, this would still prompt for a credit card which I want to avoid.</li> <li>Add a &quot;paid&quot; boolean field directly to the User model. Set it to false for free users. Then track photo uploads and page views separately without involving subscriptions.</li> <li>Have a UserUsage model that stores the use

## Do you use default arguments in views?
 - [https://www.reddit.com/r/django/comments/1gdwmti/do_you_use_default_arguments_in_views](https://www.reddit.com/r/django/comments/1gdwmti/do_you_use_default_arguments_in_views)
 - RSS feed: $source
 - date published: 2024-10-28T07:49:40+00:00

<!-- SC_OFF --><div class="md"><p>URLs:</p> <pre><code>path(&#39;items/&#39;, views.items, name=&#39;items&#39;), # shows list of items path(&#39;items/&lt;int:pk&gt;/&#39;, views.items, name=&#39;items&#39;), # list + a detail of selected item </code></pre> <p>View:</p> <pre><code>def items(request, pk=None): ... if pk: ... </code></pre> <p>Is there any downside to this? I figured it&#39;s more DRY than what I used <a href="https://www.reddit.com/r/django/comments/1gcj6n3/new_to_web_dev_please_help_me_undersand_this/">here</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Real_Issue_9953"> /u/Real_Issue_9953 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdwmti/do_you_use_default_arguments_in_views/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdwmti/do_you_use_default_arguments_in_views/">[comments]</a></span>

## Nested serializer's `required=True` is ignored
 - [https://www.reddit.com/r/django/comments/1gdw67i/nested_serializers_requiredtrue_is_ignored](https://www.reddit.com/r/django/comments/1gdw67i/nested_serializers_requiredtrue_is_ignored)
 - RSS feed: $source
 - date published: 2024-10-28T07:12:25+00:00

<!-- SC_OFF --><div class="md"><p>I have a nested serializer defined as the following:</p> <pre><code>items = OrderItemSerializer(many=True, required=True) </code></pre> <p>However, <code>required=True</code> is getting ignored, and I am able to perform POST operation without providing any item for <code>items</code>.</p> <p>Can you explain why? I also have a custom validation and <code>create</code> methods.</p> <p><code>OrderItem</code> <strong>Serializer:</strong></p> <pre><code>class OrderItemSerializer(serializers.ModelSerializer): price = serializers.DecimalField(source=&quot;item.style.price&quot;, max_digits=10, decimal_places=2, read_only=True) total = serializers.DecimalField(source=&quot;get_total_cost&quot;, max_digits=10, decimal_places=2, read_only=True) class Meta: model = OrderItem fields = [&quot;id&quot;, &quot;order&quot;, &quot;item&quot;, &quot;price&quot;, &quot;quantity&quot;, &quot;total&quot;] read_only_fields = [&quot;order&quot;, &quot;price&quot;, &quot;to

## Question about hosting
 - [https://www.reddit.com/r/django/comments/1gdvy8q/question_about_hosting](https://www.reddit.com/r/django/comments/1gdvy8q/question_about_hosting)
 - RSS feed: $source
 - date published: 2024-10-28T06:55:23+00:00

<!-- SC_OFF --><div class="md"><p>Is there any good tutorial to learn hosting ?</p> <p>I want to host django website but i dont know where to host</p> <p>Things i wanna know - Where can i host which is cheap and great Vps vs shared hosting ? Which one to choose ? </p> <p>I just wanna host django website with a database which has secure lock emoji. SSL ig.</p> <p>My website will not be used for great needs or will have a lot of traffic, i just wanna learn.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/himynameisAhhhh"> /u/himynameisAhhhh </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdvy8q/question_about_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdvy8q/question_about_hosting/">[comments]</a></span>

## Should I go with Django or Firebase as a backend?
 - [https://www.reddit.com/r/django/comments/1gdvodc/should_i_go_with_django_or_firebase_as_a_backend](https://www.reddit.com/r/django/comments/1gdvodc/should_i_go_with_django_or_firebase_as_a_backend)
 - RSS feed: $source
 - date published: 2024-10-28T06:33:29+00:00

<!-- SC_OFF --><div class="md"><p>For context, I&#39;m working on a dating site with some adjustments to make it tailor-made for the local market. So far, I&#39;ve started writing the frontend UI (using React, though eventually I plan to also have mobile app implementations).</p> <p>I&#39;m already familiar with Django and have worked on a number of web apps with it so it would be my first option, and I&#39;ve not used Firebase before. But since I will need to include features like <strong>real-time messaging</strong>, <strong>push notifications</strong>, and <strong>Google Sign-in</strong>, I&#39;ve started wondering if Firebase might be a better option since it comes with those features already well-integrated. I&#39;ve implemented those three things in previous Django projects before and it was a bit of a hassle.</p> <p>So on the one hand, I think using Firebase as a backend would provide an easy setup which scales well, but I also have concerns about the security, vendor lock-in,

## Django REST framework project for managing product of e-commerce application
 - [https://www.reddit.com/r/django/comments/1gdtv66/django_rest_framework_project_for_managing](https://www.reddit.com/r/django/comments/1gdtv66/django_rest_framework_project_for_managing)
 - RSS feed: $source
 - date published: 2024-10-28T04:25:53+00:00

<!-- SC_OFF --><div class="md"><p>I created this Django project for an e-commerce project&#39;s product management a few months ago with the Django REST framework.</p> <p>If anyone wants to use it here is the link.<br/> <a href="https://github.com/abdulawalarif/ecommerce_backend_DRF">https://github.com/abdulawalarif/ecommerce_backend_DRF</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vegetable_Ad_2731"> /u/Vegetable_Ad_2731 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdtv66/django_rest_framework_project_for_managing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gdtv66/django_rest_framework_project_for_managing/">[comments]</a></span>

## 5 months ago i asked which course to start django with ,now what's my next step ?
 - [https://www.reddit.com/r/django/comments/1gdr3co/5_months_ago_i_asked_which_course_to_start_django](https://www.reddit.com/r/django/comments/1gdr3co/5_months_ago_i_asked_which_course_to_start_django)
 - RSS feed: $source
 - date published: 2024-10-28T01:48:33+00:00

<!-- SC_OFF --><div class="md"><p>Greetings,</p> <p>Five months ago, I created a post asking about how to start with Django. Months later, I completed a few courses, including a four-month ALX backend Django-focused course, and I made few basic API projects and few simple CRUD functionality projects using function-based views (FBV) and class-based views (CBV). Here’s one of my projects: <a href="https://github.com/Gamaljim/Fitness_dj_api">https://github.com/Gamaljim/Fitness_dj_api</a> (excuse the lack of a README or .gitignore file; I&#39;m still learning how to properly set up a repo).</p> <p>I&#39;m 30 years old, stuck in a dead-end job in a country I don&#39;t want to be in, and I&#39;m doing my best to study after work to shift my career and get back home as soon as possible. After finishing the course, I asked my instructor for feedback, and he said there’s still a lot to learn and that I’m not ready to apply for jobs yet. I understand this, but it did bring me down, and while I

## django-vite vs vite proxy server/bundling
 - [https://www.reddit.com/r/django/comments/1gdp50c/djangovite_vs_vite_proxy_serverbundling](https://www.reddit.com/r/django/comments/1gdp50c/djangovite_vs_vite_proxy_serverbundling)
 - RSS feed: $source
 - date published: 2024-10-28T00:08:13+00:00

<!-- SC_OFF --><div class="md"><p>There are 2 approaches to running react with Django using Vite.</p> <ol> <li>Vite Proxy server and bundling</li> </ol> <p>Using Vite you can run following vite proxy for dev server, and do bundling with html page in production server, and have the assets served by the django server itself.</p> <p>Proxy:</p> <p><code>server:</code><br/> <code>{</code><br/> <code>proxy: { &#39;/api&#39;: { target: &#39;http://127.0.0.1:8000&#39;, changeOrigin: true, secure: false, }, &#39;/admin&#39;: { target: &#39;http://127.0.0.1:8000&#39;, changeOrigin: true, secure: false, }</code></p> <ol> <li> django-vite plugin</li> </ol> <p>What does django-vite internally do, how it is different to the approach # 1?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/supercharger6"> /u/supercharger6 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gdp50c/djangovite_vs_vite_proxy_serverbundling/">[link]</a></span> &#32; <sp

