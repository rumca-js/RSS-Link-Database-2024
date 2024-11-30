# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## People who have styled/modified the admin page, how did that go?
 - [https://www.reddit.com/r/django/comments/1h2ybk4/people_who_have_styledmodified_the_admin_page_how](https://www.reddit.com/r/django/comments/1h2ybk4/people_who_have_styledmodified_the_admin_page_how)
 - RSS feed: $source
 - date published: 2024-11-29T23:01:29+00:00

<!-- SC_OFF --><div class="md"><p>In terms of difficulty, how bad was it? especially if you had to style it. and was it worth it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2ybk4/people_who_have_styledmodified_the_admin_page_how/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2ybk4/people_who_have_styledmodified_the_admin_page_how/">[comments]</a></span>

## Using JWT without django-rest-framework and plugins?
 - [https://www.reddit.com/r/django/comments/1h2wkjn/using_jwt_without_djangorestframework_and_plugins](https://www.reddit.com/r/django/comments/1h2wkjn/using_jwt_without_djangorestframework_and_plugins)
 - RSS feed: $source
 - date published: 2024-11-29T21:38:59+00:00

<!-- SC_OFF --><div class="md"><p>The situation in brief: I have a browser game on an external website, i use django as backend and i want to implement a Login/Register system using JWT (feel free to suggest better alternatives to JWT). The user send register and login info through the game.</p> <p>In pretty much every tutorial about django and jwt I&#39;ve seen, people are using <a href="https://github.com/jazzband/djangorestframework-simplejwt">djangorestframework-simplejwt plugin</a> which seems good and everything, but i don&#39;t get what are the advantages of installing DRF + plugin just to use jwt.<br/> I think i can implement jwt, refresh tokens etc. without drf and that plugin (i don&#39;t wanna sound presumptuous, i have to study more the subject so it&#39;s totally possible that i&#39;m wrong). So the question is, it&#39;s a bad idea to implement jwt myself or i&#39;m just re-inventing the wheel and i should go with drf? I don&#39;t like to unnecessarily rely on someone el

## Connecting Digital Ocean Spaces to Django for Media/Static files
 - [https://www.reddit.com/r/django/comments/1h2uekw/connecting_digital_ocean_spaces_to_django_for](https://www.reddit.com/r/django/comments/1h2uekw/connecting_digital_ocean_spaces_to_django_for)
 - RSS feed: $source
 - date published: 2024-11-29T20:00:13+00:00

<!-- SC_OFF --><div class="md"><p>Hey y&#39;all. I recently took on my first gig for a local organization where I created a portal system for users to upload PDF&#39;s for certain individuals. Developing locally went great, but when it came time to put it in production, I hit a few roadblocks.</p> <p>With the GitHub student developer pack, I received $200 of Digital Ocean credits for a year. Before deploying the project on the App Platform, I needed to make sure that I could access the Spaces for media/static storage. </p> <p>I looked at tons of tutorials online and tried my best to match their settings configuration as much as possible. Currently, this is what I have at the bottom of my <a href="http://settings.py">settings.py</a> file: (the Postgres DB is local currently)</p> <pre><code>DATABASES = { &#39;default&#39;: { &#39;ENGINE&#39;: &#39;django.db.backends.postgresql&#39;, &#39;NAME&#39;: os.getenv(&#39;DATABASE_NAME&#39;, env(&#39;DATABASE_NAME&#39;)), &#39;USER&#39;: os.get

## DeleteView not actually deleting object
 - [https://www.reddit.com/r/django/comments/1h2ttx8/deleteview_not_actually_deleting_object](https://www.reddit.com/r/django/comments/1h2ttx8/deleteview_not_actually_deleting_object)
 - RSS feed: $source
 - date published: 2024-11-29T19:34:01+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to Django, so I apologize if I don&#39;t use the correct vocabulary.</p> <p>I am using class based views for a program that allows for the creation of courses and their attached sections. I want to be able to choose to delete a section, be sent to a confirmation page, and after the deletion is confirmed, send the user to the course detail page where they originated.</p> <p>All of that works with the exception of the actual deletion of the object. The admin panel shows the object hasn&#39;t been deleted and the section list view still has the object on the course page.</p> <p>I&#39;m using pycharm and this is what shows up in the django console after confirming deletion:</p> <p><code>[29/Nov/2024 19:17:05] &quot;GET /course/2?csrfmiddlewaretoken=VL7R0leEHIijZRHfr0L2XWB0mds0pvMlokGppqPr1WSvEA19cK7GdrcR9rNgn0OI HTTP/1.1&quot; 200 1112</code></p> <p><code>[29/Nov/2024 19:17:06] &quot;GET /course/2/section/11/delete? HTTP/1.1&quot; 200 530</co

## Help needed for Django app deployment
 - [https://www.reddit.com/r/django/comments/1h2rnac/help_needed_for_django_app_deployment](https://www.reddit.com/r/django/comments/1h2rnac/help_needed_for_django_app_deployment)
 - RSS feed: $source
 - date published: 2024-11-29T18:00:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I am planning to deploy my Django app into non prod environments.As per the docs I am planning to use apache with mod_wsgi.</p> <p>Can anyone please share examples of sample got hub repos for the same? </p> <p>I am my angular front end end deployed where nginx is the web server..now the angular has to connect to Django backend over http..I have to deploy Django backend on the Linux VM.i have suggested to use apache as wen server with mod_wsgi..please suggest if am going in the right direction </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/prash1988"> /u/prash1988 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2rnac/help_needed_for_django_app_deployment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2rnac/help_needed_for_django_app_deployment/">[comments]</a></span>

## Why is a field not showing up even though it has been migrated properly?
 - [https://www.reddit.com/r/django/comments/1h2ok9e/why_is_a_field_not_showing_up_even_though_it_has](https://www.reddit.com/r/django/comments/1h2ok9e/why_is_a_field_not_showing_up_even_though_it_has)
 - RSS feed: $source
 - date published: 2024-11-29T15:44:19+00:00

<!-- SC_OFF --><div class="md"><p>So i’ve got this project i’m working on and im quite new to django. I’ve created my models and views and everything but when running it, i get an error saying a certain field doesn’t exist even tho i can see it does and it’s been migrated. Does anyone know what to do to fix it? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dolo_111"> /u/Dolo_111 </a> <br/> <span><a href="https://www.reddit.com/gallery/1h2ok9e">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2ok9e/why_is_a_field_not_showing_up_even_though_it_has/">[comments]</a></span>

## HELP! Custom error response schema for all exception within ninja-extra api
 - [https://www.reddit.com/r/django/comments/1h2ogyk/help_custom_error_response_schema_for_all](https://www.reddit.com/r/django/comments/1h2ogyk/help_custom_error_response_schema_for_all)
 - RSS feed: $source
 - date published: 2024-11-29T15:39:58+00:00

<!-- SC_OFF --><div class="md"><p>I am using django with django-ninja and ninja-extra. nijna-jwt for auth.</p> <p>At this moment api return error as `{&#39;detail&#39;: &#39;Error Message&#39;}` </p> <p>but there is also pydantic errors like `{&#39;type&#39;: &#39;missing&#39;, &#39;loc&#39;: (&#39;body&#39;, &#39;data&#39;, &#39;password&#39;), &#39;msg&#39;: &#39;Field required&#39;}`</p> <p>I want all errors should follow a specific format</p> <p>`{&#39;success&#39;: &#39;false&#39;, &#39;message&#39;: &#39;Human friendly message&#39;}`</p> <p>How can I achieve this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/noob_bug_hunter"> /u/noob_bug_hunter </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2ogyk/help_custom_error_response_schema_for_all/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2ogyk/help_custom_error_response_schema_for_all/">[comments]</a></span>

## Best library for Magic Links
 - [https://www.reddit.com/r/django/comments/1h2n22v/best_library_for_magic_links](https://www.reddit.com/r/django/comments/1h2n22v/best_library_for_magic_links)
 - RSS feed: $source
 - date published: 2024-11-29T14:32:33+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve seen there are several libraries for this (django-magiclink, django-magic-link, django-sesame, django-magicauth...)</p> <p>Which one do you recommend? Or which things I should take into account when choosing?</p> <p>I&#39;m a Django beginner and I&#39;m pretty lost here. </p> <p>I want to receive payments using Stripe (Stripe Checkout probably) and send a magic link to the buyers so they can access a protected URL in my Django app. I will have several products (several protected URLs). </p> <p>I don&#39;t need super advanced security or complex features. Just something simple (for me and my users). </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/migueladv"> /u/migueladv </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2n22v/best_library_for_magic_links/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2n22v/best_library_for_magic_link

## Type errors in VSCode
 - [https://www.reddit.com/r/django/comments/1h2mk4p/type_errors_in_vscode](https://www.reddit.com/r/django/comments/1h2mk4p/type_errors_in_vscode)
 - RSS feed: $source
 - date published: 2024-11-29T14:08:57+00:00

<!-- SC_OFF --><div class="md"><p>Greetings - I&#39;m a long time developer generally in the static typing camp and relatively new to Python. Loving Django&#39;s design and the Python language generally, but I do miss my compile step to tell me when I&#39;ve messed up a refactor, so I&#39;m trying to lean on type hints where I can.</p> <p>This generally works pretty well for other Python code, but I find that VSCode&#39;s Pylance integration is giving me errors about the Django models. Dynamic properties like id and references that aren&#39;t visible to the type checker show up as errors everywhere. I&#39;ve just been peppering the references with # type: ignore but I assume there is a better way.</p> <p>Is there a commonly used way to mark up a model class so Pylance / mypy are aware of the dynamic properties and can type check properly?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/eyepaq"> /u/eyepaq </a> <br/> <span><a href="h

## Any side projects that need support
 - [https://www.reddit.com/r/django/comments/1h2mhd8/any_side_projects_that_need_support](https://www.reddit.com/r/django/comments/1h2mhd8/any_side_projects_that_need_support)
 - RSS feed: $source
 - date published: 2024-11-29T14:04:59+00:00

<!-- SC_OFF --><div class="md"><p>I have some free time available, are there any projects available that have open tickets that I can contribute to?</p> <p>Just a little background, I have 6+ years of experience working in Python and Django. My recent work is available on my profile as well. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/grandimam"> /u/grandimam </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2mhd8/any_side_projects_that_need_support/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2mhd8/any_side_projects_that_need_support/">[comments]</a></span>

## Django-related Deals for Black Friday 2024
 - [https://www.reddit.com/r/django/comments/1h2kqgv/djangorelated_deals_for_black_friday_2024](https://www.reddit.com/r/django/comments/1h2kqgv/djangorelated_deals_for_black_friday_2024)
 - RSS feed: $source
 - date published: 2024-11-29T12:29:01+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/czue13"> /u/czue13 </a> <br/> <span><a href="https://adamj.eu/tech/2024/11/18/django-black-friday-deals-2024/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2kqgv/djangorelated_deals_for_black_friday_2024/">[comments]</a></span>

## appliku advice for 502 Bad Gateway error
 - [https://www.reddit.com/r/django/comments/1h2jbig/appliku_advice_for_502_bad_gateway_error](https://www.reddit.com/r/django/comments/1h2jbig/appliku_advice_for_502_bad_gateway_error)
 - RSS feed: $source
 - date published: 2024-11-29T10:55:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi</p> <p>I&#39;m deploying my first app using appliku with a Hetzner server. Followed the appliku guide and finally got to the state where the deployment was finished, but when I try to open the app using the appname and <a href="http://appliku.com">appliku.com</a> address I get the following page: 502 Bad Gateway nginx/1.24.0 (Ubuntu). </p> <p>Any advice on what I might have wrong within the coding to cause this issue? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Puzzleheaded_Tap730"> /u/Puzzleheaded_Tap730 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2jbig/appliku_advice_for_502_bad_gateway_error/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2jbig/appliku_advice_for_502_bad_gateway_error/">[comments]</a></span>

## Can I aggregate over values(Many-to-Many->ForeignKey, Date)?
 - [https://www.reddit.com/r/django/comments/1h2ghki/can_i_aggregate_over_valuesmanytomanyforeignkey](https://www.reddit.com/r/django/comments/1h2ghki/can_i_aggregate_over_valuesmanytomanyforeignkey)
 - RSS feed: $source
 - date published: 2024-11-29T07:29:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to calculate a lookup for items sharing a common related object + a common value. As an informal summary, I want to use some form of:</p> <p><code>my_queryset.values(my_related_obj, my_date).annotate(...)</code></p> <p>--in order to get, for each <code>related_obj, date</code> pair a <code>Sum</code> aggregation of matching items in the queryset.</p> <p>The <code>related_obj</code> in this case is two joins away -- a Many-to-Many relation, and then a foreign-key. So there are definitely queryset items with multiple values for the related object, or reaching the same related object through a different intermediary object. This seems like it should be doable, but I keep getting incorrect results no matter what I try. I can&#39;t get the grouping to be what I want it.</p> <p>Here&#39;s a simple example: I have <code>Persons</code> assigned to <code>Teams</code>; I have <code>ExpenseReports</code> signed by (multiple) <code>Persons</code> 

## Django templates vs React
 - [https://www.reddit.com/r/django/comments/1h2fl3y/django_templates_vs_react](https://www.reddit.com/r/django/comments/1h2fl3y/django_templates_vs_react)
 - RSS feed: $source
 - date published: 2024-11-29T06:27:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, why would I use React over Django’s templating system if I have below 500k users for anything? I feel like using React is pretty overkill for most web applications even if it needs to be dynamic, unless it’s a really custom app that needs to be highly dynamic. I feel that if I really wanted some front end reactivity, I could use libraries like AlpineJS and snabbdom, and that should be enough? </p> <p>FYI, I can be a big noob. Looking for what people experience and a difference in opinions and perspectives. I ask this question more to find out what others think because I feel like web development can quickly become overkill and overly complex for no reason. So I’m a proponent for keeping things simple. Please share your thoughts/experience! Would kindly appreciate it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lucasriki"> /u/lucasriki </a> <br/> <span><a href="https://www.reddit.com/r/django/com

## Creating a pip package to reuse Code
 - [https://www.reddit.com/r/django/comments/1h2f9s3/creating_a_pip_package_to_reuse_code](https://www.reddit.com/r/django/comments/1h2f9s3/creating_a_pip_package_to_reuse_code)
 - RSS feed: $source
 - date published: 2024-11-29T06:07:38+00:00

<!-- SC_OFF --><div class="md"><p>I am building two apps with some similar flows and features. What i want to do is create a pip package so i can reuse the code in both projects from that one pip package and then develop in that package when i make new common features and such. Any tips or guidelines to do this</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alarmed_Blueberry_99"> /u/Alarmed_Blueberry_99 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2f9s3/creating_a_pip_package_to_reuse_code/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2f9s3/creating_a_pip_package_to_reuse_code/">[comments]</a></span>

## What are the best cache backends available in Django?
 - [https://www.reddit.com/r/django/comments/1h2dt34/what_are_the_best_cache_backends_available_in](https://www.reddit.com/r/django/comments/1h2dt34/what_are_the_best_cache_backends_available_in)
 - RSS feed: $source
 - date published: 2024-11-29T04:37:54+00:00

<!-- SC_OFF --><div class="md"><p>Hey Django devs! I&#39;m looking to optimize my web application&#39;s performance and want to dive deep into caching. What cache backends have you found most effective?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tricky-Special8594"> /u/Tricky-Special8594 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2dt34/what_are_the_best_cache_backends_available_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2dt34/what_are_the_best_cache_backends_available_in/">[comments]</a></span>

## Web-sockets : real-time updates
 - [https://www.reddit.com/r/django/comments/1h2av4j/websockets_realtime_updates](https://www.reddit.com/r/django/comments/1h2av4j/websockets_realtime_updates)
 - RSS feed: $source
 - date published: 2024-11-29T01:42:49+00:00

<!-- SC_OFF --><div class="md"><p><strong>Hi everyone!</strong></p> <p>I&#39;m currently developing a personal project and encountered a challenge with implementing real-time updates. I&#39;m using WebSockets to ensure the updates are synchronous and happen in real-time. During the process, I realized I&#39;m currently using multiple WebSocket connections (four so far), each handling a specific task: managing real-time invites, instant redirections (handling invite responses), chat functionality, etc.</p> <p>My questions are:</p> <ol> <li><strong>Will having multiple WebSocket connections affect the overall quality or performance of my project?</strong></li> <li><strong>Would having multiple WebSocket connections cause any conflicts or unexpected behavior between them?</strong></li> <li><strong>Is it more efficient or favorable to reduce the number of WebSocket connections by combining tasks into fewer connections?</strong></li> <li><strong>What are the potential drawbacks of managin

## Flatpages
 - [https://www.reddit.com/r/django/comments/1h2aahd/flatpages](https://www.reddit.com/r/django/comments/1h2aahd/flatpages)
 - RSS feed: $source
 - date published: 2024-11-29T01:08:54+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using Django flatpages and looking to enhance its functionality. If anyone knows of useful modules or methods to extend flatpages, I’d appreciate your recommendations! Specifically, I’m looking for a feature that allows images to be easily added via drag-and-drop.</p> <p>Additionally, if there are any other modules or tools that you find helpful in working with flatpages, please feel free to share.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Plastic-Walrus-7629"> /u/Plastic-Walrus-7629 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h2aahd/flatpages/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h2aahd/flatpages/">[comments]</a></span>

