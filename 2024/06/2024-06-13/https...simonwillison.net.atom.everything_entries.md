# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Transcripts on Apple Podcasts
 - [https://simonwillison.net/2024/Jun/13/transcripts-on-apple-podcasts/#atom-everything](https://simonwillison.net/2024/Jun/13/transcripts-on-apple-podcasts/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-13T20:14:19+00:00

<p><a href="https://podcasters.apple.com/support/5316-transcripts-on-apple-podcasts">Transcripts on Apple Podcasts</a></p>
I missed this when it launched <a href="https://www.apple.com/newsroom/2024/03/apple-introduces-transcripts-for-apple-podcasts/">back in March</a>: the Apple Podcasts app now features searchable transcripts, including the ability to tap on text and jump to that point in the audio.</p>
<p>Confusingly, you can only tap to navigate using the view of the transcript that comes up when you hit the quote mark icon during playback - if you click the Transcript link from the episode listing page you get a static transcript without the navigation option.</p>
<p>Transcripts are created automatically server-side by Apple, or podcast authors can upload their own edited transcript using Apple Podcasts Connect.

    <p>Via <a href="https://twitter.com/simonw/status/1801316274959749225">A few people on Twitter told me about this</a></p>

## tantivy-cli
 - [https://simonwillison.net/2024/Jun/13/tantivy-cli/#atom-everything](https://simonwillison.net/2024/Jun/13/tantivy-cli/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-13T06:03:00+00:00

<p><a href="https://github.com/quickwit-oss/tantivy-cli">tantivy-cli</a></p>
I tried out this Rust based search engine today and I was very impressed.</p>
<p><a href="https://github.com/quickwit-oss/tantivy">Tantivy</a> is the core project - it's an open source (MIT) Rust library that implements Lucene-style full text search, with a very full set of features: BM25 ranking, faceted search, range queries, incremental indexing etc.</p>
<p><code>tantivy-cli</code> offers a CLI wrapper around the Rust library. It's not actually as full-featured as I hoped: it's intended as more of a demo than a full exposure of the library's features. The JSON API server it runs can only be used to run simple keyword or phrase searches for example, no faceting or filtering.</p>
<p>Tantivy's performance is fantastic. I was able to index the entire contents of my link blog in a fraction of a second.</p>
<p>I found <a href="https://fulmicoton.com/posts/behold-tantivy/">this post</a> from 2017 where Tantivy cr

## Optimal SQLite settings for Django
 - [https://simonwillison.net/2024/Jun/13/optimal-sqlite-settings-for-django/#atom-everything](https://simonwillison.net/2024/Jun/13/optimal-sqlite-settings-for-django/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-13T05:04:36+00:00

<p><a href="https://gcollazo.com/optimal-sqlite-settings-for-django/">Optimal SQLite settings for Django</a></p>
Giovanni Collazo put the work in to figure out settings to make SQLite work well for production Django workloads. WAL mode and a <code>busy_timeout</code> of 5000 make sense, but the most interesting recommendation here is <code>"transaction_mode": "IMMEDIATE"</code> to avoid locking errors when a transaction is upgraded to a write transaction.</p>
<p>Giovanni's configuration depends on the new <code>"init_command"</code> support for SQLite PRAGMA options <a href="https://docs.djangoproject.com/en/5.1/ref/databases/#setting-pragma-options">introduced in Django 5.1alpha</a>.

    <p>Via <a href="https://lobste.rs/s/9lchst/optimal_sqlite_settings_for_django">Lobste.rs</a></p>

## PDF to Podcast
 - [https://simonwillison.net/2024/Jun/13/pdf-to-podcast/#atom-everything](https://simonwillison.net/2024/Jun/13/pdf-to-podcast/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-13T01:03:56+00:00

<p><a href="https://pdf-to-podcast.com/">PDF to Podcast</a></p>
At first glance this project by Stephan Fitzpatrick is a cute demo of a terrible sounding idea... but then I tried it out and the results are weirdly effective. You can listen to a fake podcast version of the transformers paper, or upload your own PDF (with your own OpenAI API key) to make your own.</p>
<p>It's open source (Apache 2) so I had a poke around in <a href="https://github.com/knowsuchagency/pdf-to-podcast">the code</a>. It gets a lot done with a single <a href="https://github.com/knowsuchagency/pdf-to-podcast/blob/512bfbdb4fd658ad4b301336020c4ea16cb69e18/main.py">180 line Python script</a>.</p>
<p>When I'm exploring code like this I always jump straight to <a href="https://github.com/knowsuchagency/pdf-to-podcast/blob/512bfbdb4fd658ad4b301336020c4ea16cb69e18/main.py#L47-L80">the prompt</a> - it's quite long, and starts like this:</p>
<blockquote>
<p>Your task is to take the input text provided and turn it into 

