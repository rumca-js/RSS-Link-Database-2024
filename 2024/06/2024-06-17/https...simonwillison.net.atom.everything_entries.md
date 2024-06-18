# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## pkgutil.resolve_name(name)
 - [https://simonwillison.net/2024/Jun/17/pkgutil-resolve-name/#atom-everything](https://simonwillison.net/2024/Jun/17/pkgutil-resolve-name/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-17T20:32:29+00:00

<p><a href="https://docs.python.org/3/library/pkgutil.html#pkgutil.resolve_name">pkgutil.resolve_name(name)</a></p>
Adam Johnson pointed out this utility method, added to the Python standard library in Python 3.9. It lets you provide a string that specifies a Python identifier to import from a module - a pattern frequently used in things like Django's configuration.</p>
<pre><code>Path = pkgutil.resolve_name("pathlib:Path")
</code></pre>

    <p>Via <a href="https://adamj.eu/tech/2024/06/17/python-import-by-string/">Python: Import by string with pkgutil.resolve_name()</a></p>

## How researchers cracked an 11-year-old password to a crypto wallet
 - [https://simonwillison.net/2024/Jun/17/how-researchers-cracked-an-11-year-old-password-to-a-crypto-wall/#atom-everything](https://simonwillison.net/2024/Jun/17/how-researchers-cracked-an-11-year-old-password-to-a-crypto-wall/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-17T17:04:54+00:00

<p><a href="https://www.wired.com/story/roboform-password-3-million-dollar-crypto-wallet/">How researchers cracked an 11-year-old password to a crypto wallet</a></p>
If you used the RoboForm password manager to generate a password prior to their 2015 bug fix that password was generated using a pseudo-random number generator based on your device’s current time—which means an attacker may be able to brute-force the password from a shorter list of options if they can derive the rough date when it was created.</p>

<p>(In this case the password cracking was consensual, to recover a lost wallet, but this still serves as a warning to any RoboForm users with passwords from that era.)

## Language models on the command-line
 - [https://simonwillison.net/2024/Jun/17/cli-language-models/#atom-everything](https://simonwillison.net/2024/Jun/17/cli-language-models/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-17T16:44:39+00:00

<p>I gave a talk about accessing Large Language Models from the command-line last week as part of the <a href="https://maven.com/parlance-labs/fine-tuning">Mastering LLMs: A Conference For Developers &amp; Data Scientists</a> six week long online conference. The talk focused on my <a href="https://llm.datasette.io/">LLM</a> Python command-line utility and ways you can use it (and <a href="https://llm.datasette.io/en/stable/plugins/index.html">its plugins</a>) to explore LLMs and use them for useful tasks.</p>

<p>The talk was recorded and is available <a href="https://www.youtube.com/watch?v=QUXQNi6jQ30">on YouTube</a>. Here I've turned it into an <a href="https://simonwillison.net/tags/annotatedtalks/">annotated presentation</a>, with detailed notes and screenshots (there were no slides) to accompany the video.</p>

 

  <p style="margin-top: 1em;"><a href="https://llm.datasette.io/">LLM</a> is a tool I started building last year to help run LLM prompts directly from a command-line t

## Quoting Russ Cox
 - [https://simonwillison.net/2024/Jun/17/russ-cox/#atom-everything](https://simonwillison.net/2024/Jun/17/russ-cox/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-17T10:46:56+00:00

<blockquote cite="https://research.swtch.com/vgo-eng"><p>Most people think that we format Go code with gofmt to make code look nicer or to end debates among team members about program layout. But the most important reason for gofmt is that if an algorithm defines how Go source code is formatted, then programs, like goimports or gorename or go fix, can edit the source code more easily, without introducing spurious formatting changes when writing the code back. This helps you maintain code over time.</p></blockquote><p class="cite">&mdash; <a href="https://research.swtch.com/vgo-eng">Russ Cox</a>

