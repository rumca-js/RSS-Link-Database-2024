# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## (PAID Product) Dynamic Django - API, DataTables, Charts, without coding, only a minimum cfg | DOCS Link
 - [https://www.reddit.com/r/django/comments/1fwxt5y/paid_product_dynamic_django_api_datatables_charts](https://www.reddit.com/r/django/comments/1fwxt5y/paid_product_dynamic_django_api_datatables_charts)
 - RSS feed: $source
 - date published: 2024-10-05T19:08:56+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys,</p> <p>I&#39;ve finished a small R&amp;D sprint and all the work is bundled in Dynamic Django Starter (not cheap, commercial project). I will share the link to the official documentation below.</p> <p><a href="https://app-generator.dev/docs/developer-tools/dynamic-django/index.html">https://app-generator.dev/docs/developer-tools/dynamic-django/index.html</a></p> <p>The product allows the build APIs on top of DRF, Fully-fledged Server-Side DataTables, and Charts without coding.</p> <p>The goal is to provide an actively supported boilerplate with a useful design pattern flavor.</p> <p>Thanks in advance for your feedback!</p> <p><a href="https://preview.redd.it/uspj6usvkzsd1.png?width=800&amp;format=png&amp;auto=webp&amp;s=007b26fd19b4c58577d41768ff0111db13f74c3c">https://preview.redd.it/uspj6usvkzsd1.png?width=800&amp;format=png&amp;auto=webp&amp;s=007b26fd19b4c58577d41768ff0111db13f74c3c</a></p> <p><a href="https://preview.redd.it/knkevcmyk

## React with Templated JSX or server side rendering
 - [https://www.reddit.com/r/django/comments/1fwu9zw/react_with_templated_jsx_or_server_side_rendering](https://www.reddit.com/r/django/comments/1fwu9zw/react_with_templated_jsx_or_server_side_rendering)
 - RSS feed: $source
 - date published: 2024-10-05T16:29:06+00:00

<!-- SC_OFF --><div class="md"><p>There are endless posts on this subreddit about react, typical answer is to use rest-framework for implementing the API. But, implementing everything as API is overkill, and templating has its uses too.</p> <p>Is it possible to do templated react with Django? With some kind of bundler like we pack? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/supercharger6"> /u/supercharger6 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fwu9zw/react_with_templated_jsx_or_server_side_rendering/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fwu9zw/react_with_templated_jsx_or_server_side_rendering/">[comments]</a></span>

## Server Side rendered Datatables with Django
 - [https://www.reddit.com/r/django/comments/1fwqlwk/server_side_rendered_datatables_with_django](https://www.reddit.com/r/django/comments/1fwqlwk/server_side_rendered_datatables_with_django)
 - RSS feed: $source
 - date published: 2024-10-05T13:38:08+00:00

<!-- SC_OFF --><div class="md"><p>Just wrapped up a project where I had to handle a massive table with DataTables and Django. Thought I&#39;d share my experience and maybe save someone else a headache.</p> <p>The challenge: Display thousands of records with dynamic columns, sorting, and filtering - all server-side. Oh, and it needed to be blazing fast.</p> <p>Here&#39;s what worked for me:</p> <ol> <li>Custom Django view to process DataTables requests</li> <li>Dynamic column generation based on user permissions</li> <li>Efficient database queries with select_related()</li> <li>Complex sorting and filtering logic handled server-side</li> <li>Pagination to keep things snappy</li> </ol> <p>The trickiest part was definitely the dynamic ordering. I ended up writing a function to translate DataTables&#39; sorting parameters into Django ORM-friendly format. It was a pain to debug, but works like a charm now.</p> <p>Performance-wise, it&#39;s holding up well. Tables load quickly, and sorting/

## celery container continuous restarts due to PRECONDITION_FAILED
 - [https://www.reddit.com/r/django/comments/1fwofcf/celery_container_continuous_restarts_due_to](https://www.reddit.com/r/django/comments/1fwofcf/celery_container_continuous_restarts_due_to)
 - RSS feed: $source
 - date published: 2024-10-05T11:39:23+00:00

<!-- SC_OFF --><div class="md"><p>celery container keeps shutting down every hour (the consumer_timeout I set in rabbitmq) with the following error:</p> <pre><code>amqp.exceptions.PreconditionFailed: (0, 0): (406) PRECONDITION_FAILED - delivery acknowledgement on channel 1 timed out. Timeout value used: 3600000 ms. This timeout value can be configured, see consumers doc guide to learn more </code></pre> <p>When listing unacknowledged messages in rabbitmq, I find the following:</p> <pre><code>/$ rabbitmqctl list_queues name messages messages_ready messages_unacknowledged consumers critical 5 0 5 2 </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Critical-Animal8321"> /u/Critical-Animal8321 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fwofcf/celery_container_continuous_restarts_due_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fwofcf/celery_container_continuous_restarts_due_to/

## Django + Postgres: The Hunt for Long Running Queries: Using django-pgactivity for application-level monitoring of database queries.
 - [https://www.reddit.com/r/django/comments/1fwnzwz/django_postgres_the_hunt_for_long_running_queries](https://www.reddit.com/r/django/comments/1fwnzwz/django_postgres_the_hunt_for_long_running_queries)
 - RSS feed: $source
 - date published: 2024-10-05T11:10:57+00:00

<!-- SC_OFF --><div class="md"><p>A short article I wrote detailing how a Django application developer can easily monitor and kill long running PostgreSQL queries in their Django application: <a href="https://pgilmartin.substack.com/p/django-postgres-the-hunt-for-long">https://pgilmartin.substack.com/p/django-postgres-the-hunt-for-long</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/paulg1989"> /u/paulg1989 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fwnzwz/django_postgres_the_hunt_for_long_running_queries/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fwnzwz/django_postgres_the_hunt_for_long_running_queries/">[comments]</a></span>

## I cant feel some big differences from redis cache
 - [https://www.reddit.com/r/django/comments/1fwm6rm/i_cant_feel_some_big_differences_from_redis_cache](https://www.reddit.com/r/django/comments/1fwm6rm/i_cant_feel_some_big_differences_from_redis_cache)
 - RSS feed: $source
 - date published: 2024-10-05T08:58:46+00:00

<!-- SC_OFF --><div class="md"><p>I have set elasticache(redis) for my django app..</p> <p>main page has</p> <p>22 products 5 banners 9 sub banners1 5 sub banners2 business info</p> <p>It took 100ms before caching, Now it takes 20ms</p> <p>but I dont feel much differences It feels a bit lighter but a lil..</p> <p>and I thougt it would take less than 10ms..</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fwm6rm/i_cant_feel_some_big_differences_from_redis_cache/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fwm6rm/i_cant_feel_some_big_differences_from_redis_cache/">[comments]</a></span>

## iommi vs inheritance explosion
 - [https://www.reddit.com/r/django/comments/1fwlpr7/iommi_vs_inheritance_explosion](https://www.reddit.com/r/django/comments/1fwlpr7/iommi_vs_inheritance_explosion)
 - RSS feed: $source
 - date published: 2024-10-05T08:23:01+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://kodare.net/2024/09/30/iommi-vs-inheritance-explosion.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fwlpr7/iommi_vs_inheritance_explosion/">[comments]</a></span>

## Any better way between Javascript and Django to communicate with each other?
 - [https://www.reddit.com/r/django/comments/1fwkld2/any_better_way_between_javascript_and_django_to](https://www.reddit.com/r/django/comments/1fwkld2/any_better_way_between_javascript_and_django_to)
 - RSS feed: $source
 - date published: 2024-10-05T06:59:51+00:00

<!-- SC_OFF --><div class="md"><p>I am designing a front-end for an API of mine. As of now the only way for the Javascript and Django to communicate is from cookies.</p> <p>For example, If a sign in attempt is made with incorrect credentials, the server receives the sign in form, makes a POST request to the API, the API returns an error message that the credentials are incorrect, the Django server makes a temporary cookie named &quot;errorMessage&quot; and redirects the user to the Sign In page again. The cookie then is read and deleted by the Javascript to initiate an alert() function with the error message to let the user know that the credentials were wrong.</p> <p>Is there any better, simple or efficient way?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Abled_Gaming1357"> /u/Abled_Gaming1357 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fwkld2/any_better_way_between_javascript_and_django_to/">[link]</a></span> &#32; <

## Function in views.py only runs once
 - [https://www.reddit.com/r/django/comments/1fwk2df/function_in_viewspy_only_runs_once](https://www.reddit.com/r/django/comments/1fwk2df/function_in_viewspy_only_runs_once)
 - RSS feed: $source
 - date published: 2024-10-05T06:21:04+00:00

<!-- SC_OFF --><div class="md"><p>Not sure what to put on Flair, guide me, I&#39;ll change it.</p> <p>Hello, I have a logout function,</p> <pre><code>def logout(request): print(&quot;Logout Function Ran&quot;) if request.method != &quot;GET&quot;: return(JsonResponse({&quot;errorCode&quot;:1, &quot;errorMessage&quot;:&quot;Method not Allowed.&quot;})) else: url = f&#39;{base_url}/session-delete/&#39; data = { &quot;email&quot;:request.COOKIES.get(&quot;email&quot;), &quot;sessionId&quot;:request.COOKIES.get(&quot;sessionId&quot;), &quot;sessionIdW&quot;:request.COOKIES.get(&quot;sessionId&quot;) } success, dict_response = sendRequestPost(url, data) if success: response = redirect(&quot;signin&quot;, permanent=True) response.delete_cookie(&quot;email&quot;) response.delete_cookie(&quot;sessionId&quot;) return response elif success == None: response = redirect(&quot;vault&quot;, permanent=True) response.set_cookie(&quot;errorMessage&quot;, &quot;Connection Error&quot;) return response e

## Multi tenant framework with row level security
 - [https://www.reddit.com/r/django/comments/1fwez1p/multi_tenant_framework_with_row_level_security](https://www.reddit.com/r/django/comments/1fwez1p/multi_tenant_framework_with_row_level_security)
 - RSS feed: $source
 - date published: 2024-10-05T01:13:33+00:00

<!-- SC_OFF --><div class="md"><p>Popular multi tenant frameworks seems to do with seperated databases or schemas. There are recent Postgres advances in row level security, so just want to use tenant_id at row level.</p> <p>Are there any frameworks that implements multi tenant at the row level? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/supercharger6"> /u/supercharger6 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fwez1p/multi_tenant_framework_with_row_level_security/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fwez1p/multi_tenant_framework_with_row_level_security/">[comments]</a></span>

