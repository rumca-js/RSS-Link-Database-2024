# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Advice Needed: Best Technology & Database for a 24/7 User Notification Script in Django/React App
 - [https://www.reddit.com/r/django/comments/1gpxofj/advice_needed_best_technology_database_for_a_247](https://www.reddit.com/r/django/comments/1gpxofj/advice_needed_best_technology_database_for_a_247)
 - RSS feed: $source
 - date published: 2024-11-12T22:38:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m a self-taught developer working on a Django + React project, and I could really use some guidance to make sure I’m building this the right way. I need to build a Python script that continuously (24/7) manages and interacts with users. The main function of this script is to send SMS and email notifications to users at regular intervals, based on the specific timing each user has set (like every 4, 8, or 15 minutes). Here’s a quick overview of what I need:<br/> (The project currently uses Django for the backend and React for the frontend.)</p> <ul> <li><strong>Continuous Operation</strong>: The script should run non-stop, handling existing users as well as any new ones who subscribe at any time of the day or night.</li> <li><strong>Dynamic Handling of New Users</strong>: Whenever a new user subscribes, they should be incorporated into the notification schedule immediately, so if a user signs up at 20:00 and has a notification fr

## How to move images from one ImageField to another?
 - [https://www.reddit.com/r/django/comments/1gpvp52/how_to_move_images_from_one_imagefield_to_another](https://www.reddit.com/r/django/comments/1gpvp52/how_to_move_images_from_one_imagefield_to_another)
 - RSS feed: $source
 - date published: 2024-11-12T21:14:29+00:00

<!-- SC_OFF --><div class="md"><p>Here&#39;s the problem:</p> <p>I have a User model, that accepts 3 images (img_one, img_two, and img_three).</p> <p>Then I have a view, that lets me delete an image, and then &quot;rebalance them&quot;. For example if I have 3 images, and delete the second one, the img_three data should move to img_two.</p> <p>And I can&#39;t seem to figure out how to do this &quot;rebalancing part&quot; correctly.</p> <p>Here&#39;s the code for views.py:</p> <pre><code>@login_required def img_delete_action(request, img_id): if request.method == &#39;POST&#39;: if img_id == 1 and request.user.img_one: request.user.img_one.delete() elif img_id == 2 and request.user.img_two: request.user.img_two.delete() elif img_id == 3 and request.user.img_three: request.user.img_three.delete() else: return render(request, &quot;components/user-images.html&quot;) img_list = [request.user.img_one, request.user.img_two, request.user.img_three] rebalanced_list = [] for img in img_list: 

## Drop Down to Abstract Object List
 - [https://www.reddit.com/r/django/comments/1gpokx1/drop_down_to_abstract_object_list](https://www.reddit.com/r/django/comments/1gpokx1/drop_down_to_abstract_object_list)
 - RSS feed: $source
 - date published: 2024-11-12T16:23:38+00:00

<!-- SC_OFF --><div class="md"><p>I have a situation and would like some advice. I am writing a backend that downloads CSV files from different sources. Once they are downloaded, the data will be transformed into our database format. On the &quot;DataWrangler&quot; (does the mappings + Transformations), i want to add a dropdown (link) to a Connection, it could be FTP, HTTP, etc. For the life of me, i cannot figure out, how to create a dropdown that shows the possible connection types. More importantly, I want the models to be linked in django, so that i can call the methods of the associated models. Here is a &quot;summary&quot; of my models at present. I have played a bit with polymorphism but just cannot figure it out. </p> <pre><code>class ConnectionBase(models.Model,): name = models.CharField(max_length=256) … @abstractmethod def test(self): … @abstractmethod def get_file(self): … class Meta: abstract = True class ConnectionFTP(ConnectionBase): … class ConnectionHTTP(ConnectionBa

## Django admin style
 - [https://www.reddit.com/r/django/comments/1gpjwr6/django_admin_style](https://www.reddit.com/r/django/comments/1gpjwr6/django_admin_style)
 - RSS feed: $source
 - date published: 2024-11-12T12:46:40+00:00

<!-- SC_OFF --><div class="md"><p>How do you maintain the looks of Django admin when deploying a project on a server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/blobukubimbi"> /u/blobukubimbi </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gpjwr6/django_admin_style/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gpjwr6/django_admin_style/">[comments]</a></span>

## Django Monolith or Backend w/ DRF
 - [https://www.reddit.com/r/django/comments/1gpjhbw/django_monolith_or_backend_w_drf](https://www.reddit.com/r/django/comments/1gpjhbw/django_monolith_or_backend_w_drf)
 - RSS feed: $source
 - date published: 2024-11-12T12:22:51+00:00

<!-- SC_OFF --><div class="md"><p>In your industry facing projects or workplace, in which cases you have used Django monolith (templates for frontend) and in which cases you have used Django for backend only (used drf/ninja for api building) with a React/Vue framework for frontend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Responsible-Prize848"> /u/Responsible-Prize848 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gpjhbw/django_monolith_or_backend_w_drf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gpjhbw/django_monolith_or_backend_w_drf/">[comments]</a></span>

## Is uploading a file into an async view blocking?
 - [https://www.reddit.com/r/django/comments/1gpf0zf/is_uploading_a_file_into_an_async_view_blocking](https://www.reddit.com/r/django/comments/1gpf0zf/is_uploading_a_file_into_an_async_view_blocking)
 - RSS feed: $source
 - date published: 2024-11-12T07:01:33+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://docs.djangoproject.com/en/5.1/ref/files/uploads/#django.core.files.uploadedfile.UploadedFile.read">https://docs.djangoproject.com/en/5.1/ref/files/uploads/#django.core.files.uploadedfile.UploadedFile.read</a></p> <p>If we read from this file in an async django view, will it cause the whole server to block? Would it be better to wrap this with asgiref.sync_to_async?</p> <p>I guess it might also depend on whether the file crosses the threshold to end up being written to disk:<br/> <a href="https://docs.djangoproject.com/en/5.1/topics/http/file-uploads/#where-uploaded-data-is-stored">https://docs.djangoproject.com/en/5.1/topics/http/file-uploads/#where-uploaded-data-is-stored</a></p> <p>From what I understand, file io cannot be async in python currently unless we use aiofiles library.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jpkappa"> /u/jpkappa </a> <br/> <span><a href="https://www.reddit.c

## Usecases for NoSQL DB for your Django App
 - [https://www.reddit.com/r/django/comments/1gpd6bk/usecases_for_nosql_db_for_your_django_app](https://www.reddit.com/r/django/comments/1gpd6bk/usecases_for_nosql_db_for_your_django_app)
 - RSS feed: $source
 - date published: 2024-11-12T05:01:01+00:00

<!-- SC_OFF --><div class="md"><p>As Django/Python developers, in your companies, in which use cases have you used NoSQL DB like MongoDB with your Django backend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Responsible-Prize848"> /u/Responsible-Prize848 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gpd6bk/usecases_for_nosql_db_for_your_django_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gpd6bk/usecases_for_nosql_db_for_your_django_app/">[comments]</a></span>

## How are you guys managing packages and requirements
 - [https://www.reddit.com/r/django/comments/1gpc7je/how_are_you_guys_managing_packages_and](https://www.reddit.com/r/django/comments/1gpc7je/how_are_you_guys_managing_packages_and)
 - RSS feed: $source
 - date published: 2024-11-12T04:06:19+00:00

<!-- SC_OFF --><div class="md"><p>I recently worked on a node.js based backend , and I found out npm install and the node module add a new package as soon as you install in it.</p> <p>But for django backend you need to add the newly installed package to the requirements.txt , and if you forgot to add that tht become a disaster in the prod. (when you use a virual env by python3 -m venv virtual-env-name</p> <p>I read about poetry and poetry lock , which created a virtual env also addd every newly installed packge to poetry lock , which can be converted into a requirements.txt (derivable) in one line ...and this feature can be used in docker </p> <p><code>poetry export --without-hashes --format=requirements.txt &gt; requirements.txt</code></p> <p>So what are you guys do for virtual env and package management ??<br/> any opinion ?</p> <blockquote> <p>Note - I use Docker and docker-compose a lot.</p> </blockquote> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.c

## Impressed by Django
 - [https://www.reddit.com/r/django/comments/1gp90la/impressed_by_django](https://www.reddit.com/r/django/comments/1gp90la/impressed_by_django)
 - RSS feed: $source
 - date published: 2024-11-12T01:21:36+00:00

<!-- SC_OFF --><div class="md"><p>Working in big tech and using Java, Django is a fresh breath of air. What are your favorite features of Django? I’m currently really liking Django Admin. I like the batteries included approach. I’m also glad to be out of pom.xml hell. While virtual environments are a bit annoying it’s overall easier to grok what’s going on with Python. I’m also impressed by Bulma. I like that I don’t have to use JavaScript to build a functioning UI. Something I still get a bit confused about is how to separate things out into apps. It’s tempting to just keep everything in one app as one big monolith. I think I’ll get better at that when I am more experienced with Django.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/notdemiurge"> /u/notdemiurge </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gp90la/impressed_by_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gp90la/

