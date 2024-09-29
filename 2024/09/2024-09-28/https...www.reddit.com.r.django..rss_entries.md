# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## How do I help the world using django?
 - [https://www.reddit.com/r/django/comments/1frol8k/how_do_i_help_the_world_using_django](https://www.reddit.com/r/django/comments/1frol8k/how_do_i_help_the_world_using_django)
 - RSS feed: $source
 - date published: 2024-09-28T21:25:30+00:00

<!-- SC_OFF --><div class="md"><p>So, I&#39;m a 24M. I was introduced to django this year on May during my industrial attachment. My supervisor was very kind and helped me through any challenges I faced with django. As a result I learnt very quickly. Something also happened, the way this guy helped me sparked something in me. I feel like using my skills to help people. Problem is, i dont know how to do it. Are there platforms I can use my django skills to help people who are in need? Or is there any way i can just help people using this skill? Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Butterscotch_7930"> /u/Ok_Butterscotch_7930 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1frol8k/how_do_i_help_the_world_using_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1frol8k/how_do_i_help_the_world_using_django/">[comments]</a></span>

## Is django good choice for online gaming tournament website?
 - [https://www.reddit.com/r/django/comments/1frlnd3/is_django_good_choice_for_online_gaming](https://www.reddit.com/r/django/comments/1frlnd3/is_django_good_choice_for_online_gaming)
 - RSS feed: $source
 - date published: 2024-09-28T19:08:01+00:00

<!-- SC_OFF --><div class="md"><p>Features: live chat, multiple tournament at once, streaming maybe </p> <p>Thx</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NewKidInOldTown"> /u/NewKidInOldTown </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1frlnd3/is_django_good_choice_for_online_gaming/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1frlnd3/is_django_good_choice_for_online_gaming/">[comments]</a></span>

## Best Way To Model Tables For Two Way Chat Application
 - [https://www.reddit.com/r/django/comments/1frk51j/best_way_to_model_tables_for_two_way_chat](https://www.reddit.com/r/django/comments/1frk51j/best_way_to_model_tables_for_two_way_chat)
 - RSS feed: $source
 - date published: 2024-09-28T17:59:46+00:00

<!-- SC_OFF --><div class="md"><p>I have written a chat app that is used daily for clients, multiple million messages per day are sent through it.</p> <p>The Model for a message is attached here (its very stripped down).</p> <pre><code>class Message(models.Model): from_num = models.TextField(null=True) to_num = models.TextField(null=True) content = models.TextField() datetime = models.DateTimeField(auto_now_add=True) def get_conversation(self, limit=10): messages = Message.objects.filter(Q(from_num=self.from_num, to_num=self.to_num) | Q(to_num=self.from_num, from_num=self.to_num) ).order_by(&quot;-datetime&quot;)[:limit] </code></pre> <p>Currently to get the running conversation for individuals i run this the get_conversation method of a viewed message, the client only sees the last message of the conversations just like cell phones untill they expand the chat. (Thats why its just stuck in the Message model)</p> <p>The problem is that the Postgres 12 database has become quite large an

## First Work Project
 - [https://www.reddit.com/r/django/comments/1frfc21/first_work_project](https://www.reddit.com/r/django/comments/1frfc21/first_work_project)
 - RSS feed: $source
 - date published: 2024-09-28T14:20:31+00:00

<!-- SC_OFF --><div class="md"><p>I’m starting my first work project and settled on using Django.</p> <p>I’ve done some front end projects before but nothing that went into production. Just some portfolio stuff with flask and JS.</p> <p>I spend most of my days doing data engineering work or data science stuff. The organization is moving off of some old COBOL based stuff and into some staging databases, still on prem. Well, there’s a huge technical gap. The resident tech talent is mostly from 20 years ago and is focused solely on SQL and DOS like functionality. I’m the personality who’s trying to drive them to something more modern.</p> <p>The enterprise that owns our org has power platform licenses but none of the cloud environments to back it which make them accessible or interoperable with Python. Yet, they’ve hired a few people who are mass producing power apps which I know will not be scalable or sustainable in the long run.</p> <p>I’ve had our IT department start setting me up a 

## Help me on this One
 - [https://www.reddit.com/r/django/comments/1frex9d/help_me_on_this_one](https://www.reddit.com/r/django/comments/1frex9d/help_me_on_this_one)
 - RSS feed: $source
 - date published: 2024-09-28T14:00:11+00:00

<!-- SC_OFF --><div class="md"><pre><code>def send_welcome_email(request): if request.method == &#39;POST&#39;: recipient = request.POST.get(&#39;recipient&#39;) subject = request.POST.get(&#39;subject&#39;) body = request.POST.get(&#39;body&#39;) footer = request.POST.get(&#39;footer&#39;) # Handle background image upload background_image = request.FILES.get(&#39;background_image&#39;) unsubscribe_url = request.build_absolute_uri( reverse(&#39;unsubscribe&#39;, kwargs={&#39;email&#39;: recipient}) ) # Create the email object email = EmailMultiAlternatives( subject=subject, body=body, from_email=settings.DEFAULT_FROM_EMAIL, to=[recipient], ) email.content_subtype = &#39;html&#39; # Main content is text/html email.mixed_subtype = &#39;related&#39; # Ensure inline images are not shown as attachments # Prepare context for the email template context = { &#39;subject&#39;: subject, &#39;body&#39;: body, &#39;footer&#39;: footer, &#39;unsubscribe_url&#39;: unsubscribe_url, } # Attach the ba

## Lightweight Celery alternative
 - [https://www.reddit.com/r/django/comments/1fratsm/lightweight_celery_alternative](https://www.reddit.com/r/django/comments/1fratsm/lightweight_celery_alternative)
 - RSS feed: $source
 - date published: 2024-09-28T09:49:32+00:00

<!-- SC_OFF --><div class="md"><p>I just want to give this package some recognition. I have started using it as a background worker and I love it.</p> <p>It&#39;s maintained by the people at Dabapps and is well worth a look if you&#39;re looking to create asynchronous tasks in your Django app.</p> <p>Check out <a href="https://github.com/dabapps/django-db-queue">django-db-queue</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RahlokZero"> /u/RahlokZero </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fratsm/lightweight_celery_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fratsm/lightweight_celery_alternative/">[comments]</a></span>

## How do I test this custom template tag I created for my project?
 - [https://www.reddit.com/r/django/comments/1fr2px4/how_do_i_test_this_custom_template_tag_i_created](https://www.reddit.com/r/django/comments/1fr2px4/how_do_i_test_this_custom_template_tag_i_created)
 - RSS feed: $source
 - date published: 2024-09-28T00:52:25+00:00

<!-- SC_OFF --><div class="md"><p>Here&#39;s a custom template tag I created for my project:</p> <pre><code>@register.simple_tag(takes_context=True) def custom_csrf_token(context): context_csrf_token = context.get(&quot;custom_csrf_token&quot;) if context_csrf_token is not None: csrf_token_input = mark_safe(f&#39;&lt;input type=&quot;hidden&quot; name=&quot;csrfmiddlewaretoken&quot; value=&quot;{context_csrf_token}&quot;&gt;&#39;) else: request = context[&quot;request&quot;] csrf_token_input = mark_safe(f&#39;&lt;input type=&quot;hidden&quot; name=&quot;csrfmiddlewaretoken&quot; value=&quot;{get_token(request)}&quot;&gt;&#39;) return csrf_token_input </code></pre> <p>For it, I want to write two tests. One who triggers the <code>if</code> , the other who triggers the <code>else</code> I have troubles with the <code>else</code> one. In it, I need to render a fake template with my tag in it and pass a request in the context when I render it. Here&#39;s what it looks like for now:</p> <pr

## Proper access control
 - [https://www.reddit.com/r/django/comments/1fr2ij9/proper_access_control](https://www.reddit.com/r/django/comments/1fr2ij9/proper_access_control)
 - RSS feed: $source
 - date published: 2024-09-28T00:41:14+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone! I&#39;m making a management system for an online school and I need to do a rather convoluted authorization,</p> <p>where I need to check the relationship between two users before giving access to a particular resource</p> <p>I have written the rules as follows (CUD - Create, Update, Delete):</p> <p>Student:</p> <ul> <li>Can view their own and their teacher&#39;s media</li> <li>Can only edit his/her profile</li> <li>Can view his/her profile and his/her teachers&#39; profile</li> <li>Can only perform CUDs on their own media files.</li> </ul> <p>Teacher:</p> <ul> <li>Can view his/her own media and media of attached students</li> <li>Can only edit his/her profile</li> <li>Can view his/her profile and the profile of attached students</li> <li>Can perform CUD with his/her own media and the media of attached students</li> </ul> <p>Admin:</p> <ul> <li>Can attach students to teachers</li> <li>Can view all users&#39; media</li> <li>Can edit the 

