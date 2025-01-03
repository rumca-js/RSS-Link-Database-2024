# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## should i add the keywords meta to my head tag?
 - [https://www.reddit.com/r/django/comments/1h57unq/should_i_add_the_keywords_meta_to_my_head_tag](https://www.reddit.com/r/django/comments/1h57unq/should_i_add_the_keywords_meta_to_my_head_tag)
 - RSS feed: $source
 - date published: 2024-12-02T22:31:20+00:00

<!-- SC_OFF --><div class="md"><p>I understand that until recently this has been the norm. However, i just finished a frontend dev course with Meta, and they basically said that if add the keywords tag to your head, crawlers will immediately mark your website as spam. I want to deploy my website with the best possible SEO but i don&#39;t wanna risk it. what do i do?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h57unq/should_i_add_the_keywords_meta_to_my_head_tag/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h57unq/should_i_add_the_keywords_meta_to_my_head_tag/">[comments]</a></span>

## problems with a many to many relationship.
 - [https://www.reddit.com/r/django/comments/1h54vvj/problems_with_a_many_to_many_relationship](https://www.reddit.com/r/django/comments/1h54vvj/problems_with_a_many_to_many_relationship)
 - RSS feed: $source
 - date published: 2024-12-02T20:29:30+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m picking Django up after a long time away. I&#39;m struggling with something which i feel is probably really basic, so apologies if you clicked this thread looking for a really tricky puzzle to solve.</p> <p>my models.</p> <p>```</p> <h1>coaches/models.py</h1> <p>class Coach(models.Model): club = models.ForeignKey(Club, on_delete=models.CASCADE) name = models.CharField(max_length=200) email = models.EmailField(unique=True) phone = models.CharField(max_length=20)</p> <p>```</p> <p>``` teams/models.py</p> <p>class Team(models.Model): name = models.CharField(max_length=200) club = models.ForeignKey(&#39;clubs.Club&#39;, on_delete=models.CASCADE) coaches = models.ManyToManyField(Coach, related_name=&#39;teams&#39;) players = models.ManyToManyField(Player, related_name=&#39;teams&#39;)</p> <p>```</p> <p>This is the view in code. </p> <p>``` def team(request): &quot;&quot;&quot; present the user with a list of teams to choose from based on their use

## Django-mixin - A set of Grafana dashboards and Prometheus rules for Django!
 - [https://www.reddit.com/r/django/comments/1h54l5h/djangomixin_a_set_of_grafana_dashboards_and](https://www.reddit.com/r/django/comments/1h54l5h/djangomixin_a_set_of_grafana_dashboards_and)
 - RSS feed: $source
 - date published: 2024-12-02T20:17:25+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>Repository url: <a href="https://github.com/adinhodovic/django-mixin">https://github.com/adinhodovic/django-mixin</a></p> <p>I&#39;ve built a monitoring-mixin for Django-prometheus. A monitoring mixin is a set of Grafana dashboards and Prometheus rules written in Jsonnet. There are several others such as <a href="https://github.com/kubernetes-monitoring/kubernetes-mixin">https://github.com/kubernetes-monitoring/kubernetes-mixin</a> so I thought of writing one for Django.</p> <p>I also have a blog post on this topic: <a href="https://hodovi.cc/blog/django-monitoring-with-prometheus-and-grafana/">https://hodovi.cc/blog/django-monitoring-with-prometheus-and-grafana/</a>.</p> <p>There&#39;s also dashboard preview images in the repository. Looking for any input to hopefully standardize Grafana dashboards and Prometheus alerts for Django over time!</p> <p>Maybe useful for some! Thanks for taking a look.</p> </div><!-- SC_ON --> &#32; submitted 

## Error Loading MySQLdb Module in Django!
 - [https://www.reddit.com/r/django/comments/1h54k20/error_loading_mysqldb_module_in_django](https://www.reddit.com/r/django/comments/1h54k20/error_loading_mysqldb_module_in_django)
 - RSS feed: $source
 - date published: 2024-12-02T20:16:10+00:00

<!-- SC_OFF --><div class="md"><p>hmm I need help!</p> <p>I already installed mysqlclient, but whenever I try to run python <a href="http://manage.py/">manage.py</a> makemigrations I get this error:</p> <p>(I had just updated my MariaDB and I don&#39;t know if I&#39;m facing this problem because of it or not.)</p> <p>(.venv) PS C:\xampp\htdocs\Django_project&gt; python <a href="http://manage.py/">manage.py</a> makemigrations</p> <p>Traceback (most recent call last):</p> <p>File &quot;C:\xampp\htdocs\Django_project\.venv\Lib\site-packages\django\db\backends\mysql\base.py&quot;, line 16, in &lt;module&gt;</p> <p>import MySQLdb as Database</p> <p>ModuleNotFoundError: No module named &#39;MySQLdb&#39;</p> <p>The above exception was the direct cause of the following exception:</p> <p>Traceback (most recent call last):</p> <p>File &quot;C:\xampp\htdocs\Django_project\manage.py&quot;, line 22, in &lt;module&gt;</p> <p>main()</p> <p>File &quot;C:\xampp\htdocs\Django_project\manage.py&quot;, 

## Best practice for self deployable open source Django project
 - [https://www.reddit.com/r/django/comments/1h54h76/best_practice_for_self_deployable_open_source](https://www.reddit.com/r/django/comments/1h54h76/best_practice_for_self_deployable_open_source)
 - RSS feed: $source
 - date published: 2024-12-02T20:12:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I am working on a simple Django app for monitoring the progress of <a href="https://snakemake.github.io/">Snakemake</a> workflows. For context, Snakemake is a workflow manager, largely targeted towards life sciences (bioinformatics, genomics, etc). It is run on the command line and currently lacks a good way to monitor the progress of your workflows (they can run for weeks in some cases). </p> <p>I have experience building Django webapps and deploying them for myself. However with this, I would like to make the whole webapp a pip installable package such that users can just install via pip and spin up the server. This is extremely important, as in order for this to be a useful tool, the barrier to entry should be very low for users with little technical experience.</p> <p>I have already worked out how the workflows will communicate with the running Django server. My general idea is this:</p> <ol> <li>User starts the server</li> <li>Use

## Django | Django-Ninja async for OpenAI assistants
 - [https://www.reddit.com/r/django/comments/1h54cve/django_djangoninja_async_for_openai_assistants](https://www.reddit.com/r/django/comments/1h54cve/django_djangoninja_async_for_openai_assistants)
 - RSS feed: $source
 - date published: 2024-12-02T20:07:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I started testing OpenAI&#39;s new assistants API, which can automatically vectorize , and search in your uploaded files.</p> <p>I tried it out, and although it&#39;s painfully slow at the moment, it&#39;s also working flawlessly.</p> <p>Response times can vary from 3 to 10 seconds which is awful, but for me it&#39;s OK since this will only be used internally.</p> <p>Now, i&#39;ve been running my django app with gunicorn using WSGI, so every view , every API endpoint is sync.</p> <p>I have 0 experience when it comes to async, but with some examples written by OpenAI themselves i created an async version of this API.</p> <p>The whole app runs on a small VPS with 2 vCPU but i don&#39;t want to accidently block the whole app with a few users calling this endpoint at the same time.</p> <p>Is anyone using Django with 99% sync views and 1% async?</p> <p>Is it a good idea to mix and match? Should i try to handle this with my celery worke

## Django and mongo
 - [https://www.reddit.com/r/django/comments/1h543v4/django_and_mongo](https://www.reddit.com/r/django/comments/1h543v4/django_and_mongo)
 - RSS feed: $source
 - date published: 2024-12-02T19:57:55+00:00

<!-- SC_OFF --><div class="md"><p>It seems to me that there&#39;s no perfect way to use MongoDB in django. I mean as the user model and all. It seems like everything breaks and I have to rewrite a lot of functionalities and then more things break. I&#39;d have been lost with AI. I would like to know if there&#39;s are resources that actually document how to go about connect django fully with mongo. Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WayAndMeans01"> /u/WayAndMeans01 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h543v4/django_and_mongo/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h543v4/django_and_mongo/">[comments]</a></span>

## Which tech stack is a better choice?
 - [https://www.reddit.com/r/django/comments/1h53knt/which_tech_stack_is_a_better_choice](https://www.reddit.com/r/django/comments/1h53knt/which_tech_stack_is_a_better_choice)
 - RSS feed: $source
 - date published: 2024-12-02T19:36:00+00:00

<!-- SC_OFF --><div class="md"><p>Does Django for backend and svelte for frontend ideal tech stack for quick mvp development?</p> <p>How about Django, tailwindcss , and htmx?</p> <p>For db I’d go with PostgreSQL.</p> <p>Looking for honest answers, advice, possible mentorship, and tips.</p> <p>I would like to build small startups to build up a portfolio and gain these awesome skills.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WynActTroph"> /u/WynActTroph </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h53knt/which_tech_stack_is_a_better_choice/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h53knt/which_tech_stack_is_a_better_choice/">[comments]</a></span>

## Django error after splitting models to separate apps
 - [https://www.reddit.com/r/django/comments/1h51230/django_error_after_splitting_models_to_separate](https://www.reddit.com/r/django/comments/1h51230/django_error_after_splitting_models_to_separate)
 - RSS feed: $source
 - date published: 2024-12-02T17:54:47+00:00

<!-- SC_OFF --><div class="md"><p>I had 2 models and I decided to move one of them into a new app. Now whenever I call makemigrations I get the error &quot;original_app.models.MODELNAME doesn&#39;t declare an explicit app_label and isn&#39;t in an application in INSTALLED_APPS.&quot;.</p> <p>The original app is in installed apps. Any help with this issue?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legitimate_Trade_285"> /u/Legitimate_Trade_285 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h51230/django_error_after_splitting_models_to_separate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h51230/django_error_after_splitting_models_to_separate/">[comments]</a></span>

## One-Click Deployment tool for Docker Apps (First Stable Release 0.2.0)
 - [https://www.reddit.com/r/django/comments/1h50zfj/oneclick_deployment_tool_for_docker_apps_first](https://www.reddit.com/r/django/comments/1h50zfj/oneclick_deployment_tool_for_docker_apps_first)
 - RSS feed: $source
 - date published: 2024-12-02T17:51:52+00:00

<!-- SC_OFF --><div class="md"><p>Hey Django devs! 👋</p> <p>I&#39;m excited to share Leverans, a deployment tool I&#39;ve been working on that makes getting your apps online stupid simple. Here&#39;s why you might love it:</p> <p>🚀 Key Features:</p> <ul> <li>Deploy ANY Docker-based app with a single command</li> <li>No vendor lock-in</li> <li>Works on minimal hardware (just 0.5 vCPU, 500 MB RAM)</li> <li>CLI-based with super simple config</li> <li>No need for SSH, external services, or complex setups</li> </ul> <p>Why I built this: Deploying apps is a pain. Existing tools are either too complex or too restrictive. Leverans fixes that.</p> <p>For example, this is all you need to describe a simple Django project:</p> <p>```yaml</p> <p>project: django</p> <p>apps:</p> <p>main:</p> <p>domain: <a href="http://your-domain.com">your-domain.com</a></p> <p>port: 8000</p> <p>volumes:</p> <p>django-sqlite: /data</p> <p>```</p> <p>And run the `lev deploy` command. And that&#39;s it, your applica

## How can I deploy my web app (django+react)?
 - [https://www.reddit.com/r/django/comments/1h50h20/how_can_i_deploy_my_web_app_djangoreact](https://www.reddit.com/r/django/comments/1h50h20/how_can_i_deploy_my_web_app_djangoreact)
 - RSS feed: $source
 - date published: 2024-12-02T17:31:21+00:00

<!-- SC_OFF --><div class="md"><p>For the past few months, I’ve been working on a web app—a Reddit clone—using Django for the backend and React for the frontend. The app focuses on stock market tickers, allowing users to post and discuss specific securities, similar to how Reddit functions.</p> <p>This is my first time building something like this, and I don’t have a background in computer science. Now, I’m ready to take the next step and deploy my app, but I have no idea where to start.</p> <p>I’ve heard about AWS, Azure, and other hosting platforms, but I’m not sure which one would be best for a beginner like me. I’d really appreciate any guidance, resources, or tutorials (e.g., YouTube videos, step-by-step guides) that can help me with deployment.</p> <p>Thanks in advance for your help! </p> <p><a href="https://preview.redd.it/qgtsvufq2h4e1.png?width=3014&amp;format=png&amp;auto=webp&amp;s=d03eb01a358d278054906ffbd06645c39bd94d2a">login page</a></p> <p><a href="https://preview.red

## Best practice for autocomplete on a ModelChoiceField with ~10'000 entries
 - [https://www.reddit.com/r/django/comments/1h4zbyn/best_practice_for_autocomplete_on_a](https://www.reddit.com/r/django/comments/1h4zbyn/best_practice_for_autocomplete_on_a)
 - RSS feed: $source
 - date published: 2024-12-02T16:44:47+00:00

<!-- SC_OFF --><div class="md"><p>Dear Django community,</p> <p>I am using the modern standard of Django + HTMX + Crispy. As part of a form, I would like the user to select one of 10&#39;000 clients. The user should type in a few letters of either the first name or the last name and then get a dropdown of matching clients and be able to click on one of them.</p> <p>So far, I explored and considered the following options:<br/> 1. I could build it from scratch in pure HTMX. Would work, but it&#39;s work traveling back and forth, doesn&#39;t seemingly integrate with the rest of my form and I&#39;d need to travel to the backend for each letter the user types.</p> <ol> <li><p>I could pass the entire client list to the frontend and do in Javascript, but I don&#39;t like to code stuff in javascript.</p></li> <li><p>I implemented this video: <a href="https://www.youtube.com/watch?v=Zzd4sL7drKQ">django-crispy-forms &amp; ModelChoiceFields / Select2 Integration for Searchable Form Fields</a>, 

## `django-hstore-widget` 0.0.15 released
 - [https://www.reddit.com/r/django/comments/1h4whm4/djangohstorewidget_0015_released](https://www.reddit.com/r/django/comments/1h4whm4/djangohstorewidget_0015_released)
 - RSS feed: $source
 - date published: 2024-12-02T14:43:11+00:00

<!-- SC_OFF --><div class="md"><p><code>django-hstore-widget</code> is a widget that simplifies <code>HStoreField</code> usage from admin panel.</p> <p>Changes since last post: * <a href="https://github.com/baseplate-admin/django-hstore-widget/commit/f68e606a9b739cdf9097cf94039b265fc0ab420f">Fix a bug where changing text in textarea caused content to change</a> * <a href="https://github.com/baseplate-admin/django-hstore-widget/commit/981660a8d8f9107c6f044816205dba9830235574">Reduce the bytes transferred over the wire</a> * <a href="https://github.com/baseplate-admin/django-hstore-widget/commit/8cd22e9402994b6dd4f980d2188c85e85305e511">Fix some icons not being in right place</a> * <a href="https://github.com/baseplate-admin/django-hstore-widget/commit/29930c7f6dbda2a3bfa965946a5c8a49c2a3fbdf">Improve accessibility</a></p> <p>Please take a look at the <a href="https://github.com/baseplate-admin/django-hstore-widget">github repo</a> or give a ⭐</p> </div><!-- SC_ON --> &#32; submitted b

## Better, Faster Python Projects: A Deep Dive into uv
 - [https://www.reddit.com/r/django/comments/1h4vak9/better_faster_python_projects_a_deep_dive_into_uv](https://www.reddit.com/r/django/comments/1h4vak9/better_faster_python_projects_a_deep_dive_into_uv)
 - RSS feed: $source
 - date published: 2024-12-02T13:45:52+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/czue13"> /u/czue13 </a> <br/> <span><a href="https://www.saaspegasus.com/guides/uv-deep-dive/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h4vak9/better_faster_python_projects_a_deep_dive_into_uv/">[comments]</a></span>

## django-stubs in LSP without installing it into the venv?
 - [https://www.reddit.com/r/django/comments/1h4us97/djangostubs_in_lsp_without_installing_it_into_the](https://www.reddit.com/r/django/comments/1h4us97/djangostubs_in_lsp_without_installing_it_into_the)
 - RSS feed: $source
 - date published: 2024-12-02T13:19:50+00:00

<!-- SC_OFF --><div class="md"><p>I write code for Django but without a local runtime for it, because I run it on a docker container.</p> <p>All the guides I have seen about django-stubs or django-types say you have to <code>pip install</code> them. I guess you are meant to <code>pip install</code> them into the virtual environment you run the project with, and also tell your Python LSP which virtual env to use for the current project.</p> <p>How can I make my LSP (basedpyright I guess, but I will happily switch if I can have a better experience) aware of django typings, but without having a local runtime for the project?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Informal-Addendum435"> /u/Informal-Addendum435 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h4us97/djangostubs_in_lsp_without_installing_it_into_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h4us97/djangostubs_in_lsp_

## Disappearing reference when using Generic foreign key
 - [https://www.reddit.com/r/django/comments/1h4s66n/disappearing_reference_when_using_generic_foreign](https://www.reddit.com/r/django/comments/1h4s66n/disappearing_reference_when_using_generic_foreign)
 - RSS feed: $source
 - date published: 2024-12-02T10:40:20+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I am a bit confused as to why ORM behaves this way. Suppose I have models One and Two, and model Two has a Foreign key to One. The code below works fine <code> one = Model_One() two = Model_Two(model_one=one) one.save() two.save() </code> This works because we save one before two and no data is lost. two is allowed to be saved because one by that point would have an id in the DB. Cool. Now what if those two models were related by Generic Foreign Key? <code> one = Model_One() two = Model_Two(content_object=one) one.save() two.save() </code> Now this one does not work! Two complains that it&#39;s content_id is null. I went in the debugger. When models are instantiated, everything is at it should be, two has a field content_object that references one. But as soon as one is saved, for whatever reason two loses its reference to one, the field content_object is empty! Is this intended behavior? When I run the code below, everything is good, no

## Why Do REST Frameworks Use Their Own Auth Layers Instead of Django’s Auth Backends?
 - [https://www.reddit.com/r/django/comments/1h4rcx1/why_do_rest_frameworks_use_their_own_auth_layers](https://www.reddit.com/r/django/comments/1h4rcx1/why_do_rest_frameworks_use_their_own_auth_layers)
 - RSS feed: $source
 - date published: 2024-12-02T09:39:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been exploring REST frameworks like <strong>Django REST Framework (DRF)</strong> and <strong>Django Ninja</strong>, and I noticed that they both introduce their own layers for authentication.</p> <ul> <li>DRF does it in the base class of all REST views.</li> <li>Django Ninja does it in the router that wraps the views.</li> </ul> <p>This creates separate libraries, like <code>djangorestframework-simplejwt</code> for DRF and <code>django-ninja-simplejwt</code> for Django Ninja.</p> <p>But Django already has a good auth system with backends that work for all views. Why don’t these frameworks just use Django’s auth backends and a middleware?</p> <p>Is Django’s auth system missing something, or do these frameworks need extra features that Django doesn’t provide?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kmmbvnr"> /u/kmmbvnr </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h4rcx1/why_

## GSoC25 Org Selection
 - [https://www.reddit.com/r/django/comments/1h4qvn9/gsoc25_org_selection](https://www.reddit.com/r/django/comments/1h4qvn9/gsoc25_org_selection)
 - RSS feed: $source
 - date published: 2024-12-02T09:02:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I&#39;m looking to contribute to open source. I&#39;m aiming for GSOC 25. I graduated this year and am currently working as an SDE. I&#39;m looking to contribute to Python or Django organizations. Can someone please suggest a beginner-friendly repository that could help me get into GSOC 25, given 3-4 months of time?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/saiganesh03"> /u/saiganesh03 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h4qvn9/gsoc25_org_selection/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h4qvn9/gsoc25_org_selection/">[comments]</a></span>

## Django-allauth's template is confusing
 - [https://www.reddit.com/r/django/comments/1h4qcnr/djangoallauths_template_is_confusing](https://www.reddit.com/r/django/comments/1h4qcnr/djangoallauths_template_is_confusing)
 - RSS feed: $source
 - date published: 2024-12-02T08:22:11+00:00

<!-- SC_OFF --><div class="md"><p>I see that they have templatized basic html elements and it&#39;s hard to style them now.</p> <p>This gave me a headache:</p> <p><a href="https://preview.redd.it/ammd31yrae4e1.png?width=1278&amp;format=png&amp;auto=webp&amp;s=efad04cfdd677325365cfa2fff629dbb94522f75">https://preview.redd.it/ammd31yrae4e1.png?width=1278&amp;format=png&amp;auto=webp&amp;s=efad04cfdd677325365cfa2fff629dbb94522f75</a></p> <p>Any tips will be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kenshi_hiro"> /u/kenshi_hiro </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h4qcnr/djangoallauths_template_is_confusing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h4qcnr/djangoallauths_template_is_confusing/">[comments]</a></span>

## Logs for code that is being tested by the unit tests in Django
 - [https://www.reddit.com/r/django/comments/1h4po12/logs_for_code_that_is_being_tested_by_the_unit](https://www.reddit.com/r/django/comments/1h4po12/logs_for_code_that_is_being_tested_by_the_unit)
 - RSS feed: $source
 - date published: 2024-12-02T07:31:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi Folks, I have tests for a view, when run don&#39;t trigger the logger.info() statements within the view&#39;s code.</p> <p>But same view when triggered manually (for ex: via postman) shows up logs in the console generated by the logger.info() statements. </p> <p>Is there something I am missing to be able to see logs generated during tests?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chicoatwork"> /u/chicoatwork </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h4po12/logs_for_code_that_is_being_tested_by_the_unit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h4po12/logs_for_code_that_is_being_tested_by_the_unit/">[comments]</a></span>

## Having trouble uploading media with S3 API (to MinIO bucket)
 - [https://www.reddit.com/r/django/comments/1h4ov3b/having_trouble_uploading_media_with_s3_api_to](https://www.reddit.com/r/django/comments/1h4ov3b/having_trouble_uploading_media_with_s3_api_to)
 - RSS feed: $source
 - date published: 2024-12-02T06:35:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey y&#39;all. </p> <p>I have a Django project that allows users and admins to upload files to be stored in the /media directory. This works great in my local project folder, but since I&#39;m going to have to migrate to Docker and use a VPS soon, I figured that I should test everything out with a local bucket first.</p> <pre><code>import boto3 from botocore.exceptions import NoCredentialsError, ClientError def test_s3_connection(): s3 = boto3.client( &#39;s3&#39;, endpoint_url=&#39;http://localhost:9000&#39;, aws_access_key_id=&#39;minioadmin&#39;, aws_secret_access_key=&#39;minioadmin&#39;, ) try: response = s3.list_buckets() print(&quot;Buckets:&quot;) for bucket in response[&#39;Buckets&#39;]: print(f&quot; - {bucket[&#39;Name&#39;]}&quot;) except NoCredentialsError: print(&quot;Credentials not available.&quot;) except ClientError as e: print(f&quot;ClientError: {e}&quot;) if __name__ == &quot;__main__&quot;: test_s3_connection() </code></pre> <p

## Django unused css
 - [https://www.reddit.com/r/django/comments/1h4osl5/django_unused_css](https://www.reddit.com/r/django/comments/1h4osl5/django_unused_css)
 - RSS feed: $source
 - date published: 2024-12-02T06:31:19+00:00

<!-- SC_OFF --><div class="md"><p>My website is loading slowly, and I suspect the performance hit is due to unused CSS being loaded with every page. While I use frameworks like Bootstrap and custom admin styles, much of the CSS is not relevant for every page. I&#39;m wondering if there&#39;s a way to remove unused CSS dynamically, specifically through middleware.</p> <p>I’d like to know if it&#39;s possible to automatically purge unused CSS before serving the page, without permanently modifying the CSS files. The idea would be to handle this process on every request to ensure only the necessary CSS is sent to the browser, thus improving load times. Can anyone guide me on how to implement this in Django, or if there are best practices to handle CSS purging dynamically using middleware or a similar solution?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OrderPurple5928"> /u/OrderPurple5928 </a> <br/> <span><a href="https://www.reddit.com/r/djang

## Is there an easy to use CI/CD solution for deployment? My usecase below.
 - [https://www.reddit.com/r/django/comments/1h4oaub/is_there_an_easy_to_use_cicd_solution_for](https://www.reddit.com/r/django/comments/1h4oaub/is_there_an_easy_to_use_cicd_solution_for)
 - RSS feed: $source
 - date published: 2024-12-02T06:00:05+00:00

<!-- SC_OFF --><div class="md"><p>As of now, I have a VPS on hetzner (I had it on Digital Ocean previously, but I migrated to hetzner).</p> <p>I use apache to host it, all media files and static files along with database are hosted on the same VPS, and I have a bunch of cron jobs to run some background jobs...</p> <p>As of now, I make changes locally, and push them, then ssh into the VPS, pull the changes, check permissions for each directory, restart apache and all the hassle...</p> <p>I&#39;ve also used Digital Ocean&#39;s app platform, so when I push to github, it will redeploy the project, but then, I&#39;d to host the database and media files seperately, otherwise they will be gone after the re-deployment. Plus background tasks are pain, and the costs getting higher and higher.</p> <p>I am looking for similar solution, but maybe somewhere else and not on Digital Ocean. Please suggest me the easiest options, or tricks to do the same on a VPS.</p> <p>I really need some help.</p> <

## No judgement
 - [https://www.reddit.com/r/django/comments/1h4knqk/no_judgement](https://www.reddit.com/r/django/comments/1h4knqk/no_judgement)
 - RSS feed: $source
 - date published: 2024-12-02T02:35:57+00:00

<!-- SC_OFF --><div class="md"><p>I am an individual who has always loved the films of Tarantino. I’ve watched all of them at least ten times each ( 01/1224) but I can confidently say that if Django isn’t your favourite then you are wrong ( simply it’s no matter of opinion) if you watch Django unchained, the first scene of Mandingo fighting portrays 7 reactions to a murder in 3 seconds that I personally think is more valuable to modern cinematography than the 30 years that proceeds it. Honestly! Watch the eye popping scene again and again and you’ll see that in 3 seconds we have 7 different societal beliefs emerge from one action. The beneficiary The bystander The “ life goes on” The “ it is what it is” The “ is this what I must tolerate?” The “this is what society made me do” The “ this is an injustice” All performed in 3 seconds </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chonkymunky"> /u/chonkymunky </a> <br/> <span><a href="https://www.

## Django cannot connect with tkinter on zeroroc after deploy it on ubuntu sever with nginx and gunicorn even if allow port 4242 on ufw
 - [https://www.reddit.com/r/django/comments/1h4khxt/django_cannot_connect_with_tkinter_on_zeroroc](https://www.reddit.com/r/django/comments/1h4khxt/django_cannot_connect_with_tkinter_on_zeroroc)
 - RSS feed: $source
 - date published: 2024-12-02T02:27:21+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/plkxf2o6jc4e1.png?width=902&amp;format=png&amp;auto=webp&amp;s=b586c4e2de63be1b605aa28c5461ac62ae543e14">https://preview.redd.it/plkxf2o6jc4e1.png?width=902&amp;format=png&amp;auto=webp&amp;s=b586c4e2de63be1b605aa28c5461ac62ae543e14</a></p> <p><a href="https://preview.redd.it/tzqhef38jc4e1.png?width=831&amp;format=png&amp;auto=webp&amp;s=6f10fa24ef2786bc6c426694a4fd386ae3012990">https://preview.redd.it/tzqhef38jc4e1.png?width=831&amp;format=png&amp;auto=webp&amp;s=6f10fa24ef2786bc6c426694a4fd386ae3012990</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Salah_Salah_Eddine"> /u/Salah_Salah_Eddine </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h4khxt/django_cannot_connect_with_tkinter_on_zeroroc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h4khxt/django_cannot_connect_with_tkinter_on_zeroroc/">[comments]</a></span>

## Want to contribute to django projects.
 - [https://www.reddit.com/r/django/comments/1h4kbga/want_to_contribute_to_django_projects](https://www.reddit.com/r/django/comments/1h4kbga/want_to_contribute_to_django_projects)
 - RSS feed: $source
 - date published: 2024-12-02T02:18:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I want to contribute on some django projects. if any one are willing to suggest me some applications please feel free to reply to this post.</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ashu6410"> /u/Ashu6410 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h4kbga/want_to_contribute_to_django_projects/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h4kbga/want_to_contribute_to_django_projects/">[comments]</a></span>

