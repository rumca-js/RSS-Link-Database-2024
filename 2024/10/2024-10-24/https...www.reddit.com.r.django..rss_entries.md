# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Building an AI framework with Django. KitchenAI
 - [https://www.reddit.com/r/django/comments/1gbfqvc/building_an_ai_framework_with_django_kitchenai](https://www.reddit.com/r/django/comments/1gbfqvc/building_an_ai_framework_with_django_kitchenai)
 - RSS feed: $source
 - date published: 2024-10-24T22:53:14+00:00

<!-- SC_OFF --><div class="md"><p>The goal of this project is to give AI developers doing all these advanced RAG techniques a way to author shareable and production ready code instantly by removing a lot of the HTTP layer semantics. This will help bridge the gap between Application devs and the exploding complexity in production ready AI apps. </p> <p>I chose Django because it&#39;s so dang robust and extensible. I can see a future where authors can install django apps that really compliment perfectly into their AI workflow.</p> <p>Some neat Django features </p> <p>* Django async with gunicorn + uvicorn<br/> * Django ninja for dynamic routes<br/> * Django q2 for background workers</p> <p>* S6 overlay for running the qclusters and server in the same container </p> <p>* Tailwind + htmx + daisyui</p> <p>I didn&#39;t start from scratch so I def want to acknowledge the author of Falco and using <a href="https://github.com/falcopackages/falco">https://github.com/falcopackages/falco</a> as 

## Flexible multi/single tenant
 - [https://www.reddit.com/r/django/comments/1gbakoj/flexible_multisingle_tenant](https://www.reddit.com/r/django/comments/1gbakoj/flexible_multisingle_tenant)
 - RSS feed: $source
 - date published: 2024-10-24T19:06:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone</p> <p>We are currently developing an application that is separated into modules. One of the modules will contain sensitive business information of our customers, which is why we want to offer the possibility of a separate DB.</p> <p>Ideally we would like to keep a single shared DB for all customers, except for those who have chosen a separate DB.</p> <p>We use DRF and don’t intend on having a customer with its own DB also have its own subdomain, we want everything on the app subdomain. So I am thinking that all user models will have to be centrally stored so a middleware can figure out if it needs to route to a different database or something.</p> <p>So do any of you have advice on this, or can point to som resources about how you best set this flexible tenant architecture up in Django?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Electrical-Bench6733"> /u/Electrical-Bench6733 </a> <br/> <span><a

## MIGRATIONS STUCK
 - [https://www.reddit.com/r/django/comments/1gb9tmj/migrations_stuck](https://www.reddit.com/r/django/comments/1gb9tmj/migrations_stuck)
 - RSS feed: $source
 - date published: 2024-10-24T18:34:47+00:00

<!-- SC_OFF --><div class="md"><p>Migrations in django aren&#39;t working anymore for me. Here&#39;s my scenario. I&#39;m able to run migrations in other ECS UAT environments but while running migrations in production using &#39;python manage.py migrate&#39; it doesn&#39;t work. I get no logs whatsoever and the ecs container keeps on running forever. The database size is around 40 GB. Not sure if this should have any effect on the migrations.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Baymax06007"> /u/Baymax06007 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gb9tmj/migrations_stuck/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gb9tmj/migrations_stuck/">[comments]</a></span>

## [Hiring] 👆Django Developer 👆
 - [https://www.reddit.com/r/django/comments/1gb89t4/hiring_django_developer](https://www.reddit.com/r/django/comments/1gb89t4/hiring_django_developer)
 - RSS feed: $source
 - date published: 2024-10-24T17:30:14+00:00

<!-- SC_OFF --><div class="md"><p>🚀 Urgent Hiring. Apply Now. #wfh #remote</p> <p><a href="https://spotter.na.teamtailor.com/jobs/69238-django-developer-devops-gcp-kubernetes-remote?promotion=4901-trackable-share-link-d5a87f44-ee57-4d70-9515-20ccbf4d4af1">https://spotter.na.teamtailor.com/jobs/69238-django-developer-devops-gcp-kubernetes-remote?promotion=4901-trackable-share-link-d5a87f44-ee57-4d70-9515-20ccbf4d4af1</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Roxilicious"> /u/Roxilicious </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gb89t4/hiring_django_developer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gb89t4/hiring_django_developer/">[comments]</a></span>

## Please suggest model translation library for rest framework.
 - [https://www.reddit.com/r/django/comments/1gb5ikt/please_suggest_model_translation_library_for_rest](https://www.reddit.com/r/django/comments/1gb5ikt/please_suggest_model_translation_library_for_rest)
 - RSS feed: $source
 - date published: 2024-10-24T15:35:05+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to build a project where a db table will contain multiple translations of the same data. I am expecting the original (before any translation) will contain about 15 columns and 1,000,000 rows and I am planning to support at least 10 languages. Read operations will occur at least 100 times than write operations. Now I am struggling to choose among django-hvad, django-parler-rest, django-modeltrans and django-modeltranslation. I haven&#39;t worked with any of these before, only skimmed through their documentation a little bit. So, feel free to suggest any other library that you would like me to check out. And please let me know if I am missing something. Thank you in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Casio991es"> /u/Casio991es </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gb5ikt/please_suggest_model_translation_library_for_rest/">[link]</a></span> &#32; <span

## What frontend do you use?
 - [https://www.reddit.com/r/django/comments/1gb49qb/what_frontend_do_you_use](https://www.reddit.com/r/django/comments/1gb49qb/what_frontend_do_you_use)
 - RSS feed: $source
 - date published: 2024-10-24T14:42:38+00:00

<!-- SC_OFF --><div class="md"><p>I have a small project where im using Next JS + Django, but im facing trouble with Auth and Sessions. When I fetch something on next, it fetches on server (which is what i want) but it doesn&#39;t send Session Token to the browser, so i can&#39;t use Django Session.</p> <p>I&#39;m just wondering what frontends do you use and how do you tackle this problem</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/verains"> /u/verains </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gb49qb/what_frontend_do_you_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gb49qb/what_frontend_do_you_use/">[comments]</a></span>

## The amazing architect strikes
 - [https://www.reddit.com/r/django/comments/1gb33yy/the_amazing_architect_strikes](https://www.reddit.com/r/django/comments/1gb33yy/the_amazing_architect_strikes)
 - RSS feed: $source
 - date published: 2024-10-24T13:51:07+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/abybaddi009"> /u/abybaddi009 </a> <br/> <span><a href="https://i.redd.it/e8pbxpjwjpwd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gb33yy/the_amazing_architect_strikes/">[comments]</a></span>

## Is it safe to use request.get_full_path() to return user to the same page when updating form?
 - [https://www.reddit.com/r/django/comments/1gb0z41/is_it_safe_to_use_requestget_full_path_to_return](https://www.reddit.com/r/django/comments/1gb0z41/is_it_safe_to_use_requestget_full_path_to_return)
 - RSS feed: $source
 - date published: 2024-10-24T12:03:05+00:00

<!-- SC_OFF --><div class="md"><p>I have a page with a few forms and url with several parameters. When updating one of the forms, instead of extracting all parameters and redirecting to the same view, can I simply do return(redirect(request.get_full_path()))?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/peterstiglitz"> /u/peterstiglitz </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gb0z41/is_it_safe_to_use_requestget_full_path_to_return/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gb0z41/is_it_safe_to_use_requestget_full_path_to_return/">[comments]</a></span>

## Drf: When you create a delete endpoint do you return 200 with a message or just leave it at 204 without a message?
 - [https://www.reddit.com/r/django/comments/1gazwdn/drf_when_you_create_a_delete_endpoint_do_you](https://www.reddit.com/r/django/comments/1gazwdn/drf_when_you_create_a_delete_endpoint_do_you)
 - RSS feed: $source
 - date published: 2024-10-24T11:02:03+00:00

<!-- SC_OFF --><div class="md"><p>I need to have my facts right before I drop a message for my QA on slack 😂</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_BigOle"> /u/_BigOle </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gazwdn/drf_when_you_create_a_delete_endpoint_do_you/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gazwdn/drf_when_you_create_a_delete_endpoint_do_you/">[comments]</a></span>

## cotton-heroicons: A Django Cotton component library of Heroicons
 - [https://www.reddit.com/r/django/comments/1gazs0t/cottonheroicons_a_django_cotton_component_library](https://www.reddit.com/r/django/comments/1gazs0t/cottonheroicons_a_django_cotton_component_library)
 - RSS feed: $source
 - date published: 2024-10-24T10:54:41+00:00

<!-- SC_OFF --><div class="md"><p>I just published a Django Cotton component library of Heroicons. It&#39;s super simple to use and has all the latest icons. Here&#39;s a quick taste:</p> <p><code>html &lt;c-heroicon.check-circle /&gt; </code></p> <p>Install it from PyPi: <a href="https://pypi.org/project/cotton-heroicons/">https://pypi.org/project/cotton-heroicons/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Expert-Mechanic9062"> /u/Expert-Mechanic9062 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gazs0t/cottonheroicons_a_django_cotton_component_library/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gazs0t/cottonheroicons_a_django_cotton_component_library/">[comments]</a></span>

## How do I structure and write tests for a tenant based architecture in django ?
 - [https://www.reddit.com/r/django/comments/1gaz6f6/how_do_i_structure_and_write_tests_for_a_tenant](https://www.reddit.com/r/django/comments/1gaz6f6/how_do_i_structure_and_write_tests_for_a_tenant)
 - RSS feed: $source
 - date published: 2024-10-24T10:15:28+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone I&#39;m a fresher backend engineer at a startup, and I&#39;m looking for some guidance on writing tests.</p> <p>Here&#39;s some context, We have a huge codebase that isn&#39;t documented well. I&#39;ve decided to start writing tests for any new code I touch, but I&#39;ve never written tests before.</p> <p>Current Setup: 1. We use Django with django-tenants, meaning each client has their own isolated schema 2. Many features/endpoints are configuration-driven. For example, Excel sheet ingestion is driven by huge JSON configs</p> <p>My Problems: * Not sure how to approach testing in general * Don&#39;t know how to automate testing with all these configurations</p> <p>Anyone dealt with similar challenges? How would you approach this? Any tips would be really helpful!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/depressoham"> /u/depressoham </a> <br/> <span><a href="https://www.reddit.com/r/django/com

## How to send login method for social auth buttons (like google or facebook) from frontend to backend function dynamically
 - [https://www.reddit.com/r/django/comments/1gaz0ix/how_to_send_login_method_for_social_auth_buttons](https://www.reddit.com/r/django/comments/1gaz0ix/how_to_send_login_method_for_social_auth_buttons)
 - RSS feed: $source
 - date published: 2024-10-24T10:03:57+00:00

<!-- SC_OFF --><div class="md"><p>I have written login_method_view function to capture the login method for email&amp;username, google and facebook. my function is capturing the login method for email and password but not for google and facebook.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Being-Hones_9603"> /u/Being-Hones_9603 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gaz0ix/how_to_send_login_method_for_social_auth_buttons/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gaz0ix/how_to_send_login_method_for_social_auth_buttons/">[comments]</a></span>

## Django Debug=False Breaking websockets in django-channels, I'm stuck please help!
 - [https://www.reddit.com/r/django/comments/1gayq3w/django_debugfalse_breaking_websockets_in](https://www.reddit.com/r/django/comments/1gayq3w/django_debugfalse_breaking_websockets_in)
 - RSS feed: $source
 - date published: 2024-10-24T09:43:32+00:00

<!-- SC_OFF --><div class="md"><p>I have a django application that uses django channels via gunicorn/nginx/daphne everything functions perfectly fine when django is set to debug=true in my .env file, however when I set debug=false it breaks one specific consumer in django channels and for the life of me I cannot figure out why... I&#39;m happy to share code snippets if anyone can point me in the right direction? Thank you in advance!</p> <p>The issue seems to be that when client x sends message via channels (button click) client y does not receive that message however when debug=true the message is received and the code proceeds with the function. </p> <p>Things I have tested:<br/> Websockets are using the correct url and nginx is correctly proxy passing the websockets to daphne, allowed hosts is set correctly, my firewall is not blocking the communication between django/daphne/gunicorn/redis, I have set extensive logging and the logs show nothing wrong with my code, no errors, nothi

## Why is Celery hogging memory?
 - [https://www.reddit.com/r/django/comments/1gax0pj/why_is_celery_hogging_memory](https://www.reddit.com/r/django/comments/1gax0pj/why_is_celery_hogging_memory)
 - RSS feed: $source
 - date published: 2024-10-24T07:29:27+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, somewhat new here so if this isn&#39;t the right place to ask, let me know, and I&#39;ll be on my way.</p> <p>So, I&#39;ve got a project running from cookie cutter django, celery/beat/flower the whole shebang. I&#39;ve hosted it on Heroku, got a Celery task that functions! So far so good. The annoying thing is that every 20 seconds in Papertrail, the celery worker logs </p> <p><code>Oct 24 09:25:08 kinecta-eu heroku/worker.1 Process running mem=541M(105.1%)</code></p> <p><code>Oct 24 09:25:08 kinecta-eu heroku/worker.1 Error R14 (Memory quota exceeded)</code></p> <p>Now, my web dyno only uses 280MB, and I can scale that down to 110MB if I reduce concurrency from 3 to 1; this does not affect the error the worker gives. My entire database is only 17MB. The task my Celery worker has to run is a simple &#39;look at all Objects (about 100), and calculate how long ago they were created&#39;. </p> <p>Why does Celery feel it needs 500MB to do so? Ho

## Range filter in Django admin page
 - [https://www.reddit.com/r/django/comments/1gax0n5/range_filter_in_django_admin_page](https://www.reddit.com/r/django/comments/1gax0n5/range_filter_in_django_admin_page)
 - RSS feed: $source
 - date published: 2024-10-24T07:29:18+00:00

<!-- SC_OFF --><div class="md"><p>I am struggling to add a range filter for the table with number columns ( minimum ,maximum). Have to achieve by using forms. Any suggestions and it should visible for django-admin page only.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IndependentSmile320"> /u/IndependentSmile320 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gax0n5/range_filter_in_django_admin_page/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gax0n5/range_filter_in_django_admin_page/">[comments]</a></span>

