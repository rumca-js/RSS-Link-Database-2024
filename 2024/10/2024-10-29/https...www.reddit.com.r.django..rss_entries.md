# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django with celery and postgres database to AKS
 - [https://www.reddit.com/r/django/comments/1gf71s2/django_with_celery_and_postgres_database_to_aks](https://www.reddit.com/r/django/comments/1gf71s2/django_with_celery_and_postgres_database_to_aks)
 - RSS feed: $source
 - date published: 2024-10-29T22:12:48+00:00

<!-- SC_OFF --><div class="md"><p>I am anodejs developer, recently started working on django and i liked the simplicity and power of framework, i configured a project using cookiecutter-django, this had everything you need to start the app, i created a decent working MVP but now i want to deploy it on AKS, not sure how to do that, tried AKS github workflows to deploy but failed, then i managed to write shell scripting to provision new AKS cluster along with azure container registry, and this script is building, pushing and deploy image to AKS, but things still not working for me, i am not able to open app using public ip. I am working on it to fix this. </p> <p>I believe things cant be that difficult, Is there any simple way to deploy cookiecutter-django app to kubernetes cluster on azure??</p> <p>Thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lonedevlpr"> /u/lonedevlpr </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/

## Django and AI
 - [https://www.reddit.com/r/django/comments/1geztln/django_and_ai](https://www.reddit.com/r/django/comments/1geztln/django_and_ai)
 - RSS feed: $source
 - date published: 2024-10-29T17:10:33+00:00

<!-- SC_OFF --><div class="md"><p>The AI boom has brought so many frameworks and tools to the python community but very few of them use Django as their main backbone. </p> <p>Since I think Django has some unbelievable features, I decided to make the next AI tool with Django. </p> <p>It&#39;s goal is to improve the developer experience for developers that use frameworks like llama-index and langchain. </p> <p>here is the project </p> <p><a href="https://github.com/epuerta9/kitchenai">https://github.com/epuerta9/kitchenai</a></p> <p>If you like it, please give it a star and share ⭐ </p> <p>Also looking for contributors if anyone is interested :) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wait-a-minut"> /u/wait-a-minut </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1geztln/django_and_ai/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1geztln/django_and_ai/">[comments]</a></span>

## form don't get image input
 - [https://www.reddit.com/r/django/comments/1gevx6d/form_dont_get_image_input](https://www.reddit.com/r/django/comments/1gevx6d/form_dont_get_image_input)
 - RSS feed: $source
 - date published: 2024-10-29T14:26:25+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/zs5mkuckfpxd1.png?width=335&amp;format=png&amp;auto=webp&amp;s=4d18a733335ce6721b806ee157fcfadf8d45a024">screenshot error</a></p> <p>i make item add logic with CreateView class for user foreignkey user relation but when i give image input it does take image input and show (this field is required). i already give image input, again showing same error. i already write MEDIA_URL and other media settings</p> <pre><code>class ItemCreateView(CreateView): model = Item fields = [&#39;name&#39;,&#39;desp&#39;,&#39;price&#39;,&#39;image&#39;] template_name = &#39;add.html&#39; success_url = reverse_lazy(&#39;home&#39;) def form_valid(self, form): form.instance.user = self.request.user return super().form_valid(form) </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legal_Relief6756"> /u/Legal_Relief6756 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gevx6d/form

## Working with CustomUser model
 - [https://www.reddit.com/r/django/comments/1gesdha/working_with_customuser_model](https://www.reddit.com/r/django/comments/1gesdha/working_with_customuser_model)
 - RSS feed: $source
 - date published: 2024-10-29T11:32:29+00:00

<!-- SC_OFF --><div class="md"><p>I am working with CustomUser model which is inherting User model. And in other models where I needed CustomUser model as ForeignKey(fk), at the top of the <a href="http://model.py">model.py</a> I use <code>User=get_user_model()</code> and use User in the models.</p> <p>Recently, I need to set up an extra field m2m field with the CustomUser. When I try to makemigrations, i got an error like CustomUser model not defined, app is not installed etc.</p> <p>I also tried using get_user_model() method directly in the field. But I got CircularImport Error.</p> <p>How do I fix this? I am on the verge of resetting the entire database. So please help. If you have thoughts or standard way of doing this, please tell</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/captainrdx"> /u/captainrdx </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gesdha/working_with_customuser_model/">[link]</a></span> &#32; <span><

## 🚀 Open Source Contribution: Help Us Build a Robotics Club Management System in Django
 - [https://www.reddit.com/r/django/comments/1geq7xq/open_source_contribution_help_us_build_a_robotics](https://www.reddit.com/r/django/comments/1geq7xq/open_source_contribution_help_us_build_a_robotics)
 - RSS feed: $source
 - date published: 2024-10-29T09:07:47+00:00

<!-- SC_OFF --><div class="md"><p>Hello, everyone! We&#39;re a group of robotics enthusiasts working on a Robotics Club Management System using Django, and we&#39;re looking for contributors to help us improve it! 🎉 About the Project: Our project aims to streamline the management of robotics clubs, making it easier for members to collaborate, manage events, and track projects. While we&#39;re excited about our progress, we’re still learning Django and could really use your expertise! What We&#39;re Looking For:</p> <ul> <li>Developers familiar with Django to help with code reviews and feature development</li> <li>Anyone interested in contributing through documentation, testing, or design</li> <li>Suggestions and feedback to improve our project Getting Started: You can find our project here: <a href="https://github.com/SANTHOSH-MAMIDISETTI/robotics_club_management">GitHub Repository</a>. We’ve included setup instructions in the README to help you get started. How to Contribute:</li> <

## Do django developers need to learn frontend?
 - [https://www.reddit.com/r/django/comments/1geoexd/do_django_developers_need_to_learn_frontend](https://www.reddit.com/r/django/comments/1geoexd/do_django_developers_need_to_learn_frontend)
 - RSS feed: $source
 - date published: 2024-10-29T06:46:34+00:00

<!-- SC_OFF --><div class="md"><p>Is learning javascript and react necessary to get a remote job as a django developer?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sea-Catch5150"> /u/Sea-Catch5150 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1geoexd/do_django_developers_need_to_learn_frontend/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1geoexd/do_django_developers_need_to_learn_frontend/">[comments]</a></span>

## 2025 DSF Board Candidates
 - [https://www.reddit.com/r/django/comments/1gekif5/2025_dsf_board_candidates](https://www.reddit.com/r/django/comments/1gekif5/2025_dsf_board_candidates)
 - RSS feed: $source
 - date published: 2024-10-29T02:41:20+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2024/oct/28/2025-dsf-board-candidates/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gekif5/2025_dsf_board_candidates/">[comments]</a></span>

