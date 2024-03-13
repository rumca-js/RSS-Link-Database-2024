# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Fixing nginx Error: Undefined constant PDO::MYSQL_ATTR_USE_BUFFERED_QUERY
 - [https://www.jeffgeerling.com/blog/2024/fixing-nginx-error-undefined-constant-pdomysqlattrusebufferedquery](https://www.jeffgeerling.com/blog/2024/fixing-nginx-error-undefined-constant-pdomysqlattrusebufferedquery)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-03-12T04:57:08+00:00

<span class="field field--name-title field--type-string field--label-hidden">Fixing nginx Error: Undefined constant PDO::MYSQL_ATTR_USE_BUFFERED_QUERY</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>I install a <em>lot</em> of Drupal sites day to day, especially when I'm doing dev work.</p>

<p>In the course of doing that, sometimes I'll be working on infrastructure—whether that's an Ansible playbook to configure a Docker container, or testing something on a fresh server or VM.</p>

<p>In any case, I run into the following error every so often in my Nginx <code>error.log</code>:</p>

<pre><code>"php-fpm" nginx Error: Undefined constant PDO::MYSQL_ATTR_USE_BUFFERED_QUERY
</code></pre>

<p>The funny thing is, I <em>don't</em> have that error when I'm running CLI commands, like <code>vendor/bin/drush</code>, and can even install and manage the Drupal site and database on the CLI.</p>

