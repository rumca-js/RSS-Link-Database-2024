# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Help with Django ModelForm
 - [https://www.reddit.com/r/django/comments/1fz9gem/help_with_django_modelform](https://www.reddit.com/r/django/comments/1fz9gem/help_with_django_modelform)
 - RSS feed: $source
 - date published: 2024-10-08T20:16:20+00:00

<!-- SC_OFF --><div class="md"><p>I need help with Django ModelForm</p> <h1>Models.py</h1> <p>from django.db import models</p> <p>class SignUp(models.Model):</p> <pre><code>GENDER_CHOICES = [ (&#39;M&#39;, &#39;Male&#39;), (&#39;F&#39;, &#39;Female&#39;), (&#39;O&#39;, &#39;Other&#39;), ] full_name = models.CharField(max_length=100) email = models.EmailField(unique=True) location = models.CharField(max_length=100) phone = models.CharField(max_length=15) gender = models.CharField(max_length=1, choices=GENDER_CHOICES) def __str__(self): return self.full_name </code></pre> <h1>Forms.py</h1> <p>from django import forms from .models import SignUp</p> <p>class SignUpForm(forms.ModelForm):</p> <pre><code>class Meta: model = SignUp fields = [&#39;full_name&#39;, &#39;email&#39;, &#39;location&#39;, &#39;phone&#39;, &#39;gender&#39;] widgets = { &#39;full_name&#39;: forms.TextInput(attrs={&#39;class&#39;: &#39;form-control&#39;}), &#39;email&#39;: forms.EmailInput(attrs={&#39;class&#39;: &#39;

## I am at my wits end. Why is Foreign Key Integrity Error thrown when no Foreign key is ever set?
 - [https://www.reddit.com/r/django/comments/1fz5odb/i_am_at_my_wits_end_why_is_foreign_key_integrity](https://www.reddit.com/r/django/comments/1fz5odb/i_am_at_my_wits_end_why_is_foreign_key_integrity)
 - RSS feed: $source
 - date published: 2024-10-08T17:37:51+00:00

<!-- SC_OFF --><div class="md"><p>I have these three models:</p> <pre><code>class Club (models.Model): number = models.IntegerField() title = models.CharField(max_length=100) NaID = models.ForeignKey( &quot;National_Association&quot;, on_delete=models.PROTECT, blank=False ) members = models.ManyToManyField(User, through=&quot;Member_In&quot;, related_name=&quot;club_members&quot;) functionaries = models.ManyToManyField(User, through=&quot;Function_In&quot;, related_name=&quot;club_functionaries&quot;) def __str__(self): return str(self.number) + &quot; / &quot; + self.title class National_Association (models.Model): title = models.CharField(max_length=100) abbreviation = models.CharField(max_length=50) def __str__(self): return self.title class User(AbstractUser): &quot;&quot;&quot; Custom KEZ User supporting email authentication instead of username &quot;&quot;&quot; email = models.EmailField(unique=True, null=False, blank=False) username = None first_name = models.CharField(max_leng

## Landing pages with different domains
 - [https://www.reddit.com/r/django/comments/1fz5lac/landing_pages_with_different_domains](https://www.reddit.com/r/django/comments/1fz5lac/landing_pages_with_different_domains)
 - RSS feed: $source
 - date published: 2024-10-08T17:34:17+00:00

<!-- SC_OFF --><div class="md"><p>Not sure how to go about this, but I want landing pages with different domains on the same app. I want to be able to add or delete landing pages each with its own domain with specific content - there are hundreds of landing pages. Most of it seems straightforward but my main question is about SSL for each domain. How would that work? I am using digital ocean (app flatform or VPS, not sure which yet) and have used Let Encrypt cert bot before but only for a single domain and VPS. Just wondering if there is a way to do it automatically without updating nginx server block or something like that.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AttractiveCorpse"> /u/AttractiveCorpse </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fz5lac/landing_pages_with_different_domains/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fz5lac/landing_pages_with_different_domains/"

## Is Django can support on python 3.13 ?
 - [https://www.reddit.com/r/django/comments/1fz2et4/is_django_can_support_on_python_313](https://www.reddit.com/r/django/comments/1fz2et4/is_django_can_support_on_python_313)
 - RSS feed: $source
 - date published: 2024-10-08T15:22:36+00:00

<!-- SC_OFF --><div class="md"><p>Python with new J.I.T complier and removed GIL will improve django performance??? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shaheen-vsa"> /u/shaheen-vsa </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fz2et4/is_django_can_support_on_python_313/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fz2et4/is_django_can_support_on_python_313/">[comments]</a></span>

## Django bugfix release issued: 5.1.2
 - [https://www.reddit.com/r/django/comments/1fz1xdr/django_bugfix_release_issued_512](https://www.reddit.com/r/django/comments/1fz1xdr/django_bugfix_release_issued_512)
 - RSS feed: $source
 - date published: 2024-10-08T15:02:25+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2024/oct/08/bugfix-releases/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fz1xdr/django_bugfix_release_issued_512/">[comments]</a></span>

## Beginner's Guide for Django Deployment
 - [https://www.reddit.com/r/django/comments/1fz1t5d/beginners_guide_for_django_deployment](https://www.reddit.com/r/django/comments/1fz1t5d/beginners_guide_for_django_deployment)
 - RSS feed: $source
 - date published: 2024-10-08T14:57:37+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>I&#39;ve noticed beginners struggling with Django deployment, so I wanted to share this free and open-source guide. It is beginner-friendly, explains the process clearly, and helps you get your project deployed quickly.</p> <p>Any contributions are welcome from the community to improve this guide. If you find it useful, please consider giving the GitHub repo a star ⭐ (it helps a lot!)</p> <p>Link: <a href="https://bhavya-tech.github.io/django-deployment/">Beginner&#39;s Guide for Django Deployment</a></p> <p>Feel free to ask questions here, I will be happy to help!</p> <p>Happy coding!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Haunting_Ad_8730"> /u/Haunting_Ad_8730 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fz1t5d/beginners_guide_for_django_deployment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fz1t5d/beginners_guide_for_django_

## Interviewed for a Backend Role, Ended Up Being for an ERP Role – Confused About the Future Path
 - [https://www.reddit.com/r/django/comments/1fz0imx/interviewed_for_a_backend_role_ended_up_being_for](https://www.reddit.com/r/django/comments/1fz0imx/interviewed_for_a_backend_role_ended_up_being_for)
 - RSS feed: $source
 - date published: 2024-10-08T14:01:36+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I recently had an interview where I was asked questions related to core Python, SQL, and my internship experience. I went into it thinking that it was for a backend Django developer role. To my surprise, they didn’t ask a single question related to Django.</p> <p>So at the end of the interview, I decided to clarify and asked if this was for a backend developer position. They responded that the role was actually for a <em>Custom ERP</em> position, where they need someone with good knowledge of Python and experience dealing with clients. I had no idea what ERP was at that point, and I was honest with them about it. They reassured me that they would train me in this area.</p> <p>Fast forward to today – I got a call saying that I passed the interview and that the final round will be with the founder next week.</p> <p>Here’s where I’m conflicted: I’m a fresher and don’t really have any experience with ERPs, nor do I feel particularly e

## Third-Party Authentication Integration for Enterprise Users in Django SaaS Application
 - [https://www.reddit.com/r/django/comments/1fyy0n4/thirdparty_authentication_integration_for](https://www.reddit.com/r/django/comments/1fyy0n4/thirdparty_authentication_integration_for)
 - RSS feed: $source
 - date published: 2024-10-08T11:59:29+00:00

<!-- SC_OFF --><div class="md"><p>I have been maintaining a Django-based SaaS application for several years, and we now have several hundred users. Recently, we were approached by a company that wants to give all its employees access to our application through their intranet. This means user accounts will be managed by the company itself. They haven’t provided a specific authentication protocol, stating they can adapt to our requirements if needed.</p> <p>My challenge is to integrate a third-party authentication service for this enterprise in a way that restricts the created and deleted user accounts to a defined group and/or set of permissions. We already have the ability to associate users with specific teams if necessary.</p> <p>I would like the chosen solution to be as agnostic as possible, so that it could be easily extended to other enterprises should they request similar functionality, and ideally, it should require minimal configuration.</p> <p>What would be the best approach 

## I just wanna tell you guys that I did it!
 - [https://www.reddit.com/r/django/comments/1fywr26/i_just_wanna_tell_you_guys_that_i_did_it](https://www.reddit.com/r/django/comments/1fywr26/i_just_wanna_tell_you_guys_that_i_did_it)
 - RSS feed: $source
 - date published: 2024-10-08T10:43:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m sorry oif this is not the right space but I didn&#39;t have someone to share this and would actually understand my happiness.</p> <p>I was finally able to deploy my Django application on Digital Ocean with Postgres, Nginx, and Gunicorn on its Ubuntu machine. I also pointed my domain to the IP and set up the SSL certification. This took me days and I had to destroy the machine multiple times. Oh I also configured redis and celery with different workers. </p> <p>I&#39;m so hyped 😂😂</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_BigOle"> /u/_BigOle </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fywr26/i_just_wanna_tell_you_guys_that_i_did_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fywr26/i_just_wanna_tell_you_guys_that_i_did_it/">[comments]</a></span>

## Roadmap for being Django Developer
 - [https://www.reddit.com/r/django/comments/1fywp29/roadmap_for_being_django_developer](https://www.reddit.com/r/django/comments/1fywp29/roadmap_for_being_django_developer)
 - RSS feed: $source
 - date published: 2024-10-08T10:39:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a React/Next.js frontend developer looking to expand my skills into full-stack development. I&#39;m particularly interested in building AI-powered web applications, and I have an exciting idea that requires both strong backend and AI expertise. To achieve this, I want to learn Python and Django for backend development, especially for creating REST APIs to integrate with my React apps. However, after exploring various resources, I&#39;m feeling a bit overwhelmed and confused about where to start.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sure-Raspberry116"> /u/Sure-Raspberry116 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fywp29/roadmap_for_being_django_developer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fywp29/roadmap_for_being_django_developer/">[comments]</a></span>

## Développeurs, comment vous gérez les bots malveillants ? (Besoin de vos retours sur ma solution anti-bot)
 - [https://www.reddit.com/r/django/comments/1fywkhd/développeurs_comment_vous_gérez_les_bots](https://www.reddit.com/r/django/comments/1fywkhd/développeurs_comment_vous_gérez_les_bots)
 - RSS feed: $source
 - date published: 2024-10-08T10:30:38+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/EasePsychological789"> /u/EasePsychological789 </a> <br/> <span><a href="/r/developpeurs/comments/1fyvzfv/développeurs_comment_vous_gérez_les_bots/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fywkhd/développeurs_comment_vous_gérez_les_bots/">[comments]</a></span>

## How to integrate TensorFlow into django?
 - [https://www.reddit.com/r/django/comments/1fywfj2/how_to_integrate_tensorflow_into_django](https://www.reddit.com/r/django/comments/1fywfj2/how_to_integrate_tensorflow_into_django)
 - RSS feed: $source
 - date published: 2024-10-08T10:21:14+00:00

<!-- SC_OFF --><div class="md"><p>&quot;I have been searching for guidance on integrating TensorFlow into Django, but I haven&#39;t found any clear resources. I have a project that involves using a convolutional neural network (CNN) in TensorFlow and deploying it as a Django web application. I would appreciate any assistance you can provide.&quot;</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Outside_Department21"> /u/Outside_Department21 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fywfj2/how_to_integrate_tensorflow_into_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fywfj2/how_to_integrate_tensorflow_into_django/">[comments]</a></span>

## Working with django logger
 - [https://www.reddit.com/r/django/comments/1fyw1fh/working_with_django_logger](https://www.reddit.com/r/django/comments/1fyw1fh/working_with_django_logger)
 - RSS feed: $source
 - date published: 2024-10-08T09:53:14+00:00

<!-- SC_OFF --><div class="md"><p>I am working with the django logger with my logger config</p> <pre><code>LOG_DIR = BASE_DIR / &quot;logs&quot; os.makedirs(LOG_DIR, exist_ok=True) LOGGER = { &quot;version&quot;: 1, &quot;disable_existing_loggers&quot;: False, &quot;formatters&quot;: { &quot;verbose&quot;: { &quot;format&quot;: &quot;{levelname} {asctime} {module} {process:d} {thread:d} {message}&quot;, &quot;style&quot;: &quot;{&quot;, }, &quot;simple&quot;: { &quot;format&quot;: &quot;{levelname} {asctime} {message}&quot;, &quot;style&quot;: &quot;{&quot;, }, }, &quot;filters&quot;: {&quot;()&quot;: &quot;django.utils.log.RequireDebugTrue&quot;}, &quot;handlers&quot;: { &quot;console&quot;: { &quot;level&quot;: &quot;INFO&quot;, &quot;filters&quot;: [&quot;require_debug_true&quot;], &quot;class&quot;: &quot;logging.StreamHandler&quot;, &quot;formatter&quot;: &quot;verbose&quot;, }, &quot;file&quot;: { &quot;level&quot;: &quot;DEBUG&quot;, &quot;class&quot;: &quot;logging.handlers.Ro

## I Just created python and Django course for beginners with real world projects
 - [https://www.reddit.com/r/django/comments/1fyvjje/i_just_created_python_and_django_course_for](https://www.reddit.com/r/django/comments/1fyvjje/i_just_created_python_and_django_course_for)
 - RSS feed: $source
 - date published: 2024-10-08T09:15:25+00:00

<!-- SC_OFF --><div class="md"><p>I’ve recently launched a Python and Django course where learners can dive into real-world projects and build practical skills. I’ve put a lot of work into it because I’m passionate about helping others grow in their coding journey. I’ve made it super affordable too – just <strong>₹399</strong> with my coupon <strong>BYTEWISE400</strong>.</p> <p>If you’re someone who’s been wanting, or if you know anyone who could benefit from this, enrolling would mean the world to me. It’s not just about the course – it’s about supporting to help more people break into tech with practical, hands-on learning. 🚀</p> <p>I’d be incredibly grateful for any support, whether it’s enrolling, sharing the course, or even just sending some good vibes my way!</p> <p><a href="https://www.udemy.com/course/30-days-of-code-learn-python-and-django-with-projects/?couponCode=BYTEWISE400">Check it out here</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit

## Help me find out if Django is the right Choice
 - [https://www.reddit.com/r/django/comments/1fyuyik/help_me_find_out_if_django_is_the_right_choice](https://www.reddit.com/r/django/comments/1fyuyik/help_me_find_out_if_django_is_the_right_choice)
 - RSS feed: $source
 - date published: 2024-10-08T08:30:02+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 😊</p> <p>I&#39;m looking to create a web-based workspace environment and was wondering if this is something I could build using Django.</p> <h1>Overview:</h1> <ul> <li><strong>Platform</strong>: Web-based</li> <li><strong>Users</strong>: Starting with around 10+, potentially scaling to 500 per deployment in the future.</li> <li><strong>Inspiration</strong>: I saw something like this in a small company, and it was fantastic to use! Sadly, I don&#39;t know what language they used.</li> </ul> <h1>Concept:</h1> <p>Imagine a workspace with a taskbar, similar to Windows. From there, users can access various apps. Each app opens in its own window <strong>within the main browser window</strong>, which you can move, resize, minimize, or maximize. Crucially, these settings (e.g., window positions and sizes) should be saved directly to the user account—not just in the browser. The goal is to have a fully interactive desktop-like experience within t

## Background emails
 - [https://www.reddit.com/r/django/comments/1fytux2/background_emails](https://www.reddit.com/r/django/comments/1fytux2/background_emails)
 - RSS feed: $source
 - date published: 2024-10-08T07:03:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi, </p> <p>I would be integrating with an email provider like brevo to send emails to my users.</p> <p>I will save the timezone of the user when they register.</p> <p>I want to run a background task/s that goes over the database, computes whether a condition is met from my models and send users email given it is met, at the required time which is different for each user according to their timezone.</p> <p>Which technology seems best to do it and how?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Scared-Stage-3200"> /u/Scared-Stage-3200 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fytux2/background_emails/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fytux2/background_emails/">[comments]</a></span>

## 80% of a fancy SPA in 21 lines of code
 - [https://www.reddit.com/r/django/comments/1fyt2t3/80_of_a_fancy_spa_in_21_lines_of_code](https://www.reddit.com/r/django/comments/1fyt2t3/80_of_a_fancy_spa_in_21_lines_of_code)
 - RSS feed: $source
 - date published: 2024-10-08T06:05:21+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://kodare.net/2024/10/08/restore-scroll.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fyt2t3/80_of_a_fancy_spa_in_21_lines_of_code/">[comments]</a></span>

## I love Django! I don't use any third party django extensions, am I missing out?
 - [https://www.reddit.com/r/django/comments/1fyspu3/i_love_django_i_dont_use_any_third_party_django](https://www.reddit.com/r/django/comments/1fyspu3/i_love_django_i_dont_use_any_third_party_django)
 - RSS feed: $source
 - date published: 2024-10-08T05:40:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,<br/> Django has been really good lately for the different applications I use. Beyond the code, even the philosophy of Django has helped me structured my thinking. I also started using Cookie Cutter, that stuff is awesome. I have been tempted to use certain django extensions such as Django Markdown (for supporting markdown) and Django Ledger (for accounting stuff I knew now much about). </p> <p>In the end, I didn&#39;t implement neither because I found alternative solutions. I would really love hearing from the community?<br/> 1. Do you stand by any specific django extensions that you use in your projects?<br/> 2. How is your experience like as a someone who contributes to extensions?<br/> 3. What were some of your negative experiences with extensions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MikeDoesDo"> /u/MikeDoesDo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fyspu

## Replaced psycopg2 with psycopg2-binary and now my runserver ain't working
 - [https://www.reddit.com/r/django/comments/1fyscif/replaced_psycopg2_with_psycopg2binary_and_now_my](https://www.reddit.com/r/django/comments/1fyscif/replaced_psycopg2_with_psycopg2binary_and_now_my)
 - RSS feed: $source
 - date published: 2024-10-08T05:14:22+00:00

<!-- SC_OFF --><div class="md"><p>I am currently working on a school project and we are using Django as our framework and I decided to use PostgreSQL as my database. I am currently using Railway as a provider of my database. Currently we are working on deploying the project through Vercel, and based on the tutorials I have watched, psycopg2 doesn&#39;t work on Vercel and we need to use psycopg2-binary. I did those changes and successfully deployed our project on Vercel. Now I am trying to work on the project again locally, through the runserver command and I am now having issues with running the server. It says that &quot;<em>django.core.exceptions.ImproperlyConfigured: Error loading psycopg2 or psycopg module.&quot;</em> Hopefully you guys could help me fix this problem. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Active_Mulberry3534"> /u/Active_Mulberry3534 </a> <br/> <span><a href="https://www.reddit.com/r/django/comment

## Install a Second Instance of Nginx via Docker.
 - [https://www.reddit.com/r/django/comments/1fyphsj/install_a_second_instance_of_nginx_via_docker](https://www.reddit.com/r/django/comments/1fyphsj/install_a_second_instance_of_nginx_via_docker)
 - RSS feed: $source
 - date published: 2024-10-08T02:28:37+00:00

<!-- SC_OFF --><div class="md"><p>Excited to share my latest article on Installing a Second Instance of Nginx via Docker!</p> <p><a href="https://medium.com/@darwishdev.com/install-a-second-instance-of-nginx-via-docker-384e379f018e">https://medium.com/@darwishdev.com/install-a-second-instance-of-nginx-via-docker-384e379f018e</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/darwishdev"> /u/darwishdev </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fyphsj/install_a_second_instance_of_nginx_via_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fyphsj/install_a_second_instance_of_nginx_via_docker/">[comments]</a></span>

## Just Released Version 0.5.0 of Django Action Triggers!
 - [https://www.reddit.com/r/django/comments/1fyn1vo/just_released_version_050_of_django_action](https://www.reddit.com/r/django/comments/1fyn1vo/just_released_version_050_of_django_action)
 - RSS feed: $source
 - date published: 2024-10-08T00:24:43+00:00

<!-- SC_OFF --><div class="md"><p>First off, a huge thank you to everyone who provided feedback after the release of version 0.1.0! I&#39;ve taken your input to heart and have been hard at work iterating and improving this tool. I’m excited to announce the release of <strong>version 0.5.0</strong> of <strong>django-action-triggers</strong>.</p> <p>There’s still more to come in terms of features and addressing suggestions, but here’s an overview of the current progress.</p> <h1>What is Django Action Triggers</h1> <p><a href="https://github.com/Salaah01/django-action-triggers">Django Action Triggers</a> is a Django library that lets you trigger specific actions based on database events, detected via Django Signals. With this library, you can configure <strong>actions</strong> that run asynchronously when certain triggers (e.g., a model save) are detected.</p> <p>For example, you could set up a trigger that hits a webhook and sends a message to AWS SQS whenever a new sale record is saved

