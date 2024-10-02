# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## CORS and CSRF Configuration for a Separate Frontend and Backend?
 - [https://www.reddit.com/r/django/comments/1ftxuvp/cors_and_csrf_configuration_for_a_separate](https://www.reddit.com/r/django/comments/1ftxuvp/cors_and_csrf_configuration_for_a_separate)
 - RSS feed: $source
 - date published: 2024-10-01T20:13:28+00:00

<!-- SC_OFF --><div class="md"><p>I am working on a site that has the Frontend and Backend hosted on separate domains. I have been struggling so much with CORS and CSRF configurations.</p> <p>Can someone please take a look at the GitHub repo? Everything works fine locally, however once deployed I continued to get CSRF-related issues for POST to the backend.</p> <p>Github repo: <a href="https://github.com/SoRobby/DjangoSvelteCookieAuth">https://github.com/SoRobby/DjangoSvelteCookieAuth</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SoRobby"> /u/SoRobby </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ftxuvp/cors_and_csrf_configuration_for_a_separate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftxuvp/cors_and_csrf_configuration_for_a_separate/">[comments]</a></span>

## How can I make a nested Serializer available inside the create of the super Serializer
 - [https://www.reddit.com/r/django/comments/1ftwa22/how_can_i_make_a_nested_serializer_available](https://www.reddit.com/r/django/comments/1ftwa22/how_can_i_make_a_nested_serializer_available)
 - RSS feed: $source
 - date published: 2024-10-01T19:09:05+00:00

<!-- SC_OFF --><div class="md"><pre><code>class BunnySerializer(ModelSerializer): sex = serializers.CharField() class Meta: model = Bunny fields = [&#39;sex&#39;, &#39;RID&#39;, &#39;COLID&#39;] class ThrowInfoSerializer(ModelSerializer): count = SerializerMethodField() remaining = SerializerMethodField() new_bunnies = BunnySerializer(many=True, read_only=True) BID_buck = ParentBunnySerializer() BID_doe = ParentBunnySerializer() class Meta: model = Throw fields = [&#39;thrown_on&#39;, &#39;covered_on&#39;, &#39;death_count&#39;, &#39;BID_buck&#39;, &#39;BID_doe&#39;, &#39;count&#39;, &#39;remaining&#39;, &#39;new_bunnies&#39;] def get_count(self, instance): return instance.bunny_set.count() def get_remaining(self, instance): return self.get_count(instance) - instance.death_count def create(self, validated_data, **kwargs): print(validated_data) new_bunnies = validated_data.pop(&#39;new_bunnies&#39;) BID_buck = Bunny.objects.get(**validated_data.pop(&#39;BID_buck&#39;, None)) BID_doe = 

## Where do I Deploying Django Project
 - [https://www.reddit.com/r/django/comments/1ftu4l6/where_do_i_deploying_django_project](https://www.reddit.com/r/django/comments/1ftu4l6/where_do_i_deploying_django_project)
 - RSS feed: $source
 - date published: 2024-10-01T17:41:50+00:00

<!-- SC_OFF --><div class="md"><p>I have developed a chatbot, backend is written in Django. I want to deploy it. Is there any good platform to deploy it for free. Currently I have deployed it on Render but having lots of issue with it. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kavyachouhan2005"> /u/kavyachouhan2005 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ftu4l6/where_do_i_deploying_django_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftu4l6/where_do_i_deploying_django_project/">[comments]</a></span>

## Trending Django packages in September
 - [https://www.reddit.com/r/django/comments/1fttpzc/trending_django_packages_in_september](https://www.reddit.com/r/django/comments/1fttpzc/trending_django_packages_in_september)
 - RSS feed: $source
 - date published: 2024-10-01T17:25:35+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dxt0434"> /u/dxt0434 </a> <br/> <span><a href="https://django.wtf/trending/?trending=30">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fttpzc/trending_django_packages_in_september/">[comments]</a></span>

## Django Model and DRF Serializer Validation
 - [https://www.reddit.com/r/django/comments/1ftsx5h/django_model_and_drf_serializer_validation](https://www.reddit.com/r/django/comments/1ftsx5h/django_model_and_drf_serializer_validation)
 - RSS feed: $source
 - date published: 2024-10-01T16:53:04+00:00

<!-- SC_OFF --><div class="md"><p>I have validation in my models. However, errors seem to be not handling properly by DRF views. Does that mean I have to perform validation on both models and serializers? I was under the impression that DRF views catch errors in the models and present them properly as response. I feel like I&#39;m missing something.</p> <p>Thank you so much in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aliasChewyC00kies"> /u/aliasChewyC00kies </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ftsx5h/django_model_and_drf_serializer_validation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftsx5h/django_model_and_drf_serializer_validation/">[comments]</a></span>

## Question about Django-Active Directory integration
 - [https://www.reddit.com/r/django/comments/1ftsamu/question_about_djangoactive_directory_integration](https://www.reddit.com/r/django/comments/1ftsamu/question_about_djangoactive_directory_integration)
 - RSS feed: $source
 - date published: 2024-10-01T16:27:42+00:00

<!-- SC_OFF --><div class="md"><p>We have a Django-based API that viewable by the public, but you need admin credentials in order to edit the data (which is the default, I believe). I have added a feature to allow someone with admin credentials to view download statistics which uses a Django template to view them. We want, if possible, to integrate Active Directory so that someone can log into the admin area using their normal AD credentials. I found the following article which I believe describes how to do just that: <a href="https://medium.com/@satyayellacharigoli/step-by-step-guide-to-integrate-active-directory-with-django-f556390c8581">https://medium.com/@satyayellacharigoli/step-by-step-guide-to-integrate-active-directory-with-django-f556390c8581</a></p> <p>Is that in fact what it&#39;s doing, or is it making it so that you need AD credentials to access the parts of the API which are currently public?</p> <p>Bonus question: I currently limit access to the statistics view using &q

## Why does obj.bunny_set.count() return a (int, int, int)?
 - [https://www.reddit.com/r/django/comments/1fts7dy/why_does_objbunny_setcount_return_a_int_int_int](https://www.reddit.com/r/django/comments/1fts7dy/why_does_objbunny_setcount_return_a_int_int_int)
 - RSS feed: $source
 - date published: 2024-10-01T16:24:04+00:00

<!-- SC_OFF --><div class="md"><p>So I have this serializer:</p> <pre><code>class ThrowInfoSerializer(ModelSerializer): count = SerializerMethodField() remaining = SerializerMethodField() new_bunnies = BunnySerializer(many=True) BID_buck = ParentBunnySerializer() BID_doe = ParentBunnySerializer() class Meta: model = Throw fields = [&#39;thrown_on&#39;, &#39;covered_on&#39;, &#39;death_count&#39;, &#39;BID_buck&#39;, &#39;BID_doe&#39;, &#39;UID_stud_book_keeper&#39;, &#39;count&#39;, &#39;remaining&#39;, &#39;new_bunnies&#39;] write_only_fields = [&#39;UID_stud_book_keeper&#39;] read_only_fields = [&quot;count&quot;, &quot;remaining&quot;, &quot;new_bunnies&quot;, &#39;BID_buck&#39;, &#39;BID_doe&#39;] def get_count(self, obj): return obj.bunny_set.count() def get_remaining(self, obj): return get_count() - obj.death_count </code></pre> <p>And when I try to calculate <code>get_count() - obj.death_count</code> I get this error: <code>Class &#39;(int, int, int)&#39; does not define &#39;_

## Advanced Django drf
 - [https://www.reddit.com/r/django/comments/1fto6l0/advanced_django_drf](https://www.reddit.com/r/django/comments/1fto6l0/advanced_django_drf)
 - RSS feed: $source
 - date published: 2024-10-01T13:31:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone. I want to level up my Django skills. I am learning Django rest framework. I did some project like blog app, fitness app, task management, to-do list and more. My knowledge is Django, drf, jwt, redis, celery, postgresql, mongodb, o-Auth, vuejs typescript. What should I learn next? Can you suggest me something about it? I want to learn advanced Django, do you have any sources, topics, tutorials? This is my github : <a href="https://github.com/emirhantavus">https://github.com/emirhantavus</a></p> <p>Thanks. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Whisber1"> /u/Whisber1 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fto6l0/advanced_django_drf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fto6l0/advanced_django_drf/">[comments]</a></span>

## The next great leap for Django
 - [https://www.reddit.com/r/django/comments/1ftn4tj/the_next_great_leap_for_django](https://www.reddit.com/r/django/comments/1ftn4tj/the_next_great_leap_for_django)
 - RSS feed: $source
 - date published: 2024-10-01T12:42:56+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://kodare.net/2024/10/01/django-next-leap.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftn4tj/the_next_great_leap_for_django/">[comments]</a></span>

## Anyone used Channels with Django Ninja for a realtime fullstack app?
 - [https://www.reddit.com/r/django/comments/1ftm9j8/anyone_used_channels_with_django_ninja_for_a](https://www.reddit.com/r/django/comments/1ftm9j8/anyone_used_channels_with_django_ninja_for_a)
 - RSS feed: $source
 - date published: 2024-10-01T11:57:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;d like to create an app with Django Ninja which has a Nuxt/Vue frontend. I&#39;d also like to use websockets with Django Channels for realtime communication? </p> <p>Has anyone done this before? Anything I should be aware of?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KiwiNFLFan"> /u/KiwiNFLFan </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ftm9j8/anyone_used_channels_with_django_ninja_for_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftm9j8/anyone_used_channels_with_django_ninja_for_a/">[comments]</a></span>

## CMS on django
 - [https://www.reddit.com/r/django/comments/1ftm3zf/cms_on_django](https://www.reddit.com/r/django/comments/1ftm3zf/cms_on_django)
 - RSS feed: $source
 - date published: 2024-10-01T11:48:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I’m currently working on a school project and chose Django to write the backend. The project is a management tool similar to Jira. After sending the idea and describing the features to my teacher, he told me to add an admin role and look into CMS. So, my question is: what does CMS mean in this context, are there any packages or tutorials for this in Django, and how should i design this feature.</p> <p>Also, I want to add real-time features like chat and notifications. Should I just change the settings to asynchronous and add apps, or create a new project for them since other stuff work on synchronous enviroment.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RemarkableVideo8527"> /u/RemarkableVideo8527 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ftm3zf/cms_on_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftm3zf/cms_on_django/">[comm

## What Database should I use if I get to nearly 10k users?
 - [https://www.reddit.com/r/django/comments/1ftl839/what_database_should_i_use_if_i_get_to_nearly_10k](https://www.reddit.com/r/django/comments/1ftl839/what_database_should_i_use_if_i_get_to_nearly_10k)
 - RSS feed: $source
 - date published: 2024-10-01T10:55:27+00:00

<!-- SC_OFF --><div class="md"><p>If you were building a website with Django, would you stick with the Mysql bundled with Django to serve as database for over 10k users or use another DBMS?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Naija-CodeX"> /u/Naija-CodeX </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ftl839/what_database_should_i_use_if_i_get_to_nearly_10k/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftl839/what_database_should_i_use_if_i_get_to_nearly_10k/">[comments]</a></span>

## Is there any free-tier hosting site for ASGI?
 - [https://www.reddit.com/r/django/comments/1fti79h/is_there_any_freetier_hosting_site_for_asgi](https://www.reddit.com/r/django/comments/1fti79h/is_there_any_freetier_hosting_site_for_asgi)
 - RSS feed: $source
 - date published: 2024-10-01T07:13:58+00:00

<!-- SC_OFF --><div class="md"><p>Currently I&#39;m working on a live chat app that uses django-channel, React, and DRF. The issue that I&#39;m having is that I can&#39;t find a free-tier hosting site for ASGI apps. I tried Pythonanywhere and Vercel but found out that they don&#39;t support ASGI. Does anybody here know a site? Any help will be greatly appreciated. Thank you very much.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shinhosuck1973"> /u/Shinhosuck1973 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fti79h/is_there_any_freetier_hosting_site_for_asgi/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fti79h/is_there_any_freetier_hosting_site_for_asgi/">[comments]</a></span>

## Front End using Django, HTML, CSS and JS**HELP
 - [https://www.reddit.com/r/django/comments/1fti1hp/front_end_using_django_html_css_and_jshelp](https://www.reddit.com/r/django/comments/1fti1hp/front_end_using_django_html_css_and_jshelp)
 - RSS feed: $source
 - date published: 2024-10-01T07:02:15+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,<br/> I am a network engineer(fresher), and my boss wants to build a website for office internal purposes to automate some work, he has a website with built entierly using Django with a not so user friendly front end, he wants me to work and improve the front end of his website, and he&#39;s asking me to try using Django, i am not able to find documents which helps me work with Frontend (HTML,CSS,JS) like ANGULAR in Django, i am not able to find any Document or video which helps me to do frontend using Django, like in ANGULAR or REACT,<br/> he gave me a list of data from a API call, the data is in List format, and wants me to tabulate the data and beautify it like a professional website, im not sure on how to do it in Django, i have halfbaked knowledge in Front-end with ANGULAR and Django.</p> <p>TLDR; How do i code Front end with Django(HTML,CSS,JS). I got data from a API call, the data is dynamic, and i need to tabulate those data and repre

## Beginner Question - Why API?
 - [https://www.reddit.com/r/django/comments/1ftbzr9/beginner_question_why_api](https://www.reddit.com/r/django/comments/1ftbzr9/beginner_question_why_api)
 - RSS feed: $source
 - date published: 2024-10-01T01:10:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve recently been learning Django via tutorials and books solely as a personal challenge as I don&#39;t use coding in my career. That said, I am struggling to understand why REST API&#39;s (or API&#39;s in general), exist. I have created a blog API in a tutorial, but why? Beyond extracting data from a huge database, why isn&#39;t a regular website with data presented in html sufficient? As a corollary, what would be a good personal project that could utilize an API vs./on top of a standard django website?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hayduke_Deckard"> /u/Hayduke_Deckard </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ftbzr9/beginner_question_why_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ftbzr9/beginner_question_why_api/">[comments]</a></span>

