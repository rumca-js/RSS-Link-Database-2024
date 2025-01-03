# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Comparing AWS S3 and Cloudflare R2
 - [https://www.reddit.com/r/django/comments/1h19f6b/comparing_aws_s3_and_cloudflare_r2](https://www.reddit.com/r/django/comments/1h19f6b/comparing_aws_s3_and_cloudflare_r2)
 - RSS feed: $source
 - date published: 2024-11-27T17:14:56+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/gbeier"> /u/gbeier </a> <br/> <span><a href="https://kerkour.com/aws-s3-vs-cloudflare-r2-price-performance-user-experience">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h19f6b/comparing_aws_s3_and_cloudflare_r2/">[comments]</a></span>

## Django Protego - A Flexible and Dynamic Circuit Breaker
 - [https://www.reddit.com/r/django/comments/1h18ua0/django_protego_a_flexible_and_dynamic_circuit](https://www.reddit.com/r/django/comments/1h18ua0/django_protego_a_flexible_and_dynamic_circuit)
 - RSS feed: $source
 - date published: 2024-11-27T16:51:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks,</p> <p>I&#39;m excited to share a project I&#39;ve been working on: Django Protego, a dynamic and configurable Circuit Breaker for Django applications. </p> <p><strong>What is Django Protego?</strong> </p> <p>Django Protego is a library that helps to protect your services from cascading failures by providing a Circuit Breaker mechanism. It&#39;s simple to integrate, dynamic, and works seamlessly with Django-based applications. </p> <p><strong>Key Features:</strong> </p> <ul> <li>Dynamic Configuration: Configure failure thresholds, reset timeouts, and half-open retries at runtime.</li> <li>Global Registry: The circuit breaker state is shared across views via a global registry, ensuring centralized control of your application’s fault tolerance.<br/></li> <li>Easy to Use: Just decorate your views with @/protego.protect to wrap your views in the circuit breaker logic. </li> <li>Flexible: Supports multiple circuit breakers in the same project, a

## Comparing AWS S3 with Cloudflare R2: Price, Performance and User Experience
 - [https://www.reddit.com/r/django/comments/1h188tg/comparing_aws_s3_with_cloudflare_r2_price](https://www.reddit.com/r/django/comments/1h188tg/comparing_aws_s3_with_cloudflare_r2_price)
 - RSS feed: $source
 - date published: 2024-11-27T16:26:11+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/The_Naveen"> /u/The_Naveen </a> <br/> <span><a href="https://kerkour.com/aws-s3-vs-cloudflare-r2-price-performance-user-experience">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h188tg/comparing_aws_s3_with_cloudflare_r2_price/">[comments]</a></span>

## Handling pool connections with multiple CRUD threaded tasks
 - [https://www.reddit.com/r/django/comments/1h16jpg/handling_pool_connections_with_multiple_crud](https://www.reddit.com/r/django/comments/1h16jpg/handling_pool_connections_with_multiple_crud)
 - RSS feed: $source
 - date published: 2024-11-27T15:13:11+00:00

<!-- SC_OFF --><div class="md"><p>hey!</p> <p>i have a django setup with a postgres database that uses psycopg and connection pooling, here is the config:</p> <pre><code> DATABASES = { &#39;default&#39;: { &#39;ENGINE&#39;: &#39;django.db.backends.postgresql&#39;, &#39;NAME&#39;: DATABASE_URL.path.replace(&#39;/&#39;, &#39;&#39;), &#39;USER&#39;: DATABASE_URL.username, &#39;PASSWORD&#39;: DATABASE_URL.password, &#39;HOST&#39;: DATABASE_URL.hostname, &#39;PORT&#39;: DATABASE_URL.port, &#39;OPTIONS&#39;: { &#39;sslmode&#39;: &#39;require&#39;, &#39;pool&#39;: { &#39;timeout&#39;: 120, &#39;min_size&#39;: 4 &#39;max_size&#39;: 4, }, }, } } </code></pre> <p>i also have few lightweight tasks, which i execute on a separate thread so it doesnt block the main one. but when i execute a number of tasks above the pool max_size, i get a psycopg_pool.PoolTimeout error.</p> <p>i wrote a simple example so i can force the error easily:</p> <pre><code>def task(): user = User.objects.get(email=&#39;ad

## Is there a way to display a pretty JSON in admin when the field is TextField and not JsonField?
 - [https://www.reddit.com/r/django/comments/1h13fzz/is_there_a_way_to_display_a_pretty_json_in_admin](https://www.reddit.com/r/django/comments/1h13fzz/is_there_a_way_to_display_a_pretty_json_in_admin)
 - RSS feed: $source
 - date published: 2024-11-27T12:44:53+00:00

<!-- SC_OFF --><div class="md"><p>Encoder=djangojsonencoder doesnt work in the text field.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sauwa"> /u/Sauwa </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h13fzz/is_there_a_way_to_display_a_pretty_json_in_admin/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h13fzz/is_there_a_way_to_display_a_pretty_json_in_admin/">[comments]</a></span>

## How to Improve db process?
 - [https://www.reddit.com/r/django/comments/1h13bfv/how_to_improve_db_process](https://www.reddit.com/r/django/comments/1h13bfv/how_to_improve_db_process)
 - RSS feed: $source
 - date published: 2024-11-27T12:37:47+00:00

<!-- SC_OFF --><div class="md"><p>I currently have my Django connected to azure sql serverless db with pyodbc connection. </p> <p>I have noticed that trying to save small text in comment is taking a long time compared to querying and viewing objects.</p> <p>And the db costs too are expensive compared to what I am using. </p> <p>Does the app initiate authentication every time I make a request? Should I cache the connection? </p> <p>What might be the reasons and solutions for this? </p> <p>Thank you in advance. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PrestigiousFun450"> /u/PrestigiousFun450 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h13bfv/how_to_improve_db_process/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h13bfv/how_to_improve_db_process/">[comments]</a></span>

## Django Rest Framework Pagination tip
 - [https://www.reddit.com/r/django/comments/1h131yq/django_rest_framework_pagination_tip](https://www.reddit.com/r/django/comments/1h131yq/django_rest_framework_pagination_tip)
 - RSS feed: $source
 - date published: 2024-11-27T12:22:45+00:00

<!-- SC_OFF --><div class="md"><p>REST framework includes support for customizable pagination styles. This allows you to modify how large result sets are split into individual data pages.</p> <p>page_size - A numeric value indicating the page size. If set, this overrides the PAGE_SIZE setting. Defaults to the same value as the PAGE_SIZE settings key.</p> <p>page_query_param - A string value indicating the name of the query parameter to use for the pagination control.</p> <p>page_size_query_param - If set, this is a string value indicating the name of a query parameter that allows the client to set the page size on a per-request basis. Defaults to None, indicating that the client may not control the requested page size.</p> <p>max_page_size - If set, this is a numeric value indicating the maximum allowable requested page size. This attribute is only valid if page_size_query_param is also set.</p> <p>last_page_strings - A list or tuple of string values indicating values that may be use

## is 2depth nested model still good for production..?
 - [https://www.reddit.com/r/django/comments/1h10yki/is_2depth_nested_model_still_good_for_production](https://www.reddit.com/r/django/comments/1h10yki/is_2depth_nested_model_still_good_for_production)
 - RSS feed: $source
 - date published: 2024-11-27T10:02:14+00:00

<!-- SC_OFF --><div class="md"><p>hi, I am building an ecommerce and my model structures are like </p> <p>Product - &lt; OptionName -&lt; OptionValue</p> <p>2depth nested model, and I feel it is really difficult to handle create, update in drf serializer.. is 2depth a normal approach? or should I limit to 1depth? </p> <p>also, any advice or ways to handle nested models for creations and updating? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h10yki/is_2depth_nested_model_still_good_for_production/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h10yki/is_2depth_nested_model_still_good_for_production/">[comments]</a></span>

## Form fields are not showing in my template
 - [https://www.reddit.com/r/django/comments/1h0zs43/form_fields_are_not_showing_in_my_template](https://www.reddit.com/r/django/comments/1h0zs43/form_fields_are_not_showing_in_my_template)
 - RSS feed: $source
 - date published: 2024-11-27T08:32:20+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://forum.djangoproject.com/t/form-fields-not-appearing-in-html/36774">Post which contains all the problem description in Django Forum</a></p> <p>Thanks a lot.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HeroDev95"> /u/HeroDev95 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1h0zs43/form_fields_are_not_showing_in_my_template/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h0zs43/form_fields_are_not_showing_in_my_template/">[comments]</a></span>

## Django 6.x Steering Council Candidate Registration
 - [https://www.reddit.com/r/django/comments/1h0ylzc/django_6x_steering_council_candidate_registration](https://www.reddit.com/r/django/comments/1h0ylzc/django_6x_steering_council_candidate_registration)
 - RSS feed: $source
 - date published: 2024-11-27T07:07:19+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2024/nov/27/django-6x-steering-council-candidate-registration/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1h0ylzc/django_6x_steering_council_candidate_registration/">[comments]</a></span>

## Localization in Django Rest Framework
 - [https://www.reddit.com/r/django/comments/1h0xm0r/localization_in_django_rest_framework](https://www.reddit.com/r/django/comments/1h0xm0r/localization_in_django_rest_framework)
 - RSS feed: $source
 - date published: 2024-11-27T06:01:49+00:00

<!-- SC_OFF --><div class="md"><p>I have a Django Rest Framework project that is handling REST apis and React + TS application for client side.</p> <p>Now I need to add Localization to my application for multi language support and it needs to be done on server side, so that the strings can be changed from the admin panel easily. I have used i18n on client side in React before but we want to do it on server side.</p> <p>What&#39;s the best way to handle this? I am going through the documentation: <a href="https://docs.djangoproject.com/en/5.1/topics/i18n/translation/">https://docs.djangoproject.com/en/5.1/topics/i18n/translation/</a> &amp; <a href="https://www.django-rest-framework.org/topics/internationalization/">https://www.django-rest-framework.org/topics/internationalization/</a> but can&#39;t wrap my head around it how will be handled on the client side in React? Everything need to be translated from Header to Footer and everything in between.</p> <p>Thanks!</p> </div><!-- SC_ON

