# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Security by fragility
 - [https://www.reddit.com/r/django/comments/1gzsjtv/security_by_fragility](https://www.reddit.com/r/django/comments/1gzsjtv/security_by_fragility)
 - RSS feed: $source
 - date published: 2024-11-25T20:12:32+00:00

<!-- SC_OFF --><div class="md"><p>So one of our websites got attacked today. Not a critical website, </p> <p>Certain pages that require a secret 8-character alphanumeric code were being called thousands of times a minute.</p> <p>This could have been a problem.</p> <p>But thanks to my trusty SQLite3 database and literally zero optimisations anywhere, my server dutifully went down in minutes.</p> <p>And so the hacker was not able to retrieve any valuable information.</p> <p>And now we implemented some basic defenses.</p> <p>Can&#39;t get hacked if your site&#39;s crashed !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Brachamul"> /u/Brachamul </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gzsjtv/security_by_fragility/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gzsjtv/security_by_fragility/">[comments]</a></span>

## Characters and numbers in predetermined positions
 - [https://www.reddit.com/r/django/comments/1gzr3ju/characters_and_numbers_in_predetermined_positions](https://www.reddit.com/r/django/comments/1gzr3ju/characters_and_numbers_in_predetermined_positions)
 - RSS feed: $source
 - date published: 2024-11-25T19:14:30+00:00

<!-- SC_OFF --><div class="md"><p>Hello I have a 16-character field CodFiscale. I need the input, depending on the position, to allow only numbers or characters to be entered.</p> <p>For example “A3D22”</p> <p>The first letter can be only character, the second only number and so on</p> <p>I need the control during typing.</p> <p>Which solution do you recommend ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gae58"> /u/Gae58 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gzr3ju/characters_and_numbers_in_predetermined_positions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gzr3ju/characters_and_numbers_in_predetermined_positions/">[comments]</a></span>

## First deployment VPS, docker
 - [https://www.reddit.com/r/django/comments/1gznbx5/first_deployment_vps_docker](https://www.reddit.com/r/django/comments/1gznbx5/first_deployment_vps_docker)
 - RSS feed: $source
 - date published: 2024-11-25T16:46:51+00:00

<!-- SC_OFF --><div class="md"><p>Clearly something went wrong here...<br/> I try to deploy on hetzner vps using docker ce image. My site was up, but I look at it today and CPU was 100% usage, same for RAM, I couldn&#39;t even do anything in console.<br/> I must have messed something up, it&#39;s my first deployment. Can you help me figure out why so many processes are duplicating and how to fix this?<br/> My project is here: <a href="https://github.com/Pirat102/WebApp/tree/main">https://github.com/Pirat102/WebApp/tree/main</a> </p> <p><a href="https://preview.redd.it/xjx9irfsp23e1.png?width=1233&amp;format=png&amp;auto=webp&amp;s=255220411d1589e18acbd4a1264d366a9f62a2a6">https://preview.redd.it/xjx9irfsp23e1.png?width=1233&amp;format=png&amp;auto=webp&amp;s=255220411d1589e18acbd4a1264d366a9f62a2a6</a></p> <p><a href="https://preview.redd.it/zn2no2tvo23e1.png?width=1525&amp;format=png&amp;auto=webp&amp;s=bb98d187279d19b2c4566a24cd41482fa250cfde">https://preview.redd.it/zn2no2tvo23e1.

## I am lost in learning Models
 - [https://www.reddit.com/r/django/comments/1gzm0nh/i_am_lost_in_learning_models](https://www.reddit.com/r/django/comments/1gzm0nh/i_am_lost_in_learning_models)
 - RSS feed: $source
 - date published: 2024-11-25T15:53:51+00:00

<!-- SC_OFF --><div class="md"><p>there are models class and each &quot;Model&quot; in it is actually inhering from &quot;models.Model&quot;<br/> what I don&#39;t get is how models.Manager is automatically included in each of these classes?<br/> and why saying &quot;x=models.Manager()&quot; is overwriting the previous mystyrious default manager which was called objects</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TharwatMella"> /u/TharwatMella </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gzm0nh/i_am_lost_in_learning_models/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gzm0nh/i_am_lost_in_learning_models/">[comments]</a></span>

## help me with Product Variants..
 - [https://www.reddit.com/r/django/comments/1gzllss/help_me_with_product_variants](https://www.reddit.com/r/django/comments/1gzllss/help_me_with_product_variants)
 - RSS feed: $source
 - date published: 2024-11-25T15:36:25+00:00

<!-- SC_OFF --><div class="md"><p>hi, I am building an ecommerce, and I realized that I need product variants for sku and stock,<br/> I guess number of product variants should be same as the number of combinations of options(not sure).</p> <p>for example, there are 3 sizes, 3 colors, 3 materials, all the possible combinations are 27 variants.. should I create all the possible variants when creating a product? what if 3 sizes, 9 colors, 9 materials?? combinations are 243... is it normal approach??</p> <p>please give me any advices.. I waiting from experts.. thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gzllss/help_me_with_product_variants/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gzllss/help_me_with_product_variants/">[comments]</a></span>

## Is it possible to render a URL path in a template without a required path variable?
 - [https://www.reddit.com/r/django/comments/1gzlas9/is_it_possible_to_render_a_url_path_in_a_template](https://www.reddit.com/r/django/comments/1gzlas9/is_it_possible_to_render_a_url_path_in_a_template)
 - RSS feed: $source
 - date published: 2024-11-25T15:23:22+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m attempting to render a URL path in some Javascript, but without a required path variable, but this gives a template error.</p> <p>I have a URL defined as follows:</p> <pre><code>path(&quot;tanks/pill/&lt;int:pk&gt;/&quot;, tank_pill, name=&quot;tanks-pill&quot;) </code></pre> <p>This returns an HTML fragment to insert into the DOM using HTMX.</p> <p>I&#39;m calling the URL from Javascript as follows:</p> <pre><code>const baseUrl = &#39;{% url &quot;core:tanks-pill&quot; 0 %}&#39;.replace(&#39;/0/&#39;, &#39;/&#39;); const url = `${baseUrl}${id}` htmx.ajax(&#39;GET&#39;, url, {target: &#39;#additional-tanks&#39;, swap: &#39;afterend&#39;}) </code></pre> <p>As you can see I&#39;ve had to hack the URL render by providing a dummy ID. Not ideal.</p> <p>Is there a better workaround?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/badlyDrawnToy"> /u/badlyDrawnToy </a> <br/> <span><a href="https://www.reddit.com

## Why am I getting 'ModuleNotFoundError' after installing psycopg2 and running 'python manage.py migrate' in my Django project?
 - [https://www.reddit.com/r/django/comments/1gzj5oy/why_am_i_getting_modulenotfounderror_after](https://www.reddit.com/r/django/comments/1gzj5oy/why_am_i_getting_modulenotfounderror_after)
 - RSS feed: $source
 - date published: 2024-11-25T13:45:56+00:00

<!-- SC_OFF --><div class="md"><p>Hello, everyone!</p> <p>I&#39;m new to Python and have a good grasp of the fundamentals. I recently started a project using Django and PostgreSQL. Instead of using the original PostgreSQL installed on my machine, I opted to use Railway for PostgreSQL.</p> <p>Here&#39;s what I did:</p> <ol> <li><p>I created a base folder and set up a virtual environment inside it.</p></li> <li><p>Activated the virtual environment.</p></li> <li><p>Installed Django and psycopg2 using: pip install psycopg2 pip install psycopg2-binary</p></li> <li><p>Updated the DATABASES settings in settings.py to use my Railway PostgreSQL configuration.</p></li> </ol> <p>However, when I run the command:</p> <p>python manage.py migrate</p> <p>I get a ModuleNotFoundError.</p> <p>I’ve checked multiple times and confirmed that psycopg2 is installed. I’ve tried both psycopg2 and psycopg2-binary, but the issue persists.</p> <p>I’m using VS Code as my editor. My folder structure is straightfor

## Help
 - [https://www.reddit.com/r/django/comments/1gzifh0/help](https://www.reddit.com/r/django/comments/1gzifh0/help)
 - RSS feed: $source
 - date published: 2024-11-25T13:09:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am trying to implement a file poller app which basically polls a directory at regular intervals and based on a specific file presence has to copy the files from source to destination.I need to implement this in python.Is celery a good option for this or are there better ways to do this? Please suggest.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/prash1988"> /u/prash1988 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gzifh0/help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gzifh0/help/">[comments]</a></span>

## Is deploying django in shared hosting bad ?
 - [https://www.reddit.com/r/django/comments/1gzg19e/is_deploying_django_in_shared_hosting_bad](https://www.reddit.com/r/django/comments/1gzg19e/is_deploying_django_in_shared_hosting_bad)
 - RSS feed: $source
 - date published: 2024-11-25T10:40:55+00:00

<!-- SC_OFF --><div class="md"><p>I read alot of post about deploying django in shared hosting. Alot of people dont recommend it as configuration is pain but i wanted to know if its true.</p> <p>Also if you did it successfully please let me know how.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/himynameisAhhhh"> /u/himynameisAhhhh </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gzg19e/is_deploying_django_in_shared_hosting_bad/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gzg19e/is_deploying_django_in_shared_hosting_bad/">[comments]</a></span>

## Cant upload media files when I serve it with docker + nginx
 - [https://www.reddit.com/r/django/comments/1gzfsax/cant_upload_media_files_when_i_serve_it_with](https://www.reddit.com/r/django/comments/1gzfsax/cant_upload_media_files_when_i_serve_it_with)
 - RSS feed: $source
 - date published: 2024-11-25T10:22:54+00:00

<!-- SC_OFF --><div class="md"><p>Hello. I&#39;ve been dealing with this problem for 2 days and wanted to ask here.</p> <p>When I run the app locally I have no problems with uploading media files on admin panel. but when I run it with docker + nginx , It cannot finish the process and gives this error: </p> <p>EndpointConnectionError at /admin/travel/about_us/1/change/</p> <p>Could not connect to the endpoint URL: &quot;[<a href="https://c7eb2215ae1523cabac7ea55b1d00038.r2.cloudflarestorage.com/mervin-bucket/media/elementor-placeholder-image.webp%5D(vscode-file://vscode-app/c:/Users/k-desktop/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)">https://c7eb2215ae1523cabac7ea55b1d00038.r2.cloudflarestorage.com/mervin-bucket/media/elementor-placeholder-image.webp](vscode-file://vscode-app/c:/Users/k-desktop/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)</a>&qu

## Is writing permission on the basis on view right?
 - [https://www.reddit.com/r/django/comments/1gzfr1z/is_writing_permission_on_the_basis_on_view_right](https://www.reddit.com/r/django/comments/1gzfr1z/is_writing_permission_on_the_basis_on_view_right)
 - RSS feed: $source
 - date published: 2024-11-25T10:20:30+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m sorry for sharing such a messy code and approach. But I&#39;m new to Django, and I&#39;m still learning. Please help with understanding the following. Should custom_permissions be based on views and the model the view is responsible for in a DRF Api Application? Or should it be independent of the models and be based on the incoming request?</p> <p>This is what my custom_permissions.py looks like</p> <pre><code>from rest_framework import permissions from Workspaces.models import * # On Requesting User class IsNotAlreadyMemberOfAnyOrganization(permissions.BasePermission): &quot;&quot;&quot; Custom permission to check that the requesting user is not already a member of the organization. &quot;&quot;&quot; def has_permission(self, request, view): is_member = UserOrganization.objects.filter( user=request.user, ).exists() return not is_member class IsAdminOfAnyOrganization(permissions.BasePermission): &quot;&quot;&quot; Custom permission to check t

## Authentication in DEF
 - [https://www.reddit.com/r/django/comments/1gzd6c9/authentication_in_def](https://www.reddit.com/r/django/comments/1gzd6c9/authentication_in_def)
 - RSS feed: $source
 - date published: 2024-11-25T07:08:14+00:00

<!-- SC_OFF --><div class="md"><p>I’ve got a DRF app that I’m scaffolding. In the past I’ve use simplejwt + dj-rest-auth quite effectively. I like some of the features from django-rest-knox better and am thinking of building social features and passkey support by using allauth in a headless state, which dj-rest-auth doesn’t have built in. </p> <p>Outside of the stateless nature of jwts, which my backend doesn’t require at the moment (likely never), what benefits do they have over token based auth, as you can truly sign out of all devices using token based auth. </p> <p>Curious if anyone has suggestions or past experience. Cheers!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mpeyfuss"> /u/mpeyfuss </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gzd6c9/authentication_in_def/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gzd6c9/authentication_in_def/">[comments]</a></span>

