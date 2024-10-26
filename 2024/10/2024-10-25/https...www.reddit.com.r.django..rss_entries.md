# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## How to add data to a queryset ?
 - [https://www.reddit.com/r/django/comments/1gc556q/how_to_add_data_to_a_queryset](https://www.reddit.com/r/django/comments/1gc556q/how_to_add_data_to_a_queryset)
 - RSS feed: $source
 - date published: 2024-10-25T21:23:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a beginner in Django and in backend in general. And I&#39;m struggling with something.</p> <p>I have 2 models:</p> <pre><code>class SearchedJob(models.Model): uuid = models.UUIDField(default=uuid.uuid4, editable=False, unique=True) job = models.ForeignKey(Job, on_delete=models.CASCADE) experience = models.ForeignKey(Experience, on_delete=models.CASCADE, blank=True, null=True) candidate = models.ForeignKey(Candidate, on_delete=models.CASCADE, related_name=&#39;searched_jobs&#39;) working_time = models.ForeignKey( WorkingTime, verbose_name=_(&#39;Working time&#39;), blank=True, null=True, on_delete=models.SET_NULL ) contract = models.ManyToManyField(Contract, verbose_name=_(&#39;Contract&#39;), blank=True) remote = models.ForeignKey(Remote, verbose_name=_(&#39;Remote&#39;), blank=True, null=True, on_delete=models.SET_NULL) class Meta: unique_together = [&#39;candidate&#39;, &#39;job&#39;] class JobSearchArea(models.Model): candidate = models.Fo

## Where do I create the views and urls for a specific application if the view uses models from another application?
 - [https://www.reddit.com/r/django/comments/1gc2rd0/where_do_i_create_the_views_and_urls_for_a](https://www.reddit.com/r/django/comments/1gc2rd0/where_do_i_create_the_views_and_urls_for_a)
 - RSS feed: $source
 - date published: 2024-10-25T19:38:21+00:00

<!-- SC_OFF --><div class="md"><p>I am having a bit of an issue with the design of my project. I have a CRUD project for a client where his clients would post jobs to the website and his employees can accept jobs and complete them. The jobs have different statuses of: Open, In Progress, Completed, and Canceled. </p> <p>I created a custom admin app in the django project and I am trying to display all the completed assignments/jobs of all the employees of the company. I have already created an assignment app and an employee app in the project. I&#39;ve already created a view to display all the assignments an employee completes for their profile in the assignment app. I&#39;m now confused on where I should create a view to display all the completed assignments across all the employees to display to the admin. I want to do this because I want the admin to review the completed assignment before he can accept the assignment and create an Invoice via an API call with the assignment details 

## Webapp hosting resources
 - [https://www.reddit.com/r/django/comments/1gc1vx9/webapp_hosting_resources](https://www.reddit.com/r/django/comments/1gc1vx9/webapp_hosting_resources)
 - RSS feed: $source
 - date published: 2024-10-25T19:00:10+00:00

<!-- SC_OFF --><div class="md"><p>I going develop a webapp in django that can to post image and text. Get registion form data from user. Now don&#39;t know how much Hosting resource like cpu, ram, bandwidth for 100 to 500 user . Also tell some free and paid webapp Hosting service in low cost for startup</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legal_Relief6756"> /u/Legal_Relief6756 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gc1vx9/webapp_hosting_resources/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gc1vx9/webapp_hosting_resources/">[comments]</a></span>

## How to include query parameters except one to reverse() in a view?
 - [https://www.reddit.com/r/django/comments/1gc1nd1/how_to_include_query_parameters_except_one_to](https://www.reddit.com/r/django/comments/1gc1nd1/how_to_include_query_parameters_except_one_to)
 - RSS feed: $source
 - date published: 2024-10-25T18:49:32+00:00

<!-- SC_OFF --><div class="md"><p>Let&#39;s say I have a page with several query parameters that define a list of items, various filters applied to that list, and a form with selected item: /items/?filter1=somefilter&amp;filter2=somefilter&amp;item_id=1</p> <p>There is a delete button that sends request to item_delete view:</p> <pre><code>def item_delete (request, pk): ... return redirect(reverse(&#39;items&#39;)) #include querystring without item_id here </code></pre> <p>After deleting the item, I want to redirect to the same page with the same filters applied, except item_id=1 (since the item no longer exists).</p> <p>How would you go about this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/peterstiglitz"> /u/peterstiglitz </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gc1nd1/how_to_include_query_parameters_except_one_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gc1nd1/how_to_inc

## My simple Django/REST endpoint returns an HTML response instead of JSON, I'm baffled
 - [https://www.reddit.com/r/django/comments/1gbv0da/my_simple_djangorest_endpoint_returns_an_html](https://www.reddit.com/r/django/comments/1gbv0da/my_simple_djangorest_endpoint_returns_an_html)
 - RSS feed: $source
 - date published: 2024-10-25T14:03:14+00:00

<!-- SC_OFF --><div class="md"><p>EDIT: SOLVED</p> <p>I guess I had to post this to realize what the issue is...</p> <p>It appears that I missed a forward slash in the URL on my front side.</p> <p>I was making a request to:</p> <p>api/reports/count/</p> <p>instead of</p> <p>/api/reports/count/</p> <p>___________________________________________________</p> <p>I have this simple endpoint:</p> <pre><code># Removed csrf, api_view and IsAuthenticated decorators to rule out those as issues. def report_count(request): user_report_count = GeneratedReport.objects.filter(user=request.user).count() return JsonResponse(data={&#39;user_report_count&#39;: user_report_count}, status=200) </code></pre> <p>the relevant url:</p> <pre><code>... path(&#39;reports/count/&#39;, views.report_count, name=&quot;reports_count&quot;), ... </code></pre> <p>I make a GET request to this endpoint via my frontend, and observe it in browser dev tools -&gt; <a href="https://imgur.com/QbHyWml">https://imgur.com/QbHyWm

## Feature Friday: Django's update_or_create() got Smarter in v5.0!
 - [https://www.reddit.com/r/django/comments/1gbutdy/feature_friday_djangos_update_or_create_got](https://www.reddit.com/r/django/comments/1gbutdy/feature_friday_djangos_update_or_create_got)
 - RSS feed: $source
 - date published: 2024-10-25T13:54:37+00:00

<!-- SC_OFF --><div class="md"><p>This post discusses a small but useful quality of life improvement that dropped in Django 5.0: <code>create_defaults</code>.</p> <p>The new <code>create_defaults</code> argument lets you handle creation vs update scenarios elegantly, bringing more power to Django&#39;s object management.</p> <p>Previously, there was a single defaults dict for both creating and updating objects. This led to awkward workarounds and exception handling when you needed different behavior on creation vs update, resulting in code like this:</p> <pre><code>defaults = {&quot;first_name&quot;: &quot;Bob&quot;} create_defaults = {&quot;first_name&quot;: &quot;Bob&quot;, &quot;birthday&quot;: date(1940, 10, 9)} try: obj = Person.objects.get(first_name=&quot;John&quot;, last_name=&quot;Lennon&quot;) for key, value in defaults.items(): setattr(obj, key, value) obj.save() except Person.DoesNotExist: new_values = {&quot;first_name&quot;: &quot;John&quot;, &quot;last_name&quot;: &quo

## RAG-Enhanced Chatbot Application | AI-Powered Document Retrieval & Chatbot Demo | LangChain & OpenAI
 - [https://www.reddit.com/r/django/comments/1gbtw0l/ragenhanced_chatbot_application_aipowered](https://www.reddit.com/r/django/comments/1gbtw0l/ragenhanced_chatbot_application_aipowered)
 - RSS feed: $source
 - date published: 2024-10-25T13:10:58+00:00

<!-- SC_OFF --><div class="md"><p>I’m excited to share my latest project, an AI-driven chatbot built with LangChain, OpenAI’s GPT-4, ChromaDB, and Streamlit. By leveraging Retrieval-Augmented Generation (RAG) this application delivers data-backed, contextually rich responses, perfect for high-impact customer support and knowledge-based applications. </p> <p>📽️ Watch the Demo - <a href="https://youtu.be/MZDiMMai6zo?si=xN6hJ-Zj0S627Sj0">https://youtu.be/MZDiMMai6zo?si=xN6hJ-Zj0S627Sj0</a><br/> 💻 Explore the Project - <a href="https://github.com/abdurrahimcs50/RAG_Chatbot_Project.git">https://github.com/abdurrahimcs50/RAG_Chatbot_Project.git</a> </p> <p>🟢 Key Features:</p> <p>✅ Real-Time Chat Interface: Chat with AI models like OpenAI’s GPT-4 in a responsive interface.<br/> ✅ Document Uploads for RAG: Improve chatbot responses by uploading your own documents (PDF, TXT, DOCX, MD).<br/> ✅ URL-Based RAG: Integrate real-time web content into your chat interactions for up-to-date responses. 

## Deploying Django Project
 - [https://www.reddit.com/r/django/comments/1gbqijs/deploying_django_project](https://www.reddit.com/r/django/comments/1gbqijs/deploying_django_project)
 - RSS feed: $source
 - date published: 2024-10-25T09:50:16+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not sure how to state this but I wanna deploy my django project using gunicorn, nginx , Docker? Any tutorials, resources where I can learn ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PrudentArgument4073"> /u/PrudentArgument4073 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gbqijs/deploying_django_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gbqijs/deploying_django_project/">[comments]</a></span>

## Django loads forever static
 - [https://www.reddit.com/r/django/comments/1gboihl/django_loads_forever_static](https://www.reddit.com/r/django/comments/1gboihl/django_loads_forever_static)
 - RSS feed: $source
 - date published: 2024-10-25T07:14:58+00:00

<!-- SC_OFF --><div class="md"><p>I am new to Django and I am trying to understand why the page keeps reloading after executing a long function. It correctly finishes but the page keeps reloading. I tried to debug by parts and is like a timeout thing. After a certain point the browser will keep loading even if the function finishes. The same function works for smaller data and correctly loads the static showing that if finished. Is it normal behavior in development mode ? </p> <p>EDIT: Basically, I created a ParquetLoading model that stores a parquet file and I overwrite the save function of the model so that it loads data to a PostgreSQL db for other models when saving the file.</p> <p>Due to having to load large amount of data I use bulk_create (for some models with small data) and Django-Postgres-copy for the largest models. I log every step to a log file.</p> <p>I have to load 4 parquet files in order because the last 2 have foreign keys of the others. The last 2 files are the bi

## Best Front-End Framework for Local Web-App with Django as Back-End?
 - [https://www.reddit.com/r/django/comments/1gbllpu/best_frontend_framework_for_local_webapp_with](https://www.reddit.com/r/django/comments/1gbllpu/best_frontend_framework_for_local_webapp_with)
 - RSS feed: $source
 - date published: 2024-10-25T04:00:04+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I&#39;m planning to build a web-app that will be hosted locally on a computer in a LAN environment. I’ll be using <strong>Django for the back-end</strong>, and I need suggestions for the best <strong>front-end framework</strong> to pair with it. The app will have two login/sign-up features (one for a superuser and another for a regular user), with their details stored in a <strong>local database</strong>. The app should also have an option to store and retrieve data from a <strong>cloud database</strong>.</p> <p>Here are my questions:</p> <ol> <li>What’s the best <strong>front-end framework</strong> for this setup? Should I go with React, Vue, or something else?</li> <li>For the <strong>local database</strong>, what would you recommend? I’m considering <strong>SQLite</strong> or <strong>PostgreSQL</strong>, but open to other ideas.</li> <li>Any suggestions for a <strong>cloud database</strong> that integrates well with Django?</l

## Python/Django Developer Looking Opportunities
 - [https://www.reddit.com/r/django/comments/1gbk5dx/pythondjango_developer_looking_opportunities](https://www.reddit.com/r/django/comments/1gbk5dx/pythondjango_developer_looking_opportunities)
 - RSS feed: $source
 - date published: 2024-10-25T02:38:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey Redditors! 👋</p> <p>I&#39;m a Python developer with over a year of experience, focusing primarily on Django, and I&#39;m currently on the lookout for new opportunities to grow my skills and contribute to exciting projects. I&#39;ve got experience in building web applications, managing databases (PostgreSQL) and containerization with Docker..</p> <p>Whether it&#39;s a full-time gig, freelance work, or even an internship, I&#39;m eager to connect with teams where I can bring my passion for clean code, system design, and problem-solving.</p> <p>If you or someone you know is looking for a motivated and fast-learning developer, feel free to hit me up !</p> <p><strong>Here are my links:</strong></p> <ul> <li><a href="https://github.com/djokodev">https://github.com/djokodev</a></li> <li><a href="https://www.linkedin.com/in/djoko-christian/">https://www.linkedin.com/in/djoko-christian/</a></li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href=

