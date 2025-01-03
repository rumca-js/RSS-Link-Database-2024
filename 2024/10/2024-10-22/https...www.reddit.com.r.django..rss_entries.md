# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## How call a Django API from inside a Django process?
 - [https://www.reddit.com/r/django/comments/1g9v4p4/how_call_a_django_api_from_inside_a_django_process](https://www.reddit.com/r/django/comments/1g9v4p4/how_call_a_django_api_from_inside_a_django_process)
 - RSS feed: $source
 - date published: 2024-10-22T22:34:41+00:00

<!-- SC_OFF --><div class="md"><p>I have complex Django app with many different endpoints and pretty complicated filtering. </p> <p>I want to build an export service that accepts the URL and query string. The makes a call and it pages thru the data writes to a file.</p> <p>For example, say there is a User API: &quot;/api/users/?name__startswith=Bob&quot;</p> <p>Consider the database is larger and there are 100k &quot;Bobs&quot;. I want to page thru this and write results to a file. Finally, the query sets behind the API are sensitive to which user calls them. So the results are dependent on <code>request.user</code>.</p> <p>For large exports, this has to run in background task. The question is how in the background test do I effectively fake the user auth. I can&#39;t just copy the user auth over as it may/will expire.</p> <p>I could easily write the ORM again, but I really want to use the existing filters and validated business logic.</p> <p>The only way I have come up so far is to u

## Ignore Specific Error "Invalid HTTP_HOST header"
 - [https://www.reddit.com/r/django/comments/1g9uwkp/ignore_specific_error_invalid_http_host_header](https://www.reddit.com/r/django/comments/1g9uwkp/ignore_specific_error_invalid_http_host_header)
 - RSS feed: $source
 - date published: 2024-10-22T22:24:24+00:00

<!-- SC_OFF --><div class="md"><p>I keep getting these errors for a subdomain:</p> <pre><code>Invalid HTTP_HOST header: &#39;mail.domain.com&#39;. You may need to add &#39;mail.domain.com&#39; to ALLOWED_HOSTS. </code></pre> <p>I don&#39;t have the domain domain in allowed_hosts and I don&#39;t want to add it because it shouldn&#39;t be handled by the app.</p> <p>I&#39;m assuming the reason I&#39;m always getting these is because of malware scans because the URLS are always like:</p> <pre><code>http://mail.domain.com/.well-known/pki-validation/de06e834-937c-4b4e-a67c-8f85e4cec8c2.php http://mail.domain.com/.well-known/pki-validation/8919b61a-3ada-4193-8f3f-9a11b5df6454.php http://mail.domain.com/.well-known/pki-validation/xmrlpc.php?p= http://mail.domain.com/.well-known/pki-validation/classwithtostring.php http://mail.domain.com/.well-known/pki-validation/404.php </code></pre> <p>The app is hosted on a cPanel and I tried blocking and redirecting these requests before the app loads on 

## What's a good and complete Django course?
 - [https://www.reddit.com/r/django/comments/1g9kk6p/whats_a_good_and_complete_django_course](https://www.reddit.com/r/django/comments/1g9kk6p/whats_a_good_and_complete_django_course)
 - RSS feed: $source
 - date published: 2024-10-22T15:14:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello internet, I have decent experince with python and have used flask for a few personal projects before. I wanted to learn django because I heard that&#39;s what the cool kids use </p> <p>Intitially I was going to buy this course<br/> <a href="https://www.udemy.com/course/python-and-django-full-stack-web-developer-bootcamp/">https://www.udemy.com/course/python-and-django-full-stack-web-developer-bootcamp/</a></p> <p>as it&#39;s the most rated course on udemy but then I looked at the last_update date 2019 ;-; it uses django 1.1 </p> <p>I want a course that is up-to-date and possibly have many projects so I can &quot;actually&quot; learn </p> <p>while searching on reddit a lot of people talked about <a href="https://www.udemy.com/user/dennis-ivanov-5/">Dennis Ivy</a></p> <p>So I was thinking of learning via this course:</p> <p><a href="https://www.udemy.com/course/python-django-2021-complete-course/">https://www.udemy.com/course/python-django-2021-co

## Django frontend rendering vs React
 - [https://www.reddit.com/r/django/comments/1g9khn3/django_frontend_rendering_vs_react](https://www.reddit.com/r/django/comments/1g9khn3/django_frontend_rendering_vs_react)
 - RSS feed: $source
 - date published: 2024-10-22T15:11:09+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, I don&#39;t know if some of you have experience in both Django and React/Next . Do you feel that Django+HTMX is limitating compared to what you can achieve with React + (any backend) ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bdavidxyz"> /u/bdavidxyz </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g9khn3/django_frontend_rendering_vs_react/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g9khn3/django_frontend_rendering_vs_react/">[comments]</a></span>

## Easiest way to communicate between Django and Postgres?
 - [https://www.reddit.com/r/django/comments/1g9gwds/easiest_way_to_communicate_between_django_and](https://www.reddit.com/r/django/comments/1g9gwds/easiest_way_to_communicate_between_django_and)
 - RSS feed: $source
 - date published: 2024-10-22T12:27:15+00:00

<!-- SC_OFF --><div class="md"><p>Wrote a db for a website last night. Spending the day trying to connect it to my django backend. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RevengeOfNell"> /u/RevengeOfNell </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g9gwds/easiest_way_to_communicate_between_django_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g9gwds/easiest_way_to_communicate_between_django_and/">[comments]</a></span>

## Micro services with Django
 - [https://www.reddit.com/r/django/comments/1g9et8z/micro_services_with_django](https://www.reddit.com/r/django/comments/1g9et8z/micro_services_with_django)
 - RSS feed: $source
 - date published: 2024-10-22T10:23:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks I have done two big Django project they were monolithic</p> <p>But i really like the idea of micro services but i was wondering is it worth the headache </p> <p>Let&#39;s make this discussion about when micro services will be indicated So</p> <p>1 why</p> <p>2 when</p> <p>3 design cause i found people separate db or share it between multiple services</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sorry_Asparagus_3194"> /u/Sorry_Asparagus_3194 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g9et8z/micro_services_with_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g9et8z/micro_services_with_django/">[comments]</a></span>

## Email Verification in Django
 - [https://www.reddit.com/r/django/comments/1g9dvgb/email_verification_in_django](https://www.reddit.com/r/django/comments/1g9dvgb/email_verification_in_django)
 - RSS feed: $source
 - date published: 2024-10-22T09:14:18+00:00

<!-- SC_OFF --><div class="md"><h1>SMTPAuthenticationError at /signup/</h1> <p>Can anyone help me in fixing this error. As i using django smtp authentication for the signup and email verification and it is not working even though i modified it. it gives me </p> <pre><code>Username and Password not accepted </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Inside_Meet_4991"> /u/Inside_Meet_4991 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g9dvgb/email_verification_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g9dvgb/email_verification_in_django/">[comments]</a></span>

## django-cotton global 'only'
 - [https://www.reddit.com/r/django/comments/1g9aue6/djangocotton_global_only](https://www.reddit.com/r/django/comments/1g9aue6/djangocotton_global_only)
 - RSS feed: $source
 - date published: 2024-10-22T05:29:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I&#39;ve started a project with django-cotton, and more people will start working on it soon.<br/> I want to avoid using context variables willy nilly. There&#39;s an &#39;only&#39; attribute in django-cotton which makes sure that the component only gets the attributes I&#39;ve explicitly passed to it.<br/> Right now I&#39;m just slapping it on every component I put in the templates, but I&#39;d like to avoid the possibility of forgetting to do so.</p> <p>Any ideas/tips on how to apply it to all components in the project without explicitly writing it out everywhere?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vegeq"> /u/vegeq </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g9aue6/djangocotton_global_only/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g9aue6/djangocotton_global_only/">[comments]</a></span>

## I'm having trouble using JS packages in django.
 - [https://www.reddit.com/r/django/comments/1g99mke/im_having_trouble_using_js_packages_in_django](https://www.reddit.com/r/django/comments/1g99mke/im_having_trouble_using_js_packages_in_django)
 - RSS feed: $source
 - date published: 2024-10-22T04:13:15+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know of any YouTube tutorials that explain how to use npm with django? I was trying to use GSAP in my JavaScript template file but the import simply wouldn&#39;t work. The only way was to use inline JS to import it. I need to be able to install packages and import them in my Django file.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g99mke/im_having_trouble_using_js_packages_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g99mke/im_having_trouble_using_js_packages_in_django/">[comments]</a></span>

## Having hard time implementing search functionality in django
 - [https://www.reddit.com/r/django/comments/1g98l21/having_hard_time_implementing_search](https://www.reddit.com/r/django/comments/1g98l21/having_hard_time_implementing_search)
 - RSS feed: $source
 - date published: 2024-10-22T03:15:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a complete beginner in backend development and I&#39;m currently working on a search functionality that includes multiple advanced filters. I&#39;m using Django Filters for filtering, but since I&#39;m new to this, I haven&#39;t found many tutorials on YouTube. Most of the content I came across relates to Q objects, which raises the question of which is better to use: Django Filters or Q objects?</p> <p>Additionally, I&#39;m gathering data from APIs for weather, air quality, and datasets related to the cost of living. I&#39;m unsure how to store this data so that when users apply filters in their searches, the system can display relevant cities. The project is aimed at digital nomads looking for cities based on specific criteria.</p> <p>I would greatly apprciate any guidance on these topics, and I apologize if my questions seem basic.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/misba_ImaginaryLimit"> 

## Configuring a Lambda to act as a Celery Worker.
 - [https://www.reddit.com/r/django/comments/1g97dfl/configuring_a_lambda_to_act_as_a_celery_worker](https://www.reddit.com/r/django/comments/1g97dfl/configuring_a_lambda_to_act_as_a_celery_worker)
 - RSS feed: $source
 - date published: 2024-10-22T02:11:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i&#39;m looking for advise on how to proper use a lambda to mimic a worker job, by using the following configuration:</p> <p>AWS MQ using rabbitMQ as broker.</p> <p>Lambda with configured Trigger listening on a MQ queue.</p> <p>A Workflow defined in my celery app with some tasks:</p> <p>task_01: runs on a celery worker instance.<br/> task_02: runs on lambda, i put then on a specific queue that no other worker listen to.<br/> task_03: runs on a celery worker instance.</p> <pre><code> workflow = chain( task_01.s(), task_02.s(), task_03.s() ) </code></pre> <p>If i execute task_01, the lambda on task_02 is triggered correctly, but i need to mimic celery code, save the result to the backend and trigger task_03 correctly.</p> <p>I&#39;m currently using the code below to save the task_02 result, but i need to make some workflow functions like chain, group, chord, to be called.</p> <pre><code>from celery.worker.request import Request def handler(event, co

## I'm working with a huge API (Close CRM) to build an app, what's the best way to save the API responses so I can process and update them easily later?
 - [https://www.reddit.com/r/django/comments/1g96g6e/im_working_with_a_huge_api_close_crm_to_build_an](https://www.reddit.com/r/django/comments/1g96g6e/im_working_with_a_huge_api_close_crm_to_build_an)
 - RSS feed: $source
 - date published: 2024-10-22T01:24:59+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m building a project trying to connect READ.AI and Close CRM together and I need to work with Close CRM API, I&#39;m looking for the best way to save the responses to use later. Raw JSON would be good? Or saving in a database is more efficient?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Minarctic"> /u/Minarctic </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1g96g6e/im_working_with_a_huge_api_close_crm_to_build_an/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1g96g6e/im_working_with_a_huge_api_close_crm_to_build_an/">[comments]</a></span>

