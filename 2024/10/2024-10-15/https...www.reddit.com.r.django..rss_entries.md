# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Possible to move apps to multiple folders without modification?
 - [https://www.reddit.com/r/django/comments/1g4kt6d/possible_to_move_apps_to_multiple_folders_without](https://www.reddit.com/r/django/comments/1g4kt6d/possible_to_move_apps_to_multiple_folders_without)
 - RSS feed: $source
 - date published: 2024-10-15T22:53:15+00:00

<!-- SC_OFF --><div class="md"><p>The number of apps in one of my Django projects is causing it to become cluttered. I&#39;d like to organize them by placing them in multiple folders, but I don&#39;t want the apps to depend on having that particular folder structure. </p> <p>I made a few attempts at this, but something always seems to break (e.g. migrations, management commands, tests). Is this possible?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FilmWeasle"> /u/FilmWeasle </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g4kt6d/possible_to_move_apps_to_multiple_folders_without/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g4kt6d/possible_to_move_apps_to_multiple_folders_without/">[comments]</a></span>

## Scaling apps individually
 - [https://www.reddit.com/r/django/comments/1g4ju05/scaling_apps_individually](https://www.reddit.com/r/django/comments/1g4ju05/scaling_apps_individually)
 - RSS feed: $source
 - date published: 2024-10-15T22:08:00+00:00

<!-- SC_OFF --><div class="md"><p>I thought about this today when answering a question. </p> <p>Are there any projects or library out there that specializes in deploying and scaling the Django apps separately? I.e if you have a products app for a merchant application, and there’s a high influx of search using the product api but no transactions . </p> <p>The project would scale the product app but not payment app to better utilize resources. </p> <p>Yes I know Django is a deeply coupled monolith but I’m more so curious if anyone has tried to address this disadvantage of being a monolith. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Even-Advertising-332"> /u/Even-Advertising-332 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g4ju05/scaling_apps_individually/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g4ju05/scaling_apps_individually/">[comments]</a></span>

## Which front-end framework should I start with for my first side project in Django?
 - [https://www.reddit.com/r/django/comments/1g4jl0g/which_frontend_framework_should_i_start_with_for](https://www.reddit.com/r/django/comments/1g4jl0g/which_frontend_framework_should_i_start_with_for)
 - RSS feed: $source
 - date published: 2024-10-15T21:56:44+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,<br/> 34M here, working as a backend developer for over 10 years, though not in Python or web development. Recently, I’ve taken the time to learn Django, and I’ve built a few simple pages with it. I’m also pretty comfortable with the basics of web development—things like JS, HTML, and CSS.</p> <p>For my side project, I’m planning to use Django and Django Rest Framework (DRF) to handle the backend, and I don’t foresee any major issues with that. However, I’ve never really designed or built a solid front-end. I’m looking for recommendations on what front-end framework I should start with for a more substantial project.</p> <p><strong>What would you recommend for someone like me who’s a beginner to front-end (but not completely clueless) in terms of frameworks, templates, or tools?</strong></p> <p>Bonus points if you can point me to some tutorials, GitHub repos, or other resources where I can see how things are done! Thanks!</p> </div><!-- S

## What steps should I take to separate my web hosting from my backend hosting?
 - [https://www.reddit.com/r/django/comments/1g4if0z/what_steps_should_i_take_to_separate_my_web](https://www.reddit.com/r/django/comments/1g4if0z/what_steps_should_i_take_to_separate_my_web)
 - RSS feed: $source
 - date published: 2024-10-15T21:05:05+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to Django and started a traditional django project that runs an AI model and returns the results to the user. I dockerized it and used celery with redis for task scheduling. I recently got advice that I should separate my webhosting from my AI model hosting to avoid running the web server on high-GPU hardware used to run the AI software and increase efficiency/reduce cost. How do I do it? I just read a book on Django REST which went over some simple projects built using REST APIs but I&#39;m really not sure what my next steps should be. Would really like some guidance. What I&#39;m thinking is to setup the backend on something like Google Cloud/Hetzner/Vast.ai/Digital Ocean then connect to a frontend hosting elsewhere(like Heroku) using a REST API. But I don&#39;t know how to do that for a dockerized django project. My frontend(html, css,js) and file storage is already completed.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="h

## Django tenant-specific migrations issue: relation does not exist after applying custom migrations
 - [https://www.reddit.com/r/django/comments/1g4hy4k/django_tenantspecific_migrations_issue_relation](https://www.reddit.com/r/django/comments/1g4hy4k/django_tenantspecific_migrations_issue_relation)
 - RSS feed: $source
 - date published: 2024-10-15T20:45:05+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a Django multi-tenant setup where each tenant has a separate database. I have custom migration directories for each tenant. After running <code>migrate_tenant</code> for a tenant, the migration completes successfully, but when trying to query the table in the admin or the Django shell, I get an error: <code>relation &quot;custom_migrations_customer&quot; does not exist</code>.</p> <ul> <li>I’m using PostgreSQL for the tenant databases.</li> <li>The migration files are stored in custom locations (<code>localhost_migrations</code>).</li> <li>The table does not appear in the PostgreSQL schema.</li> </ul> <p>Steps taken so far:</p> <ul> <li>Ensured <code>MIGRATION_MODULES</code> points to the correct path.</li> <li>Verified database connection during migrations.</li> <li>Manually checked the schema in PostgreSQL.</li> </ul> <p>Any help or guidance would be appreciated. Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href

## Django for large scale projects
 - [https://www.reddit.com/r/django/comments/1g4dxkk/django_for_large_scale_projects](https://www.reddit.com/r/django/comments/1g4dxkk/django_for_large_scale_projects)
 - RSS feed: $source
 - date published: 2024-10-15T17:55:54+00:00

<!-- SC_OFF --><div class="md"><p>Why do people say Django is mostly used for small - mid sized applications. Why, isn&#39;t Django a Framework? Are there limitations to it? Why do developers say that? </p> <p>Have you built any large scale application(s) with Django? Speak your truth</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/primado_"> /u/primado_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g4dxkk/django_for_large_scale_projects/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g4dxkk/django_for_large_scale_projects/">[comments]</a></span>

## Integrating markdownx within Admin Interface
 - [https://www.reddit.com/r/django/comments/1g4dx74/integrating_markdownx_within_admin_interface](https://www.reddit.com/r/django/comments/1g4dx74/integrating_markdownx_within_admin_interface)
 - RSS feed: $source
 - date published: 2024-10-15T17:55:27+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m currently using <strong>`markdownx`</strong> in my Django project and could use some advice. Has anyone here worked with it?</p> <p>I’m having trouble with the UI, basic stuff like headings (like <code># Headings</code>) showing up blank. Has anyone faced that? How did you fix it?</p> <p>If I&#39;m being honest, I would love to avoid the UI issues and just upload <code>.md</code> files instead of dealing with it? Thoughts on how I can do that? That would be super helpful!</p> <p>If you have any tips on using markdownx or modifications that made it work better for you, I’d love to hear them.</p> <p>Thanks a bunch!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Old_Friend166"> /u/Old_Friend166 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g4dx74/integrating_markdownx_within_admin_interface/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/commen

## Is there any client side state management mechanism in Django or within the Django ecosystem? Not DRF + React or something like that, just pure Django framework and maybe one JS library you can add.
 - [https://www.reddit.com/r/django/comments/1g4a812/is_there_any_client_side_state_management](https://www.reddit.com/r/django/comments/1g4a812/is_there_any_client_side_state_management)
 - RSS feed: $source
 - date published: 2024-10-15T15:20:12+00:00

<!-- SC_OFF --><div class="md"><p>Recently, I&#39;ve decided to purely use Django for any and all development I do for my own projects. I&#39;ve got some experience with Django, and I&#39;ve used Django REST Framework + React as well as Next JS, but I just don&#39;t like developing using JavaScript frameworks. Just a personal preference.</p> <p>With React, you have the Context API. Using the modular approach where you have a separate DRF backend and a frontend project using React, you can also use Redux or any other state management library that sits well inside the React ecosystem.</p> <p>I&#39;m curious if there&#39;s something equivalent for Django i.e. a client-side state management mechanism that I can plug into my templates.</p> <p>As a contextual sample, I once developed a transcript editor using React. It had the audio controls for pause/play/fast forward/rewind as well as a playback progress tracker. I hid the default audio player and redeveloped an audio player using custom 

## Dockerizing a Django and React Application: Docker + Django + React
 - [https://www.reddit.com/r/django/comments/1g4767r/dockerizing_a_django_and_react_application_docker](https://www.reddit.com/r/django/comments/1g4767r/dockerizing_a_django_and_react_application_docker)
 - RSS feed: $source
 - date published: 2024-10-15T13:02:20+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/NoSEVDev"> /u/NoSEVDev </a> <br/> <span><a href="https://slimsaas.com/blog/docker-django-react">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g4767r/dockerizing_a_django_and_react_application_docker/">[comments]</a></span>

## Efficient and correct method to check for unique strings in models with users uploading 10000s of strings
 - [https://www.reddit.com/r/django/comments/1g45wx6/efficient_and_correct_method_to_check_for_unique](https://www.reddit.com/r/django/comments/1g45wx6/efficient_and_correct_method_to_check_for_unique)
 - RSS feed: $source
 - date published: 2024-10-15T11:58:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi,<br/> Thank you for reading this.</p> <p>I am making an app where users can upload their bookmarks. Let&#39;s make the problem difficult by saying each user has 10,000 bookmarks.</p> <p>Once they upload the bookmarks, I extract the urls uptil &quot;?&quot;.</p> <p>I have a model which stores unique links uploaded.</p> <p>So if I have a url in the model already existing, I can&#39;t create a new one.</p> <p>As this is a major use-case, I want to optimise this for best performance.</p> <p>Imagine a scenario where a user has uploaded 10000 unique urls. I have them saved to db. Now, another user comes in and adds another 10000 urls, out of which 3000 are matching.</p> <p>Imagine this happening 100 times a day, if I assume 100 people signup per day for my app.</p> <p>Best solutions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ib_bunny"> /u/ib_bunny </a> <br/> <span><a href="https://www.reddit.com/r/django/comme

## Hi! 😊 I'm a self-taught backend developer
 - [https://www.reddit.com/r/django/comments/1g432ly/hi_im_a_selftaught_backend_developer](https://www.reddit.com/r/django/comments/1g432ly/hi_im_a_selftaught_backend_developer)
 - RSS feed: $source
 - date published: 2024-10-15T08:39:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve learned Django, REST API, Docker just finished learning it today and it was easy and fun , and many other skills. Here’s a list of what I&#39;ve learned so far: django Django rest Docker javaScript MySQL Git/GitHub Django channels html and css I&#39;ve also completed several projects, including: ecommerce website Real-time chat app To-do list app CRUD application Portfolio website</p> <p>I’m not sure what to learn next to land a job i have nobdy to guide my what to do next im right know in a rabbit hole . Any advice would be awesome! 🙏</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aromatic_Leg9829"> /u/Aromatic_Leg9829 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g432ly/hi_im_a_selftaught_backend_developer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g432ly/hi_im_a_selftaught_backend_developer/">[comments]</a></span>

## Creating a login page with dj-rest-auth with data from my database
 - [https://www.reddit.com/r/django/comments/1g42r7q/creating_a_login_page_with_djrestauth_with_data](https://www.reddit.com/r/django/comments/1g42r7q/creating_a_login_page_with_djrestauth_with_data)
 - RSS feed: $source
 - date published: 2024-10-15T08:12:53+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using Rest Framework to display data from my database and I want to create a login page using the same credentials and restrictions from that database. Is there a way to do that with dj-rest-auth? If not what should i use? Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bobbypenut"> /u/bobbypenut </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g42r7q/creating_a_login_page_with_djrestauth_with_data/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g42r7q/creating_a_login_page_with_djrestauth_with_data/">[comments]</a></span>

## Help in visualizing database schemas
 - [https://www.reddit.com/r/django/comments/1g42lt0/help_in_visualizing_database_schemas](https://www.reddit.com/r/django/comments/1g42lt0/help_in_visualizing_database_schemas)
 - RSS feed: $source
 - date published: 2024-10-15T08:00:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone , i just wanna know what toot or library or package do you use to visualize djando models , i am using postgresql db , thanks in advance </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/L4z3x"> /u/L4z3x </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g42lt0/help_in_visualizing_database_schemas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g42lt0/help_in_visualizing_database_schemas/">[comments]</a></span>

## Implementing Neapolitan in iommi
 - [https://www.reddit.com/r/django/comments/1g427n9/implementing_neapolitan_in_iommi](https://www.reddit.com/r/django/comments/1g427n9/implementing_neapolitan_in_iommi)
 - RSS feed: $source
 - date published: 2024-10-15T07:28:22+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://kodare.net/2024/10/15/implementing-neapolitan-in-iommi.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g427n9/implementing_neapolitan_in_iommi/">[comments]</a></span>

## Django project deploy
 - [https://www.reddit.com/r/django/comments/1g405zk/django_project_deploy](https://www.reddit.com/r/django/comments/1g405zk/django_project_deploy)
 - RSS feed: $source
 - date published: 2024-10-15T05:00:36+00:00

<!-- SC_OFF --><div class="md"><p>I am working on a django project and my manager have created a repository on github for it. He added the virtual environment and i am now having issues stating that python is not there. I check the system variable and everyhing looks fine there. What coukd be the problem? I am new to django and couldnt find a solution online. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dry_Ad4465"> /u/Dry_Ad4465 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g405zk/django_project_deploy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g405zk/django_project_deploy/">[comments]</a></span>

## Django admin email - hide settings variables
 - [https://www.reddit.com/r/django/comments/1g3vgnj/django_admin_email_hide_settings_variables](https://www.reddit.com/r/django/comments/1g3vgnj/django_admin_email_hide_settings_variables)
 - RSS feed: $source
 - date published: 2024-10-15T00:44:43+00:00

<!-- SC_OFF --><div class="md"><p>I recently integrated Celery and Celery beat into my Django project and decided to use the database instead of Redis or similar tools. In my settings.py file I have a Celery setting that looks like: CELERY_BROKER_URL = sqla+postgresql://user:<a href="mailto:pwd@127.0.0.1">pwd@127.0.0.1</a>:5432/dbname</p> <p>The problem here is that in the admin emails tracestack that we receive does not hide the value of CELERY_BROKER_URL, fully exposing the username and password. </p> <p>Has anyone been able to redact/hide sensitive variables that are in their settings.py file when receiving admin emails?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/enriqc3"> /u/enriqc3 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g3vgnj/django_admin_email_hide_settings_variables/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g3vgnj/django_admin_email_hide_settings_variables/">[comme

