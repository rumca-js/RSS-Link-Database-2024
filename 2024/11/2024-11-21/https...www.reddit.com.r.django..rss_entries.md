# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## How do you handle speeding up frequent reads on aggregations without redundancy risks?
 - [https://www.reddit.com/r/django/comments/1gwt719/how_do_you_handle_speeding_up_frequent_reads_on](https://www.reddit.com/r/django/comments/1gwt719/how_do_you_handle_speeding_up_frequent_reads_on)
 - RSS feed: $source
 - date published: 2024-11-21T23:10:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve built an internal tool for Estimating, Inventory, Schedule &amp; Dispatch, Job Costing &amp; Reconciliation at a construction contractor business. We&#39;re using postgres. Now that much of the operational functionality is there with proper normalization, I&#39;m building out dashboards that do a lot of aggregation on deeply nested fields.</p> <p><strong>So the</strong> <em>(possibly misguided/skill issue?)</em> <strong>goal is to persist some aggregated values to distant parent model objects.</strong> <em>But the values can never be out of sync!</em></p> <p>I&#39;ve implemented the new <code>GeneratedField</code> with <code>db_persist=True</code> in a number of places, which just simplifies some things, but as I understand it I can&#39;t use a GeneratedField to sum a value on a child related model.</p> <p>So there&#39;s a few options I&#39;m aware of, and I&#39;m curious what you use in production environments where data validity and integr

## Converting Database Value to Label in HTML Template
 - [https://www.reddit.com/r/django/comments/1gws9vc/converting_database_value_to_label_in_html](https://www.reddit.com/r/django/comments/1gws9vc/converting_database_value_to_label_in_html)
 - RSS feed: $source
 - date published: 2024-11-21T22:29:32+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to using choices in Django models. I&#39;m currently running 4.2.16.</p> <p>Is there a shortcut to converting a database value from a models.TextChoices in the HTML template? Or do I have to do all that translation in views.py? Currently I have the following model defined:</p> <pre><code>class Device_Message_Event(models.Model): class Event_Type(models.TextChoices): T1 = 1, &#39;Text 1&#39; T2 = 2, &#39;Text 2&#39; T3 = 3, &#39;Text 3&#39; T4 = 4, &#39;Text 4&#39; class Origin(models.TextChoices): O1 = 1, &#39;Origin 1&#39; O2 = 2, &#39;Origin 2&#39; device = models.ForeignKey(Device, on_delete=models.CASCADE) created = models.DateTimeField(auto_now_add=True) event = models.IntegerField(choices=Event_Type.choices, default=1) origin = models.IntegerField(choices=Origin.choices, default=1) message_body = models.CharField(max_length=512) message_size = models.IntegerField(default=0) message_id = models.BigIntegerField(default=-1) </code></pr

## My first Pypi release of a django-oauth2-capture: Acquire OAuth2 tokens for your apps (not for authentication)
 - [https://www.reddit.com/r/django/comments/1gwr4dv/my_first_pypi_release_of_a_djangooauth2capture](https://www.reddit.com/r/django/comments/1gwr4dv/my_first_pypi_release_of_a_djangooauth2capture)
 - RSS feed: $source
 - date published: 2024-11-21T21:40:06+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/simplecto"> /u/simplecto </a> <br/> <span><a href="https://github.com/heysamtexas/django-oauth2-capture">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwr4dv/my_first_pypi_release_of_a_djangooauth2capture/">[comments]</a></span>

## Django ninja vs fast api
 - [https://www.reddit.com/r/django/comments/1gwr0ju/django_ninja_vs_fast_api](https://www.reddit.com/r/django/comments/1gwr0ju/django_ninja_vs_fast_api)
 - RSS feed: $source
 - date published: 2024-11-21T21:35:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi yall, I am a .net developer who is trynna get into backend development using python and I know django is the robust framework. Now I want to create a full stack web app and I want to built apis with either fastapi for Django’s ninja. Please tell me why should I use ninja over fast api? I know this is Django’s subreddit but please try to be less bias as possible, I would like pros/cons for each of them for educational purposes. P.S</p> <p>I do know python</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lovethem-tears994"> /u/Lovethem-tears994 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gwr0ju/django_ninja_vs_fast_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwr0ju/django_ninja_vs_fast_api/">[comments]</a></span>

## Why can't my app send errors to Sentry? (SSL Verify errors)
 - [https://www.reddit.com/r/django/comments/1gwq7wi/why_cant_my_app_send_errors_to_sentry_ssl_verify](https://www.reddit.com/r/django/comments/1gwq7wi/why_cant_my_app_send_errors_to_sentry_ssl_verify)
 - RSS feed: $source
 - date published: 2024-11-21T21:02:04+00:00

<!-- SC_OFF --><div class="md"><p>I recently decided to try Sentry as I was getting some random 500 errors and figured adding some tooling to my app was a good idea.</p> <p>It seemed like a basic enough setup. Install the SDK, setup the SDK init, and throw some errors and get details from the Sentry dashboard. That was like a week ago. So I&#39;ve been diving deeper into why this doesn&#39;t work (the irony huh?) and enabled <code>debug=True</code> in my init call so I can see the stack traces that are happening inside the SDK itself.</p> <p><code>urllib3.exceptions.MaxRetryError: HTTPSConnectionPool(host=&#39;xxxxxxxxxxxxxxxx.ingest.us.sentry.io&#39;, port=443):</code> <code>Max retries exceeded with url: /api/xxxxxxxxxxxxxx/envelope/</code> <code>(Caused by SSLError(SSLCertVerificationError(1, &#39;[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1006)&#39;)))</code></p> <p>I&#39;ve been going through versions of Python, ver

## Finished my first Django app! (But deployment is hell)
 - [https://www.reddit.com/r/django/comments/1gwly9h/finished_my_first_django_app_but_deployment_is](https://www.reddit.com/r/django/comments/1gwly9h/finished_my_first_django_app_but_deployment_is)
 - RSS feed: $source
 - date published: 2024-11-21T18:10:02+00:00

<!-- SC_OFF --><div class="md"><p>I just finished my first django app. A simple crm for my company. Developing it was an experience that makes me want to switch carrers into web app development. It’s been really really awesome. Sadly I can’t say the same thing about deploying the app. I’ve been trying to get it to work on and off without complete success.</p> <p>This is how my process looks like: Pull from repo -&gt; break gunicorn in various ways and spend half and hour figuring out what broke-&gt; get asked to change something -&gt; have fun modifying stuff in my development environment -&gt; pull from repo -&gt; break gunicorn in various ways and spend half and hour figuring out what broke-&gt; get asked to change something -&gt; have fun modifying stuff in my development environment -&gt; …</p> <p>Is it always like this or am I missing something?</p> <p>I am just a python/django enthusiast. I know about css and html, but I am not an engineer by any means.</p> <p>I really enjoy de

## Finally launched my portfolio with Django
 - [https://www.reddit.com/r/django/comments/1gwlx9o/finally_launched_my_portfolio_with_django](https://www.reddit.com/r/django/comments/1gwlx9o/finally_launched_my_portfolio_with_django)
 - RSS feed: $source
 - date published: 2024-11-21T18:08:54+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/0wec41h4pa2e1.png?width=1904&amp;format=png&amp;auto=webp&amp;s=0b06f10f26406892d7a7a85f02f0b3c334630595">https://preview.redd.it/0wec41h4pa2e1.png?width=1904&amp;format=png&amp;auto=webp&amp;s=0b06f10f26406892d7a7a85f02f0b3c334630595</a></p> <p>After years of working with Django, I always postponed building my own personal site. Recently, I decided it was time, and that’s how <a href="https://www.eriktaveras.com/">eriktaveras.com</a> came to life.</p> <h1>What’s included?</h1> <ul> <li><strong>Backend:</strong> Django to manage projects and a contact form with spam protection (<em>rate limiting</em> and content detection).</li> <li><strong>Frontend:</strong> Tailwind CSS for a clean design and Alpine.js for light interactivity.</li> <li><strong>Extras:</strong> Automatic Telegram notifications whenever someone submits the contact form.</li> </ul> <p>I’m also working on adding a blog and still uploading more projects 

## Django as a pure API layer?
 - [https://www.reddit.com/r/django/comments/1gwkt0d/django_as_a_pure_api_layer](https://www.reddit.com/r/django/comments/1gwkt0d/django_as_a_pure_api_layer)
 - RSS feed: $source
 - date published: 2024-11-21T17:26:16+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, </p> <p>I have a real beginner question here, because I am barely familiar with Django even though I wanted to learn it in the past.</p> <p>I&#39;m building a webapp for my University, and I originally planned to build it in React (since I am more familiar with it and it looks great with my Tailwind components). Usually I use Google Cloud Functions together with Firebase as the backend by having a duct-tape API in GCS.</p> <p>But I spoke to one of the IT guys today, and he recommends that I rather use Django to build the new app in. He says that the university does have hosting options, and they can provision a VM for me that runs Debian, so I can basically Dockerize and run my tool without the cost issue (which usually dictates my decisions in Cloud).</p> <p>So suddenly the downside of a SQL database being more expensive than a no-SQL database is eliminated, because the university is paying for the server to be run regardless.</p> <p>S

## 2024 Django Developers Survey
 - [https://www.reddit.com/r/django/comments/1gwkk9t/2024_django_developers_survey](https://www.reddit.com/r/django/comments/1gwkk9t/2024_django_developers_survey)
 - RSS feed: $source
 - date published: 2024-11-21T17:16:50+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2024/nov/21/2024-django-developers-survey/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwkk9t/2024_django_developers_survey/">[comments]</a></span>

## Django Developers Survey 2024
 - [https://www.reddit.com/r/django/comments/1gwkewu/django_developers_survey_2024](https://www.reddit.com/r/django/comments/1gwkewu/django_developers_survey_2024)
 - RSS feed: $source
 - date published: 2024-11-21T17:11:14+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/thibaudcolas"> /u/thibaudcolas </a> <br/> <span><a href="https://jb.gg/asjljo">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwkewu/django_developers_survey_2024/">[comments]</a></span>

## (fields.E005) 'choices' must be an iterable
 - [https://www.reddit.com/r/django/comments/1gwjc6l/fieldse005_choices_must_be_an_iterable](https://www.reddit.com/r/django/comments/1gwjc6l/fieldse005_choices_must_be_an_iterable)
 - RSS feed: $source
 - date published: 2024-11-21T16:28:56+00:00

<!-- SC_OFF --><div class="md"><p>Is there a mistake in the Django documentation regarding choices for Fields? When I run their specific example:</p> <pre><code>from django.db import models class Student(models.Model): FRESHMAN = &quot;FR&quot; SOPHOMORE = &quot;SO&quot; JUNIOR = &quot;JR&quot; SENIOR = &quot;SR&quot; GRADUATE = &quot;GR&quot; YEAR_IN_SCHOOL_CHOICES = { FRESHMAN: &quot;Freshman&quot;, SOPHOMORE: &quot;Sophomore&quot;, JUNIOR: &quot;Junior&quot;, SENIOR: &quot;Senior&quot;, GRADUATE: &quot;Graduate&quot;, } year_in_school = models.CharField( max_length=2, choices=YEAR_IN_SCHOOL_CHOICES, default=FRESHMAN, ) def is_upperclass(self): return self.year_in_school in {self.JUNIOR, self.SENIOR} </code></pre> <p>I get the following error: Student.year_in_school: (fields.E005) &#39;choices&#39; must be an iterable containing (actual value, human readable name) tuples.</p> <p>If I change to:</p> <pre><code>class Student(models.Model): FRESHMAN = &quot;FR&quot; SOPHOMORE = &quot;

## How much can I expect out of Postgres full text search?
 - [https://www.reddit.com/r/django/comments/1gwfdf7/how_much_can_i_expect_out_of_postgres_full_text](https://www.reddit.com/r/django/comments/1gwfdf7/how_much_can_i_expect_out_of_postgres_full_text)
 - RSS feed: $source
 - date published: 2024-11-21T12:42:45+00:00

<!-- SC_OFF --><div class="md"><p>I’m making a niche search engine. So far around 500k web pages in the db.</p> <p>Searching it is slow, sometimes times out.</p> <p>Using an azure managed Postgres db on the 2nd lowest plan - 2vcpu </p> <p>What can I reasonably expect out of Postgres? </p> <p>Or do I need to go with something like Melisearch from the start?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/painthack"> /u/painthack </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gwfdf7/how_much_can_i_expect_out_of_postgres_full_text/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwfdf7/how_much_can_i_expect_out_of_postgres_full_text/">[comments]</a></span>

## Multiple sites one database
 - [https://www.reddit.com/r/django/comments/1gwe9lh/multiple_sites_one_database](https://www.reddit.com/r/django/comments/1gwe9lh/multiple_sites_one_database)
 - RSS feed: $source
 - date published: 2024-11-21T11:39:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m creating a django project with multiple sites for different retailers. They&#39;ll all follow the same database schema. I need a way to have multiple domains each with their own separate values in the database and also values that must be aggregrated across all the sites for that shouldn&#39;t be viewable in the views for the sites but only in one main site that I specify.</p> <p>I&#39;m thinking of using django-tenants to achieve this, do I also need to use django sites framework to achieve the view routing?</p> <p>Is there any better way of accomplishing this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legitimate_Trade_285"> /u/Legitimate_Trade_285 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gwe9lh/multiple_sites_one_database/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwe9lh/multiple_sites_one_database/">[comments]</a></span>

## Celery picks up new tasks, but all old are stuck in PENDING
 - [https://www.reddit.com/r/django/comments/1gwdv3s/celery_picks_up_new_tasks_but_all_old_are_stuck](https://www.reddit.com/r/django/comments/1gwdv3s/celery_picks_up_new_tasks_but_all_old_are_stuck)
 - RSS feed: $source
 - date published: 2024-11-21T11:12:45+00:00

<!-- SC_OFF --><div class="md"><p>In a nutshell when I put new task to the queue, Celery processes and finishes it, but the old tasks are constantly pending.</p> <p>I ran celery a couple of times and everything was good, but now I constantly see some old tasks as &quot;PENDING&quot; state when I read their state in Django with <code>AsyncState(task_id).</code></p> <p>I&#39;m using Celery 5.4.0 and redis-server 7.4.1 on WSL (Windows Linux)</p> <p>The celery and Django app runs on windows and the redis-server in WSL.</p> <p>I run celery with: <code>celery -A config.celery_app worker --pool=solo --loglevel=info</code></p> <p>Purging the queue with <code>celery -A config.celery_app purge</code> didn&#39;t make anything either.</p> <p>I think the problem might started appearing after closing a celery worker (could been forcefully), but anyway I&#39;d like to get to bottom of this why this might be happening and how to fix this (I know probably reinstalling redis or celery could do the tri

## High CPU Usage with Gunicorn in Docker
 - [https://www.reddit.com/r/django/comments/1gwd0ym/high_cpu_usage_with_gunicorn_in_docker](https://www.reddit.com/r/django/comments/1gwd0ym/high_cpu_usage_with_gunicorn_in_docker)
 - RSS feed: $source
 - date published: 2024-11-21T10:14:38+00:00

<!-- SC_OFF --><div class="md"><p>Hello, </p> <p>We are running a Django application on an RHEL 9 server with the following specs:</p> <ul> <li><strong>6 CPU Cores</strong></li> <li><strong>12 GB RAM</strong></li> <li><strong>200 GB Storage</strong></li> </ul> <p>Our setup involves Docker to run the Django application, and we use Apache as a reverse proxy. The <a href="http://entrypoint.sh"><code>entrypoint.sh</code></a> file for the container is:</p> <pre><code>exec gunicorn --bind 0.0.0.0:${PORT:-8000} --timeout 300 -w 2 -k gevent ecommapp.wsgi:application </code></pre> <p><strong>Problem:</strong></p> <ul> <li>For some pages, <code>docker stats</code> shows <strong>100%+ CPU usage</strong> for the Django container.</li> <li>Running <code>top</code> inside the container reveals two Gunicorn instances consuming high CPU.</li> <li>During these spikes, we intermittently face <strong>500 Internal Server Errors</strong>.</li> </ul> <p><strong>Our Django version:</strong> 4.2<br/> <stron

## Announcing the 6.x Steering Council elections 🚀
 - [https://www.reddit.com/r/django/comments/1gwb9cj/announcing_the_6x_steering_council_elections](https://www.reddit.com/r/django/comments/1gwb9cj/announcing_the_6x_steering_council_elections)
 - RSS feed: $source
 - date published: 2024-11-21T08:02:47+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2024/nov/21/announcing-the-6x-steering-council-elections/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwb9cj/announcing_the_6x_steering_council_elections/">[comments]</a></span>

## Announcing the 6.x Steering Council elections 🚀
 - [https://www.reddit.com/r/django/comments/1gwb8ae/announcing_the_6x_steering_council_elections](https://www.reddit.com/r/django/comments/1gwb8ae/announcing_the_6x_steering_council_elections)
 - RSS feed: $source
 - date published: 2024-11-21T08:00:47+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/thibaudcolas"> /u/thibaudcolas </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2024/nov/21/announcing-the-6x-steering-council-elections/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwb8ae/announcing_the_6x_steering_council_elections/">[comments]</a></span>

## Tips to morph Internal DRF App into Multi Tenant SaaS Setup
 - [https://www.reddit.com/r/django/comments/1gwaw56/tips_to_morph_internal_drf_app_into_multi_tenant](https://www.reddit.com/r/django/comments/1gwaw56/tips_to_morph_internal_drf_app_into_multi_tenant)
 - RSS feed: $source
 - date published: 2024-11-21T07:35:38+00:00

<!-- SC_OFF --><div class="md"><p>Dear community, I learned A TON over the last months from all the posts and great answers here.</p> <p>My small team and I built a small django react app using DRF, PostgreSQL, Redis, Celery and minio.</p> <p>Currently we have to manage a lot manually in the classic Django admin Dashboard.</p> <p>Now we want to make it possible to onboard new clients to the app and thus we need to implement the kind of multi tenancy (sure Django Tenants) and some kind of SaaS settings including logic to enable user-admins to make setting, data and user changes themselves.</p> <p>Sure we tried to set it up, but I am highly interested in your suggestions for good guides, best practices and tips to do so.</p> <p>Happy to answer your questions if more details are required! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MikeHHHH99"> /u/MikeHHHH99 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gwaw56/tips_to_mor

## React+DRF or NextJS+DRF
 - [https://www.reddit.com/r/django/comments/1gwanlr/reactdrf_or_nextjsdrf](https://www.reddit.com/r/django/comments/1gwanlr/reactdrf_or_nextjsdrf)
 - RSS feed: $source
 - date published: 2024-11-21T07:18:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,I am working in django+drd last 1.5 years. I would like to start learn front end framework and become full stack web developer.please tell me your thoughts about this, which one I need start to learn. Nd also tell me which library components is best for both. Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/prabhuk786"> /u/prabhuk786 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gwanlr/reactdrf_or_nextjsdrf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwanlr/reactdrf_or_nextjsdrf/">[comments]</a></span>

## Should I Learn a New Tech or Start Applying?
 - [https://www.reddit.com/r/django/comments/1gw81a7/should_i_learn_a_new_tech_or_start_applying](https://www.reddit.com/r/django/comments/1gw81a7/should_i_learn_a_new_tech_or_start_applying)
 - RSS feed: $source
 - date published: 2024-11-21T04:35:23+00:00

<!-- SC_OFF --><div class="md"><p>Hello folks,</p> <p>I&#39;ve been working with Django for the past 3 months and have hands-on experience in Machine Learning, Computer Vision, and other AI-related projects. I&#39;m pretty confident in Python and have completed two remote internships, each lasting 2 months.</p> <p>I&#39;m aiming for a decent package of around 5-6 LPA, but I&#39;m at a crossroads: 1)Should I learn a different technology (like Node.js, since many job postings mention it), or is Django enough? 2)Should I start applying for jobs now or focus on adding more skills to match industry demands?</p> <p>Also, can you suggest platforms or places where I can find Django-related job opportunities? Most openings I come across seem to require JavaScript or Node.js expertise.</p> <p>Thank you in advance for your advice!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Outrageous_Story_666"> /u/Outrageous_Story_666 </a> <br/> <span><a href="https:

## dtebar.pythonanywhere.com
 - [https://www.reddit.com/r/django/comments/1gw4iy4/dtebarpythonanywherecom](https://www.reddit.com/r/django/comments/1gw4iy4/dtebarpythonanywherecom)
 - RSS feed: $source
 - date published: 2024-11-21T01:38:04+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/q19j5zdas52e1.jpg?width=1488&amp;format=pjpg&amp;auto=webp&amp;s=c988e4de7bc91773e620c7a213ae437479b18dc6">https://preview.redd.it/q19j5zdas52e1.jpg?width=1488&amp;format=pjpg&amp;auto=webp&amp;s=c988e4de7bc91773e620c7a213ae437479b18dc6</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dtebar_nyc"> /u/dtebar_nyc </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gw4iy4/dtebarpythonanywherecom/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gw4iy4/dtebarpythonanywherecom/">[comments]</a></span>

## Safe way to append to a remote txt file
 - [https://www.reddit.com/r/django/comments/1gw3bp7/safe_way_to_append_to_a_remote_txt_file](https://www.reddit.com/r/django/comments/1gw3bp7/safe_way_to_append_to_a_remote_txt_file)
 - RSS feed: $source
 - date published: 2024-11-21T00:42:46+00:00

<!-- SC_OFF --><div class="md"><p>Folks,</p> <p>If I need to append to a remote txt file, is there a way to &quot;safely&quot; do this in Django? The servers Django is on and the remote txt file are on the same vlan so they can talk to each other without issues. Values I&#39;m appending are generated from a Django process</p> <p>I also intend to have a process that runs maybe once every month or so to prune the same text file.</p> <p>What are reliable ways to do this in Django? The file always need to exist and I can risk a bad file. Is Django a suitable approach for this? </p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cyberdot14"> /u/cyberdot14 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gw3bp7/safe_way_to_append_to_a_remote_txt_file/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gw3bp7/safe_way_to_append_to_a_remote_txt_file/">[comments]</a></span>

