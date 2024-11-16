# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Is there a better way to handle multiple DRF generic views for a single endpoint with different methods?
 - [https://www.reddit.com/r/django/comments/1gsa3jt/is_there_a_better_way_to_handle_multiple_drf](https://www.reddit.com/r/django/comments/1gsa3jt/is_there_a_better_way_to_handle_multiple_drf)
 - RSS feed: $source
 - date published: 2024-11-15T23:39:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to build by user endpoint out with 3 methods, GET to get info about the current user, POST to create a new user, and DELETE to delete a user. I have a generic view for each of those methods, but right now i have to use a really sketchy way of combining them all into one url with different methods. Here is my views code:</p> <pre><code> class UserView(APIView): def delete(self, request, *args, **kwargs): # DRF views expect a normal django request object, and when they get one, they automatically upgrade it to a DRF request # So when this view gets a Django request, it upgrades it to a DRF request, so when I pass it down to another DRF view # It breaks because that one is also expecting a normal Django request. Adding ._request gets around this by getting the # original Django request object out of the DRF one. return DeleteUserView.as_view()(request._request, *args, **kwargs) def post(self, request, *args, **kwargs): return RegisterUser

## User schemes. Admin/staff and end users using the same system?
 - [https://www.reddit.com/r/django/comments/1gs8ah4/user_schemes_adminstaff_and_end_users_using_the](https://www.reddit.com/r/django/comments/1gs8ah4/user_schemes_adminstaff_and_end_users_using_the)
 - RSS feed: $source
 - date published: 2024-11-15T22:15:37+00:00

<!-- SC_OFF --><div class="md"><p>It always seemed like a bad idea to have end users and staff users use the same user system. Seems like even their DB tables should be isolated from each other. The dango User system is pretty good for staff so is there a good approach for extending that for end users that would also define a strong separation?</p> <p>For example, devs and content staff should be able to use the admin without any way of screwing up end user data. Migrations for Admin/staff models should have zero impact on end user models. </p> <p>Perhaps I&#39;m being too fussy about it but it just seems like end user systems and admin/staff users systems should be as disconnected as possible. </p> <p>Is there a common practice for this? </p> <p>Thank you! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hans__Blix"> /u/Hans__Blix </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gs8ah4/user_schemes_adminstaff_and_end_users_us

## Is it good decision to last django for final year student?
 - [https://www.reddit.com/r/django/comments/1gs6o8w/is_it_good_decision_to_last_django_for_final_year](https://www.reddit.com/r/django/comments/1gs6o8w/is_it_good_decision_to_last_django_for_final_year)
 - RSS feed: $source
 - date published: 2024-11-15T21:03:53+00:00

<!-- SC_OFF --><div class="md"><p>I’m currently in final year of mca Placements are going on already ……:) is it a good Devon to Learn Django.? But solved nearly 100 question on leetcode using Java 😶</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Age9954"> /u/No-Age9954 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gs6o8w/is_it_good_decision_to_last_django_for_final_year/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gs6o8w/is_it_good_decision_to_last_django_for_final_year/">[comments]</a></span>

## What is the easiest way to send data from localstorage to views
 - [https://www.reddit.com/r/django/comments/1grynvl/what_is_the_easiest_way_to_send_data_from](https://www.reddit.com/r/django/comments/1grynvl/what_is_the_easiest_way_to_send_data_from)
 - RSS feed: $source
 - date published: 2024-11-15T15:19:36+00:00

<!-- SC_OFF --><div class="md"><p>It gives me csrf errors and i kinda dont want to rewrite my cart code into django<br/> or is there a way to disable csrf protection because it is just a study project</p> <p>Javascript code that is supposed to send the JSON with data:</p> <pre><code>function sendDataToServer(cartData) { const xhr = new XMLHttpRequest(); xhr.open(&quot;POST&quot;, &quot;cart:order_create&quot;); xhr.setRequestHeader(&quot;Content-Type&quot;, &quot;application/json&quot;); xhr.onload = function() { if (xhr.status === 200) { console.log(&quot;Data sent successfully&quot;); } else { console.error(&quot;Error sending data:&quot;, xhr.statusText); } }; xhr.send(JSON.stringify(cartData)); } function BuyButton(){ alert(&quot;Thank you for shopping with us&quot;) const cartData = getItems(); const csrfToken = document.querySelector(&#39;input[name=&quot;csrfmiddlewaretoken&quot;]&#39;).value; const dataToSend = { cartData: cartData, csrf_token: csrfToken }; sendDataToServer(d

## 🚀 Feature Friday: PostgreSQL Connection Pools!
 - [https://www.reddit.com/r/django/comments/1grwhlk/feature_friday_postgresql_connection_pools](https://www.reddit.com/r/django/comments/1grwhlk/feature_friday_postgresql_connection_pools)
 - RSS feed: $source
 - date published: 2024-11-15T13:35:56+00:00

<!-- SC_OFF --><div class="md"><p>Welcome to this week&#39;s Django Feature Friday on PostgreSQL Connection Pools!</p> <p>This small-but-mighty change lets you enable connection pooling with a single line in your settings. This reduces the overhead of accessing your database, leading to improved performance.</p> <p>You can turn it on like this:</p> <pre><code>DATABASES = { &quot;default&quot;: { &quot;ENGINE&quot;: &quot;django.db.backends.postgresql&quot;, # ... &quot;OPTIONS&quot;: { &quot;pool&quot;: True, }, }, } </code></pre> <p>If you want fine-grained control over your connection pools, you can also explicitly configure them by passing in a dictionary of settings:</p> <pre><code>DATABASES = { &quot;default&quot;: { &quot;ENGINE&quot;: &quot;django.db.backends.postgresql&quot;, # ... &quot;OPTIONS&quot;: { &quot;pool&quot;: { &quot;min_size&quot;: 2, &quot;max_size&quot;: 4, &quot;timeout&quot;: 10, } }, }, } </code></pre> <p>This little detail makes it easier to optimize your 

## How do you guys handle this case, multiple profiles for one user
 - [https://www.reddit.com/r/django/comments/1gruqrl/how_do_you_guys_handle_this_case_multiple](https://www.reddit.com/r/django/comments/1gruqrl/how_do_you_guys_handle_this_case_multiple)
 - RSS feed: $source
 - date published: 2024-11-15T11:58:38+00:00

<!-- SC_OFF --><div class="md"><p>So i&#39;ve this case where a user can create multiple profiles and can switch b/w them. It is basically like a social media platform, so that selected profile can do things just like an account.</p> <p>from what i know:</p> <ol> <li>we can create a field in User model, like &#39;active_profile&#39; and concentrate logics on backend. But there is this concurrency issue, if user access from different device/session, it won&#39;t work as expected since its a global state across all devices and sessions.</li> <li>store selected profile id on frontend storage like locatStorage, app&#39;s state and pass that id/username on every API requests made to backend. relies consistently on that saved profile reference on frontned.</li> </ol> <p>I was wondering which would be the better way to handle this and how others would approach this case.</p> <p><a href="https://github.com/quibble-dev/Quibble">code on github</a>, thanks.</p> </div><!-- SC_ON --> &#32; submit

## I just learnt how to connect my Django app to mysql
 - [https://www.reddit.com/r/django/comments/1grubxd/i_just_learnt_how_to_connect_my_django_app_to](https://www.reddit.com/r/django/comments/1grubxd/i_just_learnt_how_to_connect_my_django_app_to)
 - RSS feed: $source
 - date published: 2024-11-15T11:32:13+00:00

<!-- SC_OFF --><div class="md"><p>I just connected my django application to mysql database. I feel so proud of me right now.</p> <p><a href="https://preview.redd.it/kzb1vv1ww11e1.png?width=500&amp;format=png&amp;auto=webp&amp;s=53f2e376d59d5a7d7bbfca7accec6587505fa6fb">https://preview.redd.it/kzb1vv1ww11e1.png?width=500&amp;format=png&amp;auto=webp&amp;s=53f2e376d59d5a7d7bbfca7accec6587505fa6fb</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Butterscotch_7930"> /u/Ok_Butterscotch_7930 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1grubxd/i_just_learnt_how_to_connect_my_django_app_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1grubxd/i_just_learnt_how_to_connect_my_django_app_to/">[comments]</a></span>

## Ecommerce website
 - [https://www.reddit.com/r/django/comments/1grrofm/ecommerce_website](https://www.reddit.com/r/django/comments/1grrofm/ecommerce_website)
 - RSS feed: $source
 - date published: 2024-11-15T08:14:09+00:00

<!-- SC_OFF --><div class="md"><p>I want to make ecommerce Website using django and postgresql I want .some reference or idea to make website more attractive. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Django_Nik"> /u/Django_Nik </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1grrofm/ecommerce_website/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1grrofm/ecommerce_website/">[comments]</a></span>

## Search Accuracy and Flexibility with Django and PostgreSQL
 - [https://www.reddit.com/r/django/comments/1grrnl1/search_accuracy_and_flexibility_with_django_and](https://www.reddit.com/r/django/comments/1grrnl1/search_accuracy_and_flexibility_with_django_and)
 - RSS feed: $source
 - date published: 2024-11-15T08:12:24+00:00

<!-- SC_OFF --><div class="md"><p>Selecting the most effective comparison function depends on your specific data set and application requirements</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ruthcy"> /u/ruthcy </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1grrnl1/search_accuracy_and_flexibility_with_django_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1grrnl1/search_accuracy_and_flexibility_with_django_and/">[comments]</a></span>

## What's the most complex/Impressive thing you've built using Django?
 - [https://www.reddit.com/r/django/comments/1grri9o/whats_the_most_compleximpressive_thing_youve](https://www.reddit.com/r/django/comments/1grri9o/whats_the_most_compleximpressive_thing_youve)
 - RSS feed: $source
 - date published: 2024-11-15T08:01:31+00:00

<!-- SC_OFF --><div class="md"><p>By complex i mean code-wise. What&#39;s something that you built that really push the capabilities of Django and maybe Python? use this as a chance to show off.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1grri9o/whats_the_most_compleximpressive_thing_youve/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1grri9o/whats_the_most_compleximpressive_thing_youve/">[comments]</a></span>

## Article about CustomUser and security (FR)
 - [https://www.reddit.com/r/django/comments/1grrcad/article_about_customuser_and_security_fr](https://www.reddit.com/r/django/comments/1grrcad/article_about_customuser_and_security_fr)
 - RSS feed: $source
 - date published: 2024-11-15T07:49:26+00:00

<!-- SC_OFF --><div class="md"><p>I wrote an article about CustomUser Model.</p> <p>The importance of UserAsmin for security.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ReasonableDeer3187"> /u/ReasonableDeer3187 </a> <br/> <span><a href="https://www.gabrieltrouve.fr/blog/securiser-votre-customuser-django-indispensable-useradmin/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1grrcad/article_about_customuser_and_security_fr/">[comments]</a></span>

## How can I connect my Django app to a second PostgreSQL database on a different machine for CRUD operations?
 - [https://www.reddit.com/r/django/comments/1grqhz3/how_can_i_connect_my_django_app_to_a_second](https://www.reddit.com/r/django/comments/1grqhz3/how_can_i_connect_my_django_app_to_a_second)
 - RSS feed: $source
 - date published: 2024-11-15T06:47:47+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I have a Django web app that’s running locally and already connected to a PostgreSQL database for basic user management (login and registration). Now, I’d like to add functionality to perform CRUD operations on a <em>different</em> PostgreSQL database located on a separate machine within my local network.</p> <p>The goal is for my Django app to handle typical Create, Read, Update, and Delete operations on this second database while still maintaining the primary connection to the original database for user-related data.</p> <p>Here’s what I’m working with:</p> <ul> <li>My main PostgreSQL database is set up locally on the same machine as the Django app.</li> <li>The second PostgreSQL database is hosted on another local machine with its own IP and login details.</li> </ul> <p>I’m wondering how to set up Django to handle both connections smoothly. Is there a way to configure multiple database connections in <a href="http://settings.py"><cod

## Is django a good choice?
 - [https://www.reddit.com/r/django/comments/1groo4a/is_django_a_good_choice](https://www.reddit.com/r/django/comments/1groo4a/is_django_a_good_choice)
 - RSS feed: $source
 - date published: 2024-11-15T04:51:25+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>I currently trying to find the best solution to implement for a client of mine.</p> <p>What started as a simple HRM implementation now runs more towards some kind of lean ERP solution.</p> <p>I need something that can handle a lot of employee information and turnover across multiple clients and contracts types to generate accurate and pretty much automatic timesheets and invoicing.</p> <p>The company is pretty only generating pay and invoices, but these have to follow pretty complex business rules.</p> <p>I also have to handle a few HR processes that include on-boarding and termination along with some kind of document and signature tracking</p> <p>Nothing out of the ordinary, but I couldn&#39;t find a solution that could do that without heavy customization and license fees.</p> <p>I am leaning toward erpnext/frappe, but the installation process is much more complex than what I envisioned. I am also thinking about building something m

## Django making two database connection requests per view.
 - [https://www.reddit.com/r/django/comments/1grnmrv/django_making_two_database_connection_requests](https://www.reddit.com/r/django/comments/1grnmrv/django_making_two_database_connection_requests)
 - RSS feed: $source
 - date published: 2024-11-15T03:52:05+00:00

<!-- SC_OFF --><div class="md"><p>I read that Django does not poll database connection and makes new connection for each request and that there are ways to pool and persist connections. However, I am seeing two db connect request in traces. Is this normal or did i mess something up?</p> <p><a href="https://preview.redd.it/1v5zl5rsmz0e1.png?width=1421&amp;format=png&amp;auto=webp&amp;s=74b4ccbace1d3dddde7f8ed76eadd684cd469bc2">https://preview.redd.it/1v5zl5rsmz0e1.png?width=1421&amp;format=png&amp;auto=webp&amp;s=74b4ccbace1d3dddde7f8ed76eadd684cd469bc2</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Capable-Pitch-3189"> /u/Capable-Pitch-3189 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1grnmrv/django_making_two_database_connection_requests/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1grnmrv/django_making_two_database_connection_requests/">[comments]</a></span>

## need some help, has anyone got any ideas
 - [https://www.reddit.com/r/django/comments/1grj7gl/need_some_help_has_anyone_got_any_ideas](https://www.reddit.com/r/django/comments/1grj7gl/need_some_help_has_anyone_got_any_ideas)
 - RSS feed: $source
 - date published: 2024-11-15T00:03:38+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/bb9r8frxhy0e1.png?width=1807&amp;format=png&amp;auto=webp&amp;s=bb3ec44563e38791ba6f296a6071b2eb0ab80c86">https://preview.redd.it/bb9r8frxhy0e1.png?width=1807&amp;format=png&amp;auto=webp&amp;s=bb3ec44563e38791ba6f296a6071b2eb0ab80c86</a></p> <p>I am trying to deploy a small projhect that i am working on, this is my nginx logs:</p> <p>2024/11/14 23:37:12 [crit] 1144#1144: *15 connect() to unix:/run/gunicorn.sock failed (13: Permission denied) while connecting to upstream, client: 86.16.226.246, server: jwitcher.robbiefallcycles.cc, request: &quot;GET / HTTP/1.1&quot;, upstream: &quot;http://unix:/run/gunicorn.sock:/&quot;, host: &quot;157.245.44.47&quot;</p> <p>2024/11/14 23:37:12 [crit] 1144#1144: *15 connect() to unix:/run/gunicorn.sock failed (13: Permission denied) while connecting to upstream, client: 86.16.226.246, server: jwitcher.robbiefallcycles.cc, request: &quot;GET / HTTP/1.1&quot;, upstream: &quot;http://

