# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Force created_at and updated_at to be identical at creation?
 - [https://www.reddit.com/r/django/comments/1fyhpgk/force_created_at_and_updated_at_to_be_identical](https://www.reddit.com/r/django/comments/1fyhpgk/force_created_at_and_updated_at_to_be_identical)
 - RSS feed: $source
 - date published: 2024-10-07T20:27:26+00:00

<!-- SC_OFF --><div class="md"><p>How do I force the two fields to have an identical value when they&#39;re created? Using an <code>update_or_create</code> flow to track if something has ever changed on the row doesn&#39;t work because the microseconds in the database are different.</p> <pre><code>created_at = models.DateTimeField(auto_now_add=True) updated_at = models.DateTimeField(auto_now_add=True) </code></pre> <p>looks like this,</p> <pre><code>2024-10-07 20:23:42.180869 +00:00,2024-10-07 20:23:42.180880 +00:00 2024-10-07 20:23:42.203034 +00:00,2024-10-07 20:23:42.203040 +00:00 2024-10-07 20:23:42.225138 +00:00,2024-10-07 20:23:42.225143 +00:00 2024-10-07 20:23:42.244299 +00:00,2024-10-07 20:23:42.244305 +00:00 2024-10-07 20:23:42.256635 +00:00,2024-10-07 20:23:42.256640 +00:00 </code></pre> <p>The idea is to be able to get everything that changed.</p> <pre><code>return cls.objects.filter(**kwargs).exclude(created_at=models.F(&#39;updated_at&#39;)) </code></pre> <p>Maybe there&#3

## I’m free for 4 weeks and looking for small projects.
 - [https://www.reddit.com/r/django/comments/1fyh19h/im_free_for_4_weeks_and_looking_for_small_projects](https://www.reddit.com/r/django/comments/1fyh19h/im_free_for_4_weeks_and_looking_for_small_projects)
 - RSS feed: $source
 - date published: 2024-10-07T19:59:57+00:00

<!-- SC_OFF --><div class="md"><p>I’m an experienced Django developer and I’m on the hunt for a small project to tackle over the next 4 to 6 weeks. If you have a cool idea or need help with a web app, I’d love to collaborate! </p> <p>Here’s what I can do:</p> <p>Build RESTful APIs Create custom web applications Integrate third-party services (think payments, auth, etc.) Design efficient databases Handle deployment to platforms like AWS , digitalocean Why work with me? I’ve got solid experience, a collaborative mindset, and I love solving problems! Let’s make something awesome together! </p> <p>If you’re interested, drop me a message.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cryptolii"> /u/cryptolii </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fyh19h/im_free_for_4_weeks_and_looking_for_small_projects/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fyh19h/im_free_for_4_weeks_and_looki

## Repetetive projects. Should we even bother?
 - [https://www.reddit.com/r/django/comments/1fyfqsb/repetetive_projects_should_we_even_bother](https://www.reddit.com/r/django/comments/1fyfqsb/repetetive_projects_should_we_even_bother)
 - RSS feed: $source
 - date published: 2024-10-07T19:06:30+00:00

<!-- SC_OFF --><div class="md"><p><strong>Hello Django Community,</strong></p> <p>Let me get right to it.</p> <p>There are a lot of recurring project types out there - portfolios, eCommerce platforms, learning platforms, blogs, reservation systems, etc.</p> <p>Say I wanted to build one of these professionally, working solo, and without any custom requirements. While I do have some experience with Django, I often think about the time investment, especially in development, testing and maintenance. Given this, I’m starting to wonder if WordPress might actually be a faster option - even if I&#39;d have to learn it from scratch.</p> <p>So, here’s my question: <strong>Is it worth investing time into Django for these types of repetitive projects, or would it make more sense to go straight into WordPress for quicker development?</strong> At what point (if any) does Django pay off in terms of efficiency and maintainability?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www

## Custom User password not hashing in DRF
 - [https://www.reddit.com/r/django/comments/1fyfpba/custom_user_password_not_hashing_in_drf](https://www.reddit.com/r/django/comments/1fyfpba/custom_user_password_not_hashing_in_drf)
 - RSS feed: $source
 - date published: 2024-10-07T19:04:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks, need some help so I modified the inbuild user and created a custom user &amp; manager, but now password is not getting hashed although I used set_password method on user in my custom manager (password is hashed when creating superuser) Because of this <code>rest_framework_simplejwt</code> is giving <code>No active account found with the given credentials</code> when trying to get token. (that&#39;s my assumption as superuser token are getting return like normal)</p> <p>```python</p> <h1>models.py</h1> <p>class UserManager(BaseUserManager): def _create_user(self, email, password=None, *<em>extra_fields): if not email: raise ValueError(&quot;Email field must be set&quot;) email = self.normalize_email(email) user = self.model(email=email, *</em>extra_fields) user.set_password(password) user.save(using=self._db) return user</p> <pre><code>def create_user(self, email, password=None, **extra_fields): extra_fields.setdefault(&quot;is_superuser&quo

## do ALL front-end frameworks work with Python/Django framework as a backend?
 - [https://www.reddit.com/r/django/comments/1fyd8ct/do_all_frontend_frameworks_work_with_pythondjango](https://www.reddit.com/r/django/comments/1fyd8ct/do_all_frontend_frameworks_work_with_pythondjango)
 - RSS feed: $source
 - date published: 2024-10-07T17:23:35+00:00

<!-- SC_OFF --><div class="md"><p>If i use django/python to build an API, can i use it with ANY frontend framework? what are the best ones to use for mobile app dev?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fyd8ct/do_all_frontend_frameworks_work_with_pythondjango/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fyd8ct/do_all_frontend_frameworks_work_with_pythondjango/">[comments]</a></span>

## Django and React without REST
 - [https://www.reddit.com/r/django/comments/1fycc6a/django_and_react_without_rest](https://www.reddit.com/r/django/comments/1fycc6a/django_and_react_without_rest)
 - RSS feed: $source
 - date published: 2024-10-07T16:46:55+00:00

<!-- SC_OFF --><div class="md"><p>There is this <a href="https://ilikerobots.medium.com/django-vue-vite-rest-not-required-ca63cfa558fd">article</a> and <a href="https://2023.djangocon.us/talks/vue-django-combining-django-templates-and-vue-single-file-components-without-compromise/">video</a> about implementing Vue.JS without DRF/REST. How do this similar thing with React? </p> <p>I did see <a href="https://www.reactivated.io/">reactivated</a>, I think it&#39;s unnecessarily complicates by running a request proxy to node.js. I am looking for something simpler as hinted in the article . </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/supercharger6"> /u/supercharger6 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fycc6a/django_and_react_without_rest/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fycc6a/django_and_react_without_rest/">[comments]</a></span>

## Django Rest API Help
 - [https://www.reddit.com/r/django/comments/1fybfp3/django_rest_api_help](https://www.reddit.com/r/django/comments/1fybfp3/django_rest_api_help)
 - RSS feed: $source
 - date published: 2024-10-07T16:09:32+00:00

<!-- SC_OFF --><div class="md"><p>I was wondering if anyone is able to help me with an issue that I am facing with the Django Rest framework.</p> <p>The issue that I’m having is that my PostgreSQL database is not working correctly. More specifically, when I am attempting to select an object with a matching parameter it is not pulling anything from the database. I have verified that there is a valid connection and that there is data in the database but when I print the data from a ‘data = Object.get.all()’ it is empty. I’m not sure if i am missing a step or something because this is my first time making a Rest API but not my first time bring Django or PostgreSQL. Also, I have been doing the migrations.</p> <p>As a work around I am manually making the objects with a script but I would rather skip this. Also, when i do a ‘python3 manage.py inspectdb &gt; models.py’ it is missing a column that is present in my database table. The column is a generic integer column with no other restraints

## Migrations in production: client says it needs to be done with SQL
 - [https://www.reddit.com/r/django/comments/1fy94xu/migrations_in_production_client_says_it_needs_to](https://www.reddit.com/r/django/comments/1fy94xu/migrations_in_production_client_says_it_needs_to)
 - RSS feed: $source
 - date published: 2024-10-07T14:34:52+00:00

<!-- SC_OFF --><div class="md"><p>I thought it was a good idea calling the migrate on the initialization of the django application, but client requires that for every change on the database I need to send the necessary SQL queries. So I&#39;ve been using a script with <a href="https://docs.djangoproject.com/en/5.1/ref/django-admin/#django-admin-sqlmigrate"><code>sqlmigrate</code></a> to generate all the required sql. He says it&#39;s important to decouple database migrations from application initialization.</p> <p>I&#39;d appreciate some enlightenment on this topic. The reasons why it&#39;s important. So is the migrate command only good practice for development enviroment?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PurpleEnough9786"> /u/PurpleEnough9786 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fy94xu/migrations_in_production_client_says_it_needs_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/d

## How to find remote world wide jobs?
 - [https://www.reddit.com/r/django/comments/1fy7jhf/how_to_find_remote_world_wide_jobs](https://www.reddit.com/r/django/comments/1fy7jhf/how_to_find_remote_world_wide_jobs)
 - RSS feed: $source
 - date published: 2024-10-07T13:24:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently working at a small company in my hometown. Python and especially django are not common here. Where I&#39;m working modern technologies like microservices architecture, Test-Driven Development (TDD), or cutting-edge tools aren&#39;t used. I&#39;m eager to work on high-load projects. Additionally, I&#39;m looking for opportunities with a higher salary. Are there any other platforms besides Upwork where I can find worldwide remote jobs or roles that offer relocation?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_justaverageuser"> /u/_justaverageuser </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fy7jhf/how_to_find_remote_world_wide_jobs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fy7jhf/how_to_find_remote_world_wide_jobs/">[comments]</a></span>

## a way to open a folder, o an excel from web?
 - [https://www.reddit.com/r/django/comments/1fy7d4q/a_way_to_open_a_folder_o_an_excel_from_web](https://www.reddit.com/r/django/comments/1fy7d4q/a_way_to_open_a_folder_o_an_excel_from_web)
 - RSS feed: $source
 - date published: 2024-10-07T13:16:30+00:00

<!-- SC_OFF --><div class="md"><p>hi guys my boss is telling me to make a website where the workers could open local excel from a button, the excels are in a shared drive im triying to make it but i have no idea, he is telling, he had watched before from a engineer with <a href="http://asp.net">asp.net</a> so he is insisting with that, anyone knows how to?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kekkochu"> /u/Kekkochu </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fy7d4q/a_way_to_open_a_folder_o_an_excel_from_web/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fy7d4q/a_way_to_open_a_folder_o_an_excel_from_web/">[comments]</a></span>

## Built an AI Engineer to Help with Django – Try it Out!
 - [https://www.reddit.com/r/django/comments/1fy3ss4/built_an_ai_engineer_to_help_with_django_try_it](https://www.reddit.com/r/django/comments/1fy3ss4/built_an_ai_engineer_to_help_with_django_try_it)
 - RSS feed: $source
 - date published: 2024-10-07T09:45:24+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/Django">r/Django</a>,<br/> I’ve been building an <a href="http://chat.remedee.ai">AI engineer</a> designed to help with Django coding. It’s connected to the codebase, so you can ask technical questions and get help with issues. It’s not just an LLM, but an agent that thinks through your questions and steps to resolve them.</p> <p>As a fellow Django dev, I know how frustrating it is to sift through documentation, log files and forums to find answers. I trained it on the Django open-source repo, so whether you’re exploring features, checking issues, or troubleshooting your code, Remedee is ready to go.<br/> <strong>Try it here:</strong> <a href="http://chat.remedee.ai/">chat.remedee.ai</a><br/> I’d love your feedback – let me know what you think!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/remedee4bugs"> /u/remedee4bugs </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fy3ss4/b

## Oh wow, you built us an admin interface too?
 - [https://www.reddit.com/r/django/comments/1fxzud1/oh_wow_you_built_us_an_admin_interface_too](https://www.reddit.com/r/django/comments/1fxzud1/oh_wow_you_built_us_an_admin_interface_too)
 - RSS feed: $source
 - date published: 2024-10-07T04:51:37+00:00

<!-- SC_OFF --><div class="md"><p>Umm, yes. Yes, I did.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Away_Garbage_8942"> /u/Away_Garbage_8942 </a> <br/> <span><a href="https://i.redd.it/q0o1kj5yl9td1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fxzud1/oh_wow_you_built_us_an_admin_interface_too/">[comments]</a></span>

