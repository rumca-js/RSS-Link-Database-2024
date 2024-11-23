# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Adding Google Maps Input to Django Form Wizard
 - [https://www.reddit.com/r/django/comments/1gxjytv/adding_google_maps_input_to_django_form_wizard](https://www.reddit.com/r/django/comments/1gxjytv/adding_google_maps_input_to_django_form_wizard)
 - RSS feed: $source
 - date published: 2024-11-22T22:17:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m working on a project that uses Django&#39;s <code>formtools.wizard</code> to guide users through a multi-step form. I need help with integrating a Google Map into one of the wizard steps so that users can select a location. Ideally, the map would allow users to drop a pin, and the longitude and latitude would be captured and passed as part of the form submission.</p> <p>The solution I’m considering is:</p> <ol> <li>Customizing the HTML for the wizard step.</li> <li>Embedding a Google Map in that step.</li> <li>Using JavaScript to handle user interactions with the map (e.g., capturing latitude and longitude when a pin is dropped).</li> <li>Storing the latitude and longitude in hidden input fields within the form.</li> </ol> <p>This approach seems to work in theory, but I’m wondering if it’s the &quot;proper&quot; way to do this. Is there a more smart solution for handling this kind of integration, especially in the context of t

## Best practices for dynamic file creation ? Beginner help ?
 - [https://www.reddit.com/r/django/comments/1gxel6g/best_practices_for_dynamic_file_creation_beginner](https://www.reddit.com/r/django/comments/1gxel6g/best_practices_for_dynamic_file_creation_beginner)
 - RSS feed: $source
 - date published: 2024-11-22T18:24:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i&#39;m pretty new to django and I am curently working on a project as my internship. The idea is that i have a bunch of executables in my backend. Those executables can read a file when launched and then they write a bunch of results inside a folder of choice. The app I have to make is basically a website where people can sign up, run an executable of their choice, save the various results and view them/ compare them as graphs in the frontend. </p> <p>My idea was to dymanically create a folder in the backend for each user and when they launch the executable it will ask it to write the results in this specific folder. </p> <p>Is that a good idea ? what are the best practices to handle such a problem ? And how should i structure my application to have the cleanest thing possible ? </p> <p>As i said i&#39;m pretty new to django and I really want to do a good job on this project so any help is more than apreciated !!</p> <p>(the flow of the project 

## Problem with Django Migrations Misapplying Field Type
 - [https://www.reddit.com/r/django/comments/1gx9mmy/problem_with_django_migrations_misapplying_field](https://www.reddit.com/r/django/comments/1gx9mmy/problem_with_django_migrations_misapplying_field)
 - RSS feed: $source
 - date published: 2024-11-22T14:54:37+00:00

<!-- SC_OFF --><div class="md"><p>Yesterday I ran into a problem that I&#39;ve never had with Django before where it was setting a default null field to not null when applying migrations to a database table. Has anyone else seen this happen? I&#39;m trying to figure out if it&#39;s a fluke or if there&#39;s something I need to fix.</p> <p>For more context, I have a Django app using a mariadb database. One model has a foreign key field that&#39;s set with null=True. This has been working fine, but yesterday when testing a fresh deployment, scripts started failing with a message that this field could not be null. I checked the create table in the database itself and saw that the column was set incorrectly. I checked the migrations. They had the correct null=True, and they had all run without errors. The only recent change to the migrations was that when I generated new ones for an update to another model, Django added changes that switched this field&#39;s corresponding primary key fie

## Best Practices and Tools for Managing API Keys in a Django Public API
 - [https://www.reddit.com/r/django/comments/1gx9lmw/best_practices_and_tools_for_managing_api_keys_in](https://www.reddit.com/r/django/comments/1gx9lmw/best_practices_and_tools_for_managing_api_keys_in)
 - RSS feed: $source
 - date published: 2024-11-22T14:53:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m building a public-facing API using Django and need to implement API key management. The goal is to allow users to create, revoke, and monitor their API keys, ensuring they are authenticated to manage their keys. Are there any Django packages or free third-party platforms that can help streamline this process?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adivhaho_m"> /u/adivhaho_m </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gx9lmw/best_practices_and_tools_for_managing_api_keys_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx9lmw/best_practices_and_tools_for_managing_api_keys_in/">[comments]</a></span>

## 🚀 Feature Friday: assertNumQueries!
 - [https://www.reddit.com/r/django/comments/1gx8b9a/feature_friday_assertnumqueries](https://www.reddit.com/r/django/comments/1gx8b9a/feature_friday_assertnumqueries)
 - RSS feed: $source
 - date published: 2024-11-22T13:51:45+00:00

<!-- SC_OFF --><div class="md"><p>Today&#39;s Feature Friday reaches back into Django&#39;s history for a small-but-powerful tool: <code>assertNumQueries</code>!</p> <p>This method from <code>TransactionTestCase</code> helps you write tests that verify the number of queries made by a piece of code.</p> <p>It is a great way to check DB performance and catch regressions or &quot;n+1&quot; issues (when you accidentally make a single DB query for every object in a loop instead of loading everything up front from the database).</p> <p>You can pass a function to <code>assertNumQueries</code>, or use it as a context manager, as shown in the example below:</p> <pre><code>from django.test import TransactionTestCase from .services import my_function_that_hits_the_db class MyTest(TransactionTestCase): def test_db_performance(self): # called directly self.assertNumQueries(7, my_function_that_hits_the_db) # used as a context manager with self.assertNumQueries(2): Person.objects.create(name=&quot;

## Fellow django developers let's connect! Let's learn and create something together!
 - [https://www.reddit.com/r/django/comments/1gx7yg7/fellow_django_developers_lets_connect_lets_learn](https://www.reddit.com/r/django/comments/1gx7yg7/fellow_django_developers_lets_connect_lets_learn)
 - RSS feed: $source
 - date published: 2024-11-22T13:34:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m creating a discord channel where developers can just chat, mentor other people, and even create project together. We&#39;d be happy if you join our community!</p> <p>Discord link: <a href="https://discord.gg/SD5b4NP4Sq">https://discord.gg/SD5b4NP4Sq</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KhZaym"> /u/KhZaym </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gx7yg7/fellow_django_developers_lets_connect_lets_learn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx7yg7/fellow_django_developers_lets_connect_lets_learn/">[comments]</a></span>

## E2E Encryption implementation in django chat app ?
 - [https://www.reddit.com/r/django/comments/1gx7tfi/e2e_encryption_implementation_in_django_chat_app](https://www.reddit.com/r/django/comments/1gx7tfi/e2e_encryption_implementation_in_django_chat_app)
 - RSS feed: $source
 - date published: 2024-11-22T13:27:24+00:00

<!-- SC_OFF --><div class="md"><p>hi everyone, i am building a chat app that will go to production an i was wandering if e2ee is a standard in chat apps nowadays and if yes, how can i implement it ? and is it easy to do so ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/L4z3x"> /u/L4z3x </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gx7tfi/e2e_encryption_implementation_in_django_chat_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx7tfi/e2e_encryption_implementation_in_django_chat_app/">[comments]</a></span>

## How to use Python 3.13 REPL with Django shell
 - [https://www.reddit.com/r/django/comments/1gx6aho/how_to_use_python_313_repl_with_django_shell](https://www.reddit.com/r/django/comments/1gx6aho/how_to_use_python_313_repl_with_django_shell)
 - RSS feed: $source
 - date published: 2024-11-22T12:05:47+00:00

<!-- SC_OFF --><div class="md"><p>I really wanted to try the new Python 3.13 REPL on a real project and I got the chance for the next two or three weeks. Sadly, when you start django shell, the new REPL is not what you get.</p> <p>So after a quick google search, I came across the article with the solution. I turned that article into an installable Django app and this is the result. If you&#39;re working with Django and have the opportunity to upgrade to 3.13, this might be useful.</p> <p><a href="https://github.com/selectnull/django-pyrepl/">https://github.com/selectnull/django-pyrepl/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/selectnull"> /u/selectnull </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gx6aho/how_to_use_python_313_repl_with_django_shell/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx6aho/how_to_use_python_313_repl_with_django_shell/">[comments]</a></span>

## VPS comparisons. ?
 - [https://www.reddit.com/r/django/comments/1gx5yy5/vps_comparisons](https://www.reddit.com/r/django/comments/1gx5yy5/vps_comparisons)
 - RSS feed: $source
 - date published: 2024-11-22T11:46:01+00:00

<!-- SC_OFF --><div class="md"><p>Which VPS you guys use to deploy django apps ? I&#39;ve used EC2 free tier almost a year, now trying to switch to few affordable solutions. I&#39;d like to get insights related to cost, speed, support perspective.</p> <ol> <li>AWS EC2.</li> <li>GCP Compute Engine.</li> <li>Digital Ocean Droplets.</li> <li>Hostinger</li> <li>Hetzner (I&#39;m from Asia Pacific, not sure about the data centers near)</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Professional_Taro194"> /u/Professional_Taro194 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gx5yy5/vps_comparisons/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx5yy5/vps_comparisons/">[comments]</a></span>

## Looking to improve my Django skills! Any video recommendations for beginners?
 - [https://www.reddit.com/r/django/comments/1gx4n6e/looking_to_improve_my_django_skills_any_video](https://www.reddit.com/r/django/comments/1gx4n6e/looking_to_improve_my_django_skills_any_video)
 - RSS feed: $source
 - date published: 2024-11-22T10:15:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone! I’m relatively new to Django and I’m looking to improve my skills. I’ve started building some simple projects, but I feel like I could benefit from some video tutorials that dive deeper into Django concepts.</p> <p>Could anyone recommend some great video resources for beginners that helped them? Whether it’s a step-by-step guide on creating a project, understanding models and views, or mastering Django’s admin, I’d love to get some suggestions</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sachin_70"> /u/Sachin_70 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gx4n6e/looking_to_improve_my_django_skills_any_video/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx4n6e/looking_to_improve_my_django_skills_any_video/">[comments]</a></span>

## Why does my Node.js Proxy (proxy.js) fail with Gunicorn in Heroku deployment but works locally and with heroku run?
 - [https://www.reddit.com/r/django/comments/1gx48pm/why_does_my_nodejs_proxy_proxyjs_fail_with](https://www.reddit.com/r/django/comments/1gx48pm/why_does_my_nodejs_proxy_proxyjs_fail_with)
 - RSS feed: $source
 - date published: 2024-11-22T09:46:04+00:00

<!-- SC_OFF --><div class="md"><p>I have a Django backend (served with Gunicorn) and a Node.js proxy (proxy.js). Here&#39;s the setup: Local Setup (Works Perfectly)</p> <pre><code>Django runs on 127.0.0.1:8000. proxy.js runs on 127.0.0.1:3000. Everything works smoothly — requests are routed properly through the proxy.js server to the Django backend. </code></pre> <p>Heroku Deployment (Fails)</p> <p>On Heroku, both Django and proxy.js must run on the same web dyno. Heroku assigns a single dynamic $PORT for the dyno, and this is where things break:</p> <pre><code>Gunicorn binds to $PORT (this works). proxy.js tries to bind to 3000 (or another static port) and fails because Heroku doesn&#39;t allow multiple ports per dyno. I’ve tried making proxy.js bind to $PORT instead, but then Django and proxy.js conflict because both try to use the same port. </code></pre> <p>Weird Behavior with heroku run</p> <p>When I run heroku run &quot;node static/js/proxy.js&quot;, proxy.js starts fine with n

## Help! How to make chat app work in django using channels in production.
 - [https://www.reddit.com/r/django/comments/1gx26dx/help_how_to_make_chat_app_work_in_django_using](https://www.reddit.com/r/django/comments/1gx26dx/help_how_to_make_chat_app_work_in_django_using)
 - RSS feed: $source
 - date published: 2024-11-22T07:10:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i deployed my django app. But now im stuck where my chat app is not working I used daphne, redis server in developement and it worked But im not able to configure it in production on my vps. </p> <p>I use nginx, gunicorn </p> <p>If you have any tutorial please provide link.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/himynameisAhhhh"> /u/himynameisAhhhh </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gx26dx/help_how_to_make_chat_app_work_in_django_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx26dx/help_how_to_make_chat_app_work_in_django_using/">[comments]</a></span>

## Open source contribution project
 - [https://www.reddit.com/r/django/comments/1gx196t/open_source_contribution_project](https://www.reddit.com/r/django/comments/1gx196t/open_source_contribution_project)
 - RSS feed: $source
 - date published: 2024-11-22T06:07:31+00:00

<!-- SC_OFF --><div class="md"><p>This is my first open source contribution project I have made this with using django and DRF . You nac also contribute in this project and gain more knowledge . always remember practice makes a perfect.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Django_Nik"> /u/Django_Nik </a> <br/> <span><a href="https://github.com/NikitaJaiswal77/bookstoreAPI/tree/master">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gx196t/open_source_contribution_project/">[comments]</a></span>

## Any successful sites that use Django's template engine?
 - [https://www.reddit.com/r/django/comments/1gwxj9p/any_successful_sites_that_use_djangos_template](https://www.reddit.com/r/django/comments/1gwxj9p/any_successful_sites_that_use_djangos_template)
 - RSS feed: $source
 - date published: 2024-11-22T02:39:10+00:00

<!-- SC_OFF --><div class="md"><p>Instagram and Pinterest use Django as a backend framework. They use React or something else as front end. Have you seen any successful sites that still rely on Django&#39;s built in template engine?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Key-Leadership-3927"> /u/Key-Leadership-3927 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gwxj9p/any_successful_sites_that_use_djangos_template/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gwxj9p/any_successful_sites_that_use_djangos_template/">[comments]</a></span>

## Django app almost done but deploying is going to make me ragequit
 - [https://www.reddit.com/r/django/comments/1gwwbjb/django_app_almost_done_but_deploying_is_going_to](https://www.reddit.com/r/django/comments/1gwwbjb/django_app_almost_done_but_deploying_is_going_to)
 - RSS feed: $source
 - date published: 2024-11-22T01:38:03+00:00

<!-- SC_OFF --><div class="md"><p>In local development django run on localhost:8000 and communicate with localhost:3000 which by itself communicating with payment gateway api i got the file tap.js which in the beggining fetches from views.py with the help of urls.py now all of this on port 8000, then i call the api using port 3000 which lead to proxy.js file i configured api calls on then i fetch the data and the last call is for validation when payment is completed tap.js send triggers proxy.js which is listening on port 3000 and in the end proxy.js sends back information, this was about local but in heroku! It&#39;s madness since i can&#39;t have another port without using another dyno which costs more money can&#39;t even use the same port for django gunicorn and node.js proxy.js not really sure what to do</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ExpertMatter1850"> /u/ExpertMatter1850 </a> <br/> <span><a href="https://www.reddit.com/r/

## Performance problems with django
 - [https://www.reddit.com/r/django/comments/1gwvyf3/performance_problems_with_django](https://www.reddit.com/r/django/comments/1gwvyf3/performance_problems_with_django)
 - RSS feed: $source
 - date published: 2024-11-22T01:19:15+00:00

<!-- SC_OFF --><div class="md"><p>Hi Django community,</p> <p>I&#39;m experiencing some performance issues with my Django application and looking for advice on optimization. After watching some comparisons between Django and Go performance, I&#39;m trying to understand if my issues are related to my implementation or Django&#39;s inherent characteristics.</p> <p><strong>Current Setup:</strong></p> <ul> <li>Django 4.x</li> <li>PostgreSQL database</li> <li>Running on AWS EC2 t2.micro</li> <li>~1000 daily active users</li> </ul> <p><strong>Issues I&#39;m facing:</strong></p> <ul> <li>Slow response times (averaging 2-3 seconds for main pages)</li> <li>Database queries seem to be taking longer than expected</li> <li>Memory usage keeps climbing throughout the day</li> </ul> <p><strong>What I&#39;ve tried so far:</strong></p> <ul> <li>Added database indexes on frequently queried fields</li> <li>Implemented caching using Redis</li> <li>Used <code>select_related()</code> and <code>prefetch_re

