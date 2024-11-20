# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django and Windows environment
 - [https://www.reddit.com/r/django/comments/1gv9cdj/django_and_windows_environment](https://www.reddit.com/r/django/comments/1gv9cdj/django_and_windows_environment)
 - RSS feed: $source
 - date published: 2024-11-19T22:04:26+00:00

<!-- SC_OFF --><div class="md"><p>So, I&#39;m trying to deploy a django application on a Windows 2019 server and using a local AD to authenticate the users. This is for a new intranet website. I need to gather the AD security groups as well </p> <p>However, all of the libraries that would tie a local AD to UserModels seem to either be out of date or abandoned (that Ive found)</p> <p>Does anyone have suggestions ?</p> <p>Python-ldap3 : wouldn&#39;t package due to C++ conflict on build tools. Maybe need an old version? Django-windowsauth : out of date and depends on ldap3 as well</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thaprodigy58"> /u/thaprodigy58 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gv9cdj/django_and_windows_environment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gv9cdj/django_and_windows_environment/">[comments]</a></span>

## ASP.NET and Django. What's the difference?
 - [https://www.reddit.com/r/django/comments/1gv903l/aspnet_and_django_whats_the_difference](https://www.reddit.com/r/django/comments/1gv903l/aspnet_and_django_whats_the_difference)
 - RSS feed: $source
 - date published: 2024-11-19T21:49:54+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;d like to say that I&#39;m not looking for an answer about which one is better, but that&#39;s a lie. However, this is subjective for everyone.</p> <p>If there are anyone here who has experience with both <a href="http://ASP.NET">ASP.NET</a> and Django, please share your impressions.</p> <p>P.S. I searched, but if anyone made a comparison, it was years ago!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jonikster"> /u/Jonikster </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gv903l/aspnet_and_django_whats_the_difference/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gv903l/aspnet_and_django_whats_the_difference/">[comments]</a></span>

## How to make hot reload also reload the .py files used for django_components.
 - [https://www.reddit.com/r/django/comments/1gv8ey3/how_to_make_hot_reload_also_reload_the_py_files](https://www.reddit.com/r/django/comments/1gv8ey3/how_to_make_hot_reload_also_reload_the_py_files)
 - RSS feed: $source
 - date published: 2024-11-19T21:25:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I&#39;m using django_components in my project. Whenever I make changes to the python file for my component, I have to literally kill the server then run manage.py runserver again for the changes to take effect. I noticed that it also works that way with template tags and libraries. If you want the changes to take effect, you need to kill the whole server and restart Django.</p> <p>Now, I&#39;m also using using django_browser_reload in my project.</p> <p>Is there a way to make it so that I don&#39;t have to manually kill and restart my server to get the changes in my template .py files to take effect?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lusayo_ny"> /u/lusayo_ny </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gv8ey3/how_to_make_hot_reload_also_reload_the_py_files/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gv8ey3/how_to_make_hot_

## Has anyone here built a profitable side project with Django or created one for a client that generates profit?
 - [https://www.reddit.com/r/django/comments/1gv7q2v/has_anyone_here_built_a_profitable_side_project](https://www.reddit.com/r/django/comments/1gv7q2v/has_anyone_here_built_a_profitable_side_project)
 - RSS feed: $source
 - date published: 2024-11-19T20:56:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m curious to hear from those who’ve created side projects using Django. Have any of you built something that turned out to be profitable, either as a personal project or for a client?</p> <p>I’m working on a side project myself using Django and DRF, mainly focusing on the backend. While I enjoy the process, I’m also wondering about the potential for turning it into something financially viable.</p> <p>Thanks in advance for sharing your experiences! I’m hoping this inspires ideas and helps me (and others) approach these projects with a more practical perspective.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SadWimp"> /u/SadWimp </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gv7q2v/has_anyone_here_built_a_profitable_side_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gv7q2v/has_anyone_here_built_a_profitable_side_project/">[c

## How to Store Service Prices in Orders While Allowing Service Updates?
 - [https://www.reddit.com/r/django/comments/1gv2667/how_to_store_service_prices_in_orders_while](https://www.reddit.com/r/django/comments/1gv2667/how_to_store_service_prices_in_orders_while)
 - RSS feed: $source
 - date published: 2024-11-19T17:07:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I’m building a Django app and ran into an issue with managing financial data for customer orders. Here’s the setup: • I have a Service model that stores the current price, description, and other details of a service. • I also have an Order model that represents a customer acquiring multiple services.</p> <p>The problem is that I need to save the current price (and possibly other details) of each service at the time the order is created. However, I also want the Service model to remain editable so that I can update prices or descriptions without affecting past orders.</p> <p>How can I design my models to handle this situation? Does this approach make sense, or is there a better way to achieve this? Any advice would be greatly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Iamjuanclopez6"> /u/Iamjuanclopez6 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gv2667/how_to

## Stripe 403 Invalid Request Error on Development Server but Works Fine Locally
 - [https://www.reddit.com/r/django/comments/1guzvyy/stripe_403_invalid_request_error_on_development](https://www.reddit.com/r/django/comments/1guzvyy/stripe_403_invalid_request_error_on_development)
 - RSS feed: $source
 - date published: 2024-11-19T15:34:03+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m integrating Stripe Checkout with my Django app, and while everything works perfectly on my local environment, I&#39;m running into issues on the development server.</p> <p>When I attempt to create a Checkout Session, Stripe logs show a 403 invalid_request_error.</p> <p>Here’s the response from Stripe logs:</p> <p>&quot;error&quot;: {</p> <p>&quot;message&quot;: &quot;We&#39;re sorry, but we&#39;re unable to serve your request.&quot;,</p> <p>&quot;request_log_url&quot;: &quot;<a href="https://dashboard.stripe.com/test/logs/req%5C_V8kugNXSmBLuh2?t=1732029176">https://dashboard.stripe.com/test/logs/req\_V8kugNXSmBLuh2?t=1732029176</a>&quot;,</p> <p>&quot;type&quot;: &quot;invalid_request_error&quot;</p> <p>}</p> <p>}</p> <p>I&#39;ve double-checked the following:</p> <p>Publishable Key</p> <p>Secret Key</p> <p>Request Payload (matches the format recommended in the Stripe documentation)</p> <p>SSL Configuration (HTTPS is enabled on the development

## Pseudo OS
 - [https://www.reddit.com/r/django/comments/1guzspc/pseudo_os](https://www.reddit.com/r/django/comments/1guzspc/pseudo_os)
 - RSS feed: $source
 - date published: 2024-11-19T15:30:07+00:00

<!-- SC_OFF --><div class="md"><p>I am a novice django developer and I came up with the idea for a pet project, it will be a pseudo operating system in the browser, with its own console applications and much more. Is it a good idea? And how would you rate this project if you were an employer?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Warm-Procedure6691"> /u/Warm-Procedure6691 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1guzspc/pseudo_os/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1guzspc/pseudo_os/">[comments]</a></span>

## Cheap and easy to use hosting services?
 - [https://www.reddit.com/r/django/comments/1guylwj/cheap_and_easy_to_use_hosting_services](https://www.reddit.com/r/django/comments/1guylwj/cheap_and_easy_to_use_hosting_services)
 - RSS feed: $source
 - date published: 2024-11-19T14:38:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello there everyone, I am currently working on a django app that I want to deploy on a hosting service. I was wondering what would be a good hosting service that is relatively cheap and easy to use. The app is for a school project and it is my first django project so I&#39;m a bit lost on what would be good. My only experience with hosting before was hosting a flask project on PythonAnywhere, but from what I&#39;ve read it seems Python 3.12 is not yet supported there. I am currently using Supabase for my database so I don&#39;t think I would need to worry about that.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OneTrueFailure"> /u/OneTrueFailure </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1guylwj/cheap_and_easy_to_use_hosting_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1guylwj/cheap_and_easy_to_use_hosting_services/">[comments]</a></span>

## Related objects that can't change
 - [https://www.reddit.com/r/django/comments/1guw4l7/related_objects_that_cant_change](https://www.reddit.com/r/django/comments/1guw4l7/related_objects_that_cant_change)
 - RSS feed: $source
 - date published: 2024-11-19T12:36:46+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m curious to hear how you handle related objects that can&#39;t change - think e-commerce, with things like customer addresses and payment methods attached to orders. Foreign keys seem ideal for these types of relationships, and yet the customer might change or delete their address.</p> <p>I&#39;m using deepcopy() to clone the objects, and I&#39;m aware there are 3rd party solutions for locking or freezing models or fields. But I&#39;m curious what solutions you are all using in these cases.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/verbo_phobia"> /u/verbo_phobia </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1guw4l7/related_objects_that_cant_change/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1guw4l7/related_objects_that_cant_change/">[comments]</a></span>

## How To Deploy Django Connect With Cassandra To Pythonanywhere?
 - [https://www.reddit.com/r/django/comments/1guw251/how_to_deploy_django_connect_with_cassandra_to](https://www.reddit.com/r/django/comments/1guw251/how_to_deploy_django_connect_with_cassandra_to)
 - RSS feed: $source
 - date published: 2024-11-19T12:32:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys i have a django project connect with cassandra database </p> <p>and this database on datastax platform so on my computer connect without problem but on pythonanywhere i get this error: </p> <p><a href="https://preview.redd.it/fbhtxwejqu1e1.png?width=1167&amp;format=png&amp;auto=webp&amp;s=9afa0fc4d2f2e54a8b1de78634ed3bf380112b82">https://preview.redd.it/fbhtxwejqu1e1.png?width=1167&amp;format=png&amp;auto=webp&amp;s=9afa0fc4d2f2e54a8b1de78634ed3bf380112b82</a></p> <p>and this my settings file database config:</p> <p><a href="https://preview.redd.it/pprk5g7xqu1e1.png?width=754&amp;format=png&amp;auto=webp&amp;s=2f8e429d9957a670c6d12edf776d316ed1b0c294">https://preview.redd.it/pprk5g7xqu1e1.png?width=754&amp;format=png&amp;auto=webp&amp;s=2f8e429d9957a670c6d12edf776d316ed1b0c294</a></p> <p>Although it works on my device without problems, the problem is when uploading the Django project to the pythonanywere platform.</p> <p>I appreciate your hel

## Django Rest Framework Fields tip
 - [https://www.reddit.com/r/django/comments/1guvfu2/django_rest_framework_fields_tip](https://www.reddit.com/r/django/comments/1guvfu2/django_rest_framework_fields_tip)
 - RSS feed: $source
 - date published: 2024-11-19T11:56:09+00:00

<!-- SC_OFF --><div class="md"><p>Fields in serializers allow us to customize the serialization and deserialization process. DRF provides a wide range of field types, including built-in fields like CharField, IntegerField, and DateTimeField, as well as custom fields that we can define ourselves.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://i.redd.it/obz2fsluku1e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1guvfu2/django_rest_framework_fields_tip/">[comments]</a></span>

## Is this a good production setup?
 - [https://www.reddit.com/r/django/comments/1guuq8b/is_this_a_good_production_setup](https://www.reddit.com/r/django/comments/1guuq8b/is_this_a_good_production_setup)
 - RSS feed: $source
 - date published: 2024-11-19T11:09:21+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve just finished deploying my project on Digital Ocean and would like to hear your opinion on the way I&#39;ve done it and if this is a production-friendly setup. Any feedback is welcome but please be nice as this is my first run-in with this amount of devops.</p> <p>The application is a bookings management SaaS for small businesses to manage (calendar view) and sell (online store) their experiences (Surf camps, Yoga camps, Wellness retreats, etc)</p> <p>The stack is a Django app with AlpineJs for frontend all within the same project + Postgres + Redis + Celery.</p> <p>I set up my Django project with cookiecutter-django from the two scoops guys and for local dev I&#39;m using Docker.</p> <p>So for local Dev I use Docker and run all these services in one container.</p> <p>On Digital Ocean I decided not to use Docker and to go for their App Platform app (Django app) + Managed Database (Postgres) + Managed Cache Database (Redis) + Spaces (Static) 

## Apple signin/login with django and flutter problem - invalid_client response.
 - [https://www.reddit.com/r/django/comments/1guu7tk/apple_signinlogin_with_django_and_flutter_problem](https://www.reddit.com/r/django/comments/1guu7tk/apple_signinlogin_with_django_and_flutter_problem)
 - RSS feed: $source
 - date published: 2024-11-19T10:33:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m having an issue with implementing Apple Sign-In/Login in my Django + Flutter application. Here&#39;s the flow I&#39;m using:</p> <ol> <li>On the Flutter side, I&#39;m using the following code to get credentials from Apple:</li> </ol> <p>&#8203;</p> <pre><code>SignInWithAppleButton( onPressed: () async { final credential = await SignInWithApple.getAppleIDCredential( scopes: [ AppleIDAuthorizationScopes.email, AppleIDAuthorizationScopes.fullName, ], ); print(credential); // Now send the credential (especially `credential.authorizationCode`) to your server to create a session // after they have been validated with Apple }, ); </code></pre> <p>This returns information like identity_token and authorization_code.</p> <ol> <li>For test purposes, I send the authorization_code in a POST request to the endpoint <a href="https://appleid.apple.com/auth/token">https://appleid.apple.com/auth/token</a> with the following details:</li> </ol> <p>Headers:<

## Keeping large data available to all users in memory
 - [https://www.reddit.com/r/django/comments/1guu1t8/keeping_large_data_available_to_all_users_in](https://www.reddit.com/r/django/comments/1guu1t8/keeping_large_data_available_to_all_users_in)
 - RSS feed: $source
 - date published: 2024-11-19T10:21:45+00:00

<!-- SC_OFF --><div class="md"><p>Not quite sure if this is the correct subreddit for questions like this, but here I go:</p> <p>I&#39;m currently building a website where I each day want yesterday&#39;s financial data cached in memory for the full day, to be quickly available to all users (note that this data is incommon for all users, and can be quite big at ~50 MB). I also want to cache older data on request, e.g. if a user looks at data for some date in 2023, I also want to cache that, although for a shorter time (say maybe 1 h).</p> <p>Being new to Django, I&#39;ve tried to read up on the different caching solutions that Django offers, but I&#39;m a bit confused as to which would server me well.</p> <ul> <li>Does Django offer an existing solution fit for this purpose?</li> <li>Would it be easier to set up a manual pure python caching process, which fetches cached data if it exists, and otherwise retrieves and caches it for a specfied time period?</li> <li>Can this be solved by s

## Is anyone using Django for like super simple static websites and funnels?
 - [https://www.reddit.com/r/django/comments/1guq1a7/is_anyone_using_django_for_like_super_simple](https://www.reddit.com/r/django/comments/1guq1a7/is_anyone_using_django_for_like_super_simple)
 - RSS feed: $source
 - date published: 2024-11-19T05:29:21+00:00

<!-- SC_OFF --><div class="md"><p>I was just curious if anyone is using Django for simple websites and funnels? Simple static pages, long or short form sales or VSLs, or is it overkill?</p> <p>Appreciate your time and insight!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mufasis"> /u/mufasis </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1guq1a7/is_anyone_using_django_for_like_super_simple/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1guq1a7/is_anyone_using_django_for_like_super_simple/">[comments]</a></span>

## Going to write a blog on DJP and it's not even my library
 - [https://www.reddit.com/r/django/comments/1gupgqj/going_to_write_a_blog_on_djp_and_its_not_even_my](https://www.reddit.com/r/django/comments/1gupgqj/going_to_write_a_blog_on_djp_and_its_not_even_my)
 - RSS feed: $source
 - date published: 2024-11-19T04:56:08+00:00

<!-- SC_OFF --><div class="md"><p>idk if ya&#39;ll have taken a look at <a href="https://github.com/simonw/djp">https://github.com/simonw/djp</a> but I feel now obligated to share this since I&#39;m heavily using it for my project <a href="https://github.com/epuerta9/kitchenai">https://github.com/epuerta9/kitchenai</a> and I feel others will really benefit. Especially those building meta-frameworks </p> <p>My use case:<br/> - I wanted to leverage django&#39;s plugin framework around installing apps, middleware, etc but without exposing django internals to the user</p> <p>this is where DJP fit perfectly. Without touching the <a href="http://settings.py">settings.py</a>, and using only `pip install`, libraries can automatically get added to installed_apps, middleware, hooks, you name it. </p> <p>I&#39;m sure simonw must have had a similar issue but it fits so many good use cases. I see it as a big win for django community especially since it&#39;s fairly new. </p> <p>End result:<br/> -

## Can i do this will django as frontend?
 - [https://www.reddit.com/r/django/comments/1guok39/can_i_do_this_will_django_as_frontend](https://www.reddit.com/r/django/comments/1guok39/can_i_do_this_will_django_as_frontend)
 - RSS feed: $source
 - date published: 2024-11-19T04:06:34+00:00

<!-- SC_OFF --><div class="md"><p>I need advice, im looking to migrate my current php app (dont have source code) that uses natural php to use full django only. Because i need to add new features, the system is almost 9 years old.</p> <p>current db is mysql</p> <p>The app is a ISP(internet provider) management system that have the following:</p> <ol> <li>invoice system</li> <li>integration with mikrotik routers</li> <li>support ticket system</li> <li>inventory system</li> <li>client portal</li> <li>option for client to pay with paypal plus other custom payment gateway from Panama latinamerica</li> </ol> <p>Any tip or recommendation?</p> <p>Thanks 🙏🏻</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/agaitan026"> /u/agaitan026 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1guok39/can_i_do_this_will_django_as_frontend/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1guok39/can_i_do_this_will_djan

## Need to learn DRF for job
 - [https://www.reddit.com/r/django/comments/1guo18z/need_to_learn_drf_for_job](https://www.reddit.com/r/django/comments/1guo18z/need_to_learn_drf_for_job)
 - RSS feed: $source
 - date published: 2024-11-19T03:37:48+00:00

<!-- SC_OFF --><div class="md"><p>I recently got a new job and they use DRF and I was wondering if ya&#39;ll could supply me with some tutorials, I prefer video, but books are nice as well. Thanks. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Weak-Extension-5196"> /u/Weak-Extension-5196 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1guo18z/need_to_learn_drf_for_job/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1guo18z/need_to_learn_drf_for_job/">[comments]</a></span>

