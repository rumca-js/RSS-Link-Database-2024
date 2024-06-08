# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Newer versions of Ansible don't work with RHEL 8
 - [https://www.jeffgeerling.com/blog/2024/newer-versions-ansible-dont-work-rhel-8](https://www.jeffgeerling.com/blog/2024/newer-versions-ansible-dont-work-rhel-8)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-06-07T15:50:22+00:00

<span class="field field--name-title field--type-string field--label-hidden">Newer versions of Ansible don't work with RHEL 8</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Red Hat Enterprise Linux 8 is supported until 2029, and that distribution includes Python 3.6 for system python. Ansible's long been stuck between a rock and a hard place supporting certain modules (especially packaging modules like <code>dnf</code>/<code>yum</code> on RHEL and its derivatives, because the Python bindings for the packaging modules are stuck supporting system Python.</p>

<p>Users are getting errors like:</p>

<pre><code>/bin/sh: /usr/bin/python3: No such file or directory
The module failed to execute correctly, you probably need to set the interpreter.\nSee stdout/stderr for the exact error.

...or...

SyntaxError: future feature annotations is not defined
</code></pre>

<p>As <code>ansible-core</code>

