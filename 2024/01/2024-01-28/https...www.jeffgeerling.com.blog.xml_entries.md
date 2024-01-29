# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Resizing macOS app windows for 16:9 screen capture
 - [https://www.jeffgeerling.com/blog/2024/resizing-macos-app-windows-169-screen-capture](https://www.jeffgeerling.com/blog/2024/resizing-macos-app-windows-169-screen-capture)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-01-28T19:18:02+00:00

<span class="field field--name-title field--type-string field--label-hidden">Resizing macOS app windows for 16:9 screen capture</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>I frequently need to capture a window of some Mac app for a recording (usually for my YouTube channel), and I've used a little AppleScript I wrote years ago for the purpose.</p>

<p>Somehow, that script (which I saved as a 'one shot' App (<code>.app</code> extension) that just runs then quits) got deleted off my Script Editor folder in my iCloud Drive, so I had to re-create it.</p>

<p>Luckily, the syntax for this operation is dead simple:</p>

<pre><code>tell application "Safari"
    set bounds of front window to {0, 50, 1280, 770}
end tell
</code></pre>

<p>You can adjust the <code>{X, Y, width, height}</code> parameters accordingly—note that the width and height seem to be additive to the X/Y. So I use 77

