# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## I'd like your opinions on how to organize my template files. I've come up with a structure, haven't fully tried it yet. Let me know what you think.
 - [https://www.reddit.com/r/django/comments/1gmw3cl/id_like_your_opinions_on_how_to_organize_my](https://www.reddit.com/r/django/comments/1gmw3cl/id_like_your_opinions_on_how_to_organize_my)
 - RSS feed: $source
 - date published: 2024-11-08T23:19:01+00:00

<!-- SC_OFF --><div class="md"><pre><code>So I&#39;ve been working with django for a few months now, and I&#39;ve been thinking a lot about a good way of organizing my templates and projects. This is just a thought and I plan to refactor a project or two to see if it meshes well with this, but here&#39;s what I&#39;m thinking: limiting every app&#39;s templates to strictly adhere to the following folder structure. components - [component_x_folder] - component_x.py - component_x.js - component_x.css - template_x.html ... includes - [include_x_folder] - include_x.html ... widgets - [widget_x_folder] - widget_x.html ... layouts - sections - [section_x_folder] - section_x.html ... - partials - [x-partial_x_folder] - x-partial_x.html ... - _base.html ... pages - [page_x_folder] - sections - ... - pages - ... - partials - ... - page_x.html ====================== EXPLAINING THE FOLDERS ====================== 1. layouts ---------- - Contains templates for defining app layouts, &lt;link&gt; t

## Best way to generate a single page PDF using selected items from current page in MkDocs
 - [https://www.reddit.com/r/django/comments/1gmusyz/best_way_to_generate_a_single_page_pdf_using](https://www.reddit.com/r/django/comments/1gmusyz/best_way_to_generate_a_single_page_pdf_using)
 - RSS feed: $source
 - date published: 2024-11-08T22:20:43+00:00

<!-- SC_OFF --><div class="md"><p>Let&#39;s say i have a page in MkDocs that has a several paragraphs of text together with a checklist.</p> <p>I now want the user to be able to click a button, and generate a PDF with just the checklist on it. I do <em>not</em> want the paragraphs of text to print, and I want to be able to control how the checklist looks on paper vs the screen (e.g. change font font size).</p> <p>Is there a tool or plug-in that would be suitable for this type of use case?</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sub3andy"> /u/sub3andy </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gmusyz/best_way_to_generate_a_single_page_pdf_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmusyz/best_way_to_generate_a_single_page_pdf_using/">[comments]</a></span>

## Django-Postgres Starter
 - [https://www.reddit.com/r/django/comments/1gmof1w/djangopostgres_starter](https://www.reddit.com/r/django/comments/1gmof1w/djangopostgres_starter)
 - RSS feed: $source
 - date published: 2024-11-08T17:45:48+00:00

<!-- SC_OFF --><div class="md"><p>I was recently playing with Claude AI and decided to build a python app that will create a new Django/Postgres project.</p> <p>I have put it out on Github here: <a href="https://github.com/jhstephenson/django-postgres-starter">jhstephenson/django-postgres-starter</a></p> <p>I am curious to see if anyone finds this useful, but also want to see how it could be expanded and improved.</p> <p>Let me know any thoughts you might have.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Easy_Lettuce_4436"> /u/Easy_Lettuce_4436 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gmof1w/djangopostgres_starter/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmof1w/djangopostgres_starter/">[comments]</a></span>

## Django Tip explaining.only()/.defer() n+1
 - [https://www.reddit.com/r/django/comments/1gmo1b8/django_tip_explainingonlydefer_n1](https://www.reddit.com/r/django/comments/1gmo1b8/django_tip_explainingonlydefer_n1)
 - RSS feed: $source
 - date published: 2024-11-08T17:30:13+00:00

<!-- SC_OFF --><div class="md"><p>When using the only() or defer() methods in Django&#39;s ORM to exclude certain fields from a query, it&#39;s important to be aware that if you access those excluded fields in your templates, Django will generate additional queries to retrieve the excluded data for each object. This can result in the N+1 problem and poor performance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://www.reddit.com/gallery/1gmo1b8">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmo1b8/django_tip_explainingonlydefer_n1/">[comments]</a></span>

## Can i deploy a small django app on the Free App Platform tier on DigitalOcean?
 - [https://www.reddit.com/r/django/comments/1gmm7o8/can_i_deploy_a_small_django_app_on_the_free_app](https://www.reddit.com/r/django/comments/1gmm7o8/can_i_deploy_a_small_django_app_on_the_free_app)
 - RSS feed: $source
 - date published: 2024-11-08T16:14:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve never used digitalocean, so i wanted to try it out with a small app before i commit</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gmm7o8/can_i_deploy_a_small_django_app_on_the_free_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmm7o8/can_i_deploy_a_small_django_app_on_the_free_app/">[comments]</a></span>

## I need help deploying my django app on directadmin control panel
 - [https://www.reddit.com/r/django/comments/1gmlyzn/i_need_help_deploying_my_django_app_on](https://www.reddit.com/r/django/comments/1gmlyzn/i_need_help_deploying_my_django_app_on)
 - RSS feed: $source
 - date published: 2024-11-08T16:04:05+00:00

<!-- SC_OFF --><div class="md"><p>I watched a tutorial on how to do it (yes, the only one on YouTube) and my god was it awful. Does anyone know how to do it or any resource that might help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gmlyzn/i_need_help_deploying_my_django_app_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmlyzn/i_need_help_deploying_my_django_app_on/">[comments]</a></span>

## social media like function in django
 - [https://www.reddit.com/r/django/comments/1gmkr18/social_media_like_function_in_django](https://www.reddit.com/r/django/comments/1gmkr18/social_media_like_function_in_django)
 - RSS feed: $source
 - date published: 2024-11-08T15:11:28+00:00

<!-- SC_OFF --><div class="md"><p>i create social media in django but each i time click like button it refresh the page and working </p> <p>how work like button without refreshing the page </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legal_Relief6756"> /u/Legal_Relief6756 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gmkr18/social_media_like_function_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmkr18/social_media_like_function_in_django/">[comments]</a></span>

## Feature Friday: The querystring tag!
 - [https://www.reddit.com/r/django/comments/1gmjgep/feature_friday_the_querystring_tag](https://www.reddit.com/r/django/comments/1gmjgep/feature_friday_the_querystring_tag)
 - RSS feed: $source
 - date published: 2024-11-08T14:13:38+00:00

<!-- SC_OFF --><div class="md"><p>Today&#39;s Feature Friday is about <code>{% querystring %}</code>!</p> <p>The new <code>{% querystring %}</code> template tag in Django 5.1 makes it easier to access and modify the query string in your Django templates, letting you work with links that use query parameters.</p> <p>Previously, if you wanted to add or change a single value in the query string, you would need to write a lot of code:</p> <pre><code>{# Linebreaks added for readability, this should be one, long line. #} &lt;a href=&quot;?{% for key, values in request.GET.iterlists %} {% if key != &quot;page&quot; %} {% for value in values %} {{ key }}={{ value }}&amp;amp; {% endfor %} {% endif %} {% endfor %}page={{ page.next_page_number }}&quot;&gt;Next page&lt;/a&gt; </code></pre> <p>With <code>{% querystring %}</code> you can replace all of that with this single line:</p> <pre><code>&lt;a href=&quot;{% querystring page=page.next_page_number %}&quot;&gt;Next page&lt;/a&gt; </code></pre>

## 🎉 Introducing dj-data-generator! 🎉
 - [https://www.reddit.com/r/django/comments/1gmj9nl/introducing_djdatagenerator](https://www.reddit.com/r/django/comments/1gmj9nl/introducing_djdatagenerator)
 - RSS feed: $source
 - date published: 2024-11-08T14:04:37+00:00

<!-- SC_OFF --><div class="md"><p>We’re thrilled to announce the release of dj-data-generator, a new tool designed to simplify generating customizable test data for Django projects. Whether you’re setting up demo environments, populating databases for testing, or running performance tests, dj-data-generator offers efficient, built-in support to meet your needs—all without third-party packages.</p> <p>Key Features:</p> <p>- Generate any number of records for your project models and save them directly to the database with a simple django command</p> <p>- Easy customization for model fields</p> <p>- Handles unique and related fields</p> <p>Check it out, and let us know what you think! Feedback, contributions, and suggestions are welcome as we continue to build.</p> <p>📥 Check it out on PyPI: </p> <p><a href="https://pypi.org/project/dj-data-generator/">https://pypi.org/project/dj-data-generator/</a></p> <p>💻 Source Code and Docs on GitHub:</p> <p><a href="https://github.com/Lazarus-org/

## Please help with hosting django in hostinger !
 - [https://www.reddit.com/r/django/comments/1gmine8/please_help_with_hosting_django_in_hostinger](https://www.reddit.com/r/django/comments/1gmine8/please_help_with_hosting_django_in_hostinger)
 - RSS feed: $source
 - date published: 2024-11-08T13:34:55+00:00

<!-- SC_OFF --><div class="md"><p>I bought the vps in hostinger, they have like ubuntu with openLiteSpeed and django, i also bought a domain but i dont know what to do now.</p> <p>I cloned my github repo and im so confused. Hate to see theres no good tutorials how these things work.</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/himynameisAhhhh"> /u/himynameisAhhhh </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gmine8/please_help_with_hosting_django_in_hostinger/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmine8/please_help_with_hosting_django_in_hostinger/">[comments]</a></span>

## Choosing a Backend Framework for ML Prediction and Matching
 - [https://www.reddit.com/r/django/comments/1gme0iv/choosing_a_backend_framework_for_ml_prediction](https://www.reddit.com/r/django/comments/1gme0iv/choosing_a_backend_framework_for_ml_prediction)
 - RSS feed: $source
 - date published: 2024-11-08T08:34:50+00:00

<!-- SC_OFF --><div class="md"><p>Hey, if you’re going with some ML for prediction and matching—nothing very complicated—and implementing it in a web app, what sort of backend framework should I use, and what workflow should I implement? Usually, I’ve worked with Express.js.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Itchy_Anything6981"> /u/Itchy_Anything6981 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gme0iv/choosing_a_backend_framework_for_ml_prediction/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gme0iv/choosing_a_backend_framework_for_ml_prediction/">[comments]</a></span>

## I would like feedback
 - [https://www.reddit.com/r/django/comments/1gmcbat/i_would_like_feedback](https://www.reddit.com/r/django/comments/1gmcbat/i_would_like_feedback)
 - RSS feed: $source
 - date published: 2024-11-08T06:29:44+00:00

<!-- SC_OFF --><div class="md"><p>I am creating an application template for django and I would like to know your opinions, the only condition is that when making django-admin startapp --template=</p> <p>The app must be created within the django project in a folder called Apps</p> <p>I leave you the link: <a href="https://github.com/simuel/DjangoHexTemplate.git">https://github.com/simuel/DjangoHexTemplate.git</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Academic-Ad-1590"> /u/Academic-Ad-1590 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gmcbat/i_would_like_feedback/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gmcbat/i_would_like_feedback/">[comments]</a></span>

## 8 Amazing Microsoft Resources
 - [https://www.reddit.com/r/django/comments/1gma7x1/8_amazing_microsoft_resources](https://www.reddit.com/r/django/comments/1gma7x1/8_amazing_microsoft_resources)
 - RSS feed: $source
 - date published: 2024-11-08T04:21:56+00:00

<!-- SC_OFF --><div class="md"><p>🚀 Unlocking Potential with Microsoft: Tools and Programs to Elevate Your Skills!</p> <p>As technology continues to evolve, Microsoft offers a wealth of resources and tools designed to help developers, data enthusiasts, and AI/ML learners thrive. Here are some standout features and programs you should check out:</p> <ol> <li><p>Microsoft Copilot Transform your productivity with AI-driven assistance directly within your favorite Microsoft applications. <a href="https://learn.microsoft.com/en-us/copilot/?wt.mc_id=studentamb_421231">https://learn.microsoft.com/en-us/copilot/?wt.mc_id=studentamb_421231</a></p></li> <li><p>Microsoft Programs for Developers Explore a range of programs tailored for developers. </p></li> </ol> <p><a href="https://mvp.microsoft.com/?wt.mc_id=studentamb_421231">https://mvp.microsoft.com/?wt.mc_id=studentamb_421231</a></p> <ol> <li>.NET Framework Build robust applications with the .NET framework! It supports various programming 

## Oracle forms builder alternate
 - [https://www.reddit.com/r/django/comments/1gm6gs4/oracle_forms_builder_alternate](https://www.reddit.com/r/django/comments/1gm6gs4/oracle_forms_builder_alternate)
 - RSS feed: $source
 - date published: 2024-11-08T01:05:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi All, My employer recently upgraded from Oracle 11g to 19c..there was a reporting module that was built out of Oracle 6i and now with the upgrade the reporting module is breaking as there is no compatible version of Oracle forms builder with 19c.</p> <p>So we have been asked to find alternates.I am thinking of suggesting Django with html as the requirement mainly focuses on generating excel docs by querying the Oracle tables.they need an UI component just to trigger the Excel generation process.</p> <p>Now am from completely java background and have very minimal knowledge in Django.But I did start leaning python and found the file operations are much more clean and minimal code in python when compared to java and hence thinking of suggesting python with Django for a quick turnaround.</p> <p>Is this good suggestion or Is there anything else out there that am completely missing for this scenario?</p> <p>Thanks In advance</p> </div><!-- SC_ON --> &#32

## Help with Changing Natural Primary Key to Surrogate Key
 - [https://www.reddit.com/r/django/comments/1gm6ddn/help_with_changing_natural_primary_key_to](https://www.reddit.com/r/django/comments/1gm6ddn/help_with_changing_natural_primary_key_to)
 - RSS feed: $source
 - date published: 2024-11-08T01:01:02+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>I&#39;m working on a Django project where I currently have a model with a natural key as the primary key. I want to replace it with a surrogate key (using Django’s default auto-generated primary key). However, I have a related model where the foreign key points to the current model. I&#39;m wondering what the best approach would be to make this change smoothly.</p> <p>example:</p> <pre><code>from django.db import models class Product(models.Model): sku = models.CharField(max_length=20, primary_key=True) # This is the natural key I want to replace name = models.CharField(max_length=100) price = models.DecimalField(max_digits=10, decimal_places=2) class Order(models.Model): product = models.ForeignKey(Product, on_delete=models.CASCADE) # Foreign key points to Product quantity = models.IntegerField() order_date = models.DateTimeField(auto_now_add=True) </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddi

