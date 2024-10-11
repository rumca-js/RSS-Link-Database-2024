# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## AsyncConsumer - Create new row in DB
 - [https://www.reddit.com/r/django/comments/1g0qv06/asyncconsumer_create_new_row_in_db](https://www.reddit.com/r/django/comments/1g0qv06/asyncconsumer_create_new_row_in_db)
 - RSS feed: $source
 - date published: 2024-10-10T19:22:21+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve read the docs, ensured my ORM operation is in a seperate function / method now when I call it will successfully create the new row. However when i go to send a a message back to the client over the websocket it won&#39;t actually go through</p> <p>This is all without throwing an error. I assume it&#39;s a thread issue with context switching. Not too sure tho:</p> <pre><code>def save_new_order(self, data): order = Orders.objects.create(**data) print(&#39; Created order&#39;) return order order = await database_sync_to_async(self.save_new_order)(data[&#39;new_order&#39;]) await self.send(json.dumps({&#39;msg&#39;: &#39;order created&#39;})) </code></pre> <p>``` </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Queasy_Bee_4911"> /u/Queasy_Bee_4911 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g0qv06/asyncconsumer_create_new_row_in_db/">[link]</a></span> &#32; <span><a href="https://www.

## Google OAuth with Firebase in Django web application
 - [https://www.reddit.com/r/django/comments/1g0p9x1/google_oauth_with_firebase_in_django_web](https://www.reddit.com/r/django/comments/1g0p9x1/google_oauth_with_firebase_in_django_web)
 - RSS feed: $source
 - date published: 2024-10-10T18:14:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m building a prototype project that will later be launched as MicroSaaS and one of the requirements is authentication with a Google account.</p> <p>It seems like a silly question, <strong>but what exactly do I have to do to use only the Google Authentication in my Django project?</strong> So far I&#39;ve created my Firebase account (obviously) and then got a code to connect via CDN (JavaScript), what are the next steps?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Araujo-0608"> /u/Araujo-0608 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g0p9x1/google_oauth_with_firebase_in_django_web/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g0p9x1/google_oauth_with_firebase_in_django_web/">[comments]</a></span>

## Announcing api-response-shaper package
 - [https://www.reddit.com/r/django/comments/1g0ltvh/announcing_apiresponseshaper_package](https://www.reddit.com/r/django/comments/1g0ltvh/announcing_apiresponseshaper_package)
 - RSS feed: $source
 - date published: 2024-10-10T15:45:02+00:00

<!-- SC_OFF --><div class="md"><p>I’m thrilled to introduce <strong>api-response-shaper</strong>, a middleware and decorator-based package for Django that helps structure your API responses in a consistent, uniform format. This package offers: Dynamic configurations to suit your needs Pre-built response formats like paginated responses, batch responses, minimal success, and error responses Designed for Django REST Framework (DRF), this tool ensures your APIs maintain a clean, standardized response format across endpoints, making development smoother and more efficient. Check it out and let me know what you think!<br/> PyPI: <a href="https://pypi.org/project/api-response-shaper/">https://pypi.org/project/api-response-shaper/</a><br/> GitHub: <a href="https://github.com/Lazarus-org/api-response-shaper">https://github.com/Lazarus-org/api-response-shaper</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aryan_Nik"> /u/Aryan_Nik </a> <br/> <span><a 

## Introducing dj-notification-api package
 - [https://www.reddit.com/r/django/comments/1g0ls77/introducing_djnotificationapi_package](https://www.reddit.com/r/django/comments/1g0ls77/introducing_djnotificationapi_package)
 - RSS feed: $source
 - date published: 2024-10-10T15:43:03+00:00

<!-- SC_OFF --><div class="md"><p>Hey <strong>Django community</strong>! I’m excited to share <strong>dj-notification-api</strong>, a Django package designed to streamline managing notifications via multiple <strong>API</strong>s. With this package, integrating a notification system into your Django project is as easy as installing it! Key features include:</p> <ul> <li>Fully customizable notification API tailored to your project’s needs</li> <li>Powerful and intuitive admin interface for managing, tracking, and configuring notifications</li> <li>Optimized for flexibility and performance</li> </ul> <p>Feel free to check it out, and let me know if you have any questions!<br/> PyPI: <a href="https://pypi.org/project/dj-notification-api/">https://pypi.org/project/dj-notification-api/</a><br/> GitHub: <a href="https://github.com/Lazarus-org/dj-notification-api">https://github.com/Lazarus-org/dj-notification-api</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.red

## In-depth resource to learn Django
 - [https://www.reddit.com/r/django/comments/1g0kqb9/indepth_resource_to_learn_django](https://www.reddit.com/r/django/comments/1g0kqb9/indepth_resource_to_learn_django)
 - RSS feed: $source
 - date published: 2024-10-10T14:56:49+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I have about 1.5 year of experience using Python as a data analyst, and I wanted to learn the basics of web development to create a website. I started doing the RealPython learning path on Django, but the videos are 3-5 years old and some of them are no longer working. This has been very annoying. Because it is a smaller website, I guess they just have a harder time updating their material to keep up with new versions.</p> <p>Therefore, does anyone have recommendations for a Django course that is more likely to be up-to-date and whose website might have a larger community? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mstrsplntr1"> /u/mstrsplntr1 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g0kqb9/indepth_resource_to_learn_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g0kqb9/indepth_resource_to_learn_django/">[comments]</a

## Deploying Django App on DirectAdmin Shared Hosting
 - [https://www.reddit.com/r/django/comments/1g0kgkd/deploying_django_app_on_directadmin_shared_hosting](https://www.reddit.com/r/django/comments/1g0kgkd/deploying_django_app_on_directadmin_shared_hosting)
 - RSS feed: $source
 - date published: 2024-10-10T14:44:20+00:00

<!-- SC_OFF --><div class="md"><p>Recently bought a shared hosting plan and looking to fire up my Django app. My hosting provider uses DirectAdmin as their control panel.</p> <p>I&#39;ve been stuck at the default &#39;web server is functioning normally&#39; screen. 7 hours going through articles, tutorials, and documentations yet I don&#39;t seem to progress. </p> <p>Raising this, just in case there&#39;s a config I am missing out, there&#39;s someone who previously had a similar problem, or there&#39;s a resource that can help unstuck me. </p> <p>I am not the kind who raises issues without poking around, so kindly consider that I&#39;ve almost exhausted all the options.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Due-Net4065"> /u/Due-Net4065 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g0kgkd/deploying_django_app_on_directadmin_shared_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comm

## Deploying (Multiple) Django Apps to a Single Server with Kamal 2
 - [https://www.reddit.com/r/django/comments/1g0i0nl/deploying_multiple_django_apps_to_a_single_server](https://www.reddit.com/r/django/comments/1g0i0nl/deploying_multiple_django_apps_to_a_single_server)
 - RSS feed: $source
 - date published: 2024-10-10T12:48:51+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/czue13"> /u/czue13 </a> <br/> <span><a href="https://www.coryzue.com/writing/kamal-django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g0i0nl/deploying_multiple_django_apps_to_a_single_server/">[comments]</a></span>

## File handler app for internal use - can't grasp structure.
 - [https://www.reddit.com/r/django/comments/1g0hgrd/file_handler_app_for_internal_use_cant_grasp](https://www.reddit.com/r/django/comments/1g0hgrd/file_handler_app_for_internal_use_cant_grasp)
 - RSS feed: $source
 - date published: 2024-10-10T12:19:03+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working in a small/medium size metal fabrication company and I&#39;m a python dev/cad person here. I&#39;m building a django app for internal use, offering tools to speed up mundane tasks, mainly handling dxf files (using EZDXF library which is awesome). I have some functionalities running already, now I&#39;m working on a functionality that automates handling orders from one of our main clients. Long story short it&#39;s some classes to handle a zip, recursively go through contents, fish out dxf files, add some text entities inside so our laser cutting cam software understands it(it looks like a dictionary), prepare a document with a file list and additional info, pack everything back and send it to user as a zip. I utilize the functionalities in views.py, for example here is how the tool to change the quantity of parts looks:</p> <pre><code>def quantity(request): if request.method == &#39;POST&#39;: try: filepaths = handle_uploaded_files(req

## Digital ocean app platform + spaces
 - [https://www.reddit.com/r/django/comments/1g0h570/digital_ocean_app_platform_spaces](https://www.reddit.com/r/django/comments/1g0h570/digital_ocean_app_platform_spaces)
 - RSS feed: $source
 - date published: 2024-10-10T12:01:23+00:00

<!-- SC_OFF --><div class="md"><p>I am having a really tough time getting spaces working with digital ocean app platform. I am following <a href="https://testdriven.io/blog/django-digitalocean-spaces/">https://testdriven.io/blog/django-digitalocean-spaces/</a> and keep getting </p> <p>&quot;django.core.exceptions.ImproperlyConfigured: You&#39;re using the staticfiles app without having set the STATIC_ROOT setting to a filesystem path.&quot;</p> <p>I don&#39;t understand why this is happening, please help. I must be missing something here. </p> <p>My settings look like this, which is right from the tutorial:</p> <pre><code>if USE_SPACES: # settings AWS_ACCESS_KEY_ID = &#39;my info&#39; AWS_SECRET_ACCESS_KEY = &#39;my info&#39; AWS_STORAGE_BUCKET_NAME = &#39;my info&#39; AWS_DEFAULT_ACL = &#39;public-read&#39; AWS_S3_ENDPOINT_URL = &#39;https://nyc3.digitaloceanspaces.com&#39; AWS_S3_OBJECT_PARAMETERS = {&#39;CacheControl&#39;: &#39;max-age=86400&#39;} # static settings AWS_LOCATION = &

## How do I make a number column that automatically increases but only for a group of three column?
 - [https://www.reddit.com/r/django/comments/1g0gjp8/how_do_i_make_a_number_column_that_automatically](https://www.reddit.com/r/django/comments/1g0gjp8/how_do_i_make_a_number_column_that_automatically)
 - RSS feed: $source
 - date published: 2024-10-10T11:25:03+00:00

<!-- SC_OFF --><div class="md"><p>The model:</p> <pre><code>class Bunny(models.Model): l_ear = models.CharField(max_length=10) r_ear = models.CharField(max_length=10) sex = models.CharField(max_length=1, choices=[(&#39;M&#39;, &#39;Male&#39;), (&#39;F&#39;, &#39;Female&#39;)]) tattooed_on = models.DateTimeField(null=True) CID = models.ForeignKey(Club, on_delete=models.PROTECT) UID_owner = models.ForeignKey(&quot;auth_service.User&quot;, on_delete=models.PROTECT) TID = models.ForeignKey(&quot;coverslip.Throw&quot;, on_delete=models.PROTECT, null=True, blank=True ) RID = models.ForeignKey(&quot;bunnies.Race&quot;, on_delete=models.PROTECT) COLID = models.ForeignKey(&quot;bunnies.Color&quot;, on_delete=models.PROTECT, null=True) UID_tattoo_master = models.ForeignKey(&quot;auth_service.User&quot;, on_delete=models.PROTECT, related_name=&#39;tattooed_bunnies&#39;) serial_number = models.PositiveIntegerField(null=True, blank=True) def __str__(self): return self.l_ear + &quot; / &quot; + sel

## Nginx 404'ing all images.
 - [https://www.reddit.com/r/django/comments/1g0cvxr/nginx_404ing_all_images](https://www.reddit.com/r/django/comments/1g0cvxr/nginx_404ing_all_images)
 - RSS feed: $source
 - date published: 2024-10-10T06:51:54+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not sure if this should be in the nginx or Django Reddit, but I&#39;ll try here first. My blog is running on Docker. Initially, all images in the static files from the first set of articles I created while coding the blog were accessible to nginx. However, when I tried adding articles from the admin panel after deployment, the new images returned a 404 error. I tried debugging by checking my code and realized I didn&#39;t include a path for the media folder in the <a href="http://settings.py"><code>settings.py</code></a> file. After adding that line and rebuilding the container... well, now the previously accessible images are returning a 404. I think my nginx server might not be configured correctly. *I&#39;ve entered the container and verified that files are present*</p> <p>Dockerfile: </p> <h1>Use the official Python image from the Docker Hub</h1> <p>FROM python:3.11</p> <h1>Set environment variables</h1> <p>ENV PYTHONDONTWRITEBYTECODE=1</p

## Kpis con endpoints en django
 - [https://www.reddit.com/r/django/comments/1g0bqzo/kpis_con_endpoints_en_django](https://www.reddit.com/r/django/comments/1g0bqzo/kpis_con_endpoints_en_django)
 - RSS feed: $source
 - date published: 2024-10-10T05:28:22+00:00

<!-- SC_OFF --><div class="md"><p>holahola, ¿alguna vez alguien ha hecho un kpi mandando a llamar endpoints? actualmente estoy en django, y tengo dos filtros en mi pag inicial, eso se los mando a mi endpoint y me genera mi dato (ya probe en postman los get y funcionan), pero, al querer visualizarlo en mi kpi no se actualiza y siempre queda en 0</p> <p>por cierto, apenas inicie con django entonces, todo lo que hago es recreacion de videos o de documentación que encuentro </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jes-wo"> /u/jes-wo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g0bqzo/kpis_con_endpoints_en_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g0bqzo/kpis_con_endpoints_en_django/">[comments]</a></span>

