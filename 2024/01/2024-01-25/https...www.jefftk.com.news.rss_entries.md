# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Importing a Python File by Name
 - [https://www.jefftk.com/p/importing-a-python-file-by-name](https://www.jefftk.com/p/importing-a-python-file-by-name)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2024-01-25T08:00:00+00:00

<p><span>

Let's say you have a python script:

</span>

<pre>
2024-01-24--evaluate-chimeras.py
</pre>

And you want to pull a section of it out into a separate file:



<pre>
2024-01-25--strand-split-artifacts.py
</pre>

You would hope you could just do something like:



<pre>
import "/path/to/2024-01-25--strand-split-artifacts.py"
</pre>

But this doesn't work: 

<code>import</code> wants a module name, not a
filename.  The simplest way I know to import a python file from a path
is:



<pre>
import sys
import importlib

sys.path.append("/path/to/")
ssa = importlib.import_module("2024-01-25--strand-split-artifacts")
</pre>

There are a lot of 

<a href="https://stackoverflow.com/questions/67631/how-can-i-import-a-module-dynamically-given-the-full-path">complicated
ways to do this</a>, some of which avoid needing to add something to


<code>sys.path</code>, but for quick one-off research code better to
keep it simple.

  

<p><i>Comment via: <a href="https://www.facebook.com

