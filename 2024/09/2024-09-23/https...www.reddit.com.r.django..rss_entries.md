# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Prevent DRF API from being accessed directly through browser?
 - [https://www.reddit.com/r/django/comments/1fnuwv5/prevent_drf_api_from_being_accessed_directly](https://www.reddit.com/r/django/comments/1fnuwv5/prevent_drf_api_from_being_accessed_directly)
 - RSS feed: $source
 - date published: 2024-09-23T20:44:35+00:00

<!-- SC_OFF --><div class="md"><p>Maybe this is a bit odd, but right now my API endpoints can be easily accessed if someone opens the endpoint directly through the browser.</p> <p>I was wondering if it would be possible to set up Django to only respond if the request comes from the frontend. Using authentication wouldn&#39;t work as most of our users do not login or create an account.</p> <p>I thought that CORS would solve this issue but doesn&#39;t prevent the API from being accessed directly through the browser.</p> <p>Has anyone implemented something to solve this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adrenaline681"> /u/adrenaline681 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fnuwv5/prevent_drf_api_from_being_accessed_directly/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fnuwv5/prevent_drf_api_from_being_accessed_directly/">[comments]</a></span>

## Two apps - Three "types" of views (one per app and one as a merge of the two apps)
 - [https://www.reddit.com/r/django/comments/1fntsof/two_apps_three_types_of_views_one_per_app_and_one](https://www.reddit.com/r/django/comments/1fntsof/two_apps_three_types_of_views_one_per_app_and_one)
 - RSS feed: $source
 - date published: 2024-09-23T19:57:58+00:00

<!-- SC_OFF --><div class="md"><p>Hello fellows,</p> <p>I&#39;ve been thinking about how to handle the following situation in my Django project. I have two separate apps, each with its own models and views. For example, one app is designed to capture data from a specific type of device (such as batteries), while the other app captures data from a different type of device (such as suspension). So far, each app works well independently with its own views and functionality. </p> <p>However, the challenge arises when I need to create templates or views that need to import data into the tables from both apps simultaneously. I&#39;m unsure which approach would avoid potential issues in the future. I anticipate more cases like this, where there will be a &quot;composite&quot; nature of data handling across apps, alongside their isolated functionality.</p> <p>Any suggestion or material to read about would be of help.</p> <p>This is a work-tree that i am reasoning about. Notice how the composi

## Looking for Beta Testers: Help Me Shape Djangoly, A Tool for Django Perfectionists
 - [https://www.reddit.com/r/django/comments/1fnqwwx/looking_for_beta_testers_help_me_shape_djangoly_a](https://www.reddit.com/r/django/comments/1fnqwwx/looking_for_beta_testers_help_me_shape_djangoly_a)
 - RSS feed: $source
 - date published: 2024-09-23T17:59:44+00:00

<!-- SC_OFF --><div class="md"><p>Howdy everyone 👋, Tristan here. Over the past three years, I&#39;ve been working on various Django projects and noticed a pattern—no matter how experienced you are, code reviews tend to surface the same types of issues. You know the drill: variables with unclear names, unhandled exceptions, potential security flaws, and of course, views that get way too large and hard to maintain.</p> <p>After going through countless reviews filled with nitpicks (and delivering my fair share), I started thinking, <em>What if we could catch these problems in real-time, as we code?</em> Instead of waiting for a PR to reveal these issues, wouldn’t it be great if there was a tool that enforced best practices and conventions, saving time and keeping code quality high from the start?</p> <p>That&#39;s why I built <em>Djangoly</em>, a VS Code extension designed to help Django developers catch and resolve annoying issues in real time, before code even gets to the review stage

## My first ever Django View, and I am not even able to get past the 404.
 - [https://www.reddit.com/r/django/comments/1fnqqav/my_first_ever_django_view_and_i_am_not_even_able](https://www.reddit.com/r/django/comments/1fnqqav/my_first_ever_django_view_and_i_am_not_even_able)
 - RSS feed: $source
 - date published: 2024-09-23T17:52:16+00:00

<!-- SC_OFF --><div class="md"><p>Started learning Django 2 days ago with this course: <a href="https://www.udemy.com/share/1021t23@5KlE1UydzPZBz87JqRHlKj-isi55FgM3risKngYrGvXEPING5UDzcr70F9zpTXdjVw==/">https://www.udemy.com/share/1021t23@5KlE1UydzPZBz87JqRHlKj-isi55FgM3risKngYrGvXEPING5UDzcr70F9zpTXdjVw==/</a> Created a project called mainsite. Wrote the code for an app view and it&#39;s respective urlpatterns. I have rewrote the same code for about 30 times now, but I am still getting an Error 404 message on my local server. Can somebody please guide me?</p> <p>Image1: The &#39;mainsite&#39; project url code. Image2: View for the app(named &#39;food&#39;) code. Image3: The &#39;food&#39; app url code. Image4: The Error404 message.</p> <p>I would be highly obliged if someone would help me. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Beer_Triceps"> /u/Beer_Triceps </a> <br/> <span><a href="https://www.reddit.com/gallery/1fnqqav">[link]</a></

## In admin panel how to display aggregate values below change list table of models.
 - [https://www.reddit.com/r/django/comments/1fno2ay/in_admin_panel_how_to_display_aggregate_values](https://www.reddit.com/r/django/comments/1fno2ay/in_admin_panel_how_to_display_aggregate_values)
 - RSS feed: $source
 - date published: 2024-09-23T16:02:57+00:00

<!-- SC_OFF --><div class="md"><p>FYI, I&#39;m using django-unfold, but I can&#39;t seem to find a way to display aggregate values like in Order model there&#39;ll be amount field, and I want to display total amount sum of all the orders just below the change list table of Order model, and it should update total amount sum if data filtered.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Profile-Complex"> /u/Profile-Complex </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fno2ay/in_admin_panel_how_to_display_aggregate_values/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fno2ay/in_admin_panel_how_to_display_aggregate_values/">[comments]</a></span>

## Simplify OAuth2 token capture in your Django apps without the overhead of django-allauth.
 - [https://www.reddit.com/r/django/comments/1fnn6nl/simplify_oauth2_token_capture_in_your_django_apps](https://www.reddit.com/r/django/comments/1fnn6nl/simplify_oauth2_token_capture_in_your_django_apps)
 - RSS feed: $source
 - date published: 2024-09-23T15:27:13+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m glad to share <code>django-oauth2-capture</code>, a Django package designed to simplify the process of capturing OAuth2 tokens for non-login purposes.</p> <p><strong>Why did I create this?</strong></p> <p>While working on projects that require acting on behalf of users on external platforms like GitHub, LinkedIn, and X (Twitter), I found that existing solutions like <code>django-allauth</code> weren’t suitable. <code>django-allauth</code> is fantastic for authentication and user management, but using it solely for token capture without user authentication feels like working against the grain of both the framework and the package. It introduces unnecessary complexity when you just need to obtain an OAuth2 token.</p> <p><strong>What does</strong> <code>django-oauth2-capture</code> <strong>offer?</strong></p> <p>By removing unnecessary abstractions, the complexity of handling OAuth2 melts away into <strong>three important flows</

## Is there a way to pause all celery tasks for a while?
 - [https://www.reddit.com/r/django/comments/1fnl32c/is_there_a_way_to_pause_all_celery_tasks_for_a](https://www.reddit.com/r/django/comments/1fnl32c/is_there_a_way_to_pause_all_celery_tasks_for_a)
 - RSS feed: $source
 - date published: 2024-09-23T13:57:57+00:00

<!-- SC_OFF --><div class="md"><p>I have a list of tasks that ping an external API that has some rate limits. Is there a way that I can pause all the celery tasks for 30 secs before resuming?</p> <p>If I set a simple timer.sleep(30) would it keep the worker busy for 30 secs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Able-Match8791"> /u/Able-Match8791 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fnl32c/is_there_a_way_to_pause_all_celery_tasks_for_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fnl32c/is_there_a_way_to_pause_all_celery_tasks_for_a/">[comments]</a></span>

## Need help in login view
 - [https://www.reddit.com/r/django/comments/1fnktri/need_help_in_login_view](https://www.reddit.com/r/django/comments/1fnktri/need_help_in_login_view)
 - RSS feed: $source
 - date published: 2024-09-23T13:46:10+00:00

<!-- SC_OFF --><div class="md"><p>Newbie Here!<br/> So im working on a custom login view, it contains 2FA and email verification </p> <p>in the case if a user created an account and didnt activate it via email, when he tries to connect the response is &quot;invalid credentials&quot; where it has to be &quot;Your account is inactive. Please contact support or activate your account.&quot;, after digging i figuered that authenticate return none by default if user.is_active=False</p> <pre><code>LoginSerializer(serializers.Serializer): username = serializers.CharField() password = serializers.CharField(write_only=True) otp = serializers.CharField(required=False) def validate(self, data): username = data.get(&#39;username&#39;) password = data.get(&#39;password&#39;) if username and password: user = authenticate(username=username, password=password) print(user) if user: if not user.is_active: raise serializers.ValidationError(&quot;Your account is inactive. Please contact support or activat

## Help me out! I'm a beginner.
 - [https://www.reddit.com/r/django/comments/1fnimmn/help_me_out_im_a_beginner](https://www.reddit.com/r/django/comments/1fnimmn/help_me_out_im_a_beginner)
 - RSS feed: $source
 - date published: 2024-09-23T11:57:59+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to make my project idea come to life but I lack the technical knowledge required for it. My project requires me to create a website, that too &#39;community like&#39; with no vast features but different users being able to register and post their content (mostly text based) for others to see and comment out their views/queries. This website is supposed to be a wikipedia -type website but with the additional features that i mentioned above; </p> <p>Since I&#39;m very new to programming, I am preferring Python(django) for Backend development. Please tell me what all i need to learn and do. I&#39;ll be super thankful to you !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/arincroxx"> /u/arincroxx </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fnimmn/help_me_out_im_a_beginner/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fnimmn/help_me_out_im_a

## PyCharm & Django Campaign 2024 - encore
 - [https://www.reddit.com/r/django/comments/1fniijx/pycharm_django_campaign_2024_encore](https://www.reddit.com/r/django/comments/1fniijx/pycharm_django_campaign_2024_encore)
 - RSS feed: $source
 - date published: 2024-09-23T11:51:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2024/sep/23/pycharm-django-campaign-2024-encore/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fniijx/pycharm_django_campaign_2024_encore/">[comments]</a></span>

## What is the django equivalent of input Models in endpoints in aspnet or SpringBoot?
 - [https://www.reddit.com/r/django/comments/1fnh5cr/what_is_the_django_equivalent_of_input_models_in](https://www.reddit.com/r/django/comments/1fnh5cr/what_is_the_django_equivalent_of_input_models_in)
 - RSS feed: $source
 - date published: 2024-09-23T10:24:39+00:00

<!-- SC_OFF --><div class="md"><p>We&#39;re a group of 4 people learning django. When talking about the differences between put and patch the question of how we would validate the json fields in the put/patch request body. In SpringBoot and aspnet you&#39;d just use models like this:</p> <p>``` @RestController @RequestMapping(&quot;/api/users&quot;) public class UserController {</p> <pre><code>@Autowired private UserService userService; @PostMapping public ResponseEntity&lt;String&gt; createUser(@RequestBody User user) { String response = userService.createUser(user); return ResponseEntity.ok(response); } </code></pre> <p>} ```</p> <p>So the framework would automatically parse the json into a User object. If some fields are missing the framework raises an error and that&#39;s it.</p> <p>But since python determines variable types at runtime you can&#39;t really do that. Until now we always accessed the response data like this:</p> <p>``` def login(self): return self.client.post(&#39;/a

## Getting relative path instead of absolute in react frontend, does it have anything to do with django?
 - [https://www.reddit.com/r/django/comments/1fndl8s/getting_relative_path_instead_of_absolute_in](https://www.reddit.com/r/django/comments/1fndl8s/getting_relative_path_instead_of_absolute_in)
 - RSS feed: $source
 - date published: 2024-09-23T05:54:32+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dark_--knight"> /u/dark_--knight </a> <br/> <span><a href="/r/djangolearning/comments/1fndiss/getting_relative_path_instead_of_absolute_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fndl8s/getting_relative_path_instead_of_absolute_in/">[comments]</a></span>

## Cookiecutter-django admin dashboard is stripped away?
 - [https://www.reddit.com/r/django/comments/1fnddwi/cookiecutterdjango_admin_dashboard_is_stripped](https://www.reddit.com/r/django/comments/1fnddwi/cookiecutterdjango_admin_dashboard_is_stripped)
 - RSS feed: $source
 - date published: 2024-09-23T05:39:53+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to write a Django app using the latest <a href="https://github.com/cookiecutter/cookiecutter-django">cookiecutter-django</a> set-up and the admin dashboard looks a lot sleeker than it used to, however I don&#39;t see my models anywhere! I am also logged in as a superuser.</p> <p>I can&#39;t CRUD anything and it&#39;s a huge productivity killer.</p> <p>I can&#39;t find anyone online talking about this problem so I suspect it may be a simple fix; I&#39;m pretty sure I did all my set-up CLI config properly. ChatGPT is being useless as well..</p> <p>Like there is practically nothing and I have a bunch of models with the admin site registered in <a href="http://admin.py">admin.py</a> for the apps... I would&#39;ve expected to see the Users somewhere at a minimum as the very initial boilerplate has that all set up but nothing!</p> <p>Does anyone know what could be the issue here?</p> <p><a href="https://preview.redd.it/nuw8uvq4xhqd1.png?width=18

## Best way to learn Django admin for beginners
 - [https://www.reddit.com/r/django/comments/1fnd70e/best_way_to_learn_django_admin_for_beginners](https://www.reddit.com/r/django/comments/1fnd70e/best_way_to_learn_django_admin_for_beginners)
 - RSS feed: $source
 - date published: 2024-09-23T05:26:49+00:00

<!-- SC_OFF --><div class="md"><p>I always choose Django for my personal and freelance projects because of the Django admin and how convenient it is to get up and running. My question is what would you recommend to those who wish to learn more about how it works and how to make the most out of it? It still feels like magic to me and I wish to learn about what happens behind the scene, how to customize it and what files are relevant for tinkering with it etc…</p> <p>Yes I have checked the documentation but I fail to get a good understanding unless I build something or tinker with it. Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DoZoRaZo"> /u/DoZoRaZo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fnd70e/best_way_to_learn_django_admin_for_beginners/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fnd70e/best_way_to_learn_django_admin_for_beginners/">[comments]</a></span>

## I've just released v1.0.0 of my first Django package!
 - [https://www.reddit.com/r/django/comments/1fnc8vr/ive_just_released_v100_of_my_first_django_package](https://www.reddit.com/r/django/comments/1fnc8vr/ive_just_released_v100_of_my_first_django_package)
 - RSS feed: $source
 - date published: 2024-09-23T04:25:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! 👋 </p> <p>I&#39;ve been working with Django for the last 5 years and I&#39;ve finally released my first package! It is called <a href="https://github.com/Flexonze/django-auto-actions">django-auto-actions</a>. </p> <p>By adding it to your ModelAdmins, it will automatically generate basic Django admin actions based on your models&#39; fields. For example, if your model has a nullable <code>is_approved</code> BooleanField, it will create the following admin actions: </p> <ul> <li>Set <em>is_approved</em> to True</li> <li>Set <em>is_approved</em> to False</li> <li>Set <em>is_approved</em> to None</li> </ul> <p>Right now, it works with <strong>BooleanFields</strong>, <strong>DateTimeFields</strong>, <strong>DateField</strong> and <strong>TimeField</strong>.</p> <p>This idea came to me because of a client who kept asking me for a way to bulk update a bunch of objects. I had to create very similar admin actions for each time. I figured I&#39;d e

## Haystack and Solr
 - [https://www.reddit.com/r/django/comments/1fnaae2/haystack_and_solr](https://www.reddit.com/r/django/comments/1fnaae2/haystack_and_solr)
 - RSS feed: $source
 - date published: 2024-09-23T02:31:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys, this is just a general question, nothing specific. But I&#39;m currently building a search engine for my Django project. My question is, are there any resources where I can Haystack coupled with Solr?</p> <p>Anything would help, thank you. Please let me know if you need more details</p> <p><a href="http://company.py">company.py</a></p> <p>from django.db import models<br/> from django.conf import settings<br/> from.user import User </p> <h1>Create your models here.</h1> <p>class ArboristCompany(models.Model):<br/> user = models.OneToOneField(User, on_delete=models.CASCADE, null=True, related_name=&#39;arborist_company&#39;)<br/> arborist = models.ForeignKey(settings.AUTH_USER_MODEL, on_delete=models.CASCADE)<br/> company_name = models.CharField(max_length=30)<br/> company_logo = models.ImageField(upload_to=&#39;company_logo&#39;, blank=True) </p> <p>def __str__(self):<br/> return f&#39;{self.company_name} ArboristCompany&#39;</p> <p>```</p>

## Similarity Search in Arabic
 - [https://www.reddit.com/r/django/comments/1fn9gab/similarity_search_in_arabic](https://www.reddit.com/r/django/comments/1fn9gab/similarity_search_in_arabic)
 - RSS feed: $source
 - date published: 2024-09-23T01:46:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi All, I hope you are having a great day!<br/> I am implementing a feature where the user will be entering a name in arabic and i need to get the closest names that matches this input string. I need this to be done in arabic </p> <p>I am using postgres and django</p> <p>thanks alot!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/oelseba"> /u/oelseba </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fn9gab/similarity_search_in_arabic/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fn9gab/similarity_search_in_arabic/">[comments]</a></span>

