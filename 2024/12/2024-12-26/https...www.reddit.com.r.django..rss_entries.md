# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Can not figure this out. file upload Field 'id' expected a number but got <InMemoryUploadedFile: test image.jpg (image/jpeg)>.
 - [https://www.reddit.com/r/django/comments/1hn09gh/can_not_figure_this_out_file_upload_field_id](https://www.reddit.com/r/django/comments/1hn09gh/can_not_figure_this_out_file_upload_field_id)
 - RSS feed: $source
 - date published: 2024-12-26T22:48:29+00:00

<!-- SC_OFF --><div class="md"><p>I have a model that has a manytomany to another model. Its a competition and the other model is sponsor images (sponsor_logo) for the competition. I keep getting this error and I can&#39;t figure out why. I am creating the sponsor object, assigning the appropriate fields, saving and linking to the competition model. But I get the type error on the ID. Shouldn&#39;t that pass between these objects?</p> <pre><code>class Competition(models.Model): name = models.CharField(max_length=255) registration_deadline = models.DateTimeField() allowed_divisions = models.ManyToManyField(Division, related_name=&#39;allowed_competitions&#39;) allowed_weight_classes = models.ManyToManyField(WeightClass, related_name=&#39;allowed_competitions&#39;) federation = models.ForeignKey(Federation, on_delete=models.SET_NULL, null=True, blank=True) # Add federation field sponsor_logos = models.ManyToManyField(&#39;Sponsor&#39;, blank=True) def __str__(self): return self.name cl

## Creating Django Dynamic Admin Panel To Get a Job
 - [https://www.reddit.com/r/django/comments/1hmxp5i/creating_django_dynamic_admin_panel_to_get_a_job](https://www.reddit.com/r/django/comments/1hmxp5i/creating_django_dynamic_admin_panel_to_get_a_job)
 - RSS feed: $source
 - date published: 2024-12-26T20:51:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I am developing a new Django dynamic dashboard, which provides a better UI and extends basic Django admin panel functionality, I would like to have some people collaborating with me on this project, my main from this project is to show off my skills with Django concepts to get a job as a Django web developer, anyone have the same goal we can discuss this project further ,</p> <p>I have done the basic functionality </p> <p>* Models registry</p> <p>* Dynamic views</p> <p>* Dynamic form generation</p> <p>* tailwindcss stylized forms </p> <p>there are a lot of features in the queue to be done such as :</p> <p>* Group management</p> <p>* Dashboard access management</p> <p>* Custom permissions</p> <p>* Traffic analysis </p> <p>* Website statistics</p> <p>* Custom middleware to monitor security </p> <p>and a lot more </p> <p>you can find the GitHub source code at <a href="https://github.com/husseinnaeemsec/octopus-dash">octopus-dash</a></p> <p

## Webflow with django
 - [https://www.reddit.com/r/django/comments/1hmxg92/webflow_with_django](https://www.reddit.com/r/django/comments/1hmxg92/webflow_with_django)
 - RSS feed: $source
 - date published: 2024-12-26T20:39:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone I was working on developing tool for converting webflow templates websites into django app with this futures</p> <p>1 - organise statics files and separated in CSS ,JavaScript and assist</p> <p>2 - convert href ,src and srcset links to static tags</p> <p>3 - add blocktrans tag for any text</p> <p>4 - generate base.html contain header with styles and scripts </p> <p>5 - create django html file for each page extended from base.html , and split into multi file each file contains section of page to make editing easier </p> <p>6 - auto create app with views and urls for each webflow page</p> <p>As final results the tool will convert any webflow website into full django app with few clicks</p> <p>So I have 2 options 1 - upload tool to github and stop working on 2 - ask for 1$ per website and keep developing the tool and add user interface and extend futures </p> <p>So what option should I select?</p> </div><!-- SC_ON --> &#32; submitted by &#32

## Does anyone use DRF with Django Allauth?
 - [https://www.reddit.com/r/django/comments/1hmwbt7/does_anyone_use_drf_with_django_allauth](https://www.reddit.com/r/django/comments/1hmwbt7/does_anyone_use_drf_with_django_allauth)
 - RSS feed: $source
 - date published: 2024-12-26T19:48:59+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! </p> <p>I recently completed a project which now I want to rerewrite it with decoupling the backend and the frontend. However the project is using Allauth and I am not sure if it is possible to use it with DRF. </p> <p>ps: It is first time I am using DRF</p> <p>Any suggestion is welcome! :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Willing_Department28"> /u/Willing_Department28 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmwbt7/does_anyone_use_drf_with_django_allauth/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hmwbt7/does_anyone_use_drf_with_django_allauth/">[comments]</a></span>

## I am using react for front end should I skip going deep about views and templates?
 - [https://www.reddit.com/r/django/comments/1hmqlx7/i_am_using_react_for_front_end_should_i_skip](https://www.reddit.com/r/django/comments/1hmqlx7/i_am_using_react_for_front_end_should_i_skip)
 - RSS feed: $source
 - date published: 2024-12-26T15:29:18+00:00

<!-- SC_OFF --><div class="md"><p>I am learning django, using the docs and django books written by william. My question is should skip learning too deep about templates and such that are used for creating ui and focus on only backend and jump straight to django for apis book?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Injera-man"> /u/Injera-man </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmqlx7/i_am_using_react_for_front_end_should_i_skip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hmqlx7/i_am_using_react_for_front_end_should_i_skip/">[comments]</a></span>

## Show Django flash messages as toasts with Htmx
 - [https://www.reddit.com/r/django/comments/1hmqlba/show_django_flash_messages_as_toasts_with_htmx](https://www.reddit.com/r/django/comments/1hmqlba/show_django_flash_messages_as_toasts_with_htmx)
 - RSS feed: $source
 - date published: 2024-12-26T15:28:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/NodeJS4Lyfe"> /u/NodeJS4Lyfe </a> <br/> <span><a href="https://joshkaramuth.com/blog/django-messages-toast-htmx/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hmqlba/show_django_flash_messages_as_toasts_with_htmx/">[comments]</a></span>

## Vaga de freelancer Para Python/Django Remoto
 - [https://www.reddit.com/r/django/comments/1hmnsdk/vaga_de_freelancer_para_pythondjango_remoto](https://www.reddit.com/r/django/comments/1hmnsdk/vaga_de_freelancer_para_pythondjango_remoto)
 - RSS feed: $source
 - date published: 2024-12-26T12:54:26+00:00

<!-- SC_OFF --><div class="md"><p>Pessoal, Bom dia estou uma vaga de dev Freelancer:</p> <p>Experiencia em:</p> <p>Python usando o framework Django, </p> <p>experiencia com SQL, </p> <p>Banco de dados Oracle, </p> <p>conhecimento de triggers e views (Não iremos desenvolver triggers em SQL, porém já existe triggers e views prontas que iremos usá-las, importante entender o que a trigger faz),</p> <p>git</p> <p>Interessados entrar em contato no email: [<a href="mailto:ninjadaprogramacao@gmail.com">ninjadaprogramacao@gmail.com</a>](mailto:<a href="mailto:ninjadaprogramacao@gmail.com">ninjadaprogramacao@gmail.com</a>) informando seu nome, seu curriculo e de onde você viu a vaga.</p> <p>modelo:</p> <p>Remoto</p> <p>Fulltime</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pedrohesm"> /u/pedrohesm </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmnsdk/vaga_de_freelancer_para_pythondjango_remoto/">[link]</a></span> &#32; <span><a href

## Django with Bunny
 - [https://www.reddit.com/r/django/comments/1hmnpiv/django_with_bunny](https://www.reddit.com/r/django/comments/1hmnpiv/django_with_bunny)
 - RSS feed: $source
 - date published: 2024-12-26T12:49:16+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to use Bunny for media file storage, but every solution I&#39;ve attempted so far results in an error.</p> <p>Here’s what I’ve tried:</p> <ul> <li><code>django-bunny</code> - File upload works, but Wagtail gives an error when trying to create a rendition</li> <li><code>django-storages</code> (FTP) - File upload works, but the files can not be opened</li> <li><code>django-storages</code> (SFTP) - Does not work at all</li> </ul> <p>I&#39;ve noticed many people in this subreddit successfully using Bunny. How are you integrating it? I’d greatly appreciate any help :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DaddyAbdule"> /u/DaddyAbdule </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmnpiv/django_with_bunny/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hmnpiv/django_with_bunny/">[comments]</a></span>

## Would it be possible to host a django backend on an Android device?
 - [https://www.reddit.com/r/django/comments/1hmki0e/would_it_be_possible_to_host_a_django_backend_on](https://www.reddit.com/r/django/comments/1hmki0e/would_it_be_possible_to_host_a_django_backend_on)
 - RSS feed: $source
 - date published: 2024-12-26T08:51:42+00:00

<!-- SC_OFF --><div class="md"><p>Also, would it be possible for that backend to access sqlite on said Android device?</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/novis-ramus"> /u/novis-ramus </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmki0e/would_it_be_possible_to_host_a_django_backend_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hmki0e/would_it_be_possible_to_host_a_django_backend_on/">[comments]</a></span>

## Authentication state management reactnative django
 - [https://www.reddit.com/r/django/comments/1hmjyke/authentication_state_management_reactnative_django](https://www.reddit.com/r/django/comments/1hmjyke/authentication_state_management_reactnative_django)
 - RSS feed: $source
 - date published: 2024-12-26T08:08:17+00:00

<!-- SC_OFF --><div class="md"><p>so i am a nub, and this is my first project i&#39;ve created login page and signup and used drf to connect, everything works fine and when i create user and login then i&#39;ve placed welcome,firstname. now i want to make my app acessible after login and i found out i&#39;ve to learn autentication state but when searching i can&#39;t find any docs or proper tutorial related to the stuff. so plz help guys any docs or tutorial. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Significant-Ad3434"> /u/Significant-Ad3434 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmjyke/authentication_state_management_reactnative_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hmjyke/authentication_state_management_reactnative_django/">[comments]</a></span>

## How to use Django-allauth(Oauth2) access token to share youtube private videos securely .
 - [https://www.reddit.com/r/django/comments/1hmibth/how_to_use_djangoallauthoauth2_access_token_to](https://www.reddit.com/r/django/comments/1hmibth/how_to_use_djangoallauthoauth2_access_token_to)
 - RSS feed: $source
 - date published: 2024-12-26T06:06:38+00:00

<!-- SC_OFF --><div class="md"><p>I am building a website and I want to use Oauth acces token to share my private youtube videos.</p> <p>And the access token from django-allauth is not working </p> <p>jn settings.py i have set the SCOPE to yiutube.readonly and force-ssl</p> <p>Any help please before I lose a client 🙏</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sural_mk"> /u/sural_mk </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmibth/how_to_use_djangoallauthoauth2_access_token_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hmibth/how_to_use_djangoallauthoauth2_access_token_to/">[comments]</a></span>

## Affordable and Reliable Hosting for Django Project with PostgreSQL, Redis, and AWS S3?
 - [https://www.reddit.com/r/django/comments/1hmhox1/affordable_and_reliable_hosting_for_django](https://www.reddit.com/r/django/comments/1hmhox1/affordable_and_reliable_hosting_for_django)
 - RSS feed: $source
 - date published: 2024-12-26T05:25:03+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m developing a Django project which includes several key modules:</p> <ul> <li><strong>AI Integration</strong>: Uses OpenAI to provide crop recommendations and chatbot features.</li> <li><strong>Weather Module</strong>: Incorporates weather data to assist with planning and insights.</li> <li><strong>Mapping Tools</strong>: Utilizes Mapbox for GIS-related functionalities, like visualizing field and crop data.</li> <li><strong>User Management:</strong> Manages user accounts, authentication and auth.</li> </ul> <p>The app requires PostgreSQL for the database, Redis for caching, and AWS S3 for media and static files. I’m looking for a hosting platform that is both affordable and highly reliable for these requirements. Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Franz_breezy"> /u/Franz_breezy </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hmhox1/affordable_and_relia

## URGENT HELP: return jwt with django-allauth headless API
 - [https://www.reddit.com/r/django/comments/1hmdory/urgent_help_return_jwt_with_djangoallauth](https://www.reddit.com/r/django/comments/1hmdory/urgent_help_return_jwt_with_djangoallauth)
 - RSS feed: $source
 - date published: 2024-12-26T01:23:10+00:00

<!-- SC_OFF --><div class="md"><p>For some weird reason, I can&#39;t wrap my head around returning a JWT as against django-allauth&#39;s session token on user login, whether regular login or even social auth. I can&#39;t even find a tutorial that guides.</p> <p>I know allauth&#39;s docs say to create a custom token strategy, but I&#39;ve done this, and it just doesn&#39;t return JWT.</p> <pre><code>HEADLESS_ONLY = True HEADLESS_ALLOW_BEARER_TOKEN = True TOKEN_STRATEGY=&#39;user.adapters.JWTTokenStrategy&#39; ACCOUNT_AUTHENTICATION_METHOD = &#39;username_email&#39; ACCOUNT_EMAIL_REQUIRED = True ACCOUNT_UNIQUE_EMAIL = True ACCOUNT_USERNAME_REQUIRED = True ACCOUNT_EMAIL_VERIFICATION = &#39;mandatory&#39; # Automatically verify on email click ACCOUNT_CONFIRM_EMAIL_ON_GET = True ACCOUNT_LOGIN_ON_EMAIL_CONFIRMATION = False ACCOUNT_RATE_LIMIT = &quot;20/m/ip,5/m/key&quot; ACCOUNT_EMAIL_CONFIRMATION_AUTHENTICATED_REDIRECT_URL = None ACCOUNT_EMAIL_CONFIRMATION_ANONYMOUS_REDIRECT_URL = None AC

