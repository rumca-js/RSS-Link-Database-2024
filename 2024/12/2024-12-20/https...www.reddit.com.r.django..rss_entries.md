# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## (noob q) What's the best way to set up a many-to-many relationship with djangorestframework?
 - [https://www.reddit.com/r/django/comments/1hiuol0/noob_q_whats_the_best_way_to_set_up_a_manytomany](https://www.reddit.com/r/django/comments/1hiuol0/noob_q_whats_the_best_way_to_set_up_a_manytomany)
 - RSS feed: $source
 - date published: 2024-12-20T21:48:50+00:00

<!-- SC_OFF --><div class="md"><p>To simplify the scenario:</p> <p>My app has users and pre-defined cards. Users can build decks using the cards that are available.</p> <p>So of course I need models for User, Deck, and Card.</p> <p>Each User:Deck is 1:many - easy, add foreign key to Deck for User/owner</p> <p>Here&#39;s where I&#39;m not sure what the best option is:<br/> Each Deck includes many cards, and each card may belong to many decks.<br/> Should I build a list of cards that belong to the deck, then include them as a single field? (I think this would be slower because I&#39;d have to retrieve the list then query for those cards?)<br/> Or should I build a separate table that has a separate row for each deck-card relation? (So I would take Deck ID, filter DeckCards by deck ID, and all the cards listed are available)</p> <p>I&#39;m learning about serializers and hyperlinking right now, but not sure what would be the best way to set up my API here. I followed through the DRF tutor

## Help with server hardening... I can't force HTTPS!
 - [https://www.reddit.com/r/django/comments/1hinjcw/help_with_server_hardening_i_cant_force_https](https://www.reddit.com/r/django/comments/1hinjcw/help_with_server_hardening_i_cant_force_https)
 - RSS feed: $source
 - date published: 2024-12-20T16:28:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I am locally hosting my django website to the greater web. It works totally fine with let&#39;s encrypt ssl forced... But no matter what I do, I can&#39;t seem to get an HTTPS connection . I can get an SSL certification when connecting, but when I force HTTPS it fails to connect. Any tips?</p> <pre><code>NGinx Proxy Manager Django==4.1.7 gunicorn==20.1.0 PiHole to manage Local DNS, not running on 80 or 443. DDNS configured in Router, using any.DDNS Porkbun </code></pre> <p>Nginx Proxy Manager setup: </p> <p>Running in a docker<br/> Let&#39;s Encrypt Certificates<br/> Trying to switch between HTTP and HTTPS<br/> Trying to swtich between force SSL and not</p> <p>Most recently attempted &quot;Advanced&quot; config</p> <pre><code>location /static/ { alias /home/staticfiles/; } location ~ /\.ht { deny all; } </code></pre> <p>Gunicorn Setup:</p> <p>Most recently attempted CLI run:</p> <pre><code>gunicorn --forwarded-allow-ips=&quot;127.0.0.1&

## Entry Level Django Developer
 - [https://www.reddit.com/r/django/comments/1hilzaj/entry_level_django_developer](https://www.reddit.com/r/django/comments/1hilzaj/entry_level_django_developer)
 - RSS feed: $source
 - date published: 2024-12-20T15:17:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone. I hope the community can help me. I have been practicing Python for a year and build web application projects using Flask and Django so I&#39;m looking for an entry level Django job to improve my skills further, being mentored and gain experience in a company setting. I&#39;m willing to be paid less and no benefits as long as I get the job and gain Django experience.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Good_Persimmon7136"> /u/Good_Persimmon7136 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hilzaj/entry_level_django_developer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hilzaj/entry_level_django_developer/">[comments]</a></span>

## Can someone explain what sessions are, and why am I facing so much of a problem with my API permissions?
 - [https://www.reddit.com/r/django/comments/1hiicrb/can_someone_explain_what_sessions_are_and_why_am](https://www.reddit.com/r/django/comments/1hiicrb/can_someone_explain_what_sessions_are_and_why_am)
 - RSS feed: $source
 - date published: 2024-12-20T12:03:56+00:00

<!-- SC_OFF --><div class="md"><p>The problem I am facing is that I am not able to access my newly built APIs that require the [IsAuthenticated] permissions to fetch the data in my Svelte frontend, whereas I am able to perform all the [IsAuthenticated] API functions on the django restframework UI while testing my APIs. For example, whenever I login using my DRF UI, this is the output I get:<br/> <code>User: Turf Nation</code></p> <p><code>Turf ID: 1, Date: 2024-12-18</code></p> <p><code>[20/Dec/2024 16:46:42] &quot;GET /enterprise/slot-status/?turf_id=1&amp;date=2024-12-18 HTTP/1.1&quot; 200 16716</code></p> <p>and now whenever I do the same process using the Svelte frontend, I get this:</p> <p><code>User: AnonymousUser</code></p> <p><code>Turf ID: 1, Date: 2024-12-19</code></p> <p><code>[20/Dec/2024 16:47:34] &quot;GET /enterprise/slot-status/?turf_id=1&amp;date=2024-12-19 HTTP/1.1&quot; 200 4460</code></p> <p>As you can see the user is being recognised using the DRF UI while not fo

## Look for some suggestions
 - [https://www.reddit.com/r/django/comments/1hihdnp/look_for_some_suggestions](https://www.reddit.com/r/django/comments/1hihdnp/look_for_some_suggestions)
 - RSS feed: $source
 - date published: 2024-12-20T10:57:10+00:00

<!-- SC_OFF --><div class="md"><p>Hey guy I just start learning django and im building first project I want a better color grading and want some changes so that the ui can look better if have any suggestion please help 🐧</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Resolution713"> /u/No-Resolution713 </a> <br/> <span><a href="https://i.redd.it/rdwuc71miz7e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hihdnp/look_for_some_suggestions/">[comments]</a></span>

## social-auth-app-django vs django-allauth?
 - [https://www.reddit.com/r/django/comments/1hibuhm/socialauthappdjango_vs_djangoallauth](https://www.reddit.com/r/django/comments/1hibuhm/socialauthappdjango_vs_djangoallauth)
 - RSS feed: $source
 - date published: 2024-12-20T04:28:37+00:00

<!-- SC_OFF --><div class="md"><p>Which is best?</p> <p>I saw <a href="https://snyk.io/advisor/python/django-allauth">https://snyk.io/advisor/python/django-allauth</a> and <a href="https://snyk.io/advisor/python/social-auth-app-django">https://snyk.io/advisor/python/social-auth-app-django</a></p> <p>Score is pretty similar.</p> <p>I guess there are two because people may like to do things in a different way.</p> <p>Has anyone read or has strong arguments in favor or against a solution?</p> <p>I want to put social auth on my project and choosing a package that would help me get there fast &amp; safe would be nice :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Introspecti_com"> /u/Introspecti_com </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hibuhm/socialauthappdjango_vs_djangoallauth/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hibuhm/socialauthappdjango_vs_djangoallauth/">[comments]

## Tomorrow is my interview for internship for python developer and I have only few hrs .help me
 - [https://www.reddit.com/r/django/comments/1hi9uq2/tomorrow_is_my_interview_for_internship_for](https://www.reddit.com/r/django/comments/1hi9uq2/tomorrow_is_my_interview_for_internship_for)
 - RSS feed: $source
 - date published: 2024-12-20T02:35:22+00:00

<!-- SC_OFF --><div class="md"><p>Tomorrow is my interview for internship and i have only 4-5 hrs .what should I do now. what to read in coding and all and my English is also not good . I get blank if anyone ask me question in english. Guide me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fluid-Indication-863"> /u/Fluid-Indication-863 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hi9uq2/tomorrow_is_my_interview_for_internship_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hi9uq2/tomorrow_is_my_interview_for_internship_for/">[comments]</a></span>

## Tomorrow is my interview for internship for python developer and I have only few hrs .help me
 - [https://www.reddit.com/r/django/comments/1hi9tnf/tomorrow_is_my_interview_for_internship_for](https://www.reddit.com/r/django/comments/1hi9tnf/tomorrow_is_my_interview_for_internship_for)
 - RSS feed: $source
 - date published: 2024-12-20T02:33:42+00:00

<!-- SC_OFF --><div class="md"><p>Tomorrow is my interview for internship and i have only 4-5 hrs .what should I do now. what to read in coding and all and my English is also not good . I get blank if anyone ask me question in english. Guide me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fluid-Indication-863"> /u/Fluid-Indication-863 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hi9tnf/tomorrow_is_my_interview_for_internship_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hi9tnf/tomorrow_is_my_interview_for_internship_for/">[comments]</a></span>

## Best way to store images
 - [https://www.reddit.com/r/django/comments/1hi8uef/best_way_to_store_images](https://www.reddit.com/r/django/comments/1hi8uef/best_way_to_store_images)
 - RSS feed: $source
 - date published: 2024-12-20T01:40:37+00:00

<!-- SC_OFF --><div class="md"><p>👋 Hey folks!<br/> What is the best way to store images?</p> <p>I have a product model, everything standard:</p> <ul> <li>Title</li> <li>Price</li> <li>Link</li> <li>Cover photo</li> <li>Product photos - thats what I need help with. I need to store 5 photos of each product. I have total 6 products on the page. Upon click a preview will open and user will slide through them.</li> </ul> <p>Do I create on to many relation model and store each photo separately or there is a better way?</p> <p>I want to edit them from admin page. Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brave_nick"> /u/brave_nick </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hi8uef/best_way_to_store_images/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hi8uef/best_way_to_store_images/">[comments]</a></span>

