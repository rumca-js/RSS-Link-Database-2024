# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## I Built a Tool to Save Developers Time with ChatGPT it may help you a lot
 - [https://www.reddit.com/r/django/comments/1gfvww1/i_built_a_tool_to_save_developers_time_with](https://www.reddit.com/r/django/comments/1gfvww1/i_built_a_tool_to_save_developers_time_with)
 - RSS feed: $source
 - date published: 2024-10-30T20:06:24+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 👋</p> <p>I’m a developer who relies on ChatGPT sometimes , but one issue kept bugging me: every time I started a chat, I had to upload parts of my codebase and re-explain everything. It was repetitive and slowed me down.</p> <p>That’s why I built Codura (<a href="http://codura.cc">http://codura.cc</a>). With Codura, you can simply upload your project from your desktop or clone it from GitHub, and within seconds, you can start chatting with the latest GPT model (GPT-o1, which isn’t available in regular ChatGPT). Now, instead of re-uploading and explaining, you can just type something like “Add this feature” and Codura already knows your codebase and project structure.</p> <p>One of the coolest features is that as you chat, the project structure updates dynamically on the left, so you always know where the new code belongs. (This feature is currently in early access but will be available to everyone soon.)</p> <p>You can give it a try wit

## I want to make e-commerce admin panel using Django only for backend. Can anyone suggest some packages which I try. Which is customizable. For frontend I am using react. This is one store e-commerce.
 - [https://www.reddit.com/r/django/comments/1gfu31o/i_want_to_make_ecommerce_admin_panel_using_django](https://www.reddit.com/r/django/comments/1gfu31o/i_want_to_make_ecommerce_admin_panel_using_django)
 - RSS feed: $source
 - date published: 2024-10-30T18:49:02+00:00

<!-- SC_OFF --><div class="md"><p>I want to manage all e-commerce staff from this admin panel.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rabbi50"> /u/rabbi50 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gfu31o/i_want_to_make_ecommerce_admin_panel_using_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gfu31o/i_want_to_make_ecommerce_admin_panel_using_django/">[comments]</a></span>

## Django Multiple Languages Website tip
 - [https://www.reddit.com/r/django/comments/1gfu1fk/django_multiple_languages_website_tip](https://www.reddit.com/r/django/comments/1gfu1fk/django_multiple_languages_website_tip)
 - RSS feed: $source
 - date published: 2024-10-30T18:47:07+00:00

<!-- SC_OFF --><div class="md"><p>In today’s globalized world, it is essential for web applications to support multiple languages to cater to a diverse user base. Django, a popular Python web framework, provides useful tools and features for internationalization and localization. In this tip, we will explore the various aspects of multilingual support in Django apps.</p> <p>I can&#39;t upload the image so here&#39;s the link to the tip </p> <p><a href="https://www.linkedin.com/posts/djv-mo_python-django-multilingual-activity-7257366987222212608-AU6M?utm_source=share&amp;utm_medium=member_android">link to tip</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gfu1fk/django_multiple_languages_website_tip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gfu1fk/django_multiple_languages_website_tip/">[comments]</a></span>

## Mock queryset in drf fields
 - [https://www.reddit.com/r/django/comments/1gftgil/mock_queryset_in_drf_fields](https://www.reddit.com/r/django/comments/1gftgil/mock_queryset_in_drf_fields)
 - RSS feed: $source
 - date published: 2024-10-30T18:23:07+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, </p> <p>Im running into some troubles mocking the queryset parameter for some fields/validators</p> <p>Eg:</p> <pre><code>a = serializers.CharField(required=True, source=&quot;a&quot;, validators=[UniqueValidator(queryset=A.objects.all())]) b = serializers.PrimaryKeyRelatedField(queryset=B.objects.all(), required=True, source=&quot;b&quot;) </code></pre> <p>Even though in my tests I have</p> <pre><code> @patch(&#39;myapp.models.A.objects.all&#39;, return=MockSet()) @patch(&#39;myapp.models.B.objects.all&#39;, return=MockSet()) def test_someething(self, amock, bmock): ..... </code></pre> <p>I keep getting:</p> <p><code>*** django.core.exceptions.ImproperlyConfigured: settings.DATABASES is improperly configured. Please supply the ENGINE value. Check settings documentation for more details.</code></p> <p>When I tracebacked this error, I found out that is when it tries to evaluate self.queryset in both UniqueValidator and PrimaryKeyRelate

## How do I display foreignkey as a search option in Django cms Plugin
 - [https://www.reddit.com/r/django/comments/1gfqxpu/how_do_i_display_foreignkey_as_a_search_option_in](https://www.reddit.com/r/django/comments/1gfqxpu/how_do_i_display_foreignkey_as_a_search_option_in)
 - RSS feed: $source
 - date published: 2024-10-30T16:38:38+00:00

<!-- SC_OFF --><div class="md"><p>I want to be able to use the autocomplete_fields interface from Django admin in a Django CMS plugin</p> <p>I&#39;ve created a plugin which has a foreignkey field :</p> <pre><code>class ProductBlock(CMSPlugin): text = models.TextField() product = models.ForeignKey(Product, on_delete=models.CASCADE, blank=True, null=True) </code></pre> <p>When I go to add the plugin to the page the option is shown as a dropdown.</p> <p>I&#39;ve created an <a href="http://admin.py">admin.py</a> as follows:</p> <pre><code>class ProductBlockAdmin(admin.ModelAdmin): autocomplete_fields = [&#39;product&#39;] admin.site.register(ProductBlock, ProductBlockAdmin) </code></pre> <p>In the admin section the field appears with the search option but this isn&#39;t displayed in the editor for the plugin.</p> <p>I&#39;m using django cms 4.1.3 </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kopite42"> /u/kopite42 </a> <br/> <span><a href="https:

## date inputs is weird with safari
 - [https://www.reddit.com/r/django/comments/1gfqt2a/date_inputs_is_weird_with_safari](https://www.reddit.com/r/django/comments/1gfqt2a/date_inputs_is_weird_with_safari)
 - RSS feed: $source
 - date published: 2024-10-30T16:33:08+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I am using django forms for my app with tailwind which was very nice until i deployed my app and gone thru my phone I have seen that style doesn’t work on date field in safari but in chrome is fine </p> <p>my field: </p> <p>date = forms.DateField( widget=forms.DateInput( attrs={ &#39;type&#39;: &#39;date&#39;,<br/> &#39;class&#39;: &#39;my tailwind style goes here&#39;,<br/> } ), )</p> <p>Any idea how to solve this kinda of issues ? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adelulusometimes"> /u/adelulusometimes </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gfqt2a/date_inputs_is_weird_with_safari/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gfqt2a/date_inputs_is_weird_with_safari/">[comments]</a></span>

## Faire un SSO avec discord
 - [https://www.reddit.com/r/django/comments/1gfobrw/faire_un_sso_avec_discord](https://www.reddit.com/r/django/comments/1gfobrw/faire_un_sso_avec_discord)
 - RSS feed: $source
 - date published: 2024-10-30T14:49:22+00:00

<!-- SC_OFF --><div class="md"><p>Salut,</p> <p>Je voudrai savoir si vous avez de la doc pour faire un SSO avec discord et si possible en fr, </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jonas0o0"> /u/Jonas0o0 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gfobrw/faire_un_sso_avec_discord/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gfobrw/faire_un_sso_avec_discord/">[comments]</a></span>

## Operational error while redis and celery's servers are running
 - [https://www.reddit.com/r/django/comments/1gfk8fx/operational_error_while_redis_and_celerys_servers](https://www.reddit.com/r/django/comments/1gfk8fx/operational_error_while_redis_and_celerys_servers)
 - RSS feed: $source
 - date published: 2024-10-30T11:27:17+00:00

<!-- SC_OFF --><div class="md"><p>This is the error</p> <p>OperationalError at /upload-image/ [Errno 111] Connection refused Request Method: POST Request URL: <a href="http://127.0.0.1:8000/upload-image/">http://127.0.0.1:8000/upload-image/</a> Django Version: 5.1.2 Exception Type: OperationalError Exception Value: [Errno 111] Connection refused Exception Location: /home/enigma/.local/lib/python3.10/site-packages/kombu/connection.py, line 476, in _reraise_as_library_errors Raised during: app_app_celery.views.upload_image Python Executable: /usr/bin/python3 Python Version: 3.10.12 Python Path: [&#39;/home/enigma/Code/celery x redis task&#39;, &#39;/usr/lib/python310.zip&#39;, &#39;/usr/lib/python3.10&#39;, &#39;/usr/lib/python3.10/lib-dynload&#39;, &#39;/home/enigma/.local/lib/python3.10/site-packages&#39;, &#39;/usr/local/lib/python3.10/dist-packages&#39;, &#39;/usr/lib/python3/dist-packages&#39;]</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/

## Best practice for deploying Django in containers
 - [https://www.reddit.com/r/django/comments/1gfippc/best_practice_for_deploying_django_in_containers](https://www.reddit.com/r/django/comments/1gfippc/best_practice_for_deploying_django_in_containers)
 - RSS feed: $source
 - date published: 2024-10-30T09:45:30+00:00

<!-- SC_OFF --><div class="md"><p>I have a Django web app running in a Docker container on a VM, but every time I make a change to the app, I have to build a new image and ssh it over to the VM, which can take some time and resources. I saw someone somewhere else suggest putting the actual Django code in a volume on the VM mounted to the Docker container. Then when updating the Django app, you don&#39;t have to mess with the image at all, you just pull the code from GitHub to the volume and docker compose up -d. Does this make sense, or is there some important pitfall I should be aware of? What are the best practices? I suppose this wouldn&#39;t work for a major update that changes dependencies. Anyway, thanks for any guidance you can provide!!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wombatsock"> /u/wombatsock </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gfippc/best_practice_for_deploying_django_in_containers/">[li

## Need Advice: Sharing Source Code for Evaluation Before Sale – How to Protect Myself?
 - [https://www.reddit.com/r/django/comments/1gfie7u/need_advice_sharing_source_code_for_evaluation](https://www.reddit.com/r/django/comments/1gfie7u/need_advice_sharing_source_code_for_evaluation)
 - RSS feed: $source
 - date published: 2024-10-30T09:20:34+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I&#39;ve been a part of this community for years and could use some advice.</p> <p>Long story short: I built a product using Django, and now there’s serious interest from some people who want to buy it. We’ve gone through several demos (about six at this point) where I’ve explained the functionality and shown them how everything works. They’re interested, but now they’re asking for access to the source code for evaluation before they make an official offer.</p> <p>I totally understand why they’d want to see the code to confirm quality, but I’m hesitant to share it. They&#39;ve signed an NDA with me, but I still feel like just handing over the source code might be risky.</p> <p>Does anyone have tips on how I can protect myself in this situation or is this how these things go down?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vvinvardhan"> /u/vvinvardhan </a> <br/> <span><a href="https://www.reddi

## [ANN] django-daisy: A Fully Mobile-Friendly Django Admin Interface with DaisyUI!
 - [https://www.reddit.com/r/django/comments/1gfi47p/ann_djangodaisy_a_fully_mobilefriendly_django](https://www.reddit.com/r/django/comments/1gfi47p/ann_djangodaisy_a_fully_mobilefriendly_django)
 - RSS feed: $source
 - date published: 2024-10-30T08:59:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 🎉</p> <p>I&#39;m excited to share <strong>django-daisy</strong>—a Django admin interface project that I built to enhance usability and design in Django’s admin area.</p> <h1>🚀 Features:</h1> <ul> <li><strong>Built with DaisyUI</strong>: This UI library provides a clean, modern look and is fully responsive out of the box, making the admin interface truly <strong>mobile-friendly</strong>.</li> <li><strong>Enhanced UX</strong>: Replaces the default related model window with a <strong>modal box</strong> for a more seamless, in-page experience.</li> <li><strong>Polished, User-Focused Interface</strong>: Small UX improvements throughout the interface to make navigation and interactions smoother and faster.</li> </ul> <p>I’d love any feedback from the Django community—whether it&#39;s about the design, UX, or any new features you&#39;d like to see!</p> <p>Check it out here: <a href="https://github.com/hypy13/django-daisy/">django-daisy on GitH

## Model Constructors or Default Initialization?
 - [https://www.reddit.com/r/django/comments/1gfi2oq/model_constructors_or_default_initialization](https://www.reddit.com/r/django/comments/1gfi2oq/model_constructors_or_default_initialization)
 - RSS feed: $source
 - date published: 2024-10-30T08:55:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi I&#39;m new to Django, and I&#39;m logging the movement of equipment in my models. Part of creating a new log is updating the last log with the moved_out_date.</p> <p>I&#39;m handling some of this in the view currently, but this seems inefficient and it would be a whole lot better to handle these special cases every time I create a new model object, where checks could be done, such as is the equipment already at the location in which case I don&#39;t want to log a new movement etc..</p> <p>Is there a way to do this within the model class itself?</p> <pre><code>class MovementLog(models.Model): equipment = models.ForeignKey(Equipment, on_delete=models.CASCADE) to_location = models.ForeignKey(Location, on_delete=models.SET_NULL, null=True, related_name=&#39;to_location&#39;) moved_in_date = models.DateTimeField(auto_now_add=True) moved_out_date = models.DateTimeField(null=True, blank=True) </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <

## Doing Celery task with 0 knowledge
 - [https://www.reddit.com/r/django/comments/1gfh0id/doing_celery_task_with_0_knowledge](https://www.reddit.com/r/django/comments/1gfh0id/doing_celery_task_with_0_knowledge)
 - RSS feed: $source
 - date published: 2024-10-30T07:31:33+00:00

<!-- SC_OFF --><div class="md"><p>Okay so i am given a celery task to do in two days</p> <p>My task is that</p> <p>Whenever we are using celery,everytime a new task is added Its all over the place and we wanna make sure everytime a task is added,the previous task should be killed/revoked,</p> <p>I will be using redis for backend</p> <p>So how should i approach this? Should i genereate code from chatgpt and make sure it works then understand the code</p> <p>This is to check my progrees in the first job so i am kind of confused </p> <p>I have two days in the office to do it so please help me</p> <p>I never worked with celery before so its my first time </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Theonewhomogged_"> /u/Theonewhomogged_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gfh0id/doing_celery_task_with_0_knowledge/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gfh0id/doing_celery

## How to Implement Tenant-Aware RBAC in a Multi-Tenant Django Application?
 - [https://www.reddit.com/r/django/comments/1gfg4tf/how_to_implement_tenantaware_rbac_in_a](https://www.reddit.com/r/django/comments/1gfg4tf/how_to_implement_tenantaware_rbac_in_a)
 - RSS feed: $source
 - date published: 2024-10-30T06:22:02+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m developing a multi-tenant Django application where each tenant is represented by an Firm. Users (Profiles) are associated with these firms, and we need to implement an industry-standard Role-Based Access Control (RBAC) </p> <p>I don&#39;t have a Custom User and Profile has a one to one relation to the User model </p> <p>I have implemented Multi tenancy by creating base model which has tenant_id and I use a middleware that set teanan_id in thread local to create custom model managers and query set</p> <p>Requirements</p> <ul> <li>Roles: <ul> <li>Admin</li> <li>Support </li> <li>Sales</li> <li>Engineer</li> </ul></li> <li>key Features <ul> <li>Each Firm admin can configure permissions for roles within their firm.</li> <li>Admin can manage roles and assign/remove permissions for other roles.</li> <li>Every role comes with a default set of permissions, customizable per firm. </li> <li>Admin can modify permissions of each User</li> </ul></li> </ul

## Atomically Updating elements of Json fields
 - [https://www.reddit.com/r/django/comments/1gffy3a/atomically_updating_elements_of_json_fields](https://www.reddit.com/r/django/comments/1gffy3a/atomically_updating_elements_of_json_fields)
 - RSS feed: $source
 - date published: 2024-10-30T06:07:41+00:00

<!-- SC_OFF --><div class="md"><p>Let&#39;s say I have a JSON field, my_field, with multiple nested dicts. </p> <p>I want to do<br/> <code> my_object.my_field[&quot;key_1&quot;][&quot;key_2&quot;] += 5 my_object.save() </code></p> <p>However, I want to do this in a way such that if multiple threads do this simultaneously, the result will be the combined value, and there won&#39;t be a race condition. </p> <p>Is this possible?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Scary-Juggernaut-754"> /u/Scary-Juggernaut-754 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gffy3a/atomically_updating_elements_of_json_fields/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gffy3a/atomically_updating_elements_of_json_fields/">[comments]</a></span>

## Deployed Django with Redis and Celery to AWS ECS using GithubAction
 - [https://www.reddit.com/r/django/comments/1gff0ly/deployed_django_with_redis_and_celery_to_aws_ecs](https://www.reddit.com/r/django/comments/1gff0ly/deployed_django_with_redis_and_celery_to_aws_ecs)
 - RSS feed: $source
 - date published: 2024-10-30T05:01:27+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/ty6v9fzurtxd1.png?width=1553&amp;format=png&amp;auto=webp&amp;s=0e379df06d1d95edbcda627e40ac7b41913f8e5b">https://preview.redd.it/ty6v9fzurtxd1.png?width=1553&amp;format=png&amp;auto=webp&amp;s=0e379df06d1d95edbcda627e40ac7b41913f8e5b</a></p> <h1>### AWS Deployment Steps</h1> <p>The deployment uses <strong>AWS ECS</strong>, <strong>Terraform</strong>, and <strong>GitHub Actions</strong> for CI/CD:</p> <ol> <li><strong>AWS Resources Setup</strong>: <ul> <li>An ECS Cluster is created using Terraform.</li> <li>The Django, Celery worker, and Redis containers are deployed using ECS tasks.</li> <li>A CloudWatch Log Group is configured to capture logs from the containers.</li> <li>Network resources like VPC, subnets, security groups, and an Internet Gateway are created using Terraform.</li> </ul></li> <li><strong>GitHub Actions CI/CD</strong>: <ul> <li>The GitHub Actions workflow handles the build and deployment process.</li

