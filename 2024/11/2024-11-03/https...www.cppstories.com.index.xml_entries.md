# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## What is the current time around the world? Utilizing std::chrono with time zones in C++23
 - [https://www.cppstories.com/2024/chrono_dates_zones](https://www.cppstories.com/2024/chrono_dates_zones)
 - RSS feed: $source
 - date published: 2024-11-03T00:00:00+00:00

<p>In this blog post, we will explore handling dates using <code>std::chrono</code>, including time zones. We&rsquo;ll utilize the latest features of the library to retrieve the current time across various time zones, taking into account daylight saving time changes as well. Additionally, we will incorporate new capabilities introduced in C++23, such as enhanced printing functions and more.</p>
<p>Let&rsquo;s start with the following code that prints the current date and time:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-cpp" data-lang="cpp"><span class="line"><span class="cl"><span class="cp">#include</span> <span class="cpf">&lt;chrono&gt;</span><span class="cp">
</span></span></span><span class="line"><span class="cl"><span class="cp">#include</span> <span class="cpf">&lt;print&gt;</span><span class="cp">
</span></span></span><span class="line"><span class="cl"><span class="cp"></span>
</span></span><span class="line"><span class="cl"><span cla

