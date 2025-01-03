# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Do you know how to handle input field formatting and data processing in Django?
 - [https://www.reddit.com/r/django/comments/1g90lh6/do_you_know_how_to_handle_input_field_formatting](https://www.reddit.com/r/django/comments/1g90lh6/do_you_know_how_to_handle_input_field_formatting)
 - RSS feed: $source
 - date published: 2024-10-21T20:56:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I have a question. I am using a mask in the input field to format numbers like this: 100,000.00. Does Django have a recommended way to handle this? I implemented a solution using <a href="https://plentz.github.io/jquery-maskmoney/">maskMoney</a>, and the JavaScript works well for formatting. However, when I process the data in Django, it doesn&#39;t save anything, and I receive this error: &quot;costo_servicio: Enter a number.&quot;</p> <p>model.py </p> <pre><code>costo_servicio=models.DecimalField(max_digits=17, decimal_places=2, default=0.00,validators=[MinValueValidator( 100.00, message=&#39;&gt;=100&#39;)]) </code></pre> <p>forms.py</p> <pre><code>costo_servicio = forms.DecimalField(widget=forms.TextInput(attrs={&#39;class&#39;: &#39;form-control&#39;, &#39;data-mask&#39;: &quot;000,000.00&quot;})) </code></pre> <p>views.py</p> <pre><code>@method_decorator(allowed_users(allowed_roles=[&#39;admin&#39;,&#39;fianzas&#39;]), name=&#39;dispatch&

## Can I migrate my website from WordPress to a coded platform like Django
 - [https://www.reddit.com/r/django/comments/1g8z6h0/can_i_migrate_my_website_from_wordpress_to_a](https://www.reddit.com/r/django/comments/1g8z6h0/can_i_migrate_my_website_from_wordpress_to_a)
 - RSS feed: $source
 - date published: 2024-10-21T19:59:34+00:00

<!-- SC_OFF --><div class="md"><p>Five months ago, I posted a similar question on the WordPress subreddit, but it didn’t gain much traction, and the feedback was mostly negative, tbh.</p> <p>My original post was along these lines:</p> <p>&quot;I&#39;m currently trying to launch an e-commerce site using WordPress with a theme builder. I really believe this business idea can succeed in the near future (God willing). This might sound odd, but I feel uneasy about WordPress, even though I’ve never written a single line of code. To add to that, I’m not comfortable using Dokan (the marketplace plugin) either, as I want to create a highly customized multi-vendor marketplace.&quot;</p> <p>Fast forward a few months, and I&#39;ve returned to working on my website. I’m not as uncomfortable with WordPress anymore, and I’ve completed the entire site design—it looks great! But now, I’m aiming Big. I want to grow this into a fully-fledged platform with apps for buyers, sellers, and delivery. I’m cons

## TypeError Debugging Assistance
 - [https://www.reddit.com/r/django/comments/1g8wfpt/typeerror_debugging_assistance](https://www.reddit.com/r/django/comments/1g8wfpt/typeerror_debugging_assistance)
 - RSS feed: $source
 - date published: 2024-10-21T18:09:01+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Comfortable-Mix3174"> /u/Comfortable-Mix3174 </a> <br/> <span><a href="https://chatgpt.com/share/67169811-9e10-800e-a4b6-b40846b62da8">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g8wfpt/typeerror_debugging_assistance/">[comments]</a></span>

## Issues with one template filepath
 - [https://www.reddit.com/r/django/comments/1g8vtza/issues_with_one_template_filepath](https://www.reddit.com/r/django/comments/1g8vtza/issues_with_one_template_filepath)
 - RSS feed: $source
 - date published: 2024-10-21T17:44:49+00:00

<!-- SC_OFF --><div class="md"><p>Making an inventory management app as a side project for my job, and have hit a bizarre snag.</p> <p>Throughout the app so far, I&#39;ve been rendering pages in class based views using this</p> <p><code>return render(request,&#39;invmgmt\index.html&#39;)</code></p> <p>However, for one page in particular, this results in an OSError Errno 22, and that the file path to the template is not correct.</p> <p>I&#39;m totally lost as to why this template specifically is having this issue as it&#39;s written identically to other pages that serve the same function for other models. Is there something I&#39;m missing?</p> <p>A working version of this view</p> <pre><code>class Dashboard(LoginRequiredMixin, View): def get(self,request): items = InventoryItem.objects.order_by(&#39;id&#39;) return render(request,&#39;invmgmt\dashboard.html&#39;, {&#39;items&#39; : items,}) </code></pre> <p>And then the broken view</p> <pre><code>class RentalDashboard(LoginRequiredMix

## GraphQL or Rest api
 - [https://www.reddit.com/r/django/comments/1g8q3wg/graphql_or_rest_api](https://www.reddit.com/r/django/comments/1g8q3wg/graphql_or_rest_api)
 - RSS feed: $source
 - date published: 2024-10-21T13:48:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi,I am building a social media platform that contains chats and posts and some activities. this is my first project with django and i d like to know if graphql is more suitable for my case or i should just stick with the traditional rest api</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/L4z3x"> /u/L4z3x </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g8q3wg/graphql_or_rest_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g8q3wg/graphql_or_rest_api/">[comments]</a></span>

## Seeking Your Expertise: Best Tools for Team Documentation in Django + VanillaJS Projects!
 - [https://www.reddit.com/r/django/comments/1g8os36/seeking_your_expertise_best_tools_for_team](https://www.reddit.com/r/django/comments/1g8os36/seeking_your_expertise_best_tools_for_team)
 - RSS feed: $source
 - date published: 2024-10-21T12:44:22+00:00

<!-- SC_OFF --><div class="md"><p>I’m currently working on a project at my company using Django and VanillaJS. After completing the project, I plan to modularize the frequently used features and organize the documentation. I would greatly appreciate any insights or recommendations you might have on the best tools or technologies for this. Right now, I’m keeping everything organized in Notion personally, but it’s time to share documentation at the team level. Thank you in advance for your help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ohohhao"> /u/ohohhao </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g8os36/seeking_your_expertise_best_tools_for_team/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g8os36/seeking_your_expertise_best_tools_for_team/">[comments]</a></span>

## Run manage.py commands without terminal access to prod?
 - [https://www.reddit.com/r/django/comments/1g8ohoc/run_managepy_commands_without_terminal_access_to](https://www.reddit.com/r/django/comments/1g8ohoc/run_managepy_commands_without_terminal_access_to)
 - RSS feed: $source
 - date published: 2024-10-21T12:29:30+00:00

<!-- SC_OFF --><div class="md"><p>For compliance and least-privilege reasons, we try to keep developer access to production minimal. For instance, we don&#39;t want to give <code>kubectl exec</code> to developers to open terminals to Django services in our Kubernetes cluster in production.</p> <p>This presents problems when we want to run manage.py commands, like one-off scripts or migrations.</p> <p>We&#39;d love it if there was some kind of way to run arbitrary manage.py commands from the admin UI. This way we could expose this UI to certain privileged developers without requiring <code>kubectl exec</code> to containers in our production k8s cluster.</p> <p>How have others approached this issue? Any recommended packages to help with this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/oscarandjo"> /u/oscarandjo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g8ohoc/run_managepy_commands_without_terminal_access_to/">[link]</

## How do you deploy a Django app without using runserver?
 - [https://www.reddit.com/r/django/comments/1g8ns6t/how_do_you_deploy_a_django_app_without_using](https://www.reddit.com/r/django/comments/1g8ns6t/how_do_you_deploy_a_django_app_without_using)
 - RSS feed: $source
 - date published: 2024-10-21T11:51:12+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been reading that it&#39;s not recommended to use runserver for production and instead you should a dedicated server like NGINX or Apache for it. But, how do you serve the documents and how is the Django App actually running? As in, doing <a href="http://DD.BB">DD.BB</a> queries, rendering files etc?</p> <p>Or do they mean having a dedicated server to handle incoming connections and then sending it to django? AKA a Proxy?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Luised2094"> /u/Luised2094 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g8ns6t/how_do_you_deploy_a_django_app_without_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g8ns6t/how_do_you_deploy_a_django_app_without_using/">[comments]</a></span>

## Can you suggest improvements to my webapp..?
 - [https://www.reddit.com/r/django/comments/1g8ms33/can_you_suggest_improvements_to_my_webapp](https://www.reddit.com/r/django/comments/1g8ms33/can_you_suggest_improvements_to_my_webapp)
 - RSS feed: $source
 - date published: 2024-10-21T10:53:08+00:00

<!-- SC_OFF --><div class="md"><p>I am building a forum web app for share market investors in India. Where they can participate in discussions relating to the shares they are interested in. </p> <p>I am using Azure app service and azure sql serverless db. </p> <p>For the front end I tried to make it simple and using tailwind css and js for making some calls. </p> <p>I am really stuck at designing the UI as I am not experienced in it. </p> <p>Can you review my website and suggest changes and what you liked and what needs changing. </p> <p>Thanks for your support. Really helps me a lot. </p> <p>I will include the link in the comments. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PrestigiousFun450"> /u/PrestigiousFun450 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g8ms33/can_you_suggest_improvements_to_my_webapp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g8ms33/can_you_suggest_improv

## ERROR: there is no unique constraint matching given keys for referenced table "table_name"
 - [https://www.reddit.com/r/django/comments/1g8k5bn/error_there_is_no_unique_constraint_matching](https://www.reddit.com/r/django/comments/1g8k5bn/error_there_is_no_unique_constraint_matching)
 - RSS feed: $source
 - date published: 2024-10-21T07:35:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I have a database backup file (<code>newdb.091024.psql.bin</code>) that was used with a Django/Wagtail project. I&#39;m running PostgreSQL 13 on Ubuntu 20.04, and when I try to restore the backup, I encounter several errors related to the database tables.</p> <p>The command I used to restore the database is:</p> <p><code>sudo -u postgres pg_restore -d mydb ~/Download/newdb.091024/psql.bin</code></p> <p>However, I get errors like this:</p> <pre><code>pg_restore: from TOC entry 4642; 2606 356755 FK CONSTRAINT wagtailusers_userprofile wagtailusers_userprofile_user_id_59c92331_fk_auth_user_id postgres pg_restore: error: could not execute query: ERROR: there is no unique constraint matching given keys for referenced table &quot;auth_user&quot; Command was: ALTER TABLE ONLY public.wagtailusers_userprofile ADD CONSTRAINT wagtailusers_userprofile_user_id_59c92331_fk_auth_user_id FOREIGN KEY (user_id) REFERENCES public.auth_user(id) DEFERRA

## How do you go about combining multiple paramaters in GET requests in a template?
 - [https://www.reddit.com/r/django/comments/1g8k02z/how_do_you_go_about_combining_multiple_paramaters](https://www.reddit.com/r/django/comments/1g8k02z/how_do_you_go_about_combining_multiple_paramaters)
 - RSS feed: $source
 - date published: 2024-10-21T07:23:40+00:00

<!-- SC_OFF --><div class="md"><p>(Newbie question). Let&#39;s say I have a page with a list of products with /products/ URL. There are three lists of filters that let users filter products: colors, sizes, types. When users choose a filter (&lt;a href={% url &#39;products&#39; %}?color=green&gt;) it sends a GET request /products/?color=green. Now, how to set up links for the other filters, so they will update the current URL?</p> <p>If I do &lt;a href=?size=small&gt; it sends /products/?color=green&amp;size=small which does work, but when a user clicks on the same filter again, it will add to, instead of update, the current URL, like so: /products/?color=green&amp;size=small&amp;size=small.</p> <p>ChatGPT recommends using a custom template tag that updates current URL parameters or adds them if they are not present, like so: href=&quot;?{% update_query_params request size=small %}.</p> <p>I understand it&#39;s typically done with JS, but are there any other ways?</p> </div><!-- SC_ON 

## Should my websockets have ideally ONLY non-blocking actions?
 - [https://www.reddit.com/r/django/comments/1g8g7q7/should_my_websockets_have_ideally_only](https://www.reddit.com/r/django/comments/1g8g7q7/should_my_websockets_have_ideally_only)
 - RSS feed: $source
 - date published: 2024-10-21T03:08:19+00:00

<!-- SC_OFF --><div class="md"><p>I have recently transformed my channels sync websocket into an async consumer, however I have to use sync_to_async many times and honestly have no idea if I got any performance gain at all.</p> <p>This lead me to think, should I avoid blocking calls at all costs in my async websocket consumer, and use regular HTTP requests for them?</p> <p>For example, my users are already connected to a websocket and when they hover something on my page, I use the websocket to transfer some specific database item to them. Would it be better to remove this from my consumer and put it in a regular django view instead?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/3141666"> /u/3141666 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g8g7q7/should_my_websockets_have_ideally_only/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g8g7q7/should_my_websockets_have_ideally_only/">[com

## Django's TechTuber?
 - [https://www.reddit.com/r/django/comments/1g8f4xs/djangos_techtuber](https://www.reddit.com/r/django/comments/1g8f4xs/djangos_techtuber)
 - RSS feed: $source
 - date published: 2024-10-21T02:07:59+00:00

<!-- SC_OFF --><div class="md"><p>There are Youtubers or content creators who are a reference about Django, to learn about the framework, to know the latest news?.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/josueygp"> /u/josueygp </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g8f4xs/djangos_techtuber/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g8f4xs/djangos_techtuber/">[comments]</a></span>

