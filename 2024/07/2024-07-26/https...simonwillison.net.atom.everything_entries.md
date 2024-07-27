# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Image resize and quality comparison
 - [https://simonwillison.net/2024/Jul/26/image-resize-and-quality-comparison/#atom-everything](https://simonwillison.net/2024/Jul/26/image-resize-and-quality-comparison/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-26T13:20:16+00:00

<p><strong><a href="https://tools.simonwillison.net/image-resize-quality">Image resize and quality comparison</a></strong></p>
Another tiny tool I built with Claude 3.5 Sonnet and Artifacts. This one lets you select an image (or drag-drop one onto an area) and then displays that same image as a JPEG at 1, 0.9, 0.7, 0.5, 0.3 quality settings, then again but with at half the width. Each image shows its size in KB and can be downloaded directly from the page.</p>
<p>I'm trying to use more images on my blog (<a href="https://simonwillison.net/2024/Jul/25/button-stealer/">example 1</a>, <a href="https://simonwillison.net/2024/Jul/26/did-you-know-about-instruments/">example 2</a>) and I like to reduce their file size and quality while keeping them legible.</p>
<p>The prompt sequence I used for this was:</p>
<blockquote>
<p>Build an artifact (no React) that I can drop an image onto and it presents that image resized to different JPEG quality levels, each with a download link</p>
</blockquote

## Did you know about Instruments?
 - [https://simonwillison.net/2024/Jul/26/did-you-know-about-instruments/#atom-everything](https://simonwillison.net/2024/Jul/26/did-you-know-about-instruments/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-26T13:06:38+00:00

<p><strong><a href="https://registerspill.thorstenball.com/p/did-you-know-about-instruments">Did you know about Instruments?</a></strong></p>
Thorsten Ball shows how the macOS Instruments app (installed as part of Xcode) can be used to run a CPU profiler against <em>any</em> application - not just code written in Swift/Objective C.</p>
<p>I tried this against a Python process running <a href="https://llm.datasette.io/">LLM</a> executing a Llama 3.1 prompt with my new <a href="https://github.com/simonw/llm-gguf">llm-gguf</a> plugin and captured this:</p>
<p><img alt="Screenshot of a deep nested stack trace showing _PyFunction_Vectorcall from python3.10 calling PyCFuncPtr_call _ctypes.cpython-310-darwin.so which then calls ggml_ methods in libggml.dylib" src="https://static.simonwillison.net/static/2024/instruments-ggml.jpg" />

    <p><small></small>Via <a href="https://lobste.rs/s/kr9od0/did_you_know_about_instruments">lobste.rs</a></small></p>


    <p>Tags: <a href="https://simonwil

