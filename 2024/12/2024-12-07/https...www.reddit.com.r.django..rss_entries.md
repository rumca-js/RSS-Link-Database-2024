# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## dj_rest_auth: string indices must be integers, not 'str in /auth/google
 - [https://www.reddit.com/r/django/comments/1h9245r/dj_rest_auth_string_indices_must_be_integers_not](https://www.reddit.com/r/django/comments/1h9245r/dj_rest_auth_string_indices_must_be_integers_not)
 - RSS feed: $source
 - date published: 2024-12-07T20:59:32+00:00

<!-- SC_OFF --><div class="md"><p>hey i am trying to add googel oauth but i am getting this error when requesting this endpoint:</p> <p><a href="https://preview.redd.it/s5mjwtm0th5e1.png?width=1738&amp;format=png&amp;auto=webp&amp;s=5bd969ceb8e17cad57ff7b4ed8a8d3c42aa19501">login endpoint</a></p> <p>request:</p> <pre><code>path(&quot;auth/google/&quot;, GoogleLogin.as_view() ), # google social login urls class GoogleLogin(SocialLoginView): adapter_class = GoogleOAuth2Adapter client_class = OAuth2Client callback_url = GOOGLE_OAUTH_CALLBACK_URL </code></pre> <p>==&gt; packages:</p> <p>django-allauth==0.56.0</p> <p>dj-rest-auth==7.0.0 Django==5.1.2</p> <p>djangorestframework==3.15.2</p> <p>djangorestframework-simplejwt==5.3.1</p> <p>my settings.py:</p> <pre><code>SOCIALACCOUNT_PROVIDERS = { &quot;google&quot;: { &quot;APP&quot;:{ &quot;client_id&quot;: os.environ.get(&quot;GOOGLE_OAUTH_CLIENT_ID&quot;,None), &quot;secret&quot;: os.environ.get(&quot;GOOGLE_OAUTH_CLIENT_SECRET&quot;,None)

## Django E-commerce Hosting
 - [https://www.reddit.com/r/django/comments/1h8x29t/django_ecommerce_hosting](https://www.reddit.com/r/django/comments/1h8x29t/django_ecommerce_hosting)
 - RSS feed: $source
 - date published: 2024-12-07T17:11:34+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I’m developing an e-commerce website for a local pharmacy. I’m using stripe for the payment getaway. Have the domain already purchased. Just wondering would anyone have any ideas for a web host. There will be about 100 products (3 pictures needed for each product). Let me know if anymore requirements need to be listed. (Used Heroku before so new to the paid side of web hosting) Cheers </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Heavy-Experience9646"> /u/Heavy-Experience9646 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8x29t/django_ecommerce_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8x29t/django_ecommerce_hosting/">[comments]</a></span>

## made a app , which look a like baserow
 - [https://www.reddit.com/r/django/comments/1h8vbj3/made_a_app_which_look_a_like_baserow](https://www.reddit.com/r/django/comments/1h8vbj3/made_a_app_which_look_a_like_baserow)
 - RSS feed: $source
 - date published: 2024-12-07T15:52:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi ,</p> <p>i just made a app , which is an alternative to baserow , airtable </p> <p><a href="https://flexitable.web.app/">https://flexitable.web.app/</a></p> <p>frontend - react<br/> backend : django , django rest , postgres</p> <p>just use any your email to get started , its just a POC ,<br/> roast required<br/> soon will open source it .</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ambi_98"> /u/ambi_98 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8vbj3/made_a_app_which_look_a_like_baserow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8vbj3/made_a_app_which_look_a_like_baserow/">[comments]</a></span>

## Updating a Django app. A few questions…
 - [https://www.reddit.com/r/django/comments/1h8ui1i/updating_a_django_app_a_few_questions](https://www.reddit.com/r/django/comments/1h8ui1i/updating_a_django_app_a_few_questions)
 - RSS feed: $source
 - date published: 2024-12-07T15:13:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi all</p> <p>I’m a newbie to Django so please forgive any idiotic questions.</p> <p>I’ll describe my situation and then maybe it will add some context to my issues. I’m disabled and sometimes I can’t be on a screen or computer for maybe a month or two at a time. Long gaps between being online simply.</p> <p>If I was to create a Django blog site how often does it need to be updated? </p> <p>My second question is are the updates to a working app difficult for someone new to web apps? I’m new to python also. </p> <p>Thank you for any guidance or tips. :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/harrisonfordatemyass"> /u/harrisonfordatemyass </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8ui1i/updating_a_django_app_a_few_questions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8ui1i/updating_a_django_app_a_few_questions/">[comments]</a></span>

## For those that pay under $50 total in infra costs, what is your app doing?
 - [https://www.reddit.com/r/django/comments/1h8tez7/for_those_that_pay_under_50_total_in_infra_costs](https://www.reddit.com/r/django/comments/1h8tez7/for_those_that_pay_under_50_total_in_infra_costs)
 - RSS feed: $source
 - date published: 2024-12-07T14:18:26+00:00

<!-- SC_OFF --><div class="md"><p>I’ve seen a lot of people post about how they pay less than $50 in total costs so I’ve had a few questions for you.</p> <p>What is the purpose of your app? How much traffic does it see? What kind of functionality does it support? What are you using for your DB? How’s the performance? What’s the server config?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Django-fanatic"> /u/Django-fanatic </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8tez7/for_those_that_pay_under_50_total_in_infra_costs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8tez7/for_those_that_pay_under_50_total_in_infra_costs/">[comments]</a></span>

## Anyone Using Temporal?
 - [https://www.reddit.com/r/django/comments/1h8tcp9/anyone_using_temporal](https://www.reddit.com/r/django/comments/1h8tcp9/anyone_using_temporal)
 - RSS feed: $source
 - date published: 2024-12-07T14:15:12+00:00

<!-- SC_OFF --><div class="md"><p>I recently learned about temporal.io through a tech talk. Does anyone in the Django community use this as an alternative to something like Celery? It sounds too good to be true.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ChungusProvides"> /u/ChungusProvides </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8tcp9/anyone_using_temporal/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8tcp9/anyone_using_temporal/">[comments]</a></span>

## Roadmap for learning automation
 - [https://www.reddit.com/r/django/comments/1h8scx9/roadmap_for_learning_automation](https://www.reddit.com/r/django/comments/1h8scx9/roadmap_for_learning_automation)
 - RSS feed: $source
 - date published: 2024-12-07T13:21:06+00:00

<!-- SC_OFF --><div class="md"><p>What’s the best roadmap for learning Python automation for someone already experienced in Django development? Any specific tools, resources, or project ideas to get started?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/__robo___"> /u/__robo___ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8scx9/roadmap_for_learning_automation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8scx9/roadmap_for_learning_automation/">[comments]</a></span>

## Async django, who is using it and why?
 - [https://www.reddit.com/r/django/comments/1h8rd7v/async_django_who_is_using_it_and_why](https://www.reddit.com/r/django/comments/1h8rd7v/async_django_who_is_using_it_and_why)
 - RSS feed: $source
 - date published: 2024-12-07T12:22:40+00:00

<!-- SC_OFF --><div class="md"><p>I am curious to know the use cases for async django, and whether there was a performance improvement in doing it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/grandimam"> /u/grandimam </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8rd7v/async_django_who_is_using_it_and_why/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8rd7v/async_django_who_is_using_it_and_why/">[comments]</a></span>

## Weird long Response time
 - [https://www.reddit.com/r/django/comments/1h8qso3/weird_long_response_time](https://www.reddit.com/r/django/comments/1h8qso3/weird_long_response_time)
 - RSS feed: $source
 - date published: 2024-12-07T11:45:38+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have been working on one of my project. I have also deployed it on production. I have frontend peers who work on nextjs to serve frontend part and my work is to manage backend using DRF. </p> <p>Major issue here I face is sometimes it takes unexpected long response time like 4 seconds, 7 or even beyond 10 seconds. </p> <p>When I use devtools to check I see TTFB is a major chunk of time taken. Basically a response from backend. </p> <p>Then i speculate if actually my drf APIs are slow or not but they weren&#39;t. All queries gets executed under 200ms. </p> <p>We using Axios to connect backend services via fqn domain. </p> <p>I don&#39;t have much things how do I find the major root cause behind it. Is it latency when opening db connections? Is it extra network hops each requests takes or is it something internal? </p> <p>Cuz I&#39;m sure django isn&#39;t that slow framework that takes &lt;4s to respond any listapi. </p> <p>Additionally, it takes

## Why there is no form.save() in form_valid method of FormView?
 - [https://www.reddit.com/r/django/comments/1h8qkq2/why_there_is_no_formsave_in_form_valid_method_of](https://www.reddit.com/r/django/comments/1h8qkq2/why_there_is_no_formsave_in_form_valid_method_of)
 - RSS feed: $source
 - date published: 2024-12-07T11:29:45+00:00

<!-- SC_OFF --><div class="md"><p>Why there is no form.save() in form_valid method of FormView? It irritates me that in every class that inherits `FormView` I have to override `form_valid` method just to add a single `form.save()` line or create my own mixin that overrides this method this way and inherit this mixin. </p> <p>Is there a use case for a form without save? Why it&#39;s needed? And why they could not create some FormSaveMixin or something that will work for most `FormView` actual usage cases?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Achill1es"> /u/Achill1es </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8qkq2/why_there_is_no_formsave_in_form_valid_method_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8qkq2/why_there_is_no_formsave_in_form_valid_method_of/">[comments]</a></span>

## Implementing a Robust SQLite Backup System in Django
 - [https://www.reddit.com/r/django/comments/1h8qg58/implementing_a_robust_sqlite_backup_system_in](https://www.reddit.com/r/django/comments/1h8qg58/implementing_a_robust_sqlite_backup_system_in)
 - RSS feed: $source
 - date published: 2024-12-07T11:20:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Secure-Composer-9458"> /u/Secure-Composer-9458 </a> <br/> <span><a href="https://selftaughtdev.hashnode.dev/implementing-a-robust-sqlite-backup-system-in-django">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8qg58/implementing_a_robust_sqlite_backup_system_in/">[comments]</a></span>

## Whats a cheap DMCA-ignored secure service that allows deployment of django?
 - [https://www.reddit.com/r/django/comments/1h8pon1/whats_a_cheap_dmcaignored_secure_service_that](https://www.reddit.com/r/django/comments/1h8pon1/whats_a_cheap_dmcaignored_secure_service_that)
 - RSS feed: $source
 - date published: 2024-12-07T10:24:04+00:00

<!-- SC_OFF --><div class="md"><p>Just a small HTML website. with SQLite DB. I looked some but found that they are really expensive for this very small website, i will mostly pay for things i will not use ever. </p> <p>Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rare_Mammoth_3229"> /u/Rare_Mammoth_3229 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8pon1/whats_a_cheap_dmcaignored_secure_service_that/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8pon1/whats_a_cheap_dmcaignored_secure_service_that/">[comments]</a></span>

## How Are You Guys Handling Backup in SQLite Databases? 🤔
 - [https://www.reddit.com/r/django/comments/1h8oxec/how_are_you_guys_handling_backup_in_sqlite](https://www.reddit.com/r/django/comments/1h8oxec/how_are_you_guys_handling_backup_in_sqlite)
 - RSS feed: $source
 - date published: 2024-12-07T09:26:14+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks,</p> <p>I’m currently working on a project that uses SQLite as the database, and I’m trying to figure out the best way to handle backups. Since SQLite is just a single file, backing up should be straightforward, but I’m curious about how you all approach it to avoid issues like:</p> <ul> <li><strong>Database locking</strong>: How do you ensure the database isn&#39;t locked or in use during the backup process?</li> <li><strong>Consistency</strong>: Are you using tools like <code>.backup</code> or <code>.dump</code>, or just copying the file directly?</li> <li><strong>Automation</strong>: Do you use scripts to automate backups? If yes, how often do you schedule them?</li> <li><strong>Storage</strong>: Where do you store your backups—locally, on the cloud, or both?</li> </ul> <p>Also, any recommendations for handling large SQLite databases would be awesome!</p> <p>I’d love to hear your strategies, tools, and best practices for keeping SQLite b

## Need help with web app deployment [student project]
 - [https://www.reddit.com/r/django/comments/1h8onxl/need_help_with_web_app_deployment_student_project](https://www.reddit.com/r/django/comments/1h8onxl/need_help_with_web_app_deployment_student_project)
 - RSS feed: $source
 - date published: 2024-12-07T09:06:06+00:00

<!-- SC_OFF --><div class="md"><h1>[RECOMMEND HOSTING SERVICES FOR A STUDENT PROJECT]</h1> <p>hi peeps,</p> <p>my team is working on a django web app, currently deployed on render(free tier) along with their own postgresql server for elementary testing/vibe, (it looks gorgeous ngl). So far around 10-15% of the initially planned feature are completed. The expected entirety of it will become a small-decent sized web app, includes django, tensorflow, pandas, drf api and other components.</p> <p>but.. if you can help me out with some generous hosting platform (domain and small enough server) recommendations it would be really appreciable. after some digging the best I found is interserver. the lowest pricing can go without compromising on basic features/security (bcuz we kinda broke). for now free tier will do but we plan on publishing it before next year&#39;s internship period, it is a passion project after all.</p> <p>any kind of advice and suggestions with planning, deployment, strat

## Not able to execute query in Solr GUI
 - [https://www.reddit.com/r/django/comments/1h8j1yc/not_able_to_execute_query_in_solr_gui](https://www.reddit.com/r/django/comments/1h8j1yc/not_able_to_execute_query_in_solr_gui)
 - RSS feed: $source
 - date published: 2024-12-07T03:01:38+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone I was able to not only successfully scrape a website for my Django/Solr project, but I was able to also index the document after having saved it as a JSON file. </p> <p>In short, the problem I am facing right now, is that I am not able to execute search queries in Solr Admin. The Logging in Solr is fixed and my fields are defined in schema.xml. But when I add `q=company_name:&quot;Pikes Peak&quot;`, I get the following returned result for my document ```{<br/> &quot;responseHeader&quot;:{<br/> &quot;status&quot;:400,<br/> &quot;QTime&quot;:4,<br/> &quot;params&quot;:{<br/> &quot;q&quot;:&quot;q=company_name:\&quot;Pikes Peak\&quot;&quot;,<br/> &quot;indent&quot;:&quot;true&quot;,<br/> &quot;q.op&quot;:&quot;OR&quot;,<br/> &quot;useParams&quot;:&quot;&quot;,<br/> &quot;_&quot;:&quot;1733538416504&quot;<br/> }<br/> },<br/> &quot;error&quot;:{<br/> &quot;metadata&quot;:[&quot;error-class&quot;,&quot;org.apache.solr.common.SolrException&quot

## Looking to hire junior Django developer for ad-hoc remote async work
 - [https://www.reddit.com/r/django/comments/1h8iveu/looking_to_hire_junior_django_developer_for_adhoc](https://www.reddit.com/r/django/comments/1h8iveu/looking_to_hire_junior_django_developer_for_adhoc)
 - RSS feed: $source
 - date published: 2024-12-07T02:51:44+00:00

<!-- SC_OFF --><div class="md"><p>I run an education platform built on Django with a large user base.</p> <p>We already have some senior Django developers (10+ years exp), but I’m looking for an additional developer who is able to provide ad-hoc remote work as needed to tackle smaller fixes/features whilst the senior developers are in the middle of larger features and architectural work. </p> <p>I’m looking for someone with at least 3 years of Django experience. An ideal candidate would also have a good grounding in Bootstrap and JS.</p> <p>My hope is to find someone who is able to grow alongside the project with the possibility of taking on more of a regular role in the future if things go well.</p> <p>Our stack is straightforward Django 5, Bootstrap, JS and some recent sprinklings of HTMX.</p> <p>We’re fully remote and async. As mentioned this will be ad-hoc work, at least initially, I expect something like 2-3 days a month worth of time. I&#39;m happy to discuss rates, etc. You ca

## Hey guys I wanted to know what would be an operational cost to maintain a full website
 - [https://www.reddit.com/r/django/comments/1h8ikkr/hey_guys_i_wanted_to_know_what_would_be_an](https://www.reddit.com/r/django/comments/1h8ikkr/hey_guys_i_wanted_to_know_what_would_be_an)
 - RSS feed: $source
 - date published: 2024-12-07T02:35:27+00:00

<!-- SC_OFF --><div class="md"><p>So I was thinking to start a business and having a website in this day and age is very important, i wanted to know the complete cost breakdown hidden charges, operational cost, development cost it would be a great help someone could give me a cost breakdown, as I am just starting out I would like to keep the cost minimal so open source alternatives or minimum cost ideas would be appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ketanjain008"> /u/ketanjain008 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h8ikkr/hey_guys_i_wanted_to_know_what_would_be_an/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h8ikkr/hey_guys_i_wanted_to_know_what_would_be_an/">[comments]</a></span>

