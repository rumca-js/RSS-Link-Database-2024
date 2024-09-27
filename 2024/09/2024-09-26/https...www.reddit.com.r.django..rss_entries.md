# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django channel and websocket
 - [https://www.reddit.com/r/django/comments/1fq8yqb/django_channel_and_websocket](https://www.reddit.com/r/django/comments/1fq8yqb/django_channel_and_websocket)
 - RSS feed: $source
 - date published: 2024-09-26T22:34:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m struggling to find out the best, simple way to set up websocket in my Django. I have several questions that I need some help for. </p> <p>If I need a websocket that is used for bidirectional communication between react and Django server only, do I still need channel?</p> <p>This is not chat service. There need no communication between different users.</p> <p>The server (or worker) will generate events and the react needs to receive it in real time and occasionally initiate to send some data back to the same server (or worker)</p> <p>I also saw sample example of websocket consumer python code in Django side. Will this code usually run on Daphne server? How consumer process will be forked on Daphne? I guess the Daphne and Gunicorn can be in different containers. Or will they run in the same container?</p> <p>Once react open websocket to Daphne on platform render, will render allows the persistent connection between react and Daphne until conn cl

## Django hosting
 - [https://www.reddit.com/r/django/comments/1fq5w0d/django_hosting](https://www.reddit.com/r/django/comments/1fq5w0d/django_hosting)
 - RSS feed: $source
 - date published: 2024-09-26T20:19:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I&#39;d like to develop my personal portfolio website and blog with Django (DRF) and React. I&#39;d like to host both the front and backend on the same server so I&#39;m looking at utilising docker and k8s and serve the backend as a service which is consumed by the front-end. Is my only option a cloud based provider like AWS, Azure or GCP? Can I use docker and k8s on other hosting platforms? Which ones do you use, would you recommend them and if so why?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok-Flan549"> /u/Ok-Flan549 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fq5w0d/django_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fq5w0d/django_hosting/">[comments]</a></span>

## Is there an AI Chatbot that can tell me what's wrong with code?
 - [https://www.reddit.com/r/django/comments/1fq5otd/is_there_an_ai_chatbot_that_can_tell_me_whats](https://www.reddit.com/r/django/comments/1fq5otd/is_there_an_ai_chatbot_that_can_tell_me_whats)
 - RSS feed: $source
 - date published: 2024-09-26T20:11:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been cutting and pasting all the error messages I get in Terminal into a chat bot. It works most of the time I think. Is there a better way?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Negative_Ad2438"> /u/Negative_Ad2438 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fq5otd/is_there_an_ai_chatbot_that_can_tell_me_whats/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fq5otd/is_there_an_ai_chatbot_that_can_tell_me_whats/">[comments]</a></span>

## Need an external opinion on code organization.
 - [https://www.reddit.com/r/django/comments/1fq4j69/need_an_external_opinion_on_code_organization](https://www.reddit.com/r/django/comments/1fq4j69/need_an_external_opinion_on_code_organization)
 - RSS feed: $source
 - date published: 2024-09-26T19:21:55+00:00

<!-- SC_OFF --><div class="md"><p>My coworker and I have <em>very</em> different design sensibilities. We have reached a disagreement that we can&#39;t resolve between us by appeals to logic or aesthetics. </p> <p>I need an external opinions. I&#39;m going to obscure which of these I support as much as possible. </p> <p><strong>Situation:</strong> </p> <p>We have some scripts that run in a django context, using values from settings and calling management scripts with <code>call_command</code>. The Status Quo Ante is that these are management commands in an app that has nothing but management commands. </p> <p>(What these apps are doing is somewhat beside the point, but in case you care: They handle our full localization machinery, including importing and exporting between PO files from django and the localization team&#39;s preferred windows app. That app uses an xml format and is somewhat particular about directory structure.)</p> <p><strong>Proposal 1:</strong></p> <p>One of us pref

## Django all auth custom provider
 - [https://www.reddit.com/r/django/comments/1fq3org/django_all_auth_custom_provider](https://www.reddit.com/r/django/comments/1fq3org/django_all_auth_custom_provider)
 - RSS feed: $source
 - date published: 2024-09-26T18:46:25+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using Django Allauth and I want to use <a href="http://gov.br">gov.br</a>, a single sign-on method from the Brazilian government. I have the client_id, secret, and the URI where the requests should be made. Does anyone know how I can customize the providers to use this service? Or, if that&#39;s not possible, is there a better way to do this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mcosta123"> /u/mcosta123 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fq3org/django_all_auth_custom_provider/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fq3org/django_all_auth_custom_provider/">[comments]</a></span>

## Which CMP do you use?
 - [https://www.reddit.com/r/django/comments/1fpzksq/which_cmp_do_you_use](https://www.reddit.com/r/django/comments/1fpzksq/which_cmp_do_you_use)
 - RSS feed: $source
 - date published: 2024-09-26T15:54:42+00:00

<!-- SC_OFF --><div class="md"><p>Hey all! Which consent management platform do you recommend, if using any for your Django app?</p> <p>I&#39;m playing with GA4 on my portfolio app, and apparently I need consent for it. I know it&#39;s likely an overkill for a personal project but I thought I&#39;d go through all the trouble as an exercise anyway.</p> <p>Any general advice on the topic is welcome as well, thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sourdoughshploinks"> /u/sourdoughshploinks </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fpzksq/which_cmp_do_you_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fpzksq/which_cmp_do_you_use/">[comments]</a></span>

## allauth adding new providers later
 - [https://www.reddit.com/r/django/comments/1fpyhv2/allauth_adding_new_providers_later](https://www.reddit.com/r/django/comments/1fpyhv2/allauth_adding_new_providers_later)
 - RSS feed: $source
 - date published: 2024-09-26T15:09:36+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I&#39;m new to Django, and I decided to learn it for my next project. Quick questions. Is it ok to add new providers at a later time (after the initial migrations, after the DB is in production)? Or do I have to choose all the providers I want at the beginning of the project?</p> <p>Also, is it recommended to still create a new custom user model if I use allauth? I&#39;m asking because from the documentation it seems like a good practice, but I&#39;m not sure if it&#39;s needed with allauth? <a href="https://docs.djangoproject.com/en/5.1/topics/auth/customizing/#using-a-custom-user-model-when-starting-a-project">https://docs.djangoproject.com/en/5.1/topics/auth/customizing/#using-a-custom-user-model-when-starting-a-project</a></p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DeanDodgers"> /u/DeanDodgers </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fpyhv2/allau

## Django Newbe - No App installed with label '<appname>'
 - [https://www.reddit.com/r/django/comments/1fpy0jw/django_newbe_no_app_installed_with_label_appname](https://www.reddit.com/r/django/comments/1fpy0jw/django_newbe_no_app_installed_with_label_appname)
 - RSS feed: $source
 - date published: 2024-09-26T14:49:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, i&#39;m starting a project to try out django with postgre. I was following the <a href="https://docs.djangoproject.com/en/5.1/intro/tutorial01/">official tutorial</a> but when running the command makemigrations, the output is &#39;No app installed with label cms&#39;.</p> <p>This is my <a href="http://settings.py">settings.py</a> file:</p> <pre><code>INSTALLED_APPS = [ &quot;django.contrib.admin&quot;, &quot;django.contrib.auth&quot;, &quot;django.contrib.contenttypes&quot;, &quot;django.contrib.sessions&quot;, &quot;django.contrib.messages&quot;, &quot;django.contrib.staticfiles&quot;, &quot;cms.apps.CmsConfig&quot;, # &quot;cms&quot;, ] </code></pre> <p>And this is the layout of my application:</p> <p><a href="https://preview.redd.it/fhqzuz6326rd1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=049dc62ae8106d7073fbdc6bb121880818d82393">https://preview.redd.it/fhqzuz6326rd1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=049dc62ae8106d70

## Creating Dependent Dropdowns with Django and HTMX
 - [https://www.reddit.com/r/django/comments/1fpvlzv/creating_dependent_dropdowns_with_django_and_htmx](https://www.reddit.com/r/django/comments/1fpvlzv/creating_dependent_dropdowns_with_django_and_htmx)
 - RSS feed: $source
 - date published: 2024-09-26T13:00:50+00:00

<!-- SC_OFF --><div class="md"><p>I recently tackled the challenge of implementing dynamic, interdependent dropdowns in a Django project. I found a solution using Django Forms and HTMX that worked well for me.</p> <p>I&#39;ve written up my approach in a blog post. In general terms I followed the steps:</p> <ol> <li>Define the field order</li> <li>Create a custom Django Form</li> <li>Create a view to load initial values into the the first field and handle form submission</li> <li>Create a template to show the form</li> <li>Create views to load options into dependent fields</li> <li>Create templates to replace dependent field options of the form in your main view</li> </ol> <p>You can check out the full write-up here: <a href="https://serjhenrique.com/create-dependent-dropdown-with-django-and-htmx/">https://serjhenrique.com/create-dependent-dropdown-with-django-and-htmx/</a></p> <p>I&#39;m curious to hear if anyone else has tackled similar problems. What approaches have you used? </p> <

## Need Help Finding Resources for Single Page Website with Django REST API and Vanilla JavaScript
 - [https://www.reddit.com/r/django/comments/1fpszjy/need_help_finding_resources_for_single_page](https://www.reddit.com/r/django/comments/1fpszjy/need_help_finding_resources_for_single_page)
 - RSS feed: $source
 - date published: 2024-09-26T10:29:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> I’m working on a single-page website with Django REST API for the backend and HTML, CSS, and vanilla JavaScript for the front end. The features I want to implement are:</p> <ul> <li>User management (register, login, logout, profile section)</li> <li>Adding friends functionality</li> <li>Real-time chatting between users</li> </ul> <p>The problem I’m running into is that most of the resources I find use Django templates instead of Django REST API for these features. Does anyone have suggestions, helpful resources, or advice for building these features using a REST API and vanilla JavaScript? Any help would be greatly appreciated!</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Secret-Coconut-7635"> /u/Secret-Coconut-7635 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fpszjy/need_help_finding_resources_for_single_page/">[link]</a></span> &#32; <span><a href="http

## csrf token changing on every refresh
 - [https://www.reddit.com/r/django/comments/1fppqhp/csrf_token_changing_on_every_refresh](https://www.reddit.com/r/django/comments/1fppqhp/csrf_token_changing_on_every_refresh)
 - RSS feed: $source
 - date published: 2024-09-26T06:23:56+00:00

<!-- SC_OFF --><div class="md"><p>Kinda at my wits end here. Im not too experienced with django but have come across a problem with a deployed site that is refreshing the csrf token in the input hidden field on every refresh. Although the client side token is staying the same. Does anyone have any idea of what is causing this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/spoonmonkey_"> /u/spoonmonkey_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fppqhp/csrf_token_changing_on_every_refresh/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fppqhp/csrf_token_changing_on_every_refresh/">[comments]</a></span>

## Websocket and channel
 - [https://www.reddit.com/r/django/comments/1fpppry/websocket_and_channel](https://www.reddit.com/r/django/comments/1fpppry/websocket_and_channel)
 - RSS feed: $source
 - date published: 2024-09-26T06:22:29+00:00

<!-- SC_OFF --><div class="md"><p>If I need a websocket that is used for bidirectional communication between react and Django server only, do I still need channel? </p> <p>This is not chat service. There need no communication between different users. </p> <p>The server (or worker) will generate events and the react needs to receive it in real time and occasionally initiate to send some data back to the same server (or worker)</p> <p>I also saw sample example of websocket consumer python code in Django side. Will this code usually run on Daphne server? How consumer process will be forked on Daphne? I guess the Daphne and Gunicorn can be in different containers. Or will they run in the same container?</p> <p>Once react open websocket to Daphne on platform render, will render allows the persistent connection between react and Daphne until conn close is initiated ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Best_Fish_2941"> /u/Best_Fish_2941 </a

## React, Django and Allauth Headless
 - [https://www.reddit.com/r/django/comments/1fpl0cr/react_django_and_allauth_headless](https://www.reddit.com/r/django/comments/1fpl0cr/react_django_and_allauth_headless)
 - RSS feed: $source
 - date published: 2024-09-26T01:38:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi, Thanks for tuning in, </p> <p>I&#39;m trying to build a django backend with auth and social auth, I really like the features allauth offers and I wanted to integrate it&#39;s auth and some social providers with React, thus I came to this<br/> <a href="https://github.com/pennersr/django-allauth/tree/main/examples/react-spa">https://github.com/pennersr/django-allauth/tree/main/examples/react-spa</a></p> <p>I tried to run it locally, without docker, by just installing requirements and starting the frontend, had to change the base url to start with local host for django server, </p> <p>but still all of my login or signup post requests get CSRF error, despite trusting localhost (managed to get by cors headers errors by these and inclusion of corsheaders)</p> <pre><code>CSRF_TRUSTED_ORIGINS = [&quot;http://localhost:3000&quot;] CORS_ORIGIN_ALLOW_ALL = True CORS_ALLOW_CREDENTIALS = True CORS_ORIGIN_WHITELIST = [&quot;http://localhost:3000&quot;] CORS_ALL

## I'm new to using Django and its testing tools. One of the testing tools concerns me: the assertFieldOutput.
 - [https://www.reddit.com/r/django/comments/1fpkiqv/im_new_to_using_django_and_its_testing_tools_one](https://www.reddit.com/r/django/comments/1fpkiqv/im_new_to_using_django_and_its_testing_tools_one)
 - RSS feed: $source
 - date published: 2024-09-26T01:13:14+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://docs.djangoproject.com/en/5.1/topics/testing/tools/#django.test.SimpleTestCase.assertFieldOutput"><code>https://docs.djangoproject.com/en/5.1/topics/testing/tools/#django.test.SimpleTestCase.assertFieldOutput</code></a></p> <p>According to the documentation for this method, the test method accepts three mandatory arguments: fieldclass, valid, and invalid. A cursory glance tells me the method is used to test the validation methods of the form. e.g. If the validation methods accept the input (passed as a key), then the input is mapped to a cleaned version of itself. And if the validation methods reject the input, the input is mapped to a list of error messages.</p> <p>The latter bit baffles me a bit. Does the Django development team expect web developers to copy-paste error messages from their source code to their test code? Does the team expect developers to put all error messages into a dictionary to be imported by all modules that ne

## Favorite hosting options
 - [https://www.reddit.com/r/django/comments/1fpjbeb/favorite_hosting_options](https://www.reddit.com/r/django/comments/1fpjbeb/favorite_hosting_options)
 - RSS feed: $source
 - date published: 2024-09-26T00:11:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi all- just checking what the communities latest thoughts are on the best hosts for Django sites - particularly for smaller projects where I don’t want to commit to high monthly fees. In particular I need Django/python with good database and storage. Is it AWS or Digital Ocean?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rhyno_Time"> /u/Rhyno_Time </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fpjbeb/favorite_hosting_options/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fpjbeb/favorite_hosting_options/">[comments]</a></span>

