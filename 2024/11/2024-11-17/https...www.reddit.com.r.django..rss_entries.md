# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django's official tutorial is not for beginners
 - [https://www.reddit.com/r/django/comments/1gtlitn/djangos_official_tutorial_is_not_for_beginners](https://www.reddit.com/r/django/comments/1gtlitn/djangos_official_tutorial_is_not_for_beginners)
 - RSS feed: $source
 - date published: 2024-11-17T19:31:28+00:00

<!-- SC_OFF --><div class="md"><p>It really isn&#39;t. If you&#39;re an absolute beginner and don&#39;t want to spend half your time learning django confused and annoyed and having to google every 5th word the official tutorial is not for you. There are better paid and free tutorials for absolute beginners online. The best I&#39;ve found is Will Vincent&#39;s &#39;Django for Beginners&#39;. Anything from django version 4+ should be good enough. His whole Django series is pretty good and better than every other resource I&#39;ve encountered. If you can&#39;t afford it and pirating is too icky for you then the best free tutorials I&#39;ve found are the Djangogirls and MDN tutorials. I first started learning django last year(around May/June I think) from the official tutorial over a week. Started working on an app and while working on it realize how much basic stuff I didn&#39;t understand because it simply was not explained in the tutorial. It just breezes over important information, c

## recommend the best way as a beginner to learn django
 - [https://www.reddit.com/r/django/comments/1gtl78g/recommend_the_best_way_as_a_beginner_to_learn](https://www.reddit.com/r/django/comments/1gtl78g/recommend_the_best_way_as_a_beginner_to_learn)
 - RSS feed: $source
 - date published: 2024-11-17T19:17:16+00:00

<!-- SC_OFF --><div class="md"><p>recommend the best method to learn django as a beginner.Any tutotrial ,books or path you can recommend </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Grand-Airline2939"> /u/Grand-Airline2939 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gtl78g/recommend_the_best_way_as_a_beginner_to_learn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gtl78g/recommend_the_best_way_as_a_beginner_to_learn/">[comments]</a></span>

## Implementing django tenants in django cookiecutter works in local but fails in production
 - [https://www.reddit.com/r/django/comments/1gtj6eb/implementing_django_tenants_in_django](https://www.reddit.com/r/django/comments/1gtj6eb/implementing_django_tenants_in_django)
 - RSS feed: $source
 - date published: 2024-11-17T17:49:19+00:00

<!-- SC_OFF --><div class="md"><p>Well, I have created a shared app where I have create tenant and domain models and a custom admin, whenever I try to login into my custom admin site this error comes django.urls.exceptions.NoReverseMatch: Reverse for &#39;home&#39; not found. &#39;home&#39; is not a valid view function or pattern name.</p> <pre><code>##setting.base.py TENANT_MODEL = &quot;tenant.Tenant&quot; TENANT_DOMAIN_MODEL = &quot;tenant.Domain&quot; ROOT_URLCONF = &quot;config.urls&quot; PUBLIC_SCHEMA_URLCONF = &quot;shared_app.urls&quot; SHOW_PUBLIC_IF_NO_TENANT_FOUND = True ###shared_app/urls.py from django.urls import path from tenant.views import index from tenant.admin import tenant_admin_site urlpatterns = [ path(&quot;admin/&quot;, tenant_admin_site.urls), path(&quot;&quot;, index, name=&quot;index&quot;), ] ####shared_app/admin.py from django.contrib import admin from django.contrib.auth.models import User from bme.tenant.models import Tenant, Domain, Feature class Feat

## Why is my django-cte manager a lot faster than a custom QuerySet?
 - [https://www.reddit.com/r/django/comments/1gt9q67/why_is_my_djangocte_manager_a_lot_faster_than_a](https://www.reddit.com/r/django/comments/1gt9q67/why_is_my_djangocte_manager_a_lot_faster_than_a)
 - RSS feed: $source
 - date published: 2024-11-17T09:09:24+00:00

<!-- SC_OFF --><div class="md"><p>I have this Car model that I want to sort by speed. I implemented two different ways to do these: one is by using a custom queryset and the other is using an external package using django-cte (see below). For some reason, the CTE implementation is alot faster even though the queries are the same (same limit, same offset, same filters, ...). And I&#39;m talking tens of magnitude better, since for 1 million records the custom queryset runs for approx 21s while the CTE one is running for 2s only. Why is this happening? Is it because the custom queryset is sorting it first then does the necessary filters?</p> <p>``` from django.db import models from django.utils.translation import gettext_lazy as _ from django_cte import CTEManager, With</p> <p>class CarCTEManager(CTEManager): def sort<em>speed(self): cte = With( Car.objects.annotate( rank=models.Window( expression=models.functions.Rank(), order_by=[models.F(&quot;speed&quot;).desc()] ) ) ) return cte.qu

## Django usage for static sites.
 - [https://www.reddit.com/r/django/comments/1gt9go8/django_usage_for_static_sites](https://www.reddit.com/r/django/comments/1gt9go8/django_usage_for_static_sites)
 - RSS feed: $source
 - date published: 2024-11-17T08:49:50+00:00

<!-- SC_OFF --><div class="md"><p>Hey, so I&#39;ve written this website which does a bunch of utility stuff as well as scraping for users, initially most of the functiality happened via the backend but as time went on i started moving stuff to the frontend / API endpoints that I made (much cheaper than beefing up the server) and I ended up in this odd situation where my website is virtually static besides template rendering. </p> <p>For example, moved image convertion to from backend (pillow) to frontend via wasm solution I wrote in rust. </p> <p>Moved the scraping from backend fetching and data extraction to a fastApi Endpoint which fetches the target page and then extracts the data in the frontend via web workers. </p> <p>So my reasoning to stick with django are. </p> <ol> <li><p>Ive gotten used to work with it, and it&#39;s especially easy when all I do is serve static pages. </p></li> <li><p>I&#39;m eventually planning to incorporate users and payments for premium services. </p><

## OOP but for an entire Django project
 - [https://www.reddit.com/r/django/comments/1gt7y6y/oop_but_for_an_entire_django_project](https://www.reddit.com/r/django/comments/1gt7y6y/oop_but_for_an_entire_django_project)
 - RSS feed: $source
 - date published: 2024-11-17T06:58:38+00:00

<!-- SC_OFF --><div class="md"><p>I am chewing over the best way of having child Django projects based on a parent Django project. </p> <p>Here&#39;s what I want to be able to do: 1. children could use a different base template and have some variation in terms of other templates. 2. Children will each have some variation in terms of settings, from the parent 3. There could be additional code-based features in the child projects. I like the idea of being able to merge useful code back into the parent so that all children can make use of it.</p> <p>Here are some ways I am considering to do this: 1a. Chaos megaproject: have ALL the children and parent within the same project and just runserver on the child specific settings file. 1b. As above but I do wonder if someone&#39;s come up with a clean way of doing this via a 3rd party package. Chatgpt advises django-tenants and django-tenant-schemas may be good here. 2. Git: have each child as a separate repo. This is probably the wisest way 

## Django survey
 - [https://www.reddit.com/r/django/comments/1gt61ax/django_survey](https://www.reddit.com/r/django/comments/1gt61ax/django_survey)
 - RSS feed: $source
 - date published: 2024-11-17T04:52:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m interested in building a tool related to django to help start projects faster<br/> I&#39;ve been using django for several years now and I think I can use those years to do something helpful :)</p> <p>I&#39;ve made a survey so if you have 5 minutes it would be nice to help me know about how you use django </p> <p>Here is the survey: <a href="https://tally.so/r/3EBPMr">https://tally.so/r/3EBPMr</a></p> <p>Thank you very much, I&#39;m also available in dm for any question!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LeBugArtisan"> /u/LeBugArtisan </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gt61ax/django_survey/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gt61ax/django_survey/">[comments]</a></span>

## How to Build No-Code Modal Components for Wagtail CMS Content Editors | A step by step guide
 - [https://www.reddit.com/r/django/comments/1gt24og/how_to_build_nocode_modal_components_for_wagtail](https://www.reddit.com/r/django/comments/1gt24og/how_to_build_nocode_modal_components_for_wagtail)
 - RSS feed: $source
 - date published: 2024-11-17T01:13:50+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/adonis_97"> /u/adonis_97 </a> <br/> <span><a href="https://blog.adonissimo.com/how-to-build-no-code-modal-components-for-wagtail-cms-content-editors">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gt24og/how_to_build_nocode_modal_components_for_wagtail/">[comments]</a></span>

