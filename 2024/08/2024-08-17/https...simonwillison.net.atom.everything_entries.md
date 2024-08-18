# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Upgrading my cookiecutter templates to use python -m pytest
 - [https://simonwillison.net/2024/Aug/17/python-m-pytest/#atom-everything](https://simonwillison.net/2024/Aug/17/python-m-pytest/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-08-17T05:12:47+00:00

<p><strong><a href="https://github.com/simonw/python-lib/issues/9">Upgrading my cookiecutter templates to use python -m pytest</a></strong></p>
Every now and then I get caught out by weird test failures when I run <code>pytest</code> and it turns out I'm running the wrong installation of that tool, so my tests fail because that <code>pytest</code> is executing in a different virtual environment from the one needed by the tests.</p>
<p>The fix for this is easy: run <code>python -m pytest</code> instead, which guarantees that you will run <code>pytest</code> in the same environment as your currently active Python.</p>
<p>Yesterday I went through and updated every one of my <code>cookiecutter</code> templates (<a href="https://github.com/simonw/python-lib">python-lib</a>, <a href="https://github.com/simonw/click-app">click-app</a>, <a href="https://github.com/simonw/datasette-plugin">datasette-plugin</a>, <a href="https://github.com/simonw/sqlite-utils-plugin">sqlite-utils-plugin</a>, <a

