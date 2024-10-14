# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Passing disabled property to options
 - [https://www.reddit.com/r/django/comments/1g32dkj/passing_disabled_property_to_options](https://www.reddit.com/r/django/comments/1g32dkj/passing_disabled_property_to_options)
 - RSS feed: $source
 - date published: 2024-10-13T23:09:46+00:00

<!-- SC_OFF --><div class="md"><p>I am running into an issue where I can&#39;t disable an option.</p> <p><a href="https://preview.redd.it/x95fv6yrulud1.png?width=1515&amp;format=png&amp;auto=webp&amp;s=fa32393e783b12d6bfab0ccd4ec9e8aa30c1a152">https://preview.redd.it/x95fv6yrulud1.png?width=1515&amp;format=png&amp;auto=webp&amp;s=fa32393e783b12d6bfab0ccd4ec9e8aa30c1a152</a></p> <p>Basically, I have it set up where some service requires a field for Frequency. </p> <p>Using models, I Create Fields for each service. For select we have options as a json. However, when I try to pass disabled - it doesn&#39;t pass. Nor does that data. Labels and Values no trouble. </p> <p><code>{% if field.field_type == &#39;select&#39; %}</code></p> <p><code>&lt;select name=&quot;{{ field.name }}&quot;&gt;</code></p> <p><code>{% for option in field.options %}</code></p> <p><code>&lt;option value=&quot;{{ option.value }}&quot;</code></p> <p><code>data-custom=&quot;{{ option.data }}&quot;</code></p> <p><code

## Django website throwing 400 after updating static location for S3
 - [https://www.reddit.com/r/django/comments/1g2wmc4/django_website_throwing_400_after_updating_static](https://www.reddit.com/r/django/comments/1g2wmc4/django_website_throwing_400_after_updating_static)
 - RSS feed: $source
 - date published: 2024-10-13T18:43:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi All,</p> <p>I&#39;ve recently dusted of an old django website i was building once, since it was using outdated/older packages i decided to upgrade everything(also because i didn&#39;t previously pin my dependencies correctly).</p> <p>Now everything is working except there is 1 thing i really can&#39;t wrap my head around, since i use S3 to serve static files and media i am using the <code>S3Boto3Storage</code> class with the following configuraton.</p> <p><code> STORAGES = { &quot;default&quot;: { &quot;BACKEND&quot;: &#39;storages.backends.s3boto3.S3Boto3Storage&#39;, &quot;OPTIONS&quot;: { &quot;location&quot;: &quot;media&quot;, &quot;default_acl&quot;: &quot;public-read&quot; } }, &quot;staticfiles&quot;: { &quot;BACKEND&quot;: &#39;storages.backends.s3boto3.S3Boto3Storage&#39;, &quot;OPTIONS&quot;: { &quot;location&quot;: &quot;&quot;, &quot;default_acl&quot;: &quot;public-read&quot; } }, } </code></p> <p>But as soon as i changes the location 

## Is Custom backend needed for custome user model?
 - [https://www.reddit.com/r/django/comments/1g2uy4y/is_custom_backend_needed_for_custome_user_model](https://www.reddit.com/r/django/comments/1g2uy4y/is_custom_backend_needed_for_custome_user_model)
 - RSS feed: $source
 - date published: 2024-10-13T17:29:46+00:00

<!-- SC_OFF --><div class="md"><p>If I want to build a custom user model for my project so that the user will be authenticated using his email &amp; password instead of the Username &amp; password implemented by the default Django auth, do I need to implement a custom backend in this case or the Django default ModelBackend is sufficient? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/coolhead101"> /u/coolhead101 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g2uy4y/is_custom_backend_needed_for_custome_user_model/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g2uy4y/is_custom_backend_needed_for_custome_user_model/">[comments]</a></span>

## I built a cloud based focus timer using Django + redis that works even when your browser is napping. Here's how
 - [https://www.reddit.com/r/django/comments/1g2uw16/i_built_a_cloud_based_focus_timer_using_django](https://www.reddit.com/r/django/comments/1g2uw16/i_built_a_cloud_based_focus_timer_using_django)
 - RSS feed: $source
 - date published: 2024-10-13T17:27:15+00:00

<!-- SC_OFF --><div class="md"><p>Ever tried to use a web-based timer only to find it&#39;s gone off-track or crashes because you switched tabs? Yeah, me too. So I decided to fix that.</p> <p>I just finished building Tymr, a cloud-based focus timer that keeps ticking accurately no matter what. Here&#39;s the cool stuff:</p> <ol> <li>It uses Web Workers to keep time even when your browser tab is asleep</li> <li>Redis acts as a time lord, orchestrating everything</li> <li>It handles multiple users in real-time with WebSockets</li> <li>Deals with those pesky race conditions (goodbye, weird timer states!)</li> <li>multiple user can focus using a shared timer together since the timer runs in server and not in browser. </li> </ol> <p>I wrote up a detailed case study breaking down how it all works. If you&#39;re into Django, Redis, or just curious about robust web app architecture, you might find it interesting.</p> <p>Check it out here: <a href="https://selftaughtdev.hashnode.dev/case-study

## django - integrating app that uses workbox and service worker
 - [https://www.reddit.com/r/django/comments/1g2u6p3/django_integrating_app_that_uses_workbox_and](https://www.reddit.com/r/django/comments/1g2u6p3/django_integrating_app_that_uses_workbox_and)
 - RSS feed: $source
 - date published: 2024-10-13T16:56:13+00:00

<!-- SC_OFF --><div class="md"><p>I have my django app up and running, but I want to integrate a widget onto one of my routes. This widget looks to be designed as a pwa with a workbox and service worker implementation. I would like to use this widget and I have kept the widget files in the static folder (the workbox and service worker files are placed directly in the static folder while the other files for the widget are in subdirectories under static) and use the following script on the template page of my app where I want to display the widget:</p> <pre><code>&lt;script&gt; if (&#39;serviceWorker&#39; in navigator) { console.log(&quot;Will the service worker register?&quot;); navigator.serviceWorker.register(&quot;{% &#39;sw.js&#39; %}&quot;) .then(function(reg){ console.log(&quot;Yes, it did.&quot;); }).catch(function(err) { console.log(&quot;No it didn&#39;t. This happened:&quot;, err) console.log(&quot;err.message:&quot;, err.message) }); } &lt;/script&gt; </code></pre> <p>Then I

## Comprehensive Django Deployment Guide for Beginners
 - [https://www.reddit.com/r/django/comments/1g2thsv/comprehensive_django_deployment_guide_for](https://www.reddit.com/r/django/comments/1g2thsv/comprehensive_django_deployment_guide_for)
 - RSS feed: $source
 - date published: 2024-10-13T16:26:08+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Secure-Composer-9458"> /u/Secure-Composer-9458 </a> <br/> <span><a href="https://selftaughtdev.hashnode.dev/comprehensive-django-deployment-guide-for-beginners">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g2thsv/comprehensive_django_deployment_guide_for/">[comments]</a></span>

## DO App Platform root domain
 - [https://www.reddit.com/r/django/comments/1g2qywa/do_app_platform_root_domain](https://www.reddit.com/r/django/comments/1g2qywa/do_app_platform_root_domain)
 - RSS feed: $source
 - date published: 2024-10-13T14:32:47+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone been able to get a root domain working with their django app on digitalocean app platform? They don&#39;t give you an ip, so it&#39;s not accepting an A record to the app address it provides. I can only get the domain working with a CNAME and subdomain like <a href="http://www.mydomain.com">www.mydomain.com</a> but I need <a href="http://mydomain.com">mydomain.com</a> to work as well. I have tried all of this and still cant figure it out - the wildcard *.mydomain.com with TXT record throws a 400 Bad Request: <a href="https://docs.digitalocean.com/products/app-platform/how-to/manage-domains/#add-a-custom-domain-using-the-control-panel">https://docs.digitalocean.com/products/app-platform/how-to/manage-domains/#add-a-custom-domain-using-the-control-panel</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AttractiveCorpse"> /u/AttractiveCorpse </a> <br/> <span><a href="https://www.reddit.com/r/django/comm

## Facing problem in Django allauth google authentication
 - [https://www.reddit.com/r/django/comments/1g2qeqe/facing_problem_in_django_allauth_google](https://www.reddit.com/r/django/comments/1g2qeqe/facing_problem_in_django_allauth_google)
 - RSS feed: $source
 - date published: 2024-10-13T14:06:53+00:00

<!-- SC_OFF --><div class="md"><p>I am integrating google authentication in my website using django allauth. After doing all the setup, when I click on the google account to sign up then I got this error</p> <p><a href="https://preview.redd.it/q39npfgx5jud1.png?width=1885&amp;format=png&amp;auto=webp&amp;s=36bca51b53627ee5c68207bcc20cc8bd5aaa6fd5">https://preview.redd.it/q39npfgx5jud1.png?width=1885&amp;format=png&amp;auto=webp&amp;s=36bca51b53627ee5c68207bcc20cc8bd5aaa6fd5</a></p> <p>Also, I am following some yt videos, there they didn&#39;t install the &quot;jwt&quot; module but when I am doing it, it asks me to install jwt. So I installed it and now I got this error.</p> <p>If anyone in the community face this error and knows how to solve it, kindly tell</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/captainrdx"> /u/captainrdx </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g2qeqe/facing_problem_in_django_allauth_google/">

## Learning django worth it at 2024?
 - [https://www.reddit.com/r/django/comments/1g2pxsm/learning_django_worth_it_at_2024](https://www.reddit.com/r/django/comments/1g2pxsm/learning_django_worth_it_at_2024)
 - RSS feed: $source
 - date published: 2024-10-13T13:43:35+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to do apply machine learning in my projects. So will be it a good choice to learn django now? Maximum people telling that it is dead. They are preferring node js.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Confident-Flow-8787"> /u/Confident-Flow-8787 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g2pxsm/learning_django_worth_it_at_2024/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g2pxsm/learning_django_worth_it_at_2024/">[comments]</a></span>

## Setup instagram login with instagram API
 - [https://www.reddit.com/r/django/comments/1g2p1j6/setup_instagram_login_with_instagram_api](https://www.reddit.com/r/django/comments/1g2p1j6/setup_instagram_login_with_instagram_api)
 - RSS feed: $source
 - date published: 2024-10-13T12:56:10+00:00

<!-- SC_OFF --><div class="md"><p>I’m having trouble setting this up with my django all auth, I’ve already setup up Facebook and Google, I’m just having trouble with Instagram can anyone help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dramatic-Bit6552"> /u/Dramatic-Bit6552 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g2p1j6/setup_instagram_login_with_instagram_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g2p1j6/setup_instagram_login_with_instagram_api/">[comments]</a></span>

## translating your app?
 - [https://www.reddit.com/r/django/comments/1g2orzy/translating_your_app](https://www.reddit.com/r/django/comments/1g2orzy/translating_your_app)
 - RSS feed: $source
 - date published: 2024-10-13T12:41:45+00:00

<!-- SC_OFF --><div class="md"><p>hi everyone, i have a django project that is supposed to support two languages, how do you translate your app? Currently I am trying i18n but its such a pain, keep in mind i am native in both languages. So do i need to use it or theres a different way? Thanks. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adelulusometimes"> /u/adelulusometimes </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g2orzy/translating_your_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g2orzy/translating_your_app/">[comments]</a></span>

## Dear Djangonauts of UK
 - [https://www.reddit.com/r/django/comments/1g2ojqo/dear_djangonauts_of_uk](https://www.reddit.com/r/django/comments/1g2ojqo/dear_djangonauts_of_uk)
 - RSS feed: $source
 - date published: 2024-10-13T12:28:47+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I’m currently in the UK with a valid visa until 2026, and I’m looking for new opportunities in Django development. </p> <p>If anyone knows of companies in the UK that specialize in Django, I’d be grateful if you could share their names or any relevant leads so I can start my job search.</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Revolutionary_Pin299"> /u/Revolutionary_Pin299 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g2ojqo/dear_djangonauts_of_uk/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g2ojqo/dear_djangonauts_of_uk/">[comments]</a></span>

## wow redis cache is a game changer..
 - [https://www.reddit.com/r/django/comments/1g2m3nn/wow_redis_cache_is_a_game_changer](https://www.reddit.com/r/django/comments/1g2m3nn/wow_redis_cache_is_a_game_changer)
 - RSS feed: $source
 - date published: 2024-10-13T09:44:22+00:00

<!-- SC_OFF --><div class="md"><p>I made my ecommerce with django + RDS PostgresQL.. </p> <p>It was quite fast, it took about 120~150ms for fetching data.. </p> <p>However, I took 3s for the first page load. it felt a bit slow when I search my page on google or Instagram..</p> <p>I set redis for caching.. and now 20ms for data fetching and when I go on my site, the page shows immidiately.. less than a sec, it is super fast.. what a game changer..</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g2m3nn/wow_redis_cache_is_a_game_changer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g2m3nn/wow_redis_cache_is_a_game_changer/">[comments]</a></span>

