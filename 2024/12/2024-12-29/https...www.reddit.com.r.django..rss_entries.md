# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django and open source licenses
 - [https://www.reddit.com/r/django/comments/1hp86sy/django_and_open_source_licenses](https://www.reddit.com/r/django/comments/1hp86sy/django_and_open_source_licenses)
 - RSS feed: $source
 - date published: 2024-12-29T22:49:45+00:00

<!-- SC_OFF --><div class="md"><p>I know...another open source license post. </p> <p>Just curious how you guys are approaching licensing and Django projects with dependencies? Specifically websites or SaaS - are you looking at the dependencies and their licenses? Wouldn&#39;t any dependency with a GPL require you to be GPL? A lot of variation for example;</p> <p>Celery: BSD License<br/> Django Countries: MIT License<br/> Pandas: BSD3 License</p> <p>Etc.</p> <p>I am building a financial service website (crypto sphere). It might become commercial SaaS down the road. That being said I want the code to be open sourced, and MIT sounds like it would be very permissive. I&#39;m not reinventing the wheel here (I did write some algos that are useful, but nothing that a seasoned programmer couldn&#39;t write better). All the data is on a Postgresql DB, etc. </p> <p>Any downsides to using MIT? Most repos I&#39;m looking at are either MIT or BSD for libraries. </p> <p>I&#39;ve read through hundr

## Project Structure and nested apps
 - [https://www.reddit.com/r/django/comments/1hozb1i/project_structure_and_nested_apps](https://www.reddit.com/r/django/comments/1hozb1i/project_structure_and_nested_apps)
 - RSS feed: $source
 - date published: 2024-12-29T16:17:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been looking into various ways of structuring projects (highly recommended since it forces you to look under the hood at the project configuration files). I bough Two Scoops and started there, but also looking at other setups on github.</p> <p>I come from a design background, and having all the app folders along with other folders (templates, config, etc.) always seemed cluttered to me. I&#39;ve currently branched out and testing out an apps folder with the apps nested and other than having to type &quot;apps.app1&quot;, &quot;apps.app2&quot;, etc., there doesn&#39;t seem to be a downside and the project looks more ordered (IMHO).</p> <p>Is there a downside to this type of structure? What has been your experience so far? I&#39;m currently branched out in case it doesn&#39;t work well so I can revert to the old structure.</p> <pre><code>Project core settings.py apps app1 app2 app3 templates manage.py </code></pre> <p>EDIT: I can&#39;t seem to

## How do you manage sending mails with SMTP with all analytics and tracking on SES?
 - [https://www.reddit.com/r/django/comments/1hoz76e/how_do_you_manage_sending_mails_with_smtp_with](https://www.reddit.com/r/django/comments/1hoz76e/how_do_you_manage_sending_mails_with_smtp_with)
 - RSS feed: $source
 - date published: 2024-12-29T16:12:47+00:00

<!-- SC_OFF --><div class="md"><p>I am looking to have a custom implementation for sending and tracking mails. SES can do tracking, but I want to have a robust mail sending system. I have tried listmonk and it does not track for campaigns and the customizability is limited there. I&#39;m looking to build a custom sender.</p> <p>Is there anything I should avoid while building this? Is send and forget the right way and forcing SES to manage delivery +other analytics the best way? </p> <p>Does anyone have some repos with a really good implementation of a mail sending system?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/give_me_a_job_pls"> /u/give_me_a_job_pls </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hoz76e/how_do_you_manage_sending_mails_with_smtp_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hoz76e/how_do_you_manage_sending_mails_with_smtp_with/">[comments]</a></span>

## How do I integrate pytest with python-socketio and django?
 - [https://www.reddit.com/r/django/comments/1hoyu9h/how_do_i_integrate_pytest_with_pythonsocketio_and](https://www.reddit.com/r/django/comments/1hoyu9h/how_do_i_integrate_pytest_with_pythonsocketio_and)
 - RSS feed: $source
 - date published: 2024-12-29T15:56:18+00:00

<!-- SC_OFF --><div class="md"><p>No matter what I do, pytest test db is not being used by python-socketio, but the django server and APIs use the test db with no problem? It has been bugging me for a week now and I&#39;ve tried the following:</p> <ol> <li>Using socketio&#39;s AsyncServer to manage both django and socketio connections.<br/></li> <li>Using ProtocolTypeRouter to do the same thing in 1.<br/></li> <li>Using a custom test db with conftest. It didn&#39;t even get recognized.</li> </ol> <p>A lack of test server and client is ruining my productivity and I don&#39;t know if there is a better alternative that works well with django. </p> <p>I really need to fix this ASAP and any help and guidance will save me from a lot of headaches. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/give_me_a_job_pls"> /u/give_me_a_job_pls </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hoyu9h/how_do_i_integrate_pytest_with_pythonsocket

## Livereload in django
 - [https://www.reddit.com/r/django/comments/1howw3s/livereload_in_django](https://www.reddit.com/r/django/comments/1howw3s/livereload_in_django)
 - RSS feed: $source
 - date published: 2024-12-29T14:18:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I am working in python package which aims to provide livereload feature in django without need to add anything in INSTALLED_APPS.</p> <p>It runs with simple command: django-quik runserver</p> <p>It also has tailwindcss support. Github url: <a href="https://github.com/tejmagar/django-quik">https://github.com/tejmagar/django-quik</a></p> <p>Feedbacks are appreciated 😄</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tejdon"> /u/tejdon </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1howw3s/livereload_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1howw3s/livereload_in_django/">[comments]</a></span>

## 10 Tools to Consider for Your Next Django Project
 - [https://www.reddit.com/r/django/comments/1hov8sn/10_tools_to_consider_for_your_next_django_project](https://www.reddit.com/r/django/comments/1hov8sn/10_tools_to_consider_for_your_next_django_project)
 - RSS feed: $source
 - date published: 2024-12-29T12:40:21+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/tamas_dev"> /u/tamas_dev </a> <br/> <span><a href="https://thinkingbytes.co.uk/posts/favourite-django-tools/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hov8sn/10_tools_to_consider_for_your_next_django_project/">[comments]</a></span>

## What’s your library “stack”?
 - [https://www.reddit.com/r/django/comments/1houdby/whats_your_library_stack](https://www.reddit.com/r/django/comments/1houdby/whats_your_library_stack)
 - RSS feed: $source
 - date published: 2024-12-29T11:41:36+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I’m switching to Django for my personal projects haven’t spent a lot of energy using Go, which I love but I have had to reimplement a lot from scratch. I’m curious to know what are your go-to libraries for the most common needs (but feel free to drop any amazing library worth mentioning) so that I can migrate what I usually do in go to Django. </p> <p>I’ll mention what I’m thinking of using so far:</p> <ul> <li><p>Django rest framework to implement rest api (I’ll focus on react + drf for my projects)</p></li> <li><p>djoser for authentication (I’d need jwt and social)</p></li> <li><p>celery for async events and crons </p></li> <li><p>throttling, I think drf offers a solution using django-redis</p></li> <li><p>Django-impersonate to impersonate users for troubleshooting purposes</p></li> <li><p>uploading files to s3 instead of local storage</p></li> <li><p>channels for webhooks and web sockets</p></li> <li><p>permissions/groups/roles to allow dis

## Created a collaborative code editor
 - [https://www.reddit.com/r/django/comments/1hos1z6/created_a_collaborative_code_editor](https://www.reddit.com/r/django/comments/1hos1z6/created_a_collaborative_code_editor)
 - RSS feed: $source
 - date published: 2024-12-29T08:50:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I’m very new to reddit and this subreddit.</p> <p>I’ve built a code editor using django channels and websockets with features like room-based sessions, cursor tracking, syntax completion, and code execution (though I haven’t added a way to specify the path for running the code yet). It’s all set up to work locally for now.</p> <p>I’d really appreciate it if you could give reviews for the project. There is also a preview.<br/> <a href="https://github.com/ShauryaDusht/CodeTogether">https://github.com/ShauryaDusht/CodeTogether</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shauryadusht"> /u/shauryadusht </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hos1z6/created_a_collaborative_code_editor/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hos1z6/created_a_collaborative_code_editor/">[comments]</a></span>

## What Do Recruiters and Employers Look for in Junior Web Developers?
 - [https://www.reddit.com/r/django/comments/1hoq5fa/what_do_recruiters_and_employers_look_for_in](https://www.reddit.com/r/django/comments/1hoq5fa/what_do_recruiters_and_employers_look_for_in)
 - RSS feed: $source
 - date published: 2024-12-29T06:34:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m a junior web developer, and I’ve been actively applying for jobs lately. I’m curious—what do recruiters and employers typically look for when hiring junior web devs? Are there specific skills, experiences, or qualities that stand out?</p> <p>I’ve primarily been applying for remote positions outside my current country of residence, the Philippines. Could this impact the hiring process? I assume it varies by country, as hiring a foreign employee often involves additional scrutiny.</p> <p>Here are the links to my resume and portfolio as reference:</p> <ul> <li><a href="https://docs.google.com/document/d/1PCKXsHPvmur7mJHSiufv_Gid5Axo4LAi/edit?usp=sharing&amp;ouid=112487098966462460918&amp;rtpof=true&amp;sd=true">Resume link</a></li> <li><a href="https://andersonportfolio.pythonanywhere.com/">Portfolio link</a></li> </ul> <p>If you’re a recruiter, employer, or someone who’s landed a junior dev position, I’d love to hear your insigh

## Not able to login in a user to my VueJS frontend which communicates with my Django backend
 - [https://www.reddit.com/r/django/comments/1hopbtj/not_able_to_login_in_a_user_to_my_vuejs_frontend](https://www.reddit.com/r/django/comments/1hopbtj/not_able_to_login_in_a_user_to_my_vuejs_frontend)
 - RSS feed: $source
 - date published: 2024-12-29T05:42:18+00:00

<!-- SC_OFF --><div class="md"><p>This is for those that are also familiar with VueJS and DRF. But I am trying to login as a user, with an email/password I just created on the Login Page. But when I click the &#39;Login&#39; button nothing happens, it should log me in and redirect me to the &#39;Homeowner Dashboard&#39; page. To clarify I got DRF set with up Django, that is I created the API calls that connect to my Django API views.</p> <p>So I&#39;m not exactly sure why this is happening, I don&#39;t know if this is strictly a VueJS, Django or DRF issue or all of them. Also when I inspect the page in the console, it just says &#39;API call successful:&#39;. I have axios implemented in my VueJS project.</p> <p>I&#39;d share my code here, however I wouldn&#39;t even know where to begin. I&#39;m simply testing my project from the frontend to the backend. I&#39;m not sure if creating a user in Django Admin would help or not. Pretty sure this is easy fix somewhere. Please help me with t

## [ERROR] ImproperlyConfigured: Error loading psycopg2 or psycopg module
 - [https://www.reddit.com/r/django/comments/1hond1l/error_improperlyconfigured_error_loading_psycopg2](https://www.reddit.com/r/django/comments/1hond1l/error_improperlyconfigured_error_loading_psycopg2)
 - RSS feed: $source
 - date published: 2024-12-29T03:47:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently trying to update a Django rest api on AWS Lambda using the following command. </p> <pre><code>zappa update dev </code></pre> <p>However it gives me the following error</p> <pre><code>Error: Warning! Status check on the deployed lambda failed. A GET request to &#39;/&#39; yielded a 502 response code. </code></pre> <p>When I run the following </p> <pre><code>zappa tail </code></pre> <p>I see the error </p> <pre><code>ImproperlyConfigured: Error loading psycopg2 or psycopg module </code></pre> <p>Does anyone know how to fix this error? I check requirements.txt file and it has the latest version of both psycopg2 and psycopg2-binary (2.9.10). I don&#39;t know why I&#39;m getting the error.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mrreddituser111312"> /u/Mrreddituser111312 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hond1l/error_improperlyconfigured_error_loading_psycop

