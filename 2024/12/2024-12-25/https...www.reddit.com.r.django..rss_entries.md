# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Where to start with headless allauth
 - [https://www.reddit.com/r/django/comments/1hm86tk/where_to_start_with_headless_allauth](https://www.reddit.com/r/django/comments/1hm86tk/where_to_start_with_headless_allauth)
 - RSS feed: $source
 - date published: 2024-12-25T20:21:02+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! </p> <p>I&#39;ve been taking my first steps into front end development, I&#39;ve chosen sveltekit and am loving it so far. Now for the tricky part, authentication. There is a boilerplate project for allauth in react but I find the documentation to be lacking any guidance on implementation, any pointers? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/memeface231"> /u/memeface231 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hm86tk/where_to_start_with_headless_allauth/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hm86tk/where_to_start_with_headless_allauth/">[comments]</a></span>

## how to deploy asgi django on elastic beanstalk?
 - [https://www.reddit.com/r/django/comments/1hm6mqu/how_to_deploy_asgi_django_on_elastic_beanstalk](https://www.reddit.com/r/django/comments/1hm6mqu/how_to_deploy_asgi_django_on_elastic_beanstalk)
 - RSS feed: $source
 - date published: 2024-12-25T18:59:23+00:00

<!-- SC_OFF --><div class="md"><p>i have set asgi server setting using daphne.. and how to setup for aws eb? </p> <p><code>option_settings: aws:elasticbeanstalk:container:python:</code> </p> <p><code>WSGIPath: backend.wsgi:application</code> </p> <p><code>ASGIPath: backend.asgi:application</code></p> <p>i added this .ebextensions file, am I ready to go? </p> <p>is my django asgi server will talk to nginx or do I need something more..?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hm6mqu/how_to_deploy_asgi_django_on_elastic_beanstalk/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hm6mqu/how_to_deploy_asgi_django_on_elastic_beanstalk/">[comments]</a></span>

## how to integrate or connect separate asgi server with wsgi server?
 - [https://www.reddit.com/r/django/comments/1hm6d54/how_to_integrate_or_connect_separate_asgi_server](https://www.reddit.com/r/django/comments/1hm6d54/how_to_integrate_or_connect_separate_asgi_server)
 - RSS feed: $source
 - date published: 2024-12-25T18:45:12+00:00

<!-- SC_OFF --><div class="md"><p>hi, here is my concern..</p> <p>I am running wsgi server for an ecommerce site, and I am bout to create asgi server(daphne) for chat service and notification.. However, those chat and notificiation require authentification.. wsgi server takes the role for auth.. in this case, how to use separate asgi server that needs authentifications from wsgi server?? or is my architecture wrong..? please give me any suggestions.. thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hm6d54/how_to_integrate_or_connect_separate_asgi_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hm6d54/how_to_integrate_or_connect_separate_asgi_server/">[comments]</a></span>

## Do I need ECS for using Celery worker nodes?
 - [https://www.reddit.com/r/django/comments/1hm69kl/do_i_need_ecs_for_using_celery_worker_nodes](https://www.reddit.com/r/django/comments/1hm69kl/do_i_need_ecs_for_using_celery_worker_nodes)
 - RSS feed: $source
 - date published: 2024-12-25T18:39:46+00:00

<!-- SC_OFF --><div class="md"><p>hi, I need distributed system, and I am using Elastic Beanstalk for my django app. Do I need ecs for celery worker nodes and task queue? then how to set up? anything that I can refer to? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hm69kl/do_i_need_ecs_for_using_celery_worker_nodes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hm69kl/do_i_need_ecs_for_using_celery_worker_nodes/">[comments]</a></span>

## How to effectively understand the Django repository (or any large codebase)?
 - [https://www.reddit.com/r/django/comments/1hm4o4f/how_to_effectively_understand_the_django](https://www.reddit.com/r/django/comments/1hm4o4f/how_to_effectively_understand_the_django)
 - RSS feed: $source
 - date published: 2024-12-25T17:16:18+00:00

<!-- SC_OFF --><div class="md"><p>The reason I am asking this question stems from my exploration of the Django codebase, which began after I finished studying <em>Django for Beginners 4.2</em> by <a href="https://wsvincent.com/">Will Vincent</a>. Throughout the book, I often found myself asking questions like, how do CBVs and GCBVs work? Why do they inherit from the <code>View</code> class? Why is <code>.as_view()</code> used with CBVs and GCBVs, but not with FBVs?</p> <p>These questions stayed in my mind, so I decided to explore the Django repository to understand them better. While most of the code (if not all) went over my head, I believe I now partially &quot;understand&quot; the &quot;why&quot; behind some of these concepts.</p> <p>From my exploration, I realized that <code>as_view()</code> essentially “converts” CBVs and GCBVs into functions because the foundational way of building Django views are FBVs. CBVs and GCBVs are built on top of FBVs. CBVs aim to achieve better separa

## Advanced Tutorials
 - [https://www.reddit.com/r/django/comments/1hm10xf/advanced_tutorials](https://www.reddit.com/r/django/comments/1hm10xf/advanced_tutorials)
 - RSS feed: $source
 - date published: 2024-12-25T13:47:34+00:00

<!-- SC_OFF --><div class="md"><p>The Djangoverse is not lacking in any beginner tutorials. Although some cover more advanced topics, they are harder to find and some topics have none. </p> <p>I&#39;ve been following some more advanced tutorials on structuring Django projects and it really advanced my understanding of the framework. I thought it would be great if people could post tutorials they&#39;ve found useful on some of the more advanced/obscure topics (not covered in the beginner tutorials). Some of my topics of interest (feel free to add yours!):</p> <ol> <li>Email verification for custom user models (tokens anyone?):<br/></li> <li>Full email system setup in general:<br/></li> <li>Celery use beyond just setup:<br/></li> <li>How to manage changes and migrations while website is deployed already:</li> </ol> <p>I&#39;m sure there are a lot more. It would be great to have an ongoing list. </p> <p>Best wishes for 2025!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="htt

## Tips for Learning Django.. coming from Java (Spring)?
 - [https://www.reddit.com/r/django/comments/1hls0s7/tips_for_learning_django_coming_from_java_spring](https://www.reddit.com/r/django/comments/1hls0s7/tips_for_learning_django_coming_from_java_spring)
 - RSS feed: $source
 - date published: 2024-12-25T02:32:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys, I&#39;m moving from a team using Java (Spring) to a Django backend team (likely using the Django REST framework) within my company after the New Year break. I&#39;ve never worked with Django before, but I do know Python pretty well since it’s my go to language for LC. My current plan is to start with the official Django tutorial, move on to Django REST doc, and then build a small project to get some hands on experience.</p> <p>For those who know both Spring and Django, is there anything I should keep in mind while learning Django? (I also have some experience with nodeJs Express, though that was from some personal projects I worked on a long time ago) Also, is the official Django doc the best way to learn, or are there other resources you’d recommend? Would love to hear any advice or tips from people who’ve been in a similar boat. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sad-Sympathy-2

