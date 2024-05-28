# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Function Composition and the Pipe Operator in C++23 – With std::expected
 - [https://www.cppstories.com/2024/pipe-operator](https://www.cppstories.com/2024/pipe-operator)
 - RSS feed: https://www.cppstories.com/index.xml
 - date published: 2024-05-27T00:00:00+00:00

<p>In this blog post, we&rsquo;ll show how to implement a custom pipe operator and apply it to a data processing example. Thanks to C++23 and <code>std::expected</code>we can write a rather efficient framework that easily handles <code>unexpected</code> outcomes.</p>
<p>This is a collaborative guest post by <strong>prof. Bogusław Cyganek</strong>:</p>


<div style="display: flex;">        
        <div style="margin-left: 20px;">
            <a href="https://amzn.to/2OB3bBy" target="_blank"><img alt="Prof. Cyganek's Book" src="https://www.cppstories.com/2023/images/cyganek_intro.jpg" width="170px" /></a>
        </div>
        <div>
            <blockquote>
                <p><strong>Prof. Cyganek</strong> is a researcher and lecturer at the Department of Electronics, AGH University of Science and Technology in Cracow, Poland. He has worked as a software engineer for a number of companies such as Nisus Writer USA, Compression Techniques USA, Manta Corp. USA, Visual Atoms UK, Wroclaw U

