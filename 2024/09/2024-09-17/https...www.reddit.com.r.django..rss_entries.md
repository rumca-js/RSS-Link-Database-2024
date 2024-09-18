# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django/Heroku showing old data
 - [https://www.reddit.com/r/django/comments/1fjascj/djangoheroku_showing_old_data](https://www.reddit.com/r/django/comments/1fjascj/djangoheroku_showing_old_data)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T21:02:36+00:00

<!-- SC_OFF --><div class="md"><p>I have a head-scratcher that has been driving me crazy with my application. I am using Django with Heroku for my admin/back-end. When we use the admin site to update the data, it isn’t being reflected on the live site but the data is updated in the database. For example, if I changed the date of an event, those changes won’t be reflected until I refresh or wait(sometimes hours or even days). I have looked at the caching and everything looks fine, and the issue doesn’t seem to happen all of the time. I was just curious if anyone else has had this issue. TIY, let me know if more information is needed.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glittering-Chard8269"> /u/Glittering-Chard8269 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fjascj/djangoheroku_showing_old_data/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fjascj/djangoheroku_showing_old_data

## django-nice v0.1.0
 - [https://www.reddit.com/r/django/comments/1fj6bnd/djangonice_v010](https://www.reddit.com/r/django/comments/1fj6bnd/djangonice_v010)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T18:08:34+00:00

<!-- SC_OFF --><div class="md"><p>After my previous post I started working with the NiceGUI in django and it became apparent it was going to take a lot of repetitive code to bind a element to a django model field since it&#39;s not supported in the ORM, so I used a combination of DRF and SSE/signals to automate the binding and cut down on boilerplate code. I&#39;m still in the testing phase but feel free to try it out and send me feedback</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rexsum420"> /u/Rexsum420 </a> <br/> <span><a href="https://github.com/rexsum420/django-nice">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fj6bnd/djangonice_v010/">[comments]</a></span>

## Database being hit multiple times for the same evaluated queryset
 - [https://www.reddit.com/r/django/comments/1fj5oho/database_being_hit_multiple_times_for_the_same](https://www.reddit.com/r/django/comments/1fj5oho/database_being_hit_multiple_times_for_the_same)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T17:43:51+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>I work on a publishing company app and on the author details page I display every book linked to an author. I use ModelForms so the user can edit these links. In these forms, there is a book field that corresponds to every book in the DB.</p> <p>I noticed that the query to fetch all books was being executed for every form. Obviously that&#39;s not good, so I changed the form to make it use an existing and already evaluated queryset. This way every form would use one common queryset and it would only hit the DB once.</p> <p>The problem is that after implementing this change, I&#39;m hitting the database just as much as before.</p> <p>In the view:</p> <pre><code>book_authoring_list: QuerySet[BookAuthoring] = BookAuthoring.objects.filter(author=author) linkable_books: QuerySet[Book] = Book.objects.all().order_by(&#39;short_title&#39;) list(linkable_books) # evaluate the common queryset form_list = [ BookAuthoringForm( instance=model_instance,

## Have any of you looked at NiceGUI as a front-end for django?
 - [https://www.reddit.com/r/django/comments/1fj0dhy/have_any_of_you_looked_at_nicegui_as_a_frontend](https://www.reddit.com/r/django/comments/1fj0dhy/have_any_of_you_looked_at_nicegui_as_a_frontend)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T14:15:19+00:00

<!-- SC_OFF --><div class="md"><p>I seen NiceGUI just published their 2.1.0 on pypi.org the other day, and was thinking of using it as a front-end to replace react and react native. Have any of you used this because it looks pretty nice and simple to use</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rexsum420"> /u/Rexsum420 </a> <br/> <span><a href="https://nicegui.io">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fj0dhy/have_any_of_you_looked_at_nicegui_as_a_frontend/">[comments]</a></span>

## Experienced mobile developer but a Django beginner :)
 - [https://www.reddit.com/r/django/comments/1fixlh2/experienced_mobile_developer_but_a_django_beginner](https://www.reddit.com/r/django/comments/1fixlh2/experienced_mobile_developer_but_a_django_beginner)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T12:14:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks!<br/> I&#39;m an experienced Android developer working in Fintech, contributing to mobile banking solutions. Now I want to slowly move into backend. I gained a lot of interests in Python language.</p> <p>I started with Django Udemy course, this one<br/> <a href="https://www.udemy.com/course/python-django-ultimate-beginners-course-2022">https://www.udemy.com/course/python-django-ultimate-beginners-course-2022</a></p> <p>I guess this is basic Django stuff, then I would look into DRF which is related to pure backend work. I saw in the current course that there are <strong>templates</strong> which are used to make UI elements. Is this really used in production apps or frontend part usually goes with some framewrok like react?</p> <p><strong>Are there any open source repos which I could look into it, maybe start some small contribution to it or whatever to get my hands dirty asap?</strong></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href=

## How to properly deploy Django App, Ubuntu os
 - [https://www.reddit.com/r/django/comments/1fiu3ma/how_to_properly_deploy_django_app_ubuntu_os](https://www.reddit.com/r/django/comments/1fiu3ma/how_to_properly_deploy_django_app_ubuntu_os)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T08:52:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi , so recently I bought a cloud service in Hetzner Cloud where I could host my django app. I am currently running it with a <a href="http://run.sh">run.sh</a> command but I know that its not the best practice cuz I have served the static files with a re_path function in the general <a href="http://urls.py">urls.py</a> file which isnt ideal for deployment. I am looking to host it in Nginx server or even Apache2. I have tried for the past week but every tutorial or documentation has put me in a loop where I cant seem to know what I am doing and I have found myself copying and pasting commands. This is also my first ever hands on experience in Ubuntu so... Any help or blog recommendation would be appreciated. Also I am currently looking to buy the SSL certificates in order to make it HTTPS.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ek2222222"> /u/ek2222222 </a> <br/> <span><a href="https://www.reddit.com/r/d

## Does including 0.0.0.0 in Django's ALLOWED_HOSTS pose a security risk?
 - [https://www.reddit.com/r/django/comments/1fiu3jx/does_including_0000_in_djangos_allowed_hosts_pose](https://www.reddit.com/r/django/comments/1fiu3jx/does_including_0000_in_djangos_allowed_hosts_pose)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T08:52:07+00:00

<!-- SC_OFF --><div class="md"><p>I have a security-related question about Django&#39;s settings configuration.</p> <p>Context:</p> <ul> <li>Django application running in a Docker container</li> <li>Gunicorn in the same container, listening on port 8000 (command: gunicorn my_app.wsgi:application --bind 0.0.0.0:8000)</li> <li>Nginx in a separate container, public-facing on port 80</li> <li>Nginx forwards requests to the Django container via docker-compose&#39;s internal network</li> <li>Deployed on a cloud machine with a dynamic IP address</li> <li>ALLOWED_HOSTS in Django settings set to [&#39;XX.XXX.XX.XX&#39;] (where XX.XXX.XX.XX is the actual IP)</li> <li>The application is currently functional</li> </ul> <p>Now, the monitoring keeps raising some issues:</p> <pre><code>Invalid HTTP_HOST header: &#39;0.0.0.0:8000&#39;. You may need to add &#39;0.0.0.0&#39; to ALLOWED_HOSTS. </code></pre> <p>Questions:</p> <ol> <li>Is adding &#39;0.0.0.0&#39; to ALLOWED_HOSTS advisable?</li> <li>What 

## Best practice regarding serializers in DRF
 - [https://www.reddit.com/r/django/comments/1fiknj1/best_practice_regarding_serializers_in_drf](https://www.reddit.com/r/django/comments/1fiknj1/best_practice_regarding_serializers_in_drf)
 - RSS feed: https://www.reddit.com/r/django/.rss
 - date published: 2024-09-17T00:20:02+00:00

<!-- SC_OFF --><div class="md"><p>I have two sets of snippets here. The snippet is related to fetching chat_rooms and messages associated with each room. My question is which set of snippet is a better practice. Any info will be greatly appreciated. Thank you.</p> <pre><code>Example 1: class ChatRoomNameSerializer(serializers.ModelSerializer): owner = serializers.StringRelatedField() class Meta: model = ChatRoomName fields = [&#39;id&#39;, &#39;owner&#39;, &#39;name&#39;, &#39;created&#39;] class ChatRoomNamesView(ListAPIView): permission_classes = [AllowAny] queryset = ChatRoomName.objects\ .prefetch_related(&#39;messages&#39;).all() def list(self, request, *args, **kwargs): serializer = ChatRoomNameSerializer(self.get_queryset(), many=True) for data in serializer_roomname.data: messages = self.get_queryset().get(id=data[&#39;id&#39;]).messages.all() data[&#39;messages&#39;] = MessageSerializer(messages, many=True).data return Response(serializer.data) Example 2: class ChatRoomNameSe

