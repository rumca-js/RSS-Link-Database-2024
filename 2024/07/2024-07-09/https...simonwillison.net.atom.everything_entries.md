# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## hangout_services/thunk.js
 - [https://simonwillison.net/2024/Jul/9/hangout_servicesthunkjs/#atom-everything](https://simonwillison.net/2024/Jul/9/hangout_servicesthunkjs/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-09T17:50:16+00:00

<p><a href="https://github.com/chromium/chromium/blob/128.0.6586.1/chrome/browser/resources/hangout_services/thunk.js">hangout_services/thunk.js</a></p>
It turns out Google Chrome (via Chromium) includes a default extension which makes extra services available to code running on the <code>*.google.com</code> domains - tweeted about today <a href="https://twitter.com/lcasdev/status/1810696257137959018">by Luca Casonato</a>, but the code has been there in the public repo <a href="https://github.com/chromium/chromium/commit/422c736b82e7ee763c67109cde700db81ca7b443">since October 2013</a> as far as I can tell.</p>
<p>It looks like it's a way to let Google Hangouts (or presumably its modern predecessors) get additional information from the browser, including the current load on the user's CPU. Update: On Hacker News a Googler <a href="https://news.ycombinator.com/item?id=40918742">confirms</a> that the Google Meet "troubleshooting" feature uses this to review CPU utilization.</p>
<p>I got 

## Deactivating an API, one step at a time
 - [https://simonwillison.net/2024/Jul/9/deactivating-an-api/#atom-everything](https://simonwillison.net/2024/Jul/9/deactivating-an-api/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-09T17:23:07+00:00

<p><a href="https://apichangelog.substack.com/p/deactivating-an-api-one-step-at-a">Deactivating an API, one step at a time</a></p>
Bruno Pedro describes a sensible approach for web API deprecation, using API keys to first block new users from using the old API, then track which existing users are depending on the old version and reaching out to them with a sunset period.</p>
<p>The only suggestion I'd add is to implement API brownouts - short periods of time where the deprecated API returns errors, several months before the final deprecation. This can help give users who don't read emails from you notice that they need to pay attention before their integration breaks entirely.</p>
<p>I've seen GitHub use this brownout technique successfully several times over the last few years - here's <a href="https://github.blog/changelog/2021-08-10-brownout-notice-api-authentication-via-query-parameters-for-48-hours/">one example</a>.

    <p>Via <a href="https://news.ycombinator.com/item?id=40881

## Quoting Kornel Lesiński
 - [https://simonwillison.net/2024/Jul/9/kornel-lesinski/#atom-everything](https://simonwillison.net/2024/Jul/9/kornel-lesinski/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-09T10:43:32+00:00

<blockquote cite="https://mastodon.social/@kornel/112752977103985802"><p>Chrome's biggest innovation was the short release cycle with a silent unceremonious autoupdate.</p>
<p>When updates were big, rare, and manual, buggy and outdated browsers were lingering for soo long, that we were giving bugs names. We documented the bugs in magazines and books, as if they were a timeless foundation of WebDev.</p>
<p>Nowadays browser vendors can fix bugs in 6 weeks (even Safari can…). New-ish stuff is still buggy, but rarely for long enough for the bugs to make it to schools' curriculums.</p></blockquote><p class="cite">&mdash; <a href="https://mastodon.social/@kornel/112752977103985802">Kornel Lesiński</a>

## Quoting Mira Murati
 - [https://simonwillison.net/2024/Jul/9/mira-murati/#atom-everything](https://simonwillison.net/2024/Jul/9/mira-murati/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-09T03:07:26+00:00

<blockquote cite="https://www.youtube.com/watch?v=BD0Us5Bn6Lw&amp;t=900s"><p>Inside the labs we have these capable models, and they're not that far ahead from what the public has access to for free. And that's a completely different trajectory for bringing technology into the world that what we've seen historically. It's a great opportunity because it brings people along. It gives them intuitive sense for the capabilities and risks and allows people to prepare for the advent of bringing advanced AI into the world.</p></blockquote><p class="cite">&mdash; <a href="https://www.youtube.com/watch?v=BD0Us5Bn6Lw&amp;t=900s">Mira Murati</a>

