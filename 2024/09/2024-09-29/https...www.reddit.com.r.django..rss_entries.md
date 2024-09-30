# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Major Update: Simplify HTTP Security Headers in Django with secure.py
 - [https://www.reddit.com/r/django/comments/1fshldo/major_update_simplify_http_security_headers_in](https://www.reddit.com/r/django/comments/1fshldo/major_update_simplify_http_security_headers_in)
 - RSS feed: $source
 - date published: 2024-09-29T23:18:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi Django developers,</p> <p>A major update to <strong>secure.py</strong> has been released—a Python library that simplifies managing HTTP security headers in your Django applications. This release is a complete rewrite, leveraging modern Python 3.10+ features for better performance and usability.</p> <p><strong>Why Use secure.py with Django?</strong></p> <ul> <li><strong>Quick Setup</strong>: Apply BASIC or STRICT security headers with just one line.</li> <li><strong>Full Customization</strong>: Control headers like Content-Security-Policy (CSP), HSTS, X-Frame-Options, Referrer-Policy, and more.</li> <li><strong>Seamless Integration</strong>: Works smoothly with Django&#39;s middleware and view functions.</li> </ul> <p><strong>How to Integrate secure.py in Your Django Project</strong></p> <p><strong>Middleware Example:</strong></p> <p>```python from django.http import HttpResponse from secure import Secure</p> <p>secure_headers = Secure.with_default_

## Experience Django developer looking for freelance work
 - [https://www.reddit.com/r/django/comments/1fsh7vr/experience_django_developer_looking_for_freelance](https://www.reddit.com/r/django/comments/1fsh7vr/experience_django_developer_looking_for_freelance)
 - RSS feed: $source
 - date published: 2024-09-29T22:59:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for freelance software development or data engineering work. I can make web applications, interactive maps, data pipelines, or interactive data visualizations. Give me some messy data, and I’ll put it into a database and on a website for you. </p> <p>You can see some highlights of my work here: <a href="https://www.bookhead.net/sam-mcalilly/">https://www.bookhead.net/sam-mcalilly/</a></p> <p>DM me or email me at <a href="mailto:sam@bookhead.net">sam@bookhead.net</a> if you’re interested in working together.</p> <p>p.s. I&#39;m based in the US and looking for remote opportunities.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/greenie_beans11"> /u/greenie_beans11 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fsh7vr/experience_django_developer_looking_for_freelance/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fsh7vr/experience_django_devel

## Verbose CSRF Middleware
 - [https://www.reddit.com/r/django/comments/1fse80y/verbose_csrf_middleware](https://www.reddit.com/r/django/comments/1fse80y/verbose_csrf_middleware)
 - RSS feed: $source
 - date published: 2024-09-29T20:41:41+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/klaasvanschelven"> /u/klaasvanschelven </a> <br/> <span><a href="https://www.bugsink.com/docs/verbose_csrf_middleware/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fse80y/verbose_csrf_middleware/">[comments]</a></span>

## Meta vs IBM backend or other at Coursera
 - [https://www.reddit.com/r/django/comments/1fs6nb5/meta_vs_ibm_backend_or_other_at_coursera](https://www.reddit.com/r/django/comments/1fs6nb5/meta_vs_ibm_backend_or_other_at_coursera)
 - RSS feed: $source
 - date published: 2024-09-29T15:14:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i&#39;ve been overthinking a bout what of these course should i to take and not waste my time. please tell me what do you did or what of these is better. thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PerspectiveAfter9039"> /u/PerspectiveAfter9039 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fs6nb5/meta_vs_ibm_backend_or_other_at_coursera/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fs6nb5/meta_vs_ibm_backend_or_other_at_coursera/">[comments]</a></span>

## Pyenv with Global System pkgs (apt install)
 - [https://www.reddit.com/r/django/comments/1fs4ip0/pyenv_with_global_system_pkgs_apt_install](https://www.reddit.com/r/django/comments/1fs4ip0/pyenv_with_global_system_pkgs_apt_install)
 - RSS feed: $source
 - date published: 2024-09-29T13:36:39+00:00

<!-- SC_OFF --><div class="md"><p>hi all,</p> <p>I have an old app which was not upgraded since last few years and I can only run it on Debian 10 + Python</p> <p>The following global OS pkgs/libs need to be installed on Deb 10 Py 3.7.3 for this app to install properly:</p> <p>```apt install -y python3-venv python3-pip python3-dev libxml2-dev libxslt-dev libmariadb-dev build-essential libffi-dev liblzma-dev fonts-deva-extra```</p> <p>Now I need to migrate this to new server which is running Debain 12 + Python 3.11.2</p> <p>So I installed Pyenv to sideload Py 3.7.3 but how do I satisfy the &#39;global system pkgs&#39; listed above that are installed using apt? </p> <p>chatgpt gives me:</p> <p>```Unfortunately, the system-level dependencies like libxml2-dev and libmariadb-dev cannot be installed directly inside the virtual environment because they are required for compilation and linking against system libraries.```</p> <p>If I do install them systemwide with apt on Debian 12, the instal

## Sharing common code
 - [https://www.reddit.com/r/django/comments/1fs0wvq/sharing_common_code](https://www.reddit.com/r/django/comments/1fs0wvq/sharing_common_code)
 - RSS feed: $source
 - date published: 2024-09-29T09:57:22+00:00

<!-- SC_OFF --><div class="md"><p>Writing a Django rest API.</p> <p>There are 3 apps within the project.</p> <p>One of the functions I am using needs a database table to function.</p> <p>I want to use that function in all 3 of the apps.</p> <p>I am still developing that function as the app grows so I do not want to package that function at this stage.</p> <p>Not sure how to achieve this.</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Extreme-Acid"> /u/Extreme-Acid </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fs0wvq/sharing_common_code/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fs0wvq/sharing_common_code/">[comments]</a></span>

## Best way to deploy a django project with static files and a database?
 - [https://www.reddit.com/r/django/comments/1fs0w2h/best_way_to_deploy_a_django_project_with_static](https://www.reddit.com/r/django/comments/1fs0w2h/best_way_to_deploy_a_django_project_with_static)
 - RSS feed: $source
 - date published: 2024-09-29T09:55:40+00:00

<!-- SC_OFF --><div class="md"><p>I’ve just finished my django project and I’m looking to host it, however when I go to host it on vercel I follow the tutorials and for some reason my static files never load. </p> <p>I was wondering is there a better way or a more informative tutorial on how to deploy it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kyle67o"> /u/kyle67o </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fs0w2h/best_way_to_deploy_a_django_project_with_static/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fs0w2h/best_way_to_deploy_a_django_project_with_static/">[comments]</a></span>

## Looking for Advice: How’s the Job Market for Django Backend Developers?
 - [https://www.reddit.com/r/django/comments/1fs0ont/looking_for_advice_hows_the_job_market_for_django](https://www.reddit.com/r/django/comments/1fs0ont/looking_for_advice_hows_the_job_market_for_django)
 - RSS feed: $source
 - date published: 2024-09-29T09:39:59+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m curious to know if there are any backend developers here who are using Django, DRF, Docker, AWS, RabbitMQ, Celery, etc. in their tech stack. <strong>If you&#39;re using this stack, how much are you earning based on your experience?</strong> What are your salary expectations?</p> <p>Additionally, I&#39;d love some guidance on compensation expectations as a fresher. I have experience working in production with this stack (internships and projects). What kind of salary can I expect as a fresher, and what should I aim for after gaining a few years of experience?</p> <p>I’ve noticed that there seem to be a lot more opportunities for freshers in React, TypeScript, and Node.js compared to Django. While there are openings for Django, they’re often for senior roles. Would it be better to switch and focus on a different stack with more opportunities? </p> <p><strong>If you have experience with this stack, how has your career trajectory been? Any insight

## Looking for Collaboration and Django Job Opportunities! 🚀
 - [https://www.reddit.com/r/django/comments/1frznb1/looking_for_collaboration_and_django_job](https://www.reddit.com/r/django/comments/1frznb1/looking_for_collaboration_and_django_job)
 - RSS feed: $source
 - date published: 2024-09-29T08:20:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone! 👋</p> <p>I’m a Django full-stack developer and I&#39;m currently looking for collaboration opportunities and job openings in Django. If anyone is working on a project or looking for someone to join their team, I would love to connect and discuss how we can work together! 🤝</p> <p>Additionally, if there are any job openings related to Django development, I would greatly appreciate any leads or recommendations.</p> <p>Feel free to DM me or reply to this post! Thank you! 🙏</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Plenty-Average6116"> /u/Plenty-Average6116 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1frznb1/looking_for_collaboration_and_django_job/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1frznb1/looking_for_collaboration_and_django_job/">[comments]</a></span>

## Zappa with Django, what's your experience.
 - [https://www.reddit.com/r/django/comments/1frzigt/zappa_with_django_whats_your_experience](https://www.reddit.com/r/django/comments/1frzigt/zappa_with_django_whats_your_experience)
 - RSS feed: $source
 - date published: 2024-09-29T08:10:05+00:00

<!-- SC_OFF --><div class="md"><p>I have been considering giving zappa a swing for my django rest framework app via aws hosting. <a href="https://github.com/zappa/Zappa">https://github.com/zappa/Zappa</a> Was wondering if anyone used it before. What are their experiences? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fanna1119"> /u/fanna1119 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1frzigt/zappa_with_django_whats_your_experience/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1frzigt/zappa_with_django_whats_your_experience/">[comments]</a></span>

## How to make a windows app
 - [https://www.reddit.com/r/django/comments/1fry23o/how_to_make_a_windows_app](https://www.reddit.com/r/django/comments/1fry23o/how_to_make_a_windows_app)
 - RSS feed: $source
 - date published: 2024-09-29T06:23:45+00:00

<!-- SC_OFF --><div class="md"><p>I want to make a windows app and i want to make it then sell that app but I&#39;m not really good at programming but I know python a bit </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Visual-Unit2037"> /u/Visual-Unit2037 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1fry23o/how_to_make_a_windows_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1fry23o/how_to_make_a_windows_app/">[comments]</a></span>

## 🚀 Introducing DisMail – A Temporary Email Provider I Built! (Android Only)
 - [https://www.reddit.com/r/django/comments/1frttn4/introducing_dismail_a_temporary_email_provider_i](https://www.reddit.com/r/django/comments/1frttn4/introducing_dismail_a_temporary_email_provider_i)
 - RSS feed: $source
 - date published: 2024-09-29T01:59:25+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone 👋</p> <p>I’m excited to share my side project with you all—<strong>DisMail</strong>! As a self-taught software developer, I’ve built this temporary/disposable email app to help you keep your inbox clean and protect your privacy. It’s available on <strong>Android</strong> for now, and I’ll consider building for iOS if there&#39;s enough interest. It includes some great features:</p> <ul> <li>✉️ <strong>Generate Random and Custom Emails</strong>: Create temporary email addresses effortlessly, with the option to generate custom ones.</li> <li>🌑 <strong>Dark Mode</strong>: Enjoy a low-light friendly interface for comfortable use at any time.</li> <li>🔄 <strong>Reuse Previous Emails</strong>: Easily access and use previously created email addresses.</li> <li>🔐 <strong>Secure for Logins and Sign-Ups</strong>: Use disposable emails for website registrations and logins to keep your personal inbox clutter-free.</li> <li>🎨 <strong>UI Enhancements</

## Detect ad block
 - [https://www.reddit.com/r/django/comments/1frtcef/detect_ad_block](https://www.reddit.com/r/django/comments/1frtcef/detect_ad_block)
 - RSS feed: $source
 - date published: 2024-09-29T01:31:56+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking for a way to block ad blockers on my site and I know there are a lot of custom ways to do it with JavaScript but I’m wondering if anyone knows some really pythonic or Django-y ways to do this without need to add more JavaScript libraries to my frontend. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Distinct_Signal_5281"> /u/Distinct_Signal_5281 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1frtcef/detect_ad_block/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1frtcef/detect_ad_block/">[comments]</a></span>

## Looking for people to join my new python programming community
 - [https://www.reddit.com/r/django/comments/1frsnyf/looking_for_people_to_join_my_new_python](https://www.reddit.com/r/django/comments/1frsnyf/looking_for_people_to_join_my_new_python)
 - RSS feed: $source
 - date published: 2024-09-29T00:54:17+00:00

<!-- SC_OFF --><div class="md"><p>Definitely I am not yet a master but I am learning.I will do my best to help.And that will be the point of this community that everyone can help each other.Nobody has to ask a specific person but everyone is there to help each other as a growing yet Relatively new python community of friendly like minded individuals with unique invaluable skill sets! And colabs and buddies! <a href="https://discord.gg/FJkQArt7">https://discord.gg/FJkQArt7</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Far_Lab7890"> /u/Far_Lab7890 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1frsnyf/looking_for_people_to_join_my_new_python/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1frsnyf/looking_for_people_to_join_my_new_python/">[comments]</a></span>

## Improve query
 - [https://www.reddit.com/r/django/comments/1frrsm1/improve_query](https://www.reddit.com/r/django/comments/1frrsm1/improve_query)
 - RSS feed: $source
 - date published: 2024-09-29T00:06:53+00:00

<!-- SC_OFF --><div class="md"><p>Is there a way to improve this query?</p> <pre><code> current_streak = 0 for hystory in PlayerHistory.objects.filter(user=request.user).order_by( &#39;-created_at&#39; ): if hystory.correct: current_streak += 1 else: break </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ecstatic_Progress697"> /u/Ecstatic_Progress697 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1frrsm1/improve_query/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1frrsm1/improve_query/">[comments]</a></span>

