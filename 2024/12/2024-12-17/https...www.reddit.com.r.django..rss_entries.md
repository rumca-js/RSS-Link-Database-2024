# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Custom field Serializer with DRF validate max_length from model without setting it again?
 - [https://www.reddit.com/r/django/comments/1hgnkol/custom_field_serializer_with_drf_validate_max](https://www.reddit.com/r/django/comments/1hgnkol/custom_field_serializer_with_drf_validate_max)
 - RSS feed: $source
 - date published: 2024-12-17T23:08:47+00:00

<!-- SC_OFF --><div class="md"><p>Usually repeating yourself is considered bad practice. Field validation I serializer is correctly validating against max_length attribute when using default serializer directly. If validated with a custom serializer extending serializer.CharField I have to explicitly add max_length to serializer. This is quite redundant and also a source for errors. I could query Meta.model and get attributes for field, but I guess this is not good practice at this location. </p> <p>Any ideas / examples how to solve this clean and efficiently? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/metaforx"> /u/metaforx </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hgnkol/custom_field_serializer_with_drf_validate_max/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hgnkol/custom_field_serializer_with_drf_validate_max/">[comments]</a></span>

## Is there a way to render a template and then start another view
 - [https://www.reddit.com/r/django/comments/1hglcc9/is_there_a_way_to_render_a_template_and_then](https://www.reddit.com/r/django/comments/1hglcc9/is_there_a_way_to_render_a_template_and_then)
 - RSS feed: $source
 - date published: 2024-12-17T21:29:30+00:00

<!-- SC_OFF --><div class="md"><p>If a view rendered a template is there a way (with threading or something) that a different view after a bit, would render a different template or redirect after the main view already rendered</p> <p>Example:</p> <p>Views.py Def example(request): #something that would make this work Render(request, &#39;test.html&#39;)</p> <p>Def target(request): While True: If varible: Render(request, &#39;end_result.html&#39;) Urls.py URL_PATTERNS = [ path(&#39;test/&#39;, example, name=&#39;test&#39;) ]</p> <p>So baisicly is there a way to somewhat continue a view (with mybe callinga different view ), and after the main view renders a page for the other view to render something else??</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ProducePossible1882"> /u/ProducePossible1882 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hglcc9/is_there_a_way_to_render_a_template_and_then/">[link]</a></span> &#32; <span>

## Utility for defining and parsing template tags
 - [https://www.reddit.com/r/django/comments/1hgl5gk/utility_for_defining_and_parsing_template_tags](https://www.reddit.com/r/django/comments/1hgl5gk/utility_for_defining_and_parsing_template_tags)
 - RSS feed: $source
 - date published: 2024-12-17T21:21:04+00:00

<!-- SC_OFF --><div class="md"><p>For <a href="https://github.com/EmilStenstrom/django-components">django-components</a> I wrote a utility for defining and parsing Django template tags - You define the spec (&quot;TagSpec&quot;) with args, kwargs, and flags (and more) that the template tag uses. And the utility does the parsing for you.</p> <p>The tag spec makes it possible to programmatically manipulate with the Django template tag&#39;s definition - I used for the docs for django-components to automatically generate the template tag signature from the spec.</p> <p>Hand-in-hand with the TagSpec, I also wrote a parser that takes Django template tag&#39;s input (the string between <code>{% %}</code> ), and sorts and parsers it into args, kwargs, flags, etc. </p> <p>The parser converts the tag&#39;s input into AST that describes each arg / kwarg / flag, and even each filter separately.</p> <p>Should I make it into a standalone package?</p> <p><a href="https://preview.redd.it/v09p3xca6h

## Seeking Feedback on My Project!
 - [https://www.reddit.com/r/django/comments/1hgjwy8/seeking_feedback_on_my_project](https://www.reddit.com/r/django/comments/1hgjwy8/seeking_feedback_on_my_project)
 - RSS feed: $source
 - date published: 2024-12-17T20:24:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’ve been working on a project called <strong>Test Document Server</strong> as part of my journey to improve my Python skills. It’s a server-side application designed to handle and manage test documents efficiently, and I’d love to get some feedback from the community to see if there are any improvements I could make or if you have any suggestions based on your experience.</p> <p>Here’s the GitHub repository for the project:<br/> <a href="https://github.com/watcoconutareyousaying/test-doc-server.git"><strong>Test Document Server - GitHub Repo</strong></a></p> <p><strong>A little about the project</strong>:</p> <ul> <li><strong>Tech Stack</strong>: Python, Django, PostgreSQL</li> <li><strong>Features</strong>: Manage and organize test documents, CRUD operations for documents, and more.</li> </ul> <p>If anyone has suggestions on best practices, potential improvements, or new features that could be added, I would greatly appreciate 

## Rename user group using data migration?
 - [https://www.reddit.com/r/django/comments/1hghvl7/rename_user_group_using_data_migration](https://www.reddit.com/r/django/comments/1hghvl7/rename_user_group_using_data_migration)
 - RSS feed: $source
 - date published: 2024-12-17T18:56:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! im really confused about when should i use data migrations cause i have a project Django which is in a productive environment and i have some groups created in my models.py and basically they told me that they want to rename one group, lets say its actual name is &quot;A&quot; and they want it to be &quot;D&quot;. (There are already users with the group &quot;A&quot; assigned) so idk if i should make a data migration to achieve that change because i tried to change the group name from models.py and that change doesn&#39;t trigger migrations. So, should i make those changes within a data migration or should i just modify the models.py and rename the group name directly?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xbrisax"> /u/xbrisax </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hghvl7/rename_user_group_using_data_migration/">[link]</a></span> &#32; <span><a href="https://ww

## I built web app using Django!
 - [https://www.reddit.com/r/django/comments/1hgh025/i_built_web_app_using_django](https://www.reddit.com/r/django/comments/1hgh025/i_built_web_app_using_django)
 - RSS feed: $source
 - date published: 2024-12-17T18:18:32+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone 👋,</p> <p>I just wanted to show off a web app I made using Django. Outside of tutorial projects, this is my first official project. It&#39;s called <a href="https://saltedvanilla.dev/">Salted Vanilla</a> and it&#39;s a scented candle cataloging web app. </p> <p>I used <a href="https://www.youtube.com/watch?v=N1dYui7Qh0o&amp;t=1082s&amp;pp=ygUfc3RhcnQgYW5kIGRlcGxveSBkamFuZ28gcHJvamVjdA%3D%3D">this tutorial by Kostja</a> to start the project and I built from there. I&#39;m using Appliku to deploy on AWS Lightsail. I used ChatGPT to help with model structure and relationships. I am using Django templates, a little Bootstrap, and most recently Bootstrap Studio for the front end. </p> <p><a href="https://github.com/KevinPierre97/saltedvanillamvp">Here is the git repo</a></p> <p><a href="https://www.youtube.com/watch?v=KOR0V2rtz0A">Here is a video demo you can check out</a></p> <p>If you have any critiques on structure or anything, please le

## Need reviews and suggestions for improvements on my little project
 - [https://www.reddit.com/r/django/comments/1hge98u/need_reviews_and_suggestions_for_improvements_on](https://www.reddit.com/r/django/comments/1hge98u/need_reviews_and_suggestions_for_improvements_on)
 - RSS feed: $source
 - date published: 2024-12-17T16:21:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi all!</p> <p>I am new to backend rest api development and learning under a mentor who gave me a project to complete.</p> <p>The project is about:</p> <ul> <li>A barber has available time slots</li> <li>A user can see available time slots</li> <li>A user can book time slots and give review</li> <li>A user can pay barber</li> <li>(I know there is more that my mentor asked for but for now all I remember is this)</li> </ul> <p>I have done this backend in rest framework and I want opinions, reviews and suggestions for improvements.</p> <p>here is the link to the projects:</p> <p><a href="mailto:git@github.com">git@github.com</a>:Tayyab-R/barber-booking-backend.git </p> <p>(readme file is a bit off. please ignore)</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Signal-313"> /u/No-Signal-313 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hge98u/need_reviews_and_suggestions_for_i

## How to fix Postgresql connection (cursor) errors when using connection pooling (e.g. with Azure Database for Postgresql)
 - [https://www.reddit.com/r/django/comments/1hgauvx/how_to_fix_postgresql_connection_cursor_errors](https://www.reddit.com/r/django/comments/1hgauvx/how_to_fix_postgresql_connection_cursor_errors)
 - RSS feed: $source
 - date published: 2024-12-17T13:41:27+00:00

<!-- SC_OFF --><div class="md"><p>When using Postgresql as the database with a django app, and connection pooling enabled with e.g. PGBouncer, by default you might run into the following error, seemingly at random every couple of requests:</p> <pre><code>InterfaceError: connection already closed </code></pre> <p>with some error message or traceback mentioning failing to create a &quot;cursor&quot;.</p> <p>This happened to us after starting to use a more recent version of Azure Datbase for Postgresql Flexible Server, which has connection pooling enbaled by default (which is a great feature!).</p> <p>It turns out this is mentioned in the Django documentation at <a href="https://docs.djangoproject.com/en/4.2/ref/databases/#transaction-pooling-and-server-side-cursors">https://docs.djangoproject.com/en/4.2/ref/databases/#transaction-pooling-and-server-side-cursors</a></p> <blockquote> <p>Using a connection pooler in transaction pooling mode (e.g. PgBouncer) requires disabling server-side 

## Best AWS Alternative for Cloud9 When Developing a Python Django App?
 - [https://www.reddit.com/r/django/comments/1hg9zmd/best_aws_alternative_for_cloud9_when_developing_a](https://www.reddit.com/r/django/comments/1hg9zmd/best_aws_alternative_for_cloud9_when_developing_a)
 - RSS feed: $source
 - date published: 2024-12-17T12:54:47+00:00

<!-- SC_OFF --><div class="md"><p>I am currently developing a Python Django app. Since Cloud9 has recently been discontinued, what would be a good alternative app on AWS?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Plastic-Walrus-7629"> /u/Plastic-Walrus-7629 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hg9zmd/best_aws_alternative_for_cloud9_when_developing_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hg9zmd/best_aws_alternative_for_cloud9_when_developing_a/">[comments]</a></span>

## Signals for multiple nodes
 - [https://www.reddit.com/r/django/comments/1hg8b03/signals_for_multiple_nodes](https://www.reddit.com/r/django/comments/1hg8b03/signals_for_multiple_nodes)
 - RSS feed: $source
 - date published: 2024-12-17T11:04:54+00:00

<!-- SC_OFF --><div class="md"><p>Hey all of you! </p> <p>I know Django has the signal functionality, but I guess it won’t work on multiple nodes (or better said, it will only run on the node which triggered e.g. the save method of a model.) Is there a way to consume such signals straight from a shared db? I want to register e.g. a login event on each node in my cluster. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Suspicious-Cash-7685"> /u/Suspicious-Cash-7685 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hg8b03/signals_for_multiple_nodes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hg8b03/signals_for_multiple_nodes/">[comments]</a></span>

## WOWY - A Full-Featured E-commerce Platform with Stripe Integration
 - [https://www.reddit.com/r/django/comments/1hg7d2y/wowy_a_fullfeatured_ecommerce_platform_with](https://www.reddit.com/r/django/comments/1hg7d2y/wowy_a_fullfeatured_ecommerce_platform_with)
 - RSS feed: $source
 - date published: 2024-12-17T09:55:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! I wanted to share my Django e-commerce project that I&#39;ve been working on. It&#39;s a comprehensive solution with a modern UI and robust admin features.</p> <h1>Key Features</h1> <p><strong>Product Management</strong></p> <ul> <li>Multi-image product support with primary/gallery images</li> <li>Category management</li> <li>Stock tracking</li> <li>Price and discount management</li> <li>Advanced search/filtering</li> </ul> <p><strong>Orders &amp; Payments</strong></p> <ul> <li>Stripe integration</li> <li>Cash on delivery option</li> <li>PDF invoice generation</li> <li>Order status tracking</li> <li>Multiple shipping addresses</li> </ul> <p><strong>User Features</strong></p> <ul> <li>Customer accounts/profiles</li> <li>Wishlist functionality</li> <li>Real-time cart operations</li> <li>Order history</li> <li>Address management</li> </ul> <p><strong>Admin Dashboard</strong></p> <ul> <li>Sales analytics and reporting</li> <li>Customer insig

## Advice for Landing an Entry-Level Django Developer Job Without Professional Experience
 - [https://www.reddit.com/r/django/comments/1hg5lc8/advice_for_landing_an_entrylevel_django_developer](https://www.reddit.com/r/django/comments/1hg5lc8/advice_for_landing_an_entrylevel_django_developer)
 - RSS feed: $source
 - date published: 2024-12-17T07:37:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’ve been learning Django for a while and have built a few personal projects to strengthen my skills. While I feel confident in my abilities, I don’t yet have professional development experience. Because of this, I’ve been struggling to land an entry-level or junior developer role.</p> <p>I’d love to hear feedback or advice from seasoned developers or anyone currently working in the field. Your feedback and advice are truly priceless to me, and I deeply appreciate any insights you can share.</p> <p>I’m planning to include my resume and a link to my portfolio in this post for reference. Any tips or suggestions on how I can improve them, or general advice about entering the field, would mean a lot to me.</p> <p>Thank you so much for your time and help!</p> <p><a href="https://andersonportfolio.pythonanywhere.com/">Portfolio</a> , <a href="https://docs.google.com/document/d/1PCKXsHPvmur7mJHSiufv_Gid5Axo4LAi/edit?usp=sharing&amp;ouid=

## Sir Hasley Stylez
 - [https://www.reddit.com/r/django/comments/1hg4y0t/sir_hasley_stylez](https://www.reddit.com/r/django/comments/1hg4y0t/sir_hasley_stylez)
 - RSS feed: $source
 - date published: 2024-12-17T06:50:38+00:00

<!-- SC_OFF --><div class="md"><p>Add up on my Instagram account </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Possible_Swing3206"> /u/Possible_Swing3206 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hg4y0t/sir_hasley_stylez/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hg4y0t/sir_hasley_stylez/">[comments]</a></span>

## Help with gifting e-commerce website
 - [https://www.reddit.com/r/django/comments/1hg48og/help_with_gifting_ecommerce_website](https://www.reddit.com/r/django/comments/1hg48og/help_with_gifting_ecommerce_website)
 - RSS feed: $source
 - date published: 2024-12-17T06:02:20+00:00

<!-- SC_OFF --><div class="md"><p>Ayo, I&#39;m just not able to understand how to finish the backend of my website, can anyone guide me regarding this issue? The front-end is done in html css js</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aam-panna"> /u/aam-panna </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hg48og/help_with_gifting_ecommerce_website/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hg48og/help_with_gifting_ecommerce_website/">[comments]</a></span>

## Django docker issues
 - [https://www.reddit.com/r/django/comments/1hfxtdg/django_docker_issues](https://www.reddit.com/r/django/comments/1hfxtdg/django_docker_issues)
 - RSS feed: $source
 - date published: 2024-12-17T00:14:38+00:00

<!-- SC_OFF --><div class="md"><p>I have a django app that connects to a postges db they are both dockerized and run in separate containers, there&#39;s a lot more stuff going on though aside these two container but then in other for me to build the django image I need to have the postgres container up and I can&#39;t have the postgres container unless the django image is built. I&#39;m building the django image with own Dockerfil if that&#39;s important. I need help with how to go about this, I&#39;m pretty much a beginner so I might have my terms mixed up.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WayAndMeans01"> /u/WayAndMeans01 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hfxtdg/django_docker_issues/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hfxtdg/django_docker_issues/">[comments]</a></span>

