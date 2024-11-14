# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## I'm puzzled trying to update just 1 m2m object in a form
 - [https://www.reddit.com/r/django/comments/1gqo5j5/im_puzzled_trying_to_update_just_1_m2m_object_in](https://www.reddit.com/r/django/comments/1gqo5j5/im_puzzled_trying_to_update_just_1_m2m_object_in)
 - RSS feed: $source
 - date published: 2024-11-13T21:30:39+00:00

<!-- SC_OFF --><div class="md"><p>I have a form in a template where I want the ability to check a box and it shows an interest in a game for an official. There is a many-to-many relationship between games and officials. </p> <p>In the template, the form presents only the user of all officials to either check or uncheck for a game.</p> <p>If the user is unchecked and then checks their interest, any other user who had indicated a relationship is no longer associated with that game.</p> <p>If the user is checked and unchecks themself, they essentially uncheck all users associated with that game.</p> <p>Please help point me in the right direction.</p> <p>Here are relevant sections of code:</p> <p><a href="http://models.py">models.py</a></p> <pre><code>class Official(models.Model): user = models.OneToOneField(User, on_delete=models.CASCADE) class Game(models.Model): game_official_options = models.ManyToManyField(Official, blank=True, related_name=&#39;officials&#39;) </code></pre> <p><a h

## Tutorial: Turning django to async without using async
 - [https://www.reddit.com/r/django/comments/1gqlsln/tutorial_turning_django_to_async_without_using](https://www.reddit.com/r/django/comments/1gqlsln/tutorial_turning_django_to_async_without_using)
 - RSS feed: $source
 - date published: 2024-11-13T19:51:43+00:00

<!-- SC_OFF --><div class="md"><p>You may probably heard about gevent. It can turn sync code to async by monkey patching io bound libraries. </p> <p>In this tutorial i wrote, I explained everything about how to use gevent correctly with some extra configurations to achieve async-like performance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Smart-Acanthisitta35"> /u/Smart-Acanthisitta35 </a> <br/> <span><a href="https://gist.github.com/akhushnazarov/2f21bfa5227d85e87a29ad0df6a1d967">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gqlsln/tutorial_turning_django_to_async_without_using/">[comments]</a></span>

## Is async django ready for prime time? Our async django production experience
 - [https://www.reddit.com/r/django/comments/1gqfyw3/is_async_django_ready_for_prime_time_our_async](https://www.reddit.com/r/django/comments/1gqfyw3/is_async_django_ready_for_prime_time_our_async)
 - RSS feed: $source
 - date published: 2024-11-13T15:51:14+00:00

<!-- SC_OFF --><div class="md"><p>We have traditionally used Django in all our products. We believe it is one of the most underrated, beautifully designed, rock solid framework out there.</p> <p>However, if we are to be honest, the history of async usage in Django wasn&#39;t very impressive. You could argue that for most products, you don’t really need async. It was just an extra layer of complexity without any significant practical benefit.</p> <p>Over the last couple of years, AI use-cases have changed that perception. Many AI products have calling external APIs over the network as their bottleneck. This makes the complexity from async Python worth considering. FastAPI with its intuitive async usage and simplicity have risen to be the default API/web layer for AI projects. </p> <p>I wrote about using async Django in a relatively complex AI open source project here: <a href="https://jonathanadly.com/is-async-django-ready-for-prime-time">https://jonathanadly.com/is-async-django-ready

## Some of my django app metrics
 - [https://www.reddit.com/r/django/comments/1gqc4ad/some_of_my_django_app_metrics](https://www.reddit.com/r/django/comments/1gqc4ad/some_of_my_django_app_metrics)
 - RSS feed: $source
 - date published: 2024-11-13T12:49:02+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/lsfc40ft0o0e1.png?width=2128&amp;format=png&amp;auto=webp&amp;s=54218f551355bd388193ea1141031e192bcae3a4">https://preview.redd.it/lsfc40ft0o0e1.png?width=2128&amp;format=png&amp;auto=webp&amp;s=54218f551355bd388193ea1141031e192bcae3a4</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Willing_Department28"> /u/Willing_Department28 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gqc4ad/some_of_my_django_app_metrics/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gqc4ad/some_of_my_django_app_metrics/">[comments]</a></span>

## I need to improve the SEO for my web app
 - [https://www.reddit.com/r/django/comments/1gqaa41/i_need_to_improve_the_seo_for_my_web_app](https://www.reddit.com/r/django/comments/1gqaa41/i_need_to_improve_the_seo_for_my_web_app)
 - RSS feed: $source
 - date published: 2024-11-13T10:54:46+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve just deployed my django app on render, but it&#39;s REALLY hard to find it unless i actively enter the url to get it. Are there any tools and/or practices i could use to improve it&#39;s SEO?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gqaa41/i_need_to_improve_the_seo_for_my_web_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gqaa41/i_need_to_improve_the_seo_for_my_web_app/">[comments]</a></span>

## How do you label your Django tasks/issues? (e.g. on Github/Gitlab/Jira): A Thread
 - [https://www.reddit.com/r/django/comments/1gq92en/how_do_you_label_your_django_tasksissues_eg_on](https://www.reddit.com/r/django/comments/1gq92en/how_do_you_label_your_django_tasksissues_eg_on)
 - RSS feed: $source
 - date published: 2024-11-13T09:25:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, </p> <p>In my opnion, Django is really the best framework out there and I actually really enjoy getting your opinions. </p> <p>I was wondering, what do you use as labels for the issues/tasks associated with your Django projects? </p> <p>(I will also submit my own as a separate comment)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MikeDoesDo"> /u/MikeDoesDo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gq92en/how_do_you_label_your_django_tasksissues_eg_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gq92en/how_do_you_label_your_django_tasksissues_eg_on/">[comments]</a></span>

## Django Setup and Basic Overview
 - [https://www.reddit.com/r/django/comments/1gq8i4w/django_setup_and_basic_overview](https://www.reddit.com/r/django/comments/1gq8i4w/django_setup_and_basic_overview)
 - RSS feed: $source
 - date published: 2024-11-13T08:40:03+00:00

<!-- SC_OFF --><div class="md"><p>Today I have started this blog series because I struggled to find simple and clear tutorials when I was learning Django. So I wanted to share my learning process in such a way which is easy to follow and understand.</p> <ul> <li><strong>Blog Link :</strong> <a href="https://django-learning.hashnode.dev/django-setup-and-basic-overview">https://django-learning.hashnode.dev/django-setup-and-basic-overview</a></li> </ul> <p>Give it a read and share your thoughts in the comments! 💬 I’d love to keep improving and make it more helpful for everyone! 😊</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rohit8329"> /u/rohit8329 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gq8i4w/django_setup_and_basic_overview/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gq8i4w/django_setup_and_basic_overview/">[comments]</a></span>

## Do you struggle with Authentication using Django rest framework (DRF)? 𝗙𝗶𝗻𝗱 𝗛𝗼𝘄 𝘁𝗼 𝗱𝗼 𝗶𝘁 𝗶𝗻 𝗹𝗲𝘀𝘀 𝘁𝗵𝗮𝗻 𝟱 𝗺𝗶𝗻𝘂𝘁𝗲𝘀 👇🏾
 - [https://www.reddit.com/r/django/comments/1gq82y1/do_you_struggle_with_authentication_using_django](https://www.reddit.com/r/django/comments/1gq82y1/do_you_struggle_with_authentication_using_django)
 - RSS feed: $source
 - date published: 2024-11-13T08:06:42+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Initial_Armadillo_42"> /u/Initial_Armadillo_42 </a> <br/> <span><a href="https://www.reddit.com/gallery/1gq82y1">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gq82y1/do_you_struggle_with_authentication_using_django/">[comments]</a></span>

## using JavaScript packages/modules in Django
 - [https://www.reddit.com/r/django/comments/1gq5qbr/using_javascript_packagesmodules_in_django](https://www.reddit.com/r/django/comments/1gq5qbr/using_javascript_packagesmodules_in_django)
 - RSS feed: $source
 - date published: 2024-11-13T05:24:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m starting a new project, and i want to start using npm modules, but i know you can&#39;t just install them. I&#39;ve read about something called webpack but i&#39;ve never found an intuitive enough tutorial that shows how to use webpack with django. please help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gq5qbr/using_javascript_packagesmodules_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gq5qbr/using_javascript_packagesmodules_in_django/">[comments]</a></span>

## I wanna get a Google Cloud Certification, but i don't know which one
 - [https://www.reddit.com/r/django/comments/1gq5o6o/i_wanna_get_a_google_cloud_certification_but_i](https://www.reddit.com/r/django/comments/1gq5o6o/i_wanna_get_a_google_cloud_certification_but_i)
 - RSS feed: $source
 - date published: 2024-11-13T05:20:54+00:00

<!-- SC_OFF --><div class="md"><p>I just graduated from a software engineering course and a lot of the &quot;entry level&quot; jobs i apply to wants AWS/GCP experience. Which GCP certification goes best with Python development, but also looks good on a resume?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gq5o6o/i_wanna_get_a_google_cloud_certification_but_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gq5o6o/i_wanna_get_a_google_cloud_certification_but_i/">[comments]</a></span>

## Building efficient API in Django REST framework, Django-ninja, and comparing to Golang
 - [https://www.reddit.com/r/django/comments/1gq5efh/building_efficient_api_in_django_rest_framework](https://www.reddit.com/r/django/comments/1gq5efh/building_efficient_api_in_django_rest_framework)
 - RSS feed: $source
 - date published: 2024-11-13T05:04:52+00:00

<!-- SC_OFF --><div class="md"><p>A few days ago I wrote about a step-by-step guide in optimizing an API written in Django REST Framework for retrieving large amount data (100k+ records), and most Redditors here liked it.</p> <p>I have now added the same example written with Django-ninja to compare. Just for fun I also added a very light weight Golang implementation of the identical API.</p> <p><a href="https://preview.redd.it/11phws0hpl0e1.png?width=600&amp;format=png&amp;auto=webp&amp;s=b34cf1b2c6fbb2ca16760431b4890954c55a4049">https://preview.redd.it/11phws0hpl0e1.png?width=600&amp;format=png&amp;auto=webp&amp;s=b34cf1b2c6fbb2ca16760431b4890954c55a4049</a></p> <p><a href="https://preview.redd.it/sugub4hipl0e1.png?width=600&amp;format=png&amp;auto=webp&amp;s=b0aa484e8c57728f8b375a0e8d7902464dda2de7">https://preview.redd.it/sugub4hipl0e1.png?width=600&amp;format=png&amp;auto=webp&amp;s=b0aa484e8c57728f8b375a0e8d7902464dda2de7</a></p> <p>One thing that was surprising to me is that Dj

## Displaying human readable choice from a field in a template from a form
 - [https://www.reddit.com/r/django/comments/1gq4swc/displaying_human_readable_choice_from_a_field_in](https://www.reddit.com/r/django/comments/1gq4swc/displaying_human_readable_choice_from_a_field_in)
 - RSS feed: $source
 - date published: 2024-11-13T04:29:43+00:00

<!-- SC_OFF --><div class="md"><p>this took an incredible amount of time to work through all the kinks and I&#39;m wondering if there was an easier way to do this. I created a form for a profile model to be used for a dating site so a lot of the fields have a list of choices for the possible values. trying to get the human readable values from the choices lists was a challenge since the form will always send the short notation of the choice. even trying to set the default response from the model as the get_FOO display value wasn&#39;t working through the template, so i created a template tag that can be called from the template to convert into the display values and went from there. It presented it&#39;s own challenges as now the values had to be attained ising the get_field_display method, there was no more if form.status == 2 in my templates it had to be form.instance|get_field_display:&#39;&lt;field name&gt;&#39; and if i wanted to check for null values |default:&#39;&#39; had to 

