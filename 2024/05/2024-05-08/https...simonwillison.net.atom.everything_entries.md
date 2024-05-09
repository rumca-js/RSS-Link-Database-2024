# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Nathaniel Borenstein
 - [https://simonwillison.net/2024/May/8/nathaniel-borenstein/#atom-everything](https://simonwillison.net/2024/May/8/nathaniel-borenstein/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-08T20:24:29+00:00

<blockquote cite="https://blog.codinghorror.com/your-favorite-programming-quote/"><p>It should be noted that no ethically-trained software engineer would ever consent to write a DestroyBaghdad procedure. Basic professional ethics would instead require him to write a DestroyCity procedure, to which Baghdad could be given as a parameter.</p></blockquote><p class="cite">&mdash; <a href="https://blog.codinghorror.com/your-favorite-programming-quote/">Nathaniel Borenstein</a>

## Slop is the new name for unwanted AI-generated content
 - [https://simonwillison.net/2024/May/8/slop/#atom-everything](https://simonwillison.net/2024/May/8/slop/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-08T18:24:33+00:00

<p>I saw this tweet yesterday <a href="https://twitter.com/deepfates/status/1787472784106639418">from @deepfates</a>, and I am <em>very</em> on board with this:</p>
<blockquote>
<p>Watching in real time as "slop" becomes a term of art. the way that "spam" became the term for unwanted emails, "slop" is going in the dictionary as the term for unwanted AI generated content</p>
</blockquote>
<p>I'm a big proponent of LLMs as <a href="https://simonwillison.net/series/using-llms/">tools for personal productivity</a>, and as software platforms for building interesting applications that can interact with human language.</p>
<p>But I'm increasingly of the opinion that sharing unreviewed content that has been artificially generated with other people <a href="https://simonwillison.net/2023/Aug/27/wordcamp-llms/#personal-ai-ethics">is <em>rude</em></a>.</p>
<p><strong>Slop</strong> is the ideal name for this anti-pattern.</p>
<p>Not all promotional content is spam, and not all AI-generated conten

## OpenAI Model Spec, May 2024 edition
 - [https://simonwillison.net/2024/May/8/model-spec/#atom-everything](https://simonwillison.net/2024/May/8/model-spec/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-08T18:15:36+00:00

<p><a href="https://cdn.openai.com/spec/model-spec-2024-05-08.html">OpenAI Model Spec, May 2024 edition</a></p>
New from OpenAI, a detailed specification describing how they want their models to behave in both ChatGPT and the OpenAI API. </p>

<p>“It includes a set of core objectives, as well as guidance on how to deal with conflicting objectives or instructions.”</p>

<p>The document acts as guidelines for the reinforcement learning from human feedback (RLHF) process, and in the future may be used directly to help train models.

    <p>Via <a href="https://openai.com/index/introducing-the-model-spec">Introducing the Model Spec</a></p>

## Modern SQLite: Generated columns
 - [https://simonwillison.net/2024/May/8/modern-sqlite-generated-columns/#atom-everything](https://simonwillison.net/2024/May/8/modern-sqlite-generated-columns/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-08T16:55:41+00:00

<p><a href="https://antonz.org/sqlite-generated-columns/">Modern SQLite: Generated columns</a></p>
The second in Anton Zhiyanov's <a href="https://antonz.org/tags/modern-sqlite/">series</a> on SQLite features you might have missed.</p>
<p>It turns out I had an incorrect mental model of generated columns. In SQLite these can be "virtual" or "stored" (written to disk along with the rest of the table, a bit like a materialized view). Anton noted that "stored are rarely used in practice", which surprised me because I thought that storing them was necessary for them to participate in indexes.</p>
<p>It turns out that's not the case. Anton's example here shows a generated column providing indexed access to a value stored inside a JSON key:</p>
<pre><code>create table events (
  id integer primary key,
  event blob,
  etime text as (event -&gt;&gt; 'time'),
  etype text as (event -&gt;&gt; 'type')
);
create index events_time on events(etime);
insert into events(event) values (
  '{"time": "2

## Tagged Pointer Strings (2015)
 - [https://simonwillison.net/2024/May/8/tagged-pointer-strings-2015/#atom-everything](https://simonwillison.net/2024/May/8/tagged-pointer-strings-2015/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-08T14:23:13+00:00

<p><a href="https://mikeash.com/pyblog/friday-qa-2015-07-31-tagged-pointer-strings.html">Tagged Pointer Strings (2015)</a></p>
Mike Ash digs into a fascinating implementation detail of macOS.</p>
<p>Tagged pointers provide a way to embed a literal value in a pointer reference. Objective-C pointers on macOS are 64 bit, providing plenty of space for representing entire values. If the least significant bit is 1 (the pointer is a 64 bit odd number) then the pointer is "tagged" and represents a value, not a memory reference.</p>
<p>Here's where things get really clever. Storing an integer value up to 60 bits is easy. But what about strings?</p>
<p>There's enough space for three UTF-16 characters, with 12 bits left over. But if the string fits ASCII we can store 7 characters.</p>
<p>Drop everything except <code>a-z A-Z.0-9</code> and we need 6 bits per character, allowing 10 characters to fit in the pointer.</p>
<p>Apple take this a step further: if the string contains just <code>eilotrm.ap

## Towards universal version control with Patchwork
 - [https://simonwillison.net/2024/May/8/universal-version-control/#atom-everything](https://simonwillison.net/2024/May/8/universal-version-control/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-08T01:44:26+00:00

<p><a href="https://buttondown.email/geoffreylitt/archive/towards-universal-version-control-with-patchwork/">Towards universal version control with Patchwork</a></p>
Geoffrey Litt has been working with Ink &amp; Switch exploring UI patterns for applying version control to different kinds of applications, with the goal of developing a set of conceptual primitives that can bring branching and version tracking to interfaces beyond just Git-style version control.</p>

<p>Geoffrey observes that basic version control is already a metaphor in a lot of software—the undo stack in Photoshop or suggestion mode in Google Docs are two examples.</p>

<p>Extending that is a great way to interact with AI tools as well—allowing for editorial bots that can suggest their own changes for you to accept, for example.

    <p>Via <a href="https://twitter.com/stevekrouse/status/1787834460358017497">@stevekrouse</a></p>

## gpt2-chatbot confirmed as OpenAI
 - [https://simonwillison.net/2024/May/8/gpt2-chatbot-confirmed-as-openai/#atom-everything](https://simonwillison.net/2024/May/8/gpt2-chatbot-confirmed-as-openai/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-08T00:33:46+00:00

<p><a href="https://twitter.com/nanulled/status/1787938906068885747">gpt2-chatbot confirmed as OpenAI</a></p>
The mysterious <code>gpt2-chatbot</code> model that showed up in the <a href="https://chat.lmsys.org/">LMSYS arena</a> a few days ago was <a href="https://simonwillison.net/2024/Apr/29/notes-on-gpt2-chatbot/">suspected to be</a> a testing preview of a new OpenAI model. This has now been confirmed, thanks to a 429 rate limit error message that exposes details from the underlying OpenAI API platform.</p>
<p>The model has been renamed to <code>im-also-a-good-gpt-chatbot</code> and is now only randomly available in "Arena (battle)" mode, not via "Direct Chat".

    <p>Via <a href="https://twitter.com/abacaj/status/1787942691587739826">@abacaj</a></p>

