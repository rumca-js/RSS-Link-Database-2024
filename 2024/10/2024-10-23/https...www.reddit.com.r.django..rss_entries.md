# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## I need help with Django REST JSON parse error
 - [https://www.reddit.com/r/django/comments/1ga8jwx/i_need_help_with_django_rest_json_parse_error](https://www.reddit.com/r/django/comments/1ga8jwx/i_need_help_with_django_rest_json_parse_error)
 - RSS feed: $source
 - date published: 2024-10-23T11:48:19+00:00

<!-- SC_OFF --><div class="md"><p>I am very lost with this issue. </p> <p>The stack is React, Redux, Django REST framework, Gunicorn, Nginx all in Docker.</p> <p>I am sending a simple POST request from the frontend, all it contains is this data:</p> <pre><code>let data = {report_id: selectedReportId} </code></pre> <p>I verified that selectedReportId is not null or undefined. Viewing the request via browser tools, I can see the request and everything looks fine, including the JSON data. </p> <p>However, it returns a 400 Bad request.</p> <p>The urlpatterns in urls.py:</p> <pre><code>... path(&#39;reports/generate/&#39;, views.generate_report, name=&#39;generate_report&#39;), ... </code></pre> <p>The corresponding view:</p> <pre><code>@csrf_protect @api_view([&#39;POST&#39;]) @permission_classes([IsAuthenticated]) def generate_report(request): data = JSONParser().parse(request) report_id = data.get(&#39;report_id&#39;) if report_id is None: return JsonResponse({&#39;Error&#39;: &#39;Subm

## I want to hide the DRF API views in my production code.
 - [https://www.reddit.com/r/django/comments/1ga5ool/i_want_to_hide_the_drf_api_views_in_my_production](https://www.reddit.com/r/django/comments/1ga5ool/i_want_to_hide_the_drf_api_views_in_my_production)
 - RSS feed: $source
 - date published: 2024-10-23T08:37:35+00:00

<!-- SC_OFF --><div class="md"><p>I have built a full stack mobile-web application using Flutter and Svelte with Django as the backend. All of the mentioned codes have been pushed to production. All of them function on the Django rest framework APIs(GET,POST and DELETE methods). </p> <p>I have deployed the Django code using Heroku, on entering the production URL API endpoints, you can see that the API views can be accessed to anyone (refer below)</p> <p><a href="https://preview.redd.it/tpjia8dmwgwd1.png?width=1233&amp;format=png&amp;auto=webp&amp;s=7866a8e5957e3704b606a7fab4df01ca19c29064">https://preview.redd.it/tpjia8dmwgwd1.png?width=1233&amp;format=png&amp;auto=webp&amp;s=7866a8e5957e3704b606a7fab4df01ca19c29064</a></p> <p>I want to know how can I hide this page from others accessing it? Or how can I prevent this data being available online? Please help with this.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/younglegendo"> /u/younglegendo 

## Django web app hosted locally
 - [https://www.reddit.com/r/django/comments/1ga4b54/django_web_app_hosted_locally](https://www.reddit.com/r/django/comments/1ga4b54/django_web_app_hosted_locally)
 - RSS feed: $source
 - date published: 2024-10-23T06:58:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I am currently exploring Django because it has good security and my seniors suggested it. Currently they want me to use Django and have a super user and regular user. The super user can do CRUD (create, read. update and delete) data on the cloud/local data base. The regular user has a calendar dash board that has a search function and can search specific dates: Example: January 1, 2024 - it will then list down all the information of data from that specific date only. </p> <p>My seniors are also pushing Mongo DB, both used for local for User:(Signup/Login) for local and another Mongo DB in cloud that is hosted either via AWS or Google providers of MongoDB.</p> <p>Is this doable? and how will you tackle this if you are in my place? Thank you for suggestions/helps.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Frosting_1511"> /u/No_Frosting_1511 </a> <br/> <span><a href="https://www.reddit.com/r/django/c

