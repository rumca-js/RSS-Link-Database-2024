# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Strachey love letter algorithm
 - [https://simonwillison.net/2024/Mar/23/strachey-love-letter-algorithm/#atom-everything](https://simonwillison.net/2024/Mar/23/strachey-love-letter-algorithm/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-23T21:55:59+00:00

<p><a href="https://en.wikipedia.org/wiki/Strachey_love_letter_algorithm">Strachey love letter algorithm</a></p>
<p>This is a beautiful piece of computer history. In 1952, Christopher Strachey - a contemporary of Alan Turing - wrote a love letter generation program for a Manchester Mark 1 computer. It produced output like this:</p>

<p>&quot;Darling Sweetheart,</p>

<p>You are my avid fellow feeling. My affection curiously clings to your passionate wish. My liking yearns for your heart. You are my wistful sympathy: my tender liking.</p>

<p>Yours beautifully</p>

<p>M. U. C.&quot;</p>

<p>The algorithm simply combined a small set of predefined sentence structures, filled in with random adjectives.</p>

<p>Wikipedia notes that &quot;Strachey wrote about his interest in how “a rather simple trick” can produce an illusion that the computer is thinking, and that “these tricks can lead to quite unexpected and interesting results”.</p>

<p>LLMs, 1952 edition!</p>

    <p>Via <a hre

## time-machine example test for a segfault in Python
 - [https://simonwillison.net/2024/Mar/23/test-segfault-in-python/#atom-everything](https://simonwillison.net/2024/Mar/23/test-segfault-in-python/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-23T19:44:07+00:00

<p><a href="https://github.com/adamchainz/time-machine/pull/433/files#diff-92ea7165ddf0128246b9758ee9554b3eccb4eceb3d4719bdea9f5495ebbe10a1R477-R495">time-machine example test for a segfault in Python</a></p>
<p>Here&#x27;s a really neat testing trick by Adam Johnson. Someone reported a segfault bug in his time-machine library. How you you write a unit test that exercises a segfault without crashing the entire test suite?</p>

<p>Adam&#x27;s solution is a test that does this:</p>

<p>subprocess.run([sys.executable, &quot;-c&quot;, code_that_crashes_python], check=True)</p>

<p>sys.executable is the path to the current Python executable - ensuring the code will run in the same virtual environment as the test suite itself. The -c option can be used to have it run a (multi-line) string of Python code, and check=True causes the subprocess.run() function to raise an error if the subprocess fails to execute cleanly and returns an error code.</p>

<p>I&#x27;m absolutely going to be 

## Building C extensions for SQLite with ChatGPT Code Interpreter
 - [https://simonwillison.net/2024/Mar/23/building-c-extensions-for-sqlite-with-chatgpt-code-interpreter/#atom-everything](https://simonwillison.net/2024/Mar/23/building-c-extensions-for-sqlite-with-chatgpt-code-interpreter/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-23T17:50:30+00:00

<p>I wrote yesterday about how I used <a href="https://simonwillison.net/2024/Mar/22/claude-and-chatgpt-case-study/">Claude and ChatGPT Code Interpreter for simple ad-hoc side quests</a> - in that case, for converting a shapefile to GeoJSON and merging it into a single polygon.</p>

<p>Today I have a much more ambitious example.</p>

<p>I was thinking this morning about vector similarity, and how I really like the pattern of storing encoded floating point vectors in BLOB columns in a SQLite database table and then using a custom SQL function to decode them and calculate cosine similarity between them.</p>
<p>I've written code for this a few times in Python, with Python functions that get registered with SQLite as custom SQL functions. Here's <a href="https://github.com/simonw/llm/blob/fb63c92cd27053700daa5420a0d1ad8fdfb718bd/llm/embeddings.py#L240-L287">an example</a> from my <a href="https://llm.datasette.io/">LLM</a> tool.</p>
<p>What I'd really like is a SQLite C extension

## mapshaper.org
 - [https://simonwillison.net/2024/Mar/23/mapshaperorg/#atom-everything](https://simonwillison.net/2024/Mar/23/mapshaperorg/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-23T03:44:22+00:00

<p><a href="https://mapshaper.org/">mapshaper.org</a></p>
<p>It turns out the mapshaper CLI tool for manipulating geospatial data - including converting shapefiles to GeoJSON and back again - also has a web UI that runs the conversions entirely in your browser. If you need to convert between those (and other) formats it&#x27;s hard to imagine a more convenient option.</p>

    <p>Via <a href="https://twitter.com/adamrpearce/status/1771378836128854097">@adamrpearce</a></p>

