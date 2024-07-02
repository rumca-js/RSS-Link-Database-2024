# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Russell Keith-Magee: Build a cross-platform app with BeeWare
 - [https://simonwillison.net/2024/Jul/1/build-a-cross-platform-app-with-beeware/#atom-everything](https://simonwillison.net/2024/Jul/1/build-a-cross-platform-app-with-beeware/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-01T22:49:13+00:00

<p><a href="https://www.youtube.com/watch?v=New2JLvWxiE&amp;list=PL2Uw4_HvXqvYhjub9bw4uDAmNtprgAvlJ">Russell Keith-Magee: Build a cross-platform app with BeeWare</a></p>
The session videos from PyCon US 2024 have started <a href="https://www.youtube.com/playlist?list=PL2Uw4_HvXqvYhjub9bw4uDAmNtprgAvlJ">showing up on YouTube</a>. So far just for the tutorials, which gave me a chance to catch up on the BeeWare project with this tutorial run by Russell Keith-Magee.</p>
<p>Here are the <a href="https://pycon-assets.s3.amazonaws.com/2024/media/presentation_slides/41/2024-05-08T23%3A38%3A41.030747/Build_a_cross_platform_GUI_app_with_Be_NscyZ66.pdf">accompanying slides (PDF)</a>, or you can work through the <a href="https://docs.beeware.org/en/latest/tutorial/tutorial-0.html">official tutorial</a> in the BeeWare documentation.</p>
<p>The tutorial did a great job of clarifying the difference between <a href="https://briefcase.readthedocs.io/">Briefcase</a> and <a href="https://toga.readthedoc

## Quoting Evan Hahn
 - [https://simonwillison.net/2024/Jul/1/evan-hahn/#atom-everything](https://simonwillison.net/2024/Jul/1/evan-hahn/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-01T20:42:43+00:00

<blockquote cite="https://evanhahn.com/programming-beliefs-as-of-july-2024/"><p>When presented with a difficult task, I ask myself: <em>“what if I didn’t do this at all?”</em>.  Most of the time, this is a stupid question, and I have to do the thing. But ~5% of the time, I realize that I can completely skip some work.</p></blockquote><p class="cite">&mdash; <a href="https://evanhahn.com/programming-beliefs-as-of-july-2024/">Evan Hahn</a>

## Announcing the Ladybird Browser Initiative
 - [https://simonwillison.net/2024/Jul/1/the-ladybird-browser-initiative/#atom-everything](https://simonwillison.net/2024/Jul/1/the-ladybird-browser-initiative/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-01T16:08:42+00:00

<p><a href="https://ladybird.org/announcement.html">Announcing the Ladybird Browser Initiative</a></p>
Andreas Kling's <a href="https://awesomekling.github.io/Ladybird-a-new-cross-platform-browser-project/">Ladybird</a> is a really exciting project: a from-scratch implementation of a web browser, initially built as part of the Serenity OS project, which aims to provide a completely independent, open source and fully standards compliant browser.</p>
<p>Last month Andreas <a href="https://awesomekling.substack.com/p/forking-ladybird-and-stepping-down-serenityos">forked Ladybird away from Serenity</a>, recognizing that the potential impact of the browser project on its own was greater than as a component of that project. Crucially, Serenity OS avoids <em>any</em> outside code - splitting out Ladybird allows Ladybird to add dependencies like libjpeg and ffmpeg. The <a href="https://www.youtube.com/watch?v=cbw0KrMGHvc">Ladybird June update</a> video talks through some of the dependencies t

## A write-ahead log is not a universal part of durability
 - [https://simonwillison.net/2024/Jul/1/write-ahead-log/#atom-everything](https://simonwillison.net/2024/Jul/1/write-ahead-log/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-01T15:05:51+00:00

<p><a href="https://notes.eatonphil.com/2024-07-01-a-write-ahead-log-is-not-a-universal-part-of-durability.html">A write-ahead log is not a universal part of durability</a></p>
Phil Eaton uses pseudo code to provide a clear description of how write-ahead logs in transactional database systems work, useful for understanding the tradeoffs they make and the guarantees they can provided.</p>

<p>I particularly liked the pseudo code explanation of group commits, where clients block waiting for their commit to be acknowledged as part of a batch of writes flushed to disk.

    <p>Via <a href="https://news.ycombinator.com/item?id=40844825">Hacker News</a></p>

