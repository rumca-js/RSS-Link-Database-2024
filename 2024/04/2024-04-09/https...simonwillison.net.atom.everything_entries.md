# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## A solid pattern to build LLM Applications (feat. Claude)
 - [https://simonwillison.net/2024/Apr/9/a-solid-pattern-to-build-llm-applications/#atom-everything](https://simonwillison.net/2024/Apr/9/a-solid-pattern-to-build-llm-applications/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-09T18:39:30+00:00

<p><a href="https://www.youtube.com/watch?v=8w0hUcQSDy8">A solid pattern to build LLM Applications (feat. Claude)</a></p>
<p>Hrishi Olickel is one of my favourite prompt whisperers. In this YouTube video he walks through his process for building quick interactive applications with the assistance of Claude 3, spinning up an app that analyzes his meeting transcripts to extract participants and mentioned organisations, then presents a UI for exploring the results built with Next.js and shadcn/ui.</p>

<p>An interesting tip I got from this: use the weakest, not the strongest models to iterate on your prompts. If you figure out patterns that work well with Claude 3 Haiku they will have a significantly lower error rate with Sonnet or Opus. The speed of the weaker models also means you can iterate much faster, and worry less about the cost of your experiments.</p>

    <p>Via <a href="https://twitter.com/hrishioa/status/1777723898832019663">@hrishioa</a></p>

## Command R+ now ranked 6th on the LMSYS Chatbot Arena
 - [https://simonwillison.net/2024/Apr/9/command-r/#atom-everything](https://simonwillison.net/2024/Apr/9/command-r/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-09T16:19:09+00:00

<p><a href="https://fedi.simonwillison.net/@simon/112242034813525962">Command R+ now ranked 6th on the LMSYS Chatbot Arena</a></p>
<p>The LMSYS Chatbot Arena Leaderboard is one of the most interesting approaches to evaluating LLMs because it captures their ever-elusive &quot;vibes&quot; - it works by users voting on the best responses to prompts from two initially hidden models</p>

<p>Big news today is that Command R+ - the brand new open weights model (Creative Commons non-commercial) by Cohere - is now the highest ranked non-proprietary model, in at position six and beating one of the GPT-4s.</p>

<p>(Linking to my screenshot on Mastodon.)</p>

## llm.c
 - [https://simonwillison.net/2024/Apr/9/llmc/#atom-everything](https://simonwillison.net/2024/Apr/9/llmc/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-09T15:24:33+00:00

<p><a href="https://github.com/karpathy/llm.c">llm.c</a></p>
<p>Andrej Karpathy implements LLM training - initially for GPT-2, other architectures to follow - in just over 1,000 lines of C on top of CUDA. Includes a tutorial about implementing LayerNorm by porting an implementation from Python.</p>

    <p>Via <a href="https://twitter.com/karpathy/status/1777427944971083809">@karpathy</a></p>

## Hello World
 - [https://simonwillison.net/2024/Apr/9/hello-world/#atom-everything](https://simonwillison.net/2024/Apr/9/hello-world/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-09T01:06:46+00:00

<p><a href="https://thecoder08.github.io/hello-world.html">Hello World</a></p>
<p>Lennon McLean dives deep down the rabbit hole of what happens when you execute the binary compiled from &quot;Hello world&quot; in C on a Linux system, digging into the details of ELF executables, objdump disassembly, the C standard library, stack frames, null-terminated strings and taking a detour through musl because it&#x27;s easier to read than Glibc.</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=39967709">Hacker News</a></p>

