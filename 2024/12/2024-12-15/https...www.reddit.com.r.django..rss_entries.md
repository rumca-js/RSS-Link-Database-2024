# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Report of big data. Experience stories
 - [https://www.reddit.com/r/django/comments/1hey4ft/report_of_big_data_experience_stories](https://www.reddit.com/r/django/comments/1hey4ft/report_of_big_data_experience_stories)
 - RSS feed: $source
 - date published: 2024-12-15T17:55:03+00:00

<!-- SC_OFF --><div class="md"><p>Good day🙋 Is there someone who works on a project where there&#39;s big data involved, i mean big database ( we use postgresql) where in one table for example, there is a lot of entries and there is a need of generating a report of them. For us we have celery and redis doing the work. The best part, It is not blocking the application but we are not very satisfied with the generation part. For example in order to generate a report of 10000 identifications, it takes around 20min. I would like to hear other stories and experience of dealing with generation of big report with a lot of data.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/afrokemet95"> /u/afrokemet95 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hey4ft/report_of_big_data_experience_stories/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hey4ft/report_of_big_data_experience_stories/">[comments]<

## How do I pass an item and an associated formset from the view to the template in Django?
 - [https://www.reddit.com/r/django/comments/1hewrww/how_do_i_pass_an_item_and_an_associated_formset](https://www.reddit.com/r/django/comments/1hewrww/how_do_i_pass_an_item_and_an_associated_formset)
 - RSS feed: $source
 - date published: 2024-12-15T16:55:39+00:00

<!-- SC_OFF --><div class="md"><p>I understand how to pass multiple items in the views to the template, you just pass multiple items in the context.</p> <p>I&#39;m trying to learn to build a checklist app for learning and to have a formset for links associated to each item to learn. So you can like save multiple youtube instructional links to each item.</p> <p>But let&#39;s say that I am passing query of items over. And for each item has a formset created for it. How do I pass over the associated formset over with the item?</p> <p>Thru using chatgpt and google, I&#39;ve come up with this</p> <pre><code>def currentchecklist(request): items = Item.objects.filter(user=request.user, datecompleted__isnull=True) courses = request.user.checklist_courses.all() LinkFormSet = inlineformset_factory(Item, Link, fields=(&#39;url&#39;,), extra=1) formsets = [] for item in items: formsets.append((item, LinkFormSet(instance=item))) return render(request, &quot;BJJApp/currentchecklist.html&quot;, {&q

## 🚀 Building a Full-Stack Application with Next.js, Django, and MongoDB
 - [https://www.reddit.com/r/django/comments/1hew2pe/building_a_fullstack_application_with_nextjs](https://www.reddit.com/r/django/comments/1hew2pe/building_a_fullstack_application_with_nextjs)
 - RSS feed: $source
 - date published: 2024-12-15T16:23:29+00:00

<!-- SC_OFF --><div class="md"><p>I’m currently working on a full-stack application using Next.js for the front-end, Django for the back-end, and MongoDB as the database.</p> <p>While I want to leverage Django’s robust authentication system, I’m facing a challenge:💡 I don&#39;t want to use Django&#39;s ORM, but the auth features seem tightly integrated with it.</p> <p>👉 Is there a workaround to use Django’s authentication without its ORM?<br/> 👉 Or, is there a better approach I should consider for this stack?</p> <p>I’d love to hear insights and suggestions from the community!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ContentCar3092"> /u/ContentCar3092 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hew2pe/building_a_fullstack_application_with_nextjs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hew2pe/building_a_fullstack_application_with_nextjs/">[comments]</a></span>

## Licensing Django Apps
 - [https://www.reddit.com/r/django/comments/1heuapk/licensing_django_apps](https://www.reddit.com/r/django/comments/1heuapk/licensing_django_apps)
 - RSS feed: $source
 - date published: 2024-12-15T15:00:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been working on an HMIS with modules implemented as apps. We have the Nursing Station, Pharmacy, Inventory, Laboratory etc. Is it possible to license these modules independently with something like an annual subscription? I&#39;ve mostly worked with Django for web, nothing too fancy that might require licensing or subscriptions so I&#39;m not even sure if this is possible. I currently run the project using Docker and Docker Compose.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SocialKritik"> /u/SocialKritik </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1heuapk/licensing_django_apps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1heuapk/licensing_django_apps/">[comments]</a></span>

## basedpyright can't access `objects`
 - [https://www.reddit.com/r/django/comments/1heoekj/basedpyright_cant_access_objects](https://www.reddit.com/r/django/comments/1heoekj/basedpyright_cant_access_objects)
 - RSS feed: $source
 - date published: 2024-12-15T08:33:01+00:00

<!-- SC_OFF --><div class="md"><p>On the line <code>EventType.objects.filter(name=&#39;Gesperrt&#39;).first()</code> basedpyright reports <code>Cannot access attribute &quot;objects&quot; for class &quot;type[EventType]&quot; Attribute &quot;objects&quot; is unknown [reportAttributeAccessIssue]</code></p> <p>I assume, it&#39;s because the class <code>EventType</code> only contains <code>objects</code> via inheritance, ie. not explictly. How can I tell basedpyright to look in the super class or ignore the error in terms of the <code>objects</code> attribute?</p> <p>Extra karma points if you can tell me how to do this via Neovim, so far I have</p> <p><code>lua lspconfig.basedpyright.setup { on_attach = on_attach, capabilities = capabilities, settings = { basedpyright = { reportAttributeAccessIssue = &quot;none&quot;, }, } } </code> But it has no effect.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DerZweiteFeO"> /u/DerZweiteFeO </a> <br/> <span

## Streaming HTTP Response Factory
 - [https://www.reddit.com/r/django/comments/1hek6g5/streaming_http_response_factory](https://www.reddit.com/r/django/comments/1hek6g5/streaming_http_response_factory)
 - RSS feed: $source
 - date published: 2024-12-15T03:45:18+00:00

<!-- SC_OFF --><div class="md"><p>In django I have a few API integrations that take a few seconds in a single HTTP request to finish. Rather than just letting the page spin, I decided it would be way better UX to send back &quot;status updates&quot; for each step. </p> <p>Im using the StreamingHttpResponse and a custom factory I built. I&#39;m trying to implement a few more solid design patterns in the app. So this is kind of practice, but also being used in prod. The way it functions is very similar to how ChatGPT&#39;s typed text is streamed back to the client. </p> <p>Here&#39;s the code below:</p> <pre><code># task_factory.py class MyTaskFactory: def __init__(self): self.tasks = [] def _build(self): return [task.build() for task in self.tasks] def add_task(self, name): task = MyTask(name, self) self.tasks.append(task) return task def error_all(self): for task in self.tasks: task.error = &quot;This went wrong&quot; return self.render_tasks() def mark_next_complete(self): for task 

## Custom Financial Form Builder
 - [https://www.reddit.com/r/django/comments/1heh2fs/custom_financial_form_builder](https://www.reddit.com/r/django/comments/1heh2fs/custom_financial_form_builder)
 - RSS feed: $source
 - date published: 2024-12-15T00:48:40+00:00

<!-- SC_OFF --><div class="md"><p>Greetings.</p> <p>Over the past year, I’ve been developing a loan origination system. The first app I built was a Financial Spreading tool. As I continued building other apps and learning web development (my professional background is in commercial credit), I realized the Financial Spreading app needed to be more customizable.</p> <p>To address this, I started by creating a GL Code Manager, which allows users to expand upon a default Chart of Accounts. In a separate view, those accounts are displayed in a table, where users can select which ones to include in a Financial Form Template. Additionally, I began working on an &#39;Expression Manager&#39; to enable custom calculations. The goal is for users to use these templates to “spread” financial statements—a common term in credit analysis and underwriting.</p> <p>By September, I had reached a good point in development, but starting a new full-time job has limited the time I can dedicate to the projec

## How to structure a Django project?
 - [https://www.reddit.com/r/django/comments/1heg9i7/how_to_structure_a_django_project](https://www.reddit.com/r/django/comments/1heg9i7/how_to_structure_a_django_project)
 - RSS feed: $source
 - date published: 2024-12-15T00:07:27+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m use to working with Flask and the way I&#39;d typically structure my Rest Api folder is something like this.</p> <p>Repositories - Direct interactions with the database</p> <p>services - Add business logic to my repository functions </p> <p>api - Where I would keep my endpoints</p> <p>How would you do this in Django? How would I incorporate serializers?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mrreddituser111312"> /u/Mrreddituser111312 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1heg9i7/how_to_structure_a_django_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1heg9i7/how_to_structure_a_django_project/">[comments]</a></span>

