# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Breaking Instruction Hierarchy in OpenAI's gpt-4o-mini
 - [https://simonwillison.net/2024/Jul/22/breaking-instruction-hierarchy/#atom-everything](https://simonwillison.net/2024/Jul/22/breaking-instruction-hierarchy/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-22T19:51:29+00:00

<p><a href="https://embracethered.com/blog/posts/2024/chatgpt-gpt-4o-mini-instruction-hierarchie-bypasses/">Breaking Instruction Hierarchy in OpenAI&#x27;s gpt-4o-mini</a></p>
Johann Rehberger digs further into GPT-4o's "instruction hierarchy" protection and finds that it has little impact at all on common prompt injection approaches.</p>
<blockquote>
<p>I spent some time this weekend to get a better intuition about <code>gpt-4o-mini</code> model and instruction hierarchy, and the conclusion is that system instructions are still not a security boundary.</p>
<p>From a security engineering perspective nothing has changed: <strong>Do not depend on system instructions alone to secure a system, protect data or control automatic invocation of sensitive tools.</strong></p>
</blockquote>


    <p>Tags: <a href="https://simonwillison.net/tags/prompt-injection">prompt-injection</a>, <a href="https://simonwillison.net/tags/security">security</a>, <a href="https://simonwillison.net/tags/generativ

## No More Blue Fridays
 - [https://simonwillison.net/2024/Jul/22/no-more-blue-fridays/#atom-everything](https://simonwillison.net/2024/Jul/22/no-more-blue-fridays/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-22T18:33:00+00:00

<p><a href="https://www.brendangregg.com/blog/2024-07-22/no-more-blue-fridays.html">No More Blue Fridays</a></p>
Brendan Gregg: "In the future, computers will not crash due to bad software updates, even those updates that involve kernel code. In the future, these updates will push eBPF code."</p>
<p>New-to-me things I picked up from this:</p>
<ol>
<li>eBPF - a technology I had thought was unique to the a Linux kernel - is coming Windows!</li>
<li>A useful mental model to have for eBPF is that it provides a WebAssembly-style sandbox for kernel code.</li>
<li>eBPF doesn't stand for "extended Berkeley Packet Filter" any more - that name greatly understates its capabilities and has been retired. More on that <a href="https://ebpf.io/what-is-ebpf/#what-do-ebpf-and-bpf-stand-for">in the eBPF FAQ</a>.</li>
<li>From <a href="https://news.ycombinator.com/item?id=41034079">this Hacker News thread</a> eBPF programs can be analyzed before running despite the halting problem because eBPF only allo

## Jiff
 - [https://simonwillison.net/2024/Jul/22/jiff/#atom-everything](https://simonwillison.net/2024/Jul/22/jiff/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-07-22T04:48:35+00:00

<p><a href="https://github.com/BurntSushi/jiff">Jiff</a></p>
Andrew Gallant (aka BurntSushi) implemented <a href="https://github.com/rust-lang/regex">regex</a> for Rust and built the fabulous <a href="https://github.com/BurntSushi/ripgrep">ripgrep</a>, so it's worth paying attention to their new projects.</p>
<p>Jiff is a brand new datetime library for Rust which focuses on "providing high level datetime primitives that are difficult to misuse and have reasonable performance". The API design is heavily inspired by the <a href="https://tc39.es/proposal-temporal/docs/index.html">Temporal</a> proposal for JavaScript.</p>
<p>The core type provided by Jiff is <code>Zoned</code>, best imagine as a 96-bit integer nanosecond time since the Unix each combined with a geographic region timezone and a civil/local calendar date and clock time.</p>
<p>The <a href="https://docs.rs/jiff/latest/jiff/">documentation</a> is comprehensive and a fascinating read if you're interested in API design and time

