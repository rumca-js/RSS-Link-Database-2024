# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## (Unit) Testing without database
 - [https://www.reddit.com/r/django/comments/1gheicl/unit_testing_without_database](https://www.reddit.com/r/django/comments/1gheicl/unit_testing_without_database)
 - RSS feed: $source
 - date published: 2024-11-01T20:03:25+00:00

<!-- SC_OFF --><div class="md"><p>tldr how are you writing tests for parts of the code that are requiring ORM?</p> <p>Hiya,</p> <p>I am new to Django and looking for guidance in the area of the structuring tests.</p> <p>Component that I am working now is built on top of Netbox, but with a lot of custom code and features squeezed into plugins.</p> <p>As the code quality of the plugins is really bad, management came up with the goal of 85% statements coverage (I know, dumb as hell, especially as big chunk of this code is garbage and will be thrown out as soon as it is safe to do). So we have to write a lot of &quot;unit tests&quot; (actually I don&#39;t think they need to be unit, they just need to generate coverage).</p> <p>Okay, so wanted to start with &quot;classic&quot; unit tests, meaning no IO, everything happening in memory. First problem is that almost every method is either querying or saving something to DB. One of the colleagues started mocking every ORM call, like the retur

## Having trouble executing query via Solr UI for my Django project
 - [https://www.reddit.com/r/django/comments/1ghdhgh/having_trouble_executing_query_via_solr_ui_for_my](https://www.reddit.com/r/django/comments/1ghdhgh/having_trouble_executing_query_via_solr_ui_for_my)
 - RSS feed: $source
 - date published: 2024-11-01T19:18:44+00:00

<!-- SC_OFF --><div class="md"><p>So every time I try to execute a query in the Solr UI, I get blank (0) documents returned. Which doesn&#39;t make any sense, considering I have 4 documents that are indexed. I asked this same question about a week ago, and someone on here suggested that I set the required logging levels to &#39;Trace&#39;, which I did do in log4j2.xml. </p> <p>I also set up search_indexes.py for the indexed fields, created the txt files for each indexed, created a Solr core ( I only have one core), configured indexed fields in schema.xml, rebuilt the index with the following command `python <a href="http://manage.py">manage.py</a> rebuild_index` with this output ```DATABASE_NAME: arbordb</p> <p>DATABASE_USER: postgres</p> <p>DATABASE_PASSWORD: arborcor87</p> <p>DATABASE_HOST: localhost</p> <p>DATABASE_PORT: 5432</p> <p>WARNING: This will irreparably remove EVERYTHING from your search index in connection &#39;default&#39;.</p> <p>Your choices after this are to restore

## Tell one hard truth to provoke a "lazy" Jnr. dev to be serious.
 - [https://www.reddit.com/r/django/comments/1ghbku3/tell_one_hard_truth_to_provoke_a_lazy_jnr_dev_to](https://www.reddit.com/r/django/comments/1ghbku3/tell_one_hard_truth_to_provoke_a_lazy_jnr_dev_to)
 - RSS feed: $source
 - date published: 2024-11-01T17:56:47+00:00

<!-- SC_OFF --><div class="md"><p>As an experienced developer, what hard truths do you have tell a Jnr Dev to wake up from his slumber and be serious and thrive in this software development industry.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/primado_"> /u/primado_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ghbku3/tell_one_hard_truth_to_provoke_a_lazy_jnr_dev_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ghbku3/tell_one_hard_truth_to_provoke_a_lazy_jnr_dev_to/">[comments]</a></span>

## Practice with system design interview book
 - [https://www.reddit.com/r/django/comments/1gh8g4v/practice_with_system_design_interview_book](https://www.reddit.com/r/django/comments/1gh8g4v/practice_with_system_design_interview_book)
 - RSS feed: $source
 - date published: 2024-11-01T15:44:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m currently reading <em>System Design Interview</em> by Alex Xu. A lot of the concepts, such as setting up a server with a load balancer, implementing a rate limiter, using a consistent hash ring, and others, are new to me. I&#39;m wondering if there are any resources, like a GitHub repository, where I could practice these concepts with step-by-step instructions. </p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jacky171_96"> /u/jacky171_96 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gh8g4v/practice_with_system_design_interview_book/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gh8g4v/practice_with_system_design_interview_book/">[comments]</a></span>

## Feature Friday: LoginRequiredMiddleware!
 - [https://www.reddit.com/r/django/comments/1gh51ai/feature_friday_loginrequiredmiddleware](https://www.reddit.com/r/django/comments/1gh51ai/feature_friday_loginrequiredmiddleware)
 - RSS feed: $source
 - date published: 2024-11-01T13:11:46+00:00

<!-- SC_OFF --><div class="md"><p>The <code>LoginRequiredMiddleware</code> (new in Django 5.1) is great for any Django app that is mostly behind authentication. When enabled, views will require login by default. No more <code>login_required</code> decorators everywhere!</p> <p>So how do you make a view <em>not</em> require login?</p> <p>Use the new <code>login_not_required</code> decorator! This works just like the <code>login_required</code> decorator but for the opposite: any view it decorates will bypass the login requirement and be public. Be sure to put it on your login page otherwise you might get caught in redirect loops!</p> <p>If you&#39;re building an app that mostly requires login, using the <code>LoginRequiredMiddleware</code> is a great way to simplify code and prevent accidentally leaking content—by making your app private by default.</p> <p>Read more in the documentation here: <a href="https://docs.djangoproject.com/en/5.1/ref/middleware/#django.contrib.auth.middleware

## Django ORM Race Condition tip
 - [https://www.reddit.com/r/django/comments/1gh4ep2/django_orm_race_condition_tip](https://www.reddit.com/r/django/comments/1gh4ep2/django_orm_race_condition_tip)
 - RSS feed: $source
 - date published: 2024-11-01T12:40:34+00:00

<!-- SC_OFF --><div class="md"><p>Suppose we have a &#39;Product&#39; model with a &#39;quantity&#39; field and we want to increment the quantity by a specific value.</p> <p>The code using the &#39;F&#39; expression avoids retrieving the &#39;quantity&#39; value from the database into Python memory. It performs the increment operation directly at the database level, reducing unnecessary database round-trips.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://i.redd.it/69i18lndcayd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gh4ep2/django_orm_race_condition_tip/">[comments]</a></span>

## Identifying same images by giving hash values in django using celery and redis
 - [https://www.reddit.com/r/django/comments/1gh2wr1/identifying_same_images_by_giving_hash_values_in](https://www.reddit.com/r/django/comments/1gh2wr1/identifying_same_images_by_giving_hash_values_in)
 - RSS feed: $source
 - date published: 2024-11-01T11:14:21+00:00

<!-- SC_OFF --><div class="md"><p>How can i do this? My goal is to take two images and the images should be assigned hash values,based on the image names</p> <p>If two pics got same hashvalue,they will have same hash values and only one will be saved by redis </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Theonewhomogged_"> /u/Theonewhomogged_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gh2wr1/identifying_same_images_by_giving_hash_values_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gh2wr1/identifying_same_images_by_giving_hash_values_in/">[comments]</a></span>

## Login for different Users
 - [https://www.reddit.com/r/django/comments/1gh1ka1/login_for_different_users](https://www.reddit.com/r/django/comments/1gh1ka1/login_for_different_users)
 - RSS feed: $source
 - date published: 2024-11-01T09:39:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi I&#39;m new to django. I&#39;m currently doing a project Event management like a wedding, corporate conference, or community festival, involves coordinating various elements, such as budgets, vendors, guest lists, and schedules. I&#39;m using django rest framework and React vite. So to start i want different login for planners , vendors , guests , admin. So should I create a single model for storing all the user credentials ? How to differentiate various user types like for planners they can view edit and book events , and for guests only viewing etc .</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Eugene_33"> /u/Eugene_33 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gh1ka1/login_for_different_users/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gh1ka1/login_for_different_users/">[comments]</a></span>

## iommi 7.7.0 released
 - [https://www.reddit.com/r/django/comments/1gh17g6/iommi_770_released](https://www.reddit.com/r/django/comments/1gh17g6/iommi_770_released)
 - RSS feed: $source
 - date published: 2024-11-01T09:11:38+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://docs.iommi.rocks/">https://docs.iommi.rocks/</a></p> <p>News:</p> <ul> <li>Upgraded default Bootstrap version that now includes automatic dark mode</li> <li>New crud_views() function added. Create an entire CRUD for a model in a single line (more on that here: <a href="https://kodare.net/2024/10/15/implementing-neapolitan-in-iommi.html">https://kodare.net/2024/10/15/implementing-neapolitan-in-iommi.html</a>)</li> <li>iommi now ships with some views that you probably need: login, logout, change_password</li> <li>Added CSS Frameworks: Vanilla CSS, US Web Design System</li> <li>Form.create_or_edit() added</li> <li>EditTable now supports 1-to-1 fields</li> <li>Significant performance improvemnets</li> <li>Many bug fixes and smaller features</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gh17g6/iommi_770_re

## Django Brute Force Attacks tip
 - [https://www.reddit.com/r/django/comments/1gh0i70/django_brute_force_attacks_tip](https://www.reddit.com/r/django/comments/1gh0i70/django_brute_force_attacks_tip)
 - RSS feed: $source
 - date published: 2024-11-01T08:14:13+00:00

<!-- SC_OFF --><div class="md"><p>In this example, the (AUTHENTICATION_LOCKOUT_THRESHOLD) setting specifies the maximum number of login attempts before an account is locked, and the (AUTHENTICATION_LOCKOUT_DURATION) setting specifies the duration of the account lockout in seconds.</p> <p>Additionally, the (AUTH_PASSWORD_MIN_LENGTH) setting specifies the minimum password length required, and the (AUTH_PASSWORD_VALIDATORS) setting defines a list of password validation requirements.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://i.redd.it/a6dvlciv09yd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gh0i70/django_brute_force_attacks_tip/">[comments]</a></span>

## LSP server in django
 - [https://www.reddit.com/r/django/comments/1ggznuk/lsp_server_in_django](https://www.reddit.com/r/django/comments/1ggznuk/lsp_server_in_django)
 - RSS feed: $source
 - date published: 2024-11-01T07:04:20+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I want to create a LSP server in django, that could communicate with monaco code editor in javascript at front end. I&#39;ve done some googling but unable to get directions. If anyone can guide me in correct directions, that would be great. </p> <p>I&#39;m experienced developer but relatively new in django. Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/haris_008"> /u/haris_008 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ggznuk/lsp_server_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ggznuk/lsp_server_in_django/">[comments]</a></span>

## Seeking Guidance: Deploying Django App on Coolify - Best Practices and Step-by-Step Guide
 - [https://www.reddit.com/r/django/comments/1ggze2c/seeking_guidance_deploying_django_app_on_coolify](https://www.reddit.com/r/django/comments/1ggze2c/seeking_guidance_deploying_django_app_on_coolify)
 - RSS feed: $source
 - date published: 2024-11-01T06:43:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi fellow Redditors,</p> <p>I&#39;m a beginner seeking help deploying my Django web application on Coolify. Here&#39;s my setup:</p> <ul> <li>Django web app with MySQL database</li> <li>Developed locally using Apache XAMPP</li> <li>Migrated and running smoothly on localhost</li> <li>Code is ready in a folder (not on Git)</li> </ul> <p>I&#39;ve met Coolify&#39;s minimum requirements and successfully deployed a test Next.js application. However, when I try to access the deployed domain, it doesn&#39;t load.I&#39;m looking for guidance on:</p> <ol> <li>Preparing my Django project for Coolify deployment</li> <li>Configuring database settings (MySQL) on Coolify</li> <li>Handling static and media files</li> <li>Environment variables and settings</li> <li>Troubleshooting common deployment issues</li> </ol> <p>Specific questions:</p> <ul> <li>Do I need to modify my Django (link unavailable) file for Coolify?</li> <li>How do I connect my MySQL database to Coo

## Need help in a project deployment not sure how to do so no clear lectures to help
 - [https://www.reddit.com/r/django/comments/1ggyxse/need_help_in_a_project_deployment_not_sure_how_to](https://www.reddit.com/r/django/comments/1ggyxse/need_help_in_a_project_deployment_not_sure_how_to)
 - RSS feed: $source
 - date published: 2024-11-01T06:07:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I&#39;m a intermediate programmer trying to deploy my Django project. I&#39;ve been following tutorials and documentation, but I&#39;m still running into issues. Specific Problems I&#39;m Facing: * Heroku: * Configuring the Procfile * Setting up the requirements.txt file * Deploying static files * Connecting to a database (Heroku Postgres) * PythonAnywhere: * Creating a virtual environment * Configuring the WSGI file * Deploying static files I&#39;ve tried troubleshooting by checking logs, adjusting settings, and following online guides, but I&#39;m still stuck. Any advice or tips would be greatly appreciated. I&#39;m open to using other platforms or services if they might be easier. Thanks in advance for your help! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rahwik"> /u/rahwik </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ggyxse/need_help_in_a_project_deployment_not_sure_

## run local server without manage.py ?
 - [https://www.reddit.com/r/django/comments/1ggw79j/run_local_server_without_managepy](https://www.reddit.com/r/django/comments/1ggw79j/run_local_server_without_managepy)
 - RSS feed: $source
 - date published: 2024-11-01T03:08:38+00:00

<!-- SC_OFF --><div class="md"><p>How to run local server without using manage.py file ? Like do it manually through my new file !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shaheen-vsa"> /u/shaheen-vsa </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ggw79j/run_local_server_without_managepy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ggw79j/run_local_server_without_managepy/">[comments]</a></span>

