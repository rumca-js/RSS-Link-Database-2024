# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## How can i get better at asking better questions so i can build better software with less meetings
 - [https://www.reddit.com/r/django/comments/1fllt76/how_can_i_get_better_at_asking_better_questions](https://www.reddit.com/r/django/comments/1fllt76/how_can_i_get_better_at_asking_better_questions)
 - RSS feed: $source
 - date published: 2024-09-20T20:31:32+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys I&#39;m a junior developer currently working in banking and I want to know how can i learn to ask better questions so i can take business requirements and make the required software with as little meetings as possible</p> <p>I believe im a decent developer but i struggle to ask the right questions therefore there is alot of changes that happen throughout the duration of development, ive been fortunate enough to be allowed to build whole features alone but i feel my bad communication will hinder my growth. Any tips</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Themba47"> /u/Themba47 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fllt76/how_can_i_get_better_at_asking_better_questions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fllt76/how_can_i_get_better_at_asking_better_questions/">[comments]</a></span>

## Django, succesful redirect does not redirects
 - [https://www.reddit.com/r/django/comments/1flkc3i/django_succesful_redirect_does_not_redirects](https://www.reddit.com/r/django/comments/1flkc3i/django_succesful_redirect_does_not_redirects)
 - RSS feed: $source
 - date published: 2024-09-20T19:27:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I need some help. I just added a middleware to redirect the AnonymousUser to login page when they wants to buy a product.</p> <p>I integrated stripe, when they click to checkout button they sent a post reqeust to /stripe/checkout/.</p> <p>Here is my code:</p> <pre><code># middleware from django.shortcuts import redirect from django.urls import reverse class PaymentAuthenticationMiddleware: def __init__(self, get_response): self.get_response = get_response def __call__(self, request): protected_urls = [ &#39;/stripe/checkout/&#39;, ] if request.path == reverse(&#39;account_login&#39;): return self.get_response(request) if not request.user.is_authenticated: for url in protected_urls: if request.path.startswith(url): return redirect(reverse(&#39;account_login&#39;)) return self.get_response(request) # settings MIDDLEWARE = [ &quot;django.middleware.security.SecurityMiddleware&quot;, &quot;django.contrib.sessions.middleware.SessionMiddleware&

## 2 powerful frameworks: Using Django with Next.js 🥷⚛️
 - [https://www.reddit.com/r/django/comments/1fliuun/2_powerful_frameworks_using_django_with_nextjs](https://www.reddit.com/r/django/comments/1fliuun/2_powerful_frameworks_using_django_with_nextjs)
 - RSS feed: $source
 - date published: 2024-09-20T18:22:59+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/tomdekan"> /u/tomdekan </a> <br/> <span><a href="https://youtu.be/lVZ3kzXGWnk">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fliuun/2_powerful_frameworks_using_django_with_nextjs/">[comments]</a></span>

## Has anyone had any luck automating the writing of unit tests with AI?
 - [https://www.reddit.com/r/django/comments/1fle7h2/has_anyone_had_any_luck_automating_the_writing_of](https://www.reddit.com/r/django/comments/1fle7h2/has_anyone_had_any_luck_automating_the_writing_of)
 - RSS feed: $source
 - date published: 2024-09-20T15:04:47+00:00

<!-- SC_OFF --><div class="md"><p>We all know that writing tests is time consuming and annoying but in large applications they&#39;re kinda a requirement. </p> <p>I want to automate this process as much as possible - even if its just scaffolding some basic tests that work in a similar way to rest of our application.</p> <p>Does anyone have any tools or suggestions for ways to make this a simple and successful process?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jazzlike-Compote4463"> /u/Jazzlike-Compote4463 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fle7h2/has_anyone_had_any_luck_automating_the_writing_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fle7h2/has_anyone_had_any_luck_automating_the_writing_of/">[comments]</a></span>

## How to plan a new feature?
 - [https://www.reddit.com/r/django/comments/1flagah/how_to_plan_a_new_feature](https://www.reddit.com/r/django/comments/1flagah/how_to_plan_a_new_feature)
 - RSS feed: $source
 - date published: 2024-09-20T12:10:45+00:00

<!-- SC_OFF --><div class="md"><p>Iam a full-stack developer and every time I want to plan a new feature it feels very overwhelming and hard. Although my skills are way beyond this required feature yet I alwayys struggle. I read that I need to break the problem down but I don&#39;t know how to start thinking about breaking it. </p> <p>Can you guys olease tell me if you yave experience how do you plan such feature. And if there are tools that help? Also shall I write pseudo code or it is not always a good idea?</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UpstairsBaby"> /u/UpstairsBaby </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1flagah/how_to_plan_a_new_feature/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1flagah/how_to_plan_a_new_feature/">[comments]</a></span>

## Easy way to showcase a vulnerability in v1?
 - [https://www.reddit.com/r/django/comments/1fl9if9/easy_way_to_showcase_a_vulnerability_in_v1](https://www.reddit.com/r/django/comments/1fl9if9/easy_way_to_showcase_a_vulnerability_in_v1)
 - RSS feed: $source
 - date published: 2024-09-20T11:17:14+00:00

<!-- SC_OFF --><div class="md"><p>Hello we use django for a relatively small application at a small start up. We are still in django v1 and I attempted to make a case to the CEO that we should spend the dev time to update because of vulnerabilities (according to django website). He was hesatent to do it since we have so much other stuff to get to.</p> <p>I was wondering if there were ways I can &quot;hack&quot; our application to showcase this is serious or is the idea that v1 is vulnerable more of a scare tactic to upgrade django? Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PotentialCopy56"> /u/PotentialCopy56 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fl9if9/easy_way_to_showcase_a_vulnerability_in_v1/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fl9if9/easy_way_to_showcase_a_vulnerability_in_v1/">[comments]</a></span>

## What's the best way to implement a dynamic layout, printable report documents (PDF) export feature?
 - [https://www.reddit.com/r/django/comments/1fl8ega/whats_the_best_way_to_implement_a_dynamic_layout](https://www.reddit.com/r/django/comments/1fl8ega/whats_the_best_way_to_implement_a_dynamic_layout)
 - RSS feed: $source
 - date published: 2024-09-20T10:03:07+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently working on a Django SaaS app that will be used by multiple clients. This app will have a reporting feature that exports some standardized documents (as in, the contents will be more or less the same) which contains data fully processed within the app. The current problem is, each client have different layouts for those documents and one of the requirements is that the clients can set their own layouts by themselves.</p> <p>Previously I already did something similar for another app, although it&#39;s only used by one client. I used a rich text editor (TinyMCE) embedded in the app to let the user define the document layouts by typing and placing predefined tags. When the user needed to export a document, the app would render the layout accordingly to HTML string using Django&#39;s templating engine, and finally to PDF using PDFKit (wkhtmltopdf wrapper).</p> <p>Later I found that method is not very intuitive for the users since most of 

## File system for dynamic files
 - [https://www.reddit.com/r/django/comments/1fl81a7/file_system_for_dynamic_files](https://www.reddit.com/r/django/comments/1fl81a7/file_system_for_dynamic_files)
 - RSS feed: $source
 - date published: 2024-09-20T09:36:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, i&#39;m building a webapp where users can upload and edit personal files. What would be the most efficient way of storing these files?</p> <p>I am looking at <strong>object storage</strong> (S3 bucket, Azure Blob etc), but it seems this is mostly for serving data rather than dynamically editing these files, is this assumption correct? Just storing them on a local filesystem on a <strong>VPS</strong> seems easiest, but i am concerned about security and scalability.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alpaca_bananas"> /u/alpaca_bananas </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fl81a7/file_system_for_dynamic_files/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fl81a7/file_system_for_dynamic_files/">[comments]</a></span>

## I am finding the official docs of Django Rest Framework Overwhelming
 - [https://www.reddit.com/r/django/comments/1fl7m3z/i_am_finding_the_official_docs_of_django_rest](https://www.reddit.com/r/django/comments/1fl7m3z/i_am_finding_the_official_docs_of_django_rest)
 - RSS feed: $source
 - date published: 2024-09-20T09:03:51+00:00

<!-- SC_OFF --><div class="md"><p>I am constantly trying to grasp the idea about DRF from their docs but I am afraid and overwhelmed by the topics and languages used there. Most of the time when I sit to read certain topic and while reading the topic there comes another topic or feature which is new to me and I click into that link and the cycle repeats and I found myself to be lost. If you are in the field of DRF, please suggest me how you get confidence at your initial days and what we&#39;re the strategies you used to grasp the good understanding over this framework. Your suggestions would also mean another. Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/icyyyashish"> /u/icyyyashish </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fl7m3z/i_am_finding_the_official_docs_of_django_rest/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fl7m3z/i_am_finding_the_official_docs_of_django_r

## What to learn beside Django
 - [https://www.reddit.com/r/django/comments/1fl72wj/what_to_learn_beside_django](https://www.reddit.com/r/django/comments/1fl72wj/what_to_learn_beside_django)
 - RSS feed: $source
 - date published: 2024-09-20T08:22:23+00:00

<!-- SC_OFF --><div class="md"><p>3Y+ dev in Django, DRF. Designing and implementing REST API alongside Frontends (Angular, if it does matter) However, I feel like I haven&#39;t seen other ways to make a backend. Class Based View Is almost all I&#39;ve made and I haven&#39;t praticed MVC since school, 7 years ago. Backend and Frontend have almost always been separated in my experiences, I&#39;ve barely experienced server-side rendering, and I swear in python.</p> <p>What language/framework would you suggest be a good way to learn other ways of making backend? Should I try Node, Go? Is Rust truly worth it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/marmotte-de-beurre"> /u/marmotte-de-beurre </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fl72wj/what_to_learn_beside_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fl72wj/what_to_learn_beside_django/">[comments]</a></span>

## I am developing expense tracker what functionality should i add ?
 - [https://www.reddit.com/r/django/comments/1fl5wa5/i_am_developing_expense_tracker_what](https://www.reddit.com/r/django/comments/1fl5wa5/i_am_developing_expense_tracker_what)
 - RSS feed: $source
 - date published: 2024-09-20T06:50:32+00:00

<!-- SC_OFF --><div class="md"><p>I use React as frontend and DRF as backend what should i add??</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/goku___________"> /u/goku___________ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fl5wa5/i_am_developing_expense_tracker_what/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fl5wa5/i_am_developing_expense_tracker_what/">[comments]</a></span>

## Best way to eliminate or reduce redundancy in views?
 - [https://www.reddit.com/r/django/comments/1fkzzih/best_way_to_eliminate_or_reduce_redundancy_in](https://www.reddit.com/r/django/comments/1fkzzih/best_way_to_eliminate_or_reduce_redundancy_in)
 - RSS feed: $source
 - date published: 2024-09-20T00:56:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m in the process of building a live chat using django_channels and frontend as reactJS. In this project, I&#39;m trying to be more familiar with class based views and utilize them as much as I can . The question that I have is what is the convention or best practice when eliminating or reducing redundancy in the views. I have three sets of snippets in the bottom and all of them are using .list() method to implement .filter(). Is there a way to reduce this or better way to this with less code? Any info will be greatly appreciated. Thank you very much. </p> <pre><code>class CommunityMessagesView(ListAPIView): queryset = CommunityMessage.objects.all() # authentication_classes = [TokenAuthentication] # permission_classes = [IsAuthenticated] def list(self, request, *args, **kwargs): queryset = self.get_queryset().filter(community__name=kwargs[&#39;community_name&#39;]) serializer = CommunityMessageSerializer(queryset, many=True) return Response(seria

## ModuleNotFoundError: No module named 'blogs'
 - [https://www.reddit.com/r/django/comments/1fkz2uo/modulenotfounderror_no_module_named_blogs](https://www.reddit.com/r/django/comments/1fkz2uo/modulenotfounderror_no_module_named_blogs)
 - RSS feed: $source
 - date published: 2024-09-20T00:09:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> I&#39;m new into all of this, but I wanted to give it a try.<br/> I was following a tutorial, and I didn&#39;t know where I messed up. I make sure that everything was installed. I followed every instruction given and I&#39;ve seen the video over 10 times, and I don&#39;t know what I&#39;m doing wrong, so if any one can help me, thank you so much in advance. </p> <p><a href="https://preview.redd.it/sdmpx1l0wupd1.png?width=1339&amp;format=png&amp;auto=webp&amp;s=bc7ea417e8f1b0111cb454180118f8c80cadcb56">This is an screenshot of the Issue.</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Serious-Walk-221"> /u/Serious-Walk-221 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fkz2uo/modulenotfounderror_no_module_named_blogs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fkz2uo/modulenotfounderror_no_module_named_blogs/">[comments]</a></span>

