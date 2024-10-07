# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Help: (fields.E005) 'choices' must be an iterable containing (actual value, human readable name) tuples error
 - [https://www.reddit.com/r/django/comments/1fxsava/help_fieldse005_choices_must_be_an_iterable](https://www.reddit.com/r/django/comments/1fxsava/help_fieldse005_choices_must_be_an_iterable)
 - RSS feed: $source
 - date published: 2024-10-06T22:08:57+00:00

<!-- SC_OFF --><div class="md"><p>I created this model below and I was working fine for almost the whole week. Closed the server and restarted it again and it threw me the (fields.E005) &#39;choices&#39; must be an iterable containing (actual value, human readable name) tuples error. Used django documentation exactly, still no solution.</p> <pre><code>class Inspection(models.Model): RESULT_CHOICES = [ (&quot;PR&quot; &quot;Passed&quot;), (&quot;PR&quot; &quot;Passed with minor Defects&quot;), (&quot;PR&quot; &quot;Passed with major Defects&quot;), (&quot;FR&quot; &quot;Failed due to minor Defects&quot;), (&quot;FR&quot; &quot;Failed due to major Defects&quot;), (&quot;FR&quot; &quot;Failed&quot;), ] vin_number = models.ForeignKey(Vin, on_delete=models.CASCADE, related_name=&#39;inspections&#39;) inspection_number = models.CharField(max_length=20) year = models.CharField(max_length=4) inspection_result = models.CharField(max_length=30, choices=RESULT_CHOICES) ag_rating = models.CharFie

## Dropbox storage backend
 - [https://www.reddit.com/r/django/comments/1fxrwiv/dropbox_storage_backend](https://www.reddit.com/r/django/comments/1fxrwiv/dropbox_storage_backend)
 - RSS feed: $source
 - date published: 2024-10-06T21:50:35+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to use Dropbox as storage backend for user uploaded media files.</p> <p>I have upload working, but when I try to get the image I get a &quot;Not Found&quot; error. That might suggest that I&#39;m fairly close... propably some stupid mistake.</p> <p>Maybe someone can spot it, or think of what it might be?</p> <p>My settings.py look something like this:</p> <p>```</p> <h1>Media file storage</h1> <p>STORAGES = { &quot;default&quot;: { &quot;BACKEND&quot;: &quot;storages.backends.dropbox.DropboxStorage&quot;, &quot;OPTIONS&quot;: {}, }, &quot;staticfiles&quot;: {&quot;BACKEND&quot;: &quot;whitenoise.storage.CompressedStaticFilesStorage&quot;}, }</p> <p>DROPBOX_ROOT_PATH = &quot;/&quot; DROPBOX_OAUTH2_REFRESH_TOKEN = os.environ.get(&quot;DROPBOX_OAUTH2_REFRESH_TOKEN&quot;) DROPBOX_APP_KEY = os.environ.get(&quot;DROPBOX_APP_KEY&quot;) DROPBOX_APP_SECRET = os.environ.get(&quot;DROPBOX_APP_SECRET&quot;)</p> <h1>Media Folder Settings</h1> <p>MED

## Django admin unfold sidebar add
 - [https://www.reddit.com/r/django/comments/1fxo9bo/django_admin_unfold_sidebar_add](https://www.reddit.com/r/django/comments/1fxo9bo/django_admin_unfold_sidebar_add)
 - RSS feed: $source
 - date published: 2024-10-06T19:12:08+00:00

<!-- SC_OFF --><div class="md"><p>Sorry for what is probably an idiot question. How the hell do you add an item to the sidebar with unfold. I just want to add a link to my dashboard view so I don’t have to go to the browser bar to load it.</p> <p>On the website “it’s easy we did this all for you” and I am just not figuring out this dam easy button. It’s probably ridiculously simple but I am not getting it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LH187"> /u/LH187 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fxo9bo/django_admin_unfold_sidebar_add/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fxo9bo/django_admin_unfold_sidebar_add/">[comments]</a></span>

## Determining if model's FileField file is local to the machine or remote?
 - [https://www.reddit.com/r/django/comments/1fxkii6/determining_if_models_filefield_file_is_local_to](https://www.reddit.com/r/django/comments/1fxkii6/determining_if_models_filefield_file_is_local_to)
 - RSS feed: $source
 - date published: 2024-10-06T16:31:16+00:00

<!-- SC_OFF --><div class="md"><p>When I first receive a file, its local to the server. I have a workflow that operates on the file in a cache directory before it gets saved to the model&#39;s FileField.</p> <p>I&#39;m wanting to add S3 storage using django-storages which means the file will be stored remotely after the initial workflow finishes.</p> <p>If I need to work on the file after initially processing it, I will need the file to be local again in the cache directory.</p> <p>How can i safely determine if the file is remote or local? Like, before i actually add S3 to django, i need this to keep working in a local sense, once i add S3 I want logic that will determine the file is stored remotely and first copy it into local cache directory.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TwilightOldTimer"> /u/TwilightOldTimer </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fxkii6/determining_if_models_filefield_file_is_loc

## Modern state of the art website builder that plays well with Django
 - [https://www.reddit.com/r/django/comments/1fxkc41/modern_state_of_the_art_website_builder_that](https://www.reddit.com/r/django/comments/1fxkc41/modern_state_of_the_art_website_builder_that)
 - RSS feed: $source
 - date published: 2024-10-06T16:23:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello everybody</p> <p>For a new project of mine, I would like to combine a modern website builder such as Wix, Squarespace or Elementor with Django, HTMX &amp; Alpine. So, many content-driven pages can be quickly build in slick designs and then a few pages will be programmed in Django.</p> <p>The experience for the user needs to be seamless. </p> <p>Did anyone do this before? Does this work at all? Is wagtail an option? Are there any other options? Any advice is highly welcome. </p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zymonick"> /u/Zymonick </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fxkc41/modern_state_of_the_art_website_builder_that/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fxkc41/modern_state_of_the_art_website_builder_that/">[comments]</a></span>

## What is the best approach to avoid repetition of a try-except structure when fetching models?
 - [https://www.reddit.com/r/django/comments/1fxk9xr/what_is_the_best_approach_to_avoid_repetition_of](https://www.reddit.com/r/django/comments/1fxk9xr/what_is_the_best_approach_to_avoid_repetition_of)
 - RSS feed: $source
 - date published: 2024-10-06T16:20:57+00:00

<!-- SC_OFF --><div class="md"><p>I’m fetching data across multiple models and have the following try-exception structure repeated a lot:</p> <p>‘’’ try: model .get / .filter except Model.DoesNotExist: handle… except Model.MultipleInstancesReturned: handle… ‘’’</p> <p>Is it bad to just have this structure repeated across every model I’m querying or is there a cleaner way to generalize this without so much repetition?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ApprovedTopics"> /u/ApprovedTopics </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fxk9xr/what_is_the_best_approach_to_avoid_repetition_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fxk9xr/what_is_the_best_approach_to_avoid_repetition_of/">[comments]</a></span>

## Looking for a Django library to attach images to comments
 - [https://www.reddit.com/r/django/comments/1fxj0tg/looking_for_a_django_library_to_attach_images_to](https://www.reddit.com/r/django/comments/1fxj0tg/looking_for_a_django_library_to_attach_images_to)
 - RSS feed: $source
 - date published: 2024-10-06T15:26:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I&#39;m currently working on a Django project, and I&#39;m looking for a library that allows users to attach images to their comments. I want something similar to how tweets work — you write your text, and there&#39;s an option to attach an image alongside it.</p> <p>Does anyone know of a library that can achieve this? Any suggestions or recommendations would be greatly appreciated!</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/takdi"> /u/takdi </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fxj0tg/looking_for_a_django_library_to_attach_images_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fxj0tg/looking_for_a_django_library_to_attach_images_to/">[comments]</a></span>

## How to flatten incoming JSON data using serializer.
 - [https://www.reddit.com/r/django/comments/1fxcay6/how_to_flatten_incoming_json_data_using_serializer](https://www.reddit.com/r/django/comments/1fxcay6/how_to_flatten_incoming_json_data_using_serializer)
 - RSS feed: $source
 - date published: 2024-10-06T08:58:17+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/m02ni37zn3td1.png?width=1085&amp;format=png&amp;auto=webp&amp;s=e8ab3481805532b4ec0960fae6b252aa3ded3e86">This is the current output of serializer data.</a></p> <p><a href="https://preview.redd.it/128kxu3lo3td1.png?width=1516&amp;format=png&amp;auto=webp&amp;s=d50745aa933f0956597e99180a639ddbd504e3aa">This is my current Serializer class.</a></p> <p><a href="https://preview.redd.it/h6mrpt2uo3td1.png?width=745&amp;format=png&amp;auto=webp&amp;s=24fbe70dcd379437b99bca1f91f09402a4099c81">i want to flatten it like this.</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/66red99"> /u/66red99 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fxcay6/how_to_flatten_incoming_json_data_using_serializer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fxcay6/how_to_flatten_incoming_json_data_using_serializer/">[comments]</a></span>

## Django Migrations dont appear in database.
 - [https://www.reddit.com/r/django/comments/1fxado3/django_migrations_dont_appear_in_database](https://www.reddit.com/r/django/comments/1fxado3/django_migrations_dont_appear_in_database)
 - RSS feed: $source
 - date published: 2024-10-06T06:34:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi, Does anyone knows how can i fix my migrations, i can see the tables created in migrations but there were no changes in my data base it doesnt create table</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Significant_Mud_206"> /u/Significant_Mud_206 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fxado3/django_migrations_dont_appear_in_database/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fxado3/django_migrations_dont_appear_in_database/">[comments]</a></span>

## Mini POS
 - [https://www.reddit.com/r/django/comments/1fx7uhe/mini_pos](https://www.reddit.com/r/django/comments/1fx7uhe/mini_pos)
 - RSS feed: $source
 - date published: 2024-10-06T03:45:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I want to do a mini POS with Django for small/mobile business like Foodtrucks. The problem is that I am just starting to learn django with DjangoGirls but I need more info, for example I dont think it is a good idea to use sqlite. Would be very appreciated if someone knows more about. </p> <p>Just a small project for uni to do in 1 month.</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ryhard51"> /u/Ryhard51 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fx7uhe/mini_pos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fx7uhe/mini_pos/">[comments]</a></span>

## How do I bring modern JavaScript features into Django?
 - [https://www.reddit.com/r/django/comments/1fx50k0/how_do_i_bring_modern_javascript_features_into](https://www.reddit.com/r/django/comments/1fx50k0/how_do_i_bring_modern_javascript_features_into)
 - RSS feed: $source
 - date published: 2024-10-06T01:01:08+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve worked a bit with SvelteKit in the past, and before that I was quite hesitant to even use a frontend framework. I&#39;d still go back to no frontend framework and just to plain old server side rendering. But my nest project idea has a bit of data wrangling that has to happen in the frontend. A few very complex forms and need some JavaScript processing. </p> <p>But for example SvelteKit somehow (I&#39;m not a JavaScript guy, no idea how it does it) activate certain JavaScript modules only on certain sites. For example I navigate to <code>/items</code> and it activates an event listener, but when I navigate to <code>/users</code> that listener is inactive. How does it to this? And how can I do the same in Django? Sure, I could just inclide JavaScript but I&#39;d like to use ESBuild and bundle it all as one file with ES6 modules.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/i_need_gpu"> /u/i_need_gpu </a

