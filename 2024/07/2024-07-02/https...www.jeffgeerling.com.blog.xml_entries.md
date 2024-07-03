# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Installing Ansible on a RISC-V computer
 - [https://www.jeffgeerling.com/blog/2024/installing-ansible-on-risc-v-computer](https://www.jeffgeerling.com/blog/2024/installing-ansible-on-risc-v-computer)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-07-02T18:16:37+00:00

<span class="field field--name-title field--type-string field--label-hidden">Installing Ansible on a RISC-V computer</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Ansible runs on Python, and Python runs on... well pretty much <em>everything</em>. Including newer RISC-V machines.</p>

<p>But Ansible has a lot of dependencies, and some of these dependencies have caused frustration from time to time on x86 and Arm (so having issues with a dependency is just a way of life when you enter <a href="https://en.wikipedia.org/wiki/Dependency_hell">dependency hell</a>)... but in this case, for the past few months, I've never had luck installing Ansible from PyPI (Python's Package Index) on any RISC-V system, using <code>pip install ansible</code>.</p>

<p>I prefer installing this way (rather than compiling from source or from system packages) because it generally gets the latest version of Ansible,

