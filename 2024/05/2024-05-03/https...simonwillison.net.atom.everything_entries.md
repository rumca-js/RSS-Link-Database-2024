# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Quoting Daniel Zingaro
 - [https://simonwillison.net/2024/May/3/daniel-zingaro/#atom-everything](https://simonwillison.net/2024/May/3/daniel-zingaro/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-03T18:17:50+00:00

<blockquote cite="https://spectrum.ieee.org/ai-coding"><p>I used to have this singular focus on students writing code that they submit, and then I run test cases on the code to determine what their grade is. This is such a narrow view of what it means to be a software engineer, and I just felt that with generative AI, I’ve managed to overcome that restrictive view.<br /><br />It’s an opportunity for me to assess their learning process of the whole software development [life cycle]—not just code. And I feel like my courses have opened up more and they’re much broader than they used to be. I can make students work on larger and more advanced projects.</p></blockquote><p class="cite">&mdash; <a href="https://spectrum.ieee.org/ai-coding">Daniel Zingaro</a>

## I'm writing a new vector search SQLite Extension
 - [https://simonwillison.net/2024/May/3/sqlite-vec/#atom-everything](https://simonwillison.net/2024/May/3/sqlite-vec/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-05-03T03:16:39+00:00

<p><a href="https://alexgarcia.xyz/blog/2024/building-new-vector-search-sqlite/index.html">I&#x27;m writing a new vector search SQLite Extension</a></p>
Alex Garcia is working on <code>sqlite-vec</code>, a spiritual successor to his <code>sqlite-vss</code> project. The new SQLite C extension will have zero other dependencies (<code>sqlite-vss</code> used some tricky C++ libraries) and will work using virtual tables, storing chunks of vectors in shadow tables to avoid needing to load everything into memory at once.

