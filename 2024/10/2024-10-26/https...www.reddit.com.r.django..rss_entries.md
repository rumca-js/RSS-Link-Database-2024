# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Moving to Canada Soon! Looking to Connect with Fellow Django Devs
 - [https://www.reddit.com/r/django/comments/1gcx9ax/moving_to_canada_soon_looking_to_connect_with](https://www.reddit.com/r/django/comments/1gcx9ax/moving_to_canada_soon_looking_to_connect_with)
 - RSS feed: $source
 - date published: 2024-10-26T22:59:10+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I&#39;m moving to Canada in about four months, and I&#39;m excited to connect with people working with Django. I have around three years of experience building large-scale Django apps that handle millions of data entries, and I&#39;m always looking to improve and learn from others.</p> <p>If you&#39;re in Canada or familiar with the Django scene there, I&#39;d love to hear any insights, or tips, or just chat about the latest in Django development! 😊</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sudden_Bid_7670"> /u/Sudden_Bid_7670 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gcx9ax/moving_to_canada_soon_looking_to_connect_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gcx9ax/moving_to_canada_soon_looking_to_connect_with/">[comments]</a></span>

## Django guardian scalablity
 - [https://www.reddit.com/r/django/comments/1gcv6f5/django_guardian_scalablity](https://www.reddit.com/r/django/comments/1gcv6f5/django_guardian_scalablity)
 - RSS feed: $source
 - date published: 2024-10-26T21:18:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m considering using django guardian for object level permissions. I have a fairly large postgres database that I need object level permissions for. The listing table has at least 400k plus rows. Is django guardian any good? I need to control what objects are shown on listing pages depending on what user groups the user is on. I&#39;m concerned that this will slow down the site. Any other libraries that can do this? Any tips for scalability so my listing pages don&#39;t slow down too much? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ironicwil"> /u/ironicwil </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gcv6f5/django_guardian_scalablity/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gcv6f5/django_guardian_scalablity/">[comments]</a></span>

## I'm unable to login as an Admin to Django Administration
 - [https://www.reddit.com/r/django/comments/1gcuygn/im_unable_to_login_as_an_admin_to_django](https://www.reddit.com/r/django/comments/1gcuygn/im_unable_to_login_as_an_admin_to_django)
 - RSS feed: $source
 - date published: 2024-10-26T21:07:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working with MySQL workbench, I have a table called users that has a column of roleID, I want the users of roleID == 1 only to be able to login from the Django administration and I&#39;m stuck, I&#39;ll show you my code Idk what I&#39;m doing wrong, it keeps returning this error: &quot;<strong>Please enter the correct email and password for a staff account. Note that both fields may be case-sensitive.</strong>&quot;<br/> users/models.py:</p> <pre><code>from django.contrib.auth.models import AbstractBaseUser, BaseUserManager from django.db import models class UserManager(BaseUserManager): def create_superuser(self, email, password=None, **extra_fields): extra_fields.setdefault(&#39;is_staff&#39;, True) extra_fields.setdefault(&#39;is_superuser&#39;, True) return self.create_user(email, password, **extra_fields) def create_user(self, email, password=None, **extra_fields): if not email: raise ValueError(&#39;The Email field must be set&#39;) ema

## Why my Django Administration page looks like this
 - [https://www.reddit.com/r/django/comments/1gcqq5d/why_my_django_administration_page_looks_like_this](https://www.reddit.com/r/django/comments/1gcqq5d/why_my_django_administration_page_looks_like_this)
 - RSS feed: $source
 - date published: 2024-10-26T17:50:51+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/zq6i8sq825xd1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=accd043c3df996c0e52d4a4f380ff86063c72cab">https://preview.redd.it/zq6i8sq825xd1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=accd043c3df996c0e52d4a4f380ff86063c72cab</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mcphect"> /u/Mcphect </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gcqq5d/why_my_django_administration_page_looks_like_this/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gcqq5d/why_my_django_administration_page_looks_like_this/">[comments]</a></span>

## Advice Needed: Developing AI-Driven International Flight Planner for College Project – API Suggestions?
 - [https://www.reddit.com/r/django/comments/1gclnbw/advice_needed_developing_aidriven_international](https://www.reddit.com/r/django/comments/1gclnbw/advice_needed_developing_aidriven_international)
 - RSS feed: $source
 - date published: 2024-10-26T13:56:55+00:00

<!-- SC_OFF --><div class="md"><p>I’m working on my semester-end project, which is an AI-driven International Flight Planner. The goal is to help users find the best flight options tailored to their preferences (budget, airline, layovers, etc.), while also providing useful travel info like visa requirements, layover accommodation suggestions, and booking recommendations based on past pricing trends.</p> <p>I’m using <strong>Django</strong> for the backend and considering <strong>PostgreSQL</strong> for storing flight data. However, I’m still looking into APIs that can provide reliable flight and travel data. I’m especially interested in APIs with a <strong>free tier</strong> or trial access since this is a college project.</p> <p>Would really appreciate any input on API selection, as well as any insights on tech stack choices for a project like this. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/crafty-420"> /u/crafty-420 </

## Pliz help
 - [https://www.reddit.com/r/django/comments/1gclhpk/pliz_help](https://www.reddit.com/r/django/comments/1gclhpk/pliz_help)
 - RSS feed: $source
 - date published: 2024-10-26T13:48:42+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kayp1738"> /u/kayp1738 </a> <br/> <span><a href="https://i.redd.it/hy2s94e2v3xd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gclhpk/pliz_help/">[comments]</a></span>

## Pliz help
 - [https://www.reddit.com/r/django/comments/1gclefg/pliz_help](https://www.reddit.com/r/django/comments/1gclefg/pliz_help)
 - RSS feed: $source
 - date published: 2024-10-26T13:44:07+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kayp1738"> /u/kayp1738 </a> <br/> <span><a href="https://i.redd.it/qhj3poq7u3xd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gclefg/pliz_help/">[comments]</a></span>

## Connecting React and Django Rest Framework: Quick Guide
 - [https://www.reddit.com/r/django/comments/1gck0h9/connecting_react_and_django_rest_framework_quick](https://www.reddit.com/r/django/comments/1gck0h9/connecting_react_and_django_rest_framework_quick)
 - RSS feed: $source
 - date published: 2024-10-26T12:31:08+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/NoSEVDev"> /u/NoSEVDev </a> <br/> <span><a href="https://slimsaas.com/blog/react-and-django-rest-framework">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gck0h9/connecting_react_and_django_rest_framework_quick/">[comments]</a></span>

## New to web dev, please help me undersand this basic concept
 - [https://www.reddit.com/r/django/comments/1gcj6n3/new_to_web_dev_please_help_me_undersand_this](https://www.reddit.com/r/django/comments/1gcj6n3/new_to_web_dev_please_help_me_undersand_this)
 - RSS feed: $source
 - date published: 2024-10-26T11:43:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on my first project but am stuck because I&#39;m not sure if I&#39;m handling my URLs and views correctly.</p> <pre><code>URLs: /items/ views.items &#39;items&#39; /items/&lt;int:pk&gt;/ views.item_detail &#39;item-detail&#39; </code></pre> <p>/items/ can be filtered on the server side to /items/?category=...&amp;subcategory=...</p> <pre><code>def items(request): items = Item.object.all() category = request.GET.get(&#39;category&#39;) if category: ... return render(request, &#39;items.html&#39;, {&#39;items&#39;: items}) </code></pre> <p>The items in the list include hyperlinks to <code>/items/&lt;int:pk&gt;/</code>, but I want the details of the selected item to appear next to the filtered list. This means the request should include the query string, and <code>item_detail</code> should apply the same filters:</p> <pre><code>&lt;a href={{ url &#39;idem_detail&#39; pk=item.id }}?{{ request.GET.urlencode }}&gt; And the view: def item_de

## Beginner Django Developer Joining a Startup! Seeking Tips, Resources & Collaboration to Grow
 - [https://www.reddit.com/r/django/comments/1gchgrh/beginner_django_developer_joining_a_startup](https://www.reddit.com/r/django/comments/1gchgrh/beginner_django_developer_joining_a_startup)
 - RSS feed: $source
 - date published: 2024-10-26T09:44:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 👋</p> <p>I’m just starting out as an intern at a friend’s digital marketing agency, where we’re all new and learning as we go. Our agency focuses on web development, digital presence management, and app creation for businesses, and I’m responsible for backend and frontend development using Python, Django, and SQL.</p> <p>Since we’re still building our foundations, I’d love to get guidance from the seasoned developers here—anything from must-read resources, best practices, and even stories from your own experience would be a huge help!</p> <p>Also, if anyone’s open to collaboration or discussing potential projects, I’d love to connect. I’m eager to learn, experiment, and contribute however I can to help drive our startup’s growth. Thank you in advance for any insights! 🙏</p> <p>email: [<a href="mailto:ganeshghogre7057@gmail.com">ganeshghogre7057@gmail.com</a>](mailto:<a href="mailto:ganeshghogre7057@gmail.com">ganeshghogre7057@gmail.com<

## 🎉 Introducing `dj-announcement-api` package 🎉
 - [https://www.reddit.com/r/django/comments/1gch3py/introducing_djannouncementapi_package](https://www.reddit.com/r/django/comments/1gch3py/introducing_djannouncementapi_package)
 - RSS feed: $source
 - date published: 2024-10-26T09:17:18+00:00

<!-- SC_OFF --><div class="md"><p>We&#39;re thrilled to announce the release of <a href="https://pypi.org/project/dj-announcement-api/"><code>dj-announcement-api</code></a>, a versatile Django package developed by Lazarus to simplify and optimize the management and distribution of announcements through a robust API.</p> <h1>Key Features</h1> <ul> <li><strong>Full, Optimizable API</strong>: Manage announcements programmatically with an API designed for high performance and scalability.</li> <li><strong>Targeted Announcements</strong>: Create detailed, categorized announcements directed at specific user audiences.</li> <li><strong>Auto-Assign Audiences</strong>: Automatically assign users to relevant audiences for seamless, targeted communication.</li> <li><strong>Scheduling Options</strong>: Schedule announcements with customizable publication and expiration dates to deliver information at the right time.</li> </ul> <p>Ideal for modern Django applications with dynamic needs, <code>dj-

## Migrating to Django 5
 - [https://www.reddit.com/r/django/comments/1gcgqga/migrating_to_django_5](https://www.reddit.com/r/django/comments/1gcgqga/migrating_to_django_5)
 - RSS feed: $source
 - date published: 2024-10-26T08:49:20+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Crafty_Two_5747"> /u/Crafty_Two_5747 </a> <br/> <span><a href="https://jmduke.com/posts/post/django-5/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gcgqga/migrating_to_django_5/">[comments]</a></span>

## Does django devs have remote job oppurtunities?
 - [https://www.reddit.com/r/django/comments/1gcerel/does_django_devs_have_remote_job_oppurtunities](https://www.reddit.com/r/django/comments/1gcerel/does_django_devs_have_remote_job_oppurtunities)
 - RSS feed: $source
 - date published: 2024-10-26T06:18:48+00:00

<!-- SC_OFF --><div class="md"><p>Do django devs also have remote job oppurtunities like mern stack developers?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sea-Catch5150"> /u/Sea-Catch5150 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gcerel/does_django_devs_have_remote_job_oppurtunities/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gcerel/does_django_devs_have_remote_job_oppurtunities/">[comments]</a></span>

## Getting default document in the result when I execute query for my Solr core in the Solr UI when it should return several documents.
 - [https://www.reddit.com/r/django/comments/1gcbrbn/getting_default_document_in_the_result_when_i](https://www.reddit.com/r/django/comments/1gcbrbn/getting_default_document_in_the_result_when_i)
 - RSS feed: $source
 - date published: 2024-10-26T03:06:08+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys, I&#39;m having trouble with my Haystack/Solr search engine. So when I execute a query for the Solr core I created, arbor_core, I only see the default result for the document in the Solr UI. </p> <p>This is what I see in the results page:</p> <p>```{<br/> &quot;responseHeader&quot;:{<br/> &quot;status&quot;:0,<br/> &quot;QTime&quot;:2,<br/> &quot;params&quot;:{<br/> &quot;q&quot;:&quot;*:*&quot;,<br/> &quot;indent&quot;:&quot;true&quot;,<br/> &quot;q.op&quot;:&quot;OR&quot;,<br/> &quot;useParams&quot;:&quot;&quot;,<br/> &quot;_&quot;:&quot;1729910930305&quot;<br/> }<br/> },<br/> &quot;response&quot;:{<br/> &quot;numFound&quot;:0,<br/> &quot;start&quot;:0,<br/> &quot;numFoundExact&quot;:true,<br/> &quot;docs&quot;:[ ]<br/> }<br/> }```</p> <p>Here is a breakdown of everything I did, before running this search query for my core. First I created a search_indexes.py file with the following code:</p> <p>```</p> <pre><code>from haystack import in

