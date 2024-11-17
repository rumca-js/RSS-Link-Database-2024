# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## What is the industry standard for Django project structure?
 - [https://www.reddit.com/r/django/comments/1gsuhmj/what_is_the_industry_standard_for_django_project](https://www.reddit.com/r/django/comments/1gsuhmj/what_is_the_industry_standard_for_django_project)
 - RSS feed: $source
 - date published: 2024-11-16T19:08:59+00:00

<!-- SC_OFF --><div class="md"><p>tldr: I have seen many posts on what the &quot;best&quot; Django project structure is. What is standard in the industry and why?</p> <p>I&#39;m learning the Django framework and I&#39;m trying to investigate and understand the project folder structure and reasoning behind it. I&#39;m aware of clean architecture and vertical slice architecture, so my first instinct is to adapt to something like that. I came across <a href="https://www.jamesbeith.co.uk/blog/how-to-structure-django-projects/">https://www.jamesbeith.co.uk/blog/how-to-structure-django-projects/</a> , which seems in line with what I&#39;m looking for, though I&#39;m not sure how often it is used in practice.</p> <p>From Googling, it seems that a typical structure is the following, <a href="https://github.com/HackSoftware/Django-Styleguide-Example/">https://github.com/HackSoftware/Django-Styleguide-Example/</a> , where basically every module is a Django app (e.g. api, core, emails, users, e

## HELP-I'm facing issues regarding the optimising the queryset in django. I want to remove duplicate query but still facing issues inspite of using distint(), select and prefetch.
 - [https://www.reddit.com/r/django/comments/1gstyqs/helpim_facing_issues_regarding_the_optimising_the](https://www.reddit.com/r/django/comments/1gstyqs/helpim_facing_issues_regarding_the_optimising_the)
 - RSS feed: $source
 - date published: 2024-11-16T18:45:55+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Obvious-Wolverine823"> /u/Obvious-Wolverine823 </a> <br/> <span><a href="https://www.reddit.com/gallery/1gstyqs">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gstyqs/helpim_facing_issues_regarding_the_optimising_the/">[comments]</a></span>

## My site passes 45 security checks..
 - [https://www.reddit.com/r/django/comments/1gsq92b/my_site_passes_45_security_checks](https://www.reddit.com/r/django/comments/1gsq92b/my_site_passes_45_security_checks)
 - RSS feed: $source
 - date published: 2024-11-16T15:57:27+00:00

<!-- SC_OFF --><div class="md"><p>I made an ecommerce site with django, I am not that expert on security.. I try to follow what django provides for that, and I do drf’s is_valid method to incoming data..</p> <p>There are about 150 apis and 50 frontend pages. I asked the cyber security agency that the government operates.. </p> <p>They check about 45 cyber attacks include OWASP top10.. it took about 2weeks and I got the report.. I was very nervous because I spent 2years to build the site and if it had many vernerabilities.. I wouldnt know how to fix.. </p> <p>Wow.. no single vernerabilies found, thanks to django.. I cant believe that django is that solid and secure.. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsq92b/my_site_passes_45_security_checks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/commen

## emulating django pattern for setting class attributes
 - [https://www.reddit.com/r/django/comments/1gspefs/emulating_django_pattern_for_setting_class](https://www.reddit.com/r/django/comments/1gspefs/emulating_django_pattern_for_setting_class)
 - RSS feed: $source
 - date published: 2024-11-16T15:17:24+00:00

<!-- SC_OFF --><div class="md"><p>#I am learning python and django and would like to create a class that has a similar pattern for setting class attributes.</p> <pre><code>class CustomTemplateView(TemplateView): template_name = &quot;app/main.html&quot; class CustomMixin(ContextMixin): my_attribute = &quot;my_attribute_value&quot; #What does the code look like here considering I want to get the updated value in MainView before get_context_data and any TemplateView function? def get_context_data(self, **kwargs): context = super().get_context_data(**kwargs) context.update({&quot;key&quot;: &quot;value&quot;}) return context class MainView(CustomMixin, CustomTemplateView): template_name = &quot;app/main.html&quot; my_attribute = &quot;my_new_attribute_value&quot; </code></pre> <p>#From CustomMixin, what is the best way to access my_attribute set in MainView before any TemplateView function is fired?</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www

## Help for school presentation
 - [https://www.reddit.com/r/django/comments/1gsp6be/help_for_school_presentation](https://www.reddit.com/r/django/comments/1gsp6be/help_for_school_presentation)
 - RSS feed: $source
 - date published: 2024-11-16T15:06:16+00:00

<!-- SC_OFF --><div class="md"><p>I am doing a short presentation on &quot;Understanding and configuring Django projects&quot; for one of my courses. I feel like the assigned topic is kind of broad.</p> <p>I&#39;d be most grateful if someone could suggest what things should be mentioned/explained in the presentation?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jiwwsi"> /u/Jiwwsi </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsp6be/help_for_school_presentation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gsp6be/help_for_school_presentation/">[comments]</a></span>

## Cloudwatch aws
 - [https://www.reddit.com/r/django/comments/1gsmyzt/cloudwatch_aws](https://www.reddit.com/r/django/comments/1gsmyzt/cloudwatch_aws)
 - RSS feed: $source
 - date published: 2024-11-16T13:12:05+00:00

<!-- SC_OFF --><div class="md"><p>So I have a django project, where I have to manage routes with nginx, they are in two different repos. Now I want to add cloudwatch logs in AWS and the project should be deployed in aws fargate. So , what are the steps for dev , staging/prod. I am using Docker. So how to deploy project in Aws fargate and see the logs in Cloudwatch?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/userhere12"> /u/userhere12 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsmyzt/cloudwatch_aws/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gsmyzt/cloudwatch_aws/">[comments]</a></span>

## Vercel free-tier or Render Free-tier?
 - [https://www.reddit.com/r/django/comments/1gslkxt/vercel_freetier_or_render_freetier](https://www.reddit.com/r/django/comments/1gslkxt/vercel_freetier_or_render_freetier)
 - RSS feed: $source
 - date published: 2024-11-16T11:43:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently using the Render free-tier but it&#39;s INCREDIBLY slow, even for a simple portfolio website. It takes a full minute just for the website to come up. Is vercel any faster?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gslkxt/vercel_freetier_or_render_freetier/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gslkxt/vercel_freetier_or_render_freetier/">[comments]</a></span>

## Django vs springboot
 - [https://www.reddit.com/r/django/comments/1gslcr9/django_vs_springboot](https://www.reddit.com/r/django/comments/1gslcr9/django_vs_springboot)
 - RSS feed: $source
 - date published: 2024-11-16T11:27:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi, Moving from one tech stack to another.Currently building apps with angular with springboot backend.Now we have been asked to migrate to python with Django framework.</p> <p>I have zero experience in Django and hence these questions.</p> <p>Please suggest if this is a good move.</p> <p>Here are my questions</p> <p>---Django is compatible just with html for UI.Plewse correct me if am wrong.Springboot with java had compatibility with angular,react frameworks.Is Django also having options like that? </p> <p>---Boot with java had concurrency framework which offered multi threading functionalities.Does Django with python has anything like that? </p> <p>---Boot with java could be deployed in containers by bundling as a war or jar..what needs to be done for Django apps?</p> <p>----Django with python has in built connectors to Kafka? </p> <p>----how about unit testing frameworks in Django ?</p> <p>Please suggest if I need to consider anything else before 

## Custom Analytics Libraries
 - [https://www.reddit.com/r/django/comments/1gsl3vb/custom_analytics_libraries](https://www.reddit.com/r/django/comments/1gsl3vb/custom_analytics_libraries)
 - RSS feed: $source
 - date published: 2024-11-16T11:09:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve made a very basic Django site, I&#39;ll deploy it later on but I&#39;m actually having a little of fun making it. I work as an analyst and I&#39;ve managed to get 4 queries from and display them with chart.js and I&#39;m super happy with how it looks, I&#39;ll do some more formatting at a later date but I&#39;d like to keep building this out. </p> <p>Does anyone else have any experience making their own analytics stuff? What libraries look good for displaying charts and stuff? I realize I&#39;m not reinventing the wheel, we use Looker and Tableau at work but I would like to do <em>something</em> cool. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sufficient-Buy-2270"> /u/Sufficient-Buy-2270 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsl3vb/custom_analytics_libraries/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gsl3vb/custom_analytics_libr

## Django Challenges
 - [https://www.reddit.com/r/django/comments/1gsknna/django_challenges](https://www.reddit.com/r/django/comments/1gsknna/django_challenges)
 - RSS feed: $source
 - date published: 2024-11-16T10:36:05+00:00

<!-- SC_OFF --><div class="md"><p>I want to improve my coding skills on django and understand concepts better. Are they any django challenges monthly and weekly?? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mean-Pin-8271"> /u/Mean-Pin-8271 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsknna/django_challenges/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gsknna/django_challenges/">[comments]</a></span>

## Sas application and automatic subdomain register
 - [https://www.reddit.com/r/django/comments/1gsjw4u/sas_application_and_automatic_subdomain_register](https://www.reddit.com/r/django/comments/1gsjw4u/sas_application_and_automatic_subdomain_register)
 - RSS feed: $source
 - date published: 2024-11-16T09:37:09+00:00

<!-- SC_OFF --><div class="md"><p>Hey hey everyone, I want to build a sas application that customers can fill a form and get their application under the same domain. </p> <p>ex: <a href="http://a.com">a.com</a>, <a href="http://customer1.a.com">customer1.a.com</a> </p> <p>For that reason which domain registry would you suggest me that I can use their API to register a new subdomain? Preferably with terraform? </p> <p>I already tried with Godaddy but you need a minimum number of domains to be able to access the API which don&#39;t work for me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Willing_Department28"> /u/Willing_Department28 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsjw4u/sas_application_and_automatic_subdomain_register/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gsjw4u/sas_application_and_automatic_subdomain_register/">[comments]</a></span>

## This seems a complex situation: How to handle it?
 - [https://www.reddit.com/r/django/comments/1gsil1f/this_seems_a_complex_situation_how_to_handle_it](https://www.reddit.com/r/django/comments/1gsil1f/this_seems_a_complex_situation_how_to_handle_it)
 - RSS feed: $source
 - date published: 2024-11-16T07:57:49+00:00

<!-- SC_OFF --><div class="md"><p>Scenario: ModelA, and ModelB. There is a many to many relation between them, ModelA-&gt;through table-&gt;ModelB. Each model has a serializer: SerializerA and SerializerB</p> <p>When I query ModelB and use SerializerB, it includes the ID of ModelB. This is good!</p> <p>When I query ModelA, and SerializerA calls SerializerB for related records, it also includes the ID of ModelB. </p> <p>But I want to include the ID of the through table record</p> <p>I see two possible solutions:<br/> 1. Make the id output from SerializerB output the through_id dynamically if it exists.<br/> If the through_id exists, iSerializerB is being called by SerializerA, and should include the through_id<br/> If the through_id does not exist, dynamically use the ModelB id - because SerializerB is being used standalone. </p> <ol> <li> Duplicate the SerializerB, with amendments, each instance targeted to it&#39;s particular use-case.</li> </ol> <p>There may be more ways to handle 

## How to learn django
 - [https://www.reddit.com/r/django/comments/1gshu8x/how_to_learn_django](https://www.reddit.com/r/django/comments/1gshu8x/how_to_learn_django)
 - RSS feed: $source
 - date published: 2024-11-16T07:04:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys! I decided to learn Django. How should I do it? I learned a little bit python primitives types, lists, dict, sets and so on, anso I learned how to use if for and another construction also I explored os sys shutils json xml glob collections and other libraries. Yesterday ngit I decided to learn Django to make a simple web site for myself. I read about models views and so on, but here I wish to know I must explore all code in built-in librarires or jsut follow the book I&#39;ve choosen?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AnybodyNo6650"> /u/AnybodyNo6650 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gshu8x/how_to_learn_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gshu8x/how_to_learn_django/">[comments]</a></span>

## Refresh token expires before it should.
 - [https://www.reddit.com/r/django/comments/1gsfizl/refresh_token_expires_before_it_should](https://www.reddit.com/r/django/comments/1gsfizl/refresh_token_expires_before_it_should)
 - RSS feed: $source
 - date published: 2024-11-16T04:33:56+00:00

<!-- SC_OFF --><div class="md"><p>So I had a project in django as an api. I have used <code>rest_framework</code> and <code>restframework-simplejwt</code>. Here is the settings for <code>refresh_token</code> that should live for 30 days but it expires after one or two hours. What could be the workout around this?</p> <pre><code>SIMPLE_JWT = { &quot;ACCESS_TOKEN_LIFETIME&quot;: timedelta(minutes=5), &quot;REFRESH_TOKEN_LIFETIME&quot;: timedelta(days=30), &quot;UPDATE_LAST_LOGIN&quot;: True, } </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Traditional-Roof1663"> /u/Traditional-Roof1663 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsfizl/refresh_token_expires_before_it_should/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gsfizl/refresh_token_expires_before_it_should/">[comments]</a></span>

## Similarity Search with django for arabic text
 - [https://www.reddit.com/r/django/comments/1gsffrs/similarity_search_with_django_for_arabic_text](https://www.reddit.com/r/django/comments/1gsffrs/similarity_search_with_django_for_arabic_text)
 - RSS feed: $source
 - date published: 2024-11-16T04:28:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi All , hope you are having a great day!</p> <p>I am using django with posgtres and I have patient model with name field. The names are in arabic and i want to support similarity search that tolerates some mismatch between the search query and the db names. I tried </p> <pre><code>from django.contrib.postgres.search import TrigramSimilarity </code></pre> <p>But this only works on english text , does anyone had a similar issue and how did you manage to resolve it ?</p> <p>thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/oelseba"> /u/oelseba </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsffrs/similarity_search_with_django_for_arabic_text/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gsffrs/similarity_search_with_django_for_arabic_text/">[comments]</a></span>

## Rate my django project idea
 - [https://www.reddit.com/r/django/comments/1gsdxi9/rate_my_django_project_idea](https://www.reddit.com/r/django/comments/1gsdxi9/rate_my_django_project_idea)
 - RSS feed: $source
 - date published: 2024-11-16T03:01:41+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently enrolled in varsity and studying in 1st semester. Our class representatives share notices in whatsapp group where only they can message. But problem is many students forget tomorrow&#39;s notices because thesee were declared earlier. Also It&#39;s a hassle for CR to talk about same thing to many people.</p> <p>My idea is create a application where there will be four section: Class, Exam, Assignments, Notices. In home page there will be timer for upcoming class and top 2-3 recent published notices. And in Exam and Assignments sections there will be separate timer. </p> <p>If any student of my section visit that site, they do not need to ask any question to CR. Also for me, I won&#39;t forget what will happen next.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Confident-Flow-8787"> /u/Confident-Flow-8787 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gsdxi9/rate_my_django_p

