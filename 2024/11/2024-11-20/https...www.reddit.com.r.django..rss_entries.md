# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Multiple domains and allowed_hosts
 - [https://www.reddit.com/r/django/comments/1gvth59/multiple_domains_and_allowed_hosts](https://www.reddit.com/r/django/comments/1gvth59/multiple_domains_and_allowed_hosts)
 - RSS feed: $source
 - date published: 2024-11-20T16:29:20+00:00

<!-- SC_OFF --><div class="md"><p>I built a landing page app with different domain for each page, stored in a model with domain as a field. Is there a way to dynamically create ALLOWED_HOSTS in settings? I have tried this and it doesn&#39;t work because models have loaded yet. I want to avoid having a giant list of domains in my settings file and redeploying every time that needs to change. I would rather add LandingPages in the django admin and have it update allowed hosts automatically.</p> <pre><code> ALLOWED_HOSTS = list(LandingPage.objects.values_list(&#39;domain&#39;, flat=True)) </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AttractiveCorpse"> /u/AttractiveCorpse </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gvth59/multiple_domains_and_allowed_hosts/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gvth59/multiple_domains_and_allowed_hosts/">[comments]</a></span>

## Django Rest Framework Multiple Instance Creation tip
 - [https://www.reddit.com/r/django/comments/1gvnosg/django_rest_framework_multiple_instance_creation](https://www.reddit.com/r/django/comments/1gvnosg/django_rest_framework_multiple_instance_creation)
 - RSS feed: $source
 - date published: 2024-11-20T11:49:32+00:00

<!-- SC_OFF --><div class="md"><p>In this tip, we will explore how to extend DRF with a custom mixin class to enable the creation of multiple instances in a single API call, ensuring that the implementation is both clean and reusable.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://i.redd.it/y8rhhuylo12e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gvnosg/django_rest_framework_multiple_instance_creation/">[comments]</a></span>

## Solutions for Undoing Malicious Changes
 - [https://www.reddit.com/r/django/comments/1gvj6by/solutions_for_undoing_malicious_changes](https://www.reddit.com/r/django/comments/1gvj6by/solutions_for_undoing_malicious_changes)
 - RSS feed: $source
 - date published: 2024-11-20T06:17:47+00:00

<!-- SC_OFF --><div class="md"><p>Imagine a paid website with Django and PostgreSQL database.</p> <p>Customers can log in to the website and add a few employees. Data is entered daily by the customer and the employees. Now an employee is fired and is pissed off, logs in and changes the data. Or the website is hacked.</p> <p>How can the changes made by this individual employee be undone up to a certain point?</p> <p>You can&#39;t restore the entire database to a previous state, because that would also affect the data of the other customers.</p> <p>Are there well-maintained packages for this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Stella_Hill_Smith"> /u/Stella_Hill_Smith </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gvj6by/solutions_for_undoing_malicious_changes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gvj6by/solutions_for_undoing_malicious_changes/">[comments]</a></span>

## Is there a low-code Django app generator?
 - [https://www.reddit.com/r/django/comments/1gvf0ur/is_there_a_lowcode_django_app_generator](https://www.reddit.com/r/django/comments/1gvf0ur/is_there_a_lowcode_django_app_generator)
 - RSS feed: $source
 - date published: 2024-11-20T02:25:32+00:00

<!-- SC_OFF --><div class="md"><p>I see a lot of app generator products popping up these days. A lot of them are based on Next.JS. Does anyone know of a low-code app generator that produces Django code? I&#39;d love to use a prompt-based tool to speed up the creation of MVPs and to evaluate ideas quickly.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stellarcitizen"> /u/stellarcitizen </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1gvf0ur/is_there_a_lowcode_django_app_generator/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1gvf0ur/is_there_a_lowcode_django_app_generator/">[comments]</a></span>

## I want to make a new project
 - [https://www.reddit.com/r/django/comments/1gvcp23/i_want_to_make_a_new_project](https://www.reddit.com/r/django/comments/1gvcp23/i_want_to_make_a_new_project)
 - RSS feed: $source
 - date published: 2024-11-20T00:32:47+00:00

<!-- SC_OFF --><div class="md"><p>So…I had this idea earlier this year which made me interested in Django. I wanted to make a management software/application for a shelter that has different buildings. This app would allow staff login for different shifts. And there has to be a report generated for different shifts(probably 8hours shift, since shelter is 24 hours). I don’t know if this is something that makes sense. This app would already have a database of every clients living in the shelter and if new family or client comes in, they can be added to the database. There would also be a log for census counting in each building. There would be log or text field(that accepts notes like safe and secure) that takes the log for every rounds conducted every hour. Probably field that takes in reports if there was ever any kind of incident during shifts. And at the end of the shifts, a pdf can be generated from the app based on all the inputs that happened in the 8hrs shift. This app would al

