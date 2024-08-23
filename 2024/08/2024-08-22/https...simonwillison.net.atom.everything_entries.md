# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Optimizing Datasette (and other weeknotes)
 - [https://simonwillison.net/2024/Aug/22/optimizing-datasette/#atom-everything](https://simonwillison.net/2024/Aug/22/optimizing-datasette/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-22T15:46:43+00:00

<p>I've been working with Alex Garcia on an experiment involving using <a href="https://datasette.io/">Datasette</a> to explore FEC contributions. We currently have a 11GB SQLite database - trivial for SQLite to handle, but at the upper end of what I've comfortably explored with Datasette in the past.</p>
<p>This was just the excuse I needed to dig into some optimizations! The next Datasette alpha release will feature some significant speed improvements for working with large tables - they're available on the <code>main</code> branch already.</p>
<h3 id="datasette-tracing">Datasette tracing</h3>
<p>Datasette has had a <code>?_trace=1</code> feature for a while. It's only available if you run Datasette with the <code>trace_debug</code> setting enabled - which you can do like this:</p>
<div class="highlight highlight-source-shell"><pre>datasette -s trace_debug 1 mydatabase.db</pre></div>
<p>Then any request with <code>?_trace=1</code> added to the URL will return a JSON blob at the end 

## light-the-torch
 - [https://simonwillison.net/2024/Aug/22/light-the-torch/#atom-everything](https://simonwillison.net/2024/Aug/22/light-the-torch/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-22T04:11:32+00:00

<p><strong><a href="https://pypi.org/project/light-the-torch/">light-the-torch</a></strong></p>
<blockquote>
<p><code>light-the-torch</code> is a small utility that wraps <code>pip</code> to ease the installation process for PyTorch distributions like <code>torch</code>, <code>torchvision</code>, <code>torchaudio</code>, and so on as well as third-party packages that depend on them. It auto-detects compatible CUDA versions from the local setup and installs the correct PyTorch binaries without user interference.</p>
</blockquote>
<p>Use it like this:</p>
<pre><code>pip install light-the-torch
ltt install torch
</code></pre>
<p>It works by wrapping and <a href="https://github.com/pmeier/light-the-torch/blob/main/light_the_torch/_patch.py">patching pip</a>.

    <p><small></small>Via <a href="https://twitter.com/thezachmueller/status/1826384400684384476">@ thezachmueller</a></small></p>


    <p>Tags: <a href="https://simonwillison.net/tags/pytorch">pytorch</a>, <a href="https://simonwil

