# Source:The Linux Foundation, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCfX55Sx5hEFjoC3cNs6mCUQ, language:en

## Action Deduplication: Faster and Cheaper Remote Builds Without Lifting a Finger - Christian Scott
 - [https://www.youtube.com/watch?v=zZB_Q-BKJ04](https://www.youtube.com/watch?v=zZB_Q-BKJ04)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:37+00:00

Action Deduplication: Faster and Cheaper Remote Builds Without Lifting a Finger - Christian Scott, Canva

In this session I will discuss remote action deduplication, a feature of some Bazel RBE backends. I will explain the problem it solves, how it works, and some details about how well it has worked for us. I'll also quickly touch on merge queues, and mention some RBE backends that support the feature. --- If you run builds on every master commit, and you have commits landing more quickly than your slowest action can finish, you'll end up rebuilding unnecessarily. We estimated that our slowest webpack action was being re-run unnecessarily 66% of the time! This action is an input to a large number of expensive integration tests so it's very likely that we're also wasting a lot of compute on those tests as well. The web page builds and tests account for the vast majority of the compute we use in CI. The number of wasted builds would be even higher if we were using a merge queue, so we

## Aspect Build - Alex Eagle, Aspect Build Systems
 - [https://www.youtube.com/watch?v=lqo5qkzTS3k](https://www.youtube.com/watch?v=lqo5qkzTS3k)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:36+00:00

Aspect Build - Alex Eagle, Aspect Build Systems

Aspect authors many of the Bazel rules you know and love. We also provide the missing CI/CD and developer platform to integrate Bazel into your team's workflows and achieve the promised incremental build&test speed while reducing your cloud spend! This talk will update you on our latest and greatest.

## Building 1300 Container Images in 4 Minutes - Sushain Cherivirala, Stripe
 - [https://www.youtube.com/watch?v=c-yvIQooOSA](https://www.youtube.com/watch?v=c-yvIQooOSA)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:36+00:00

Building 1300 Container Images in 4 Minutes - Sushain Cherivirala, Stripe

Container images are a ubiquitous mechanism for deploying applications in the modern computing landscape. Everything from services deployed on bare-metal Kubernetes to AWS Lambda functions depend on container images. Building these images quickly and efficiently is critical to keeping CI/CD responsive. In recent years, Stripe has undergone dual migrations. One, to a service oriented architecture. Two, to running services inside Kubernetes. Together, these migrations meant our CI pipelines to build containers became slower and more expensive with each passing month. With a build producing over a terabyte of images, Bazel just couldn't build them fast enough! Even disk space was in short supply. Learn how we flipped the script on our container builds by leveraging BwoB (Build without the Bytes). Now, we can build 1300+ container images in just a couple minutes with plenty of headroom for more. Bazel's entire out

## Pigweed and Bazel for Embedded Development - Ted Pudlik, Google, LLC
 - [https://www.youtube.com/watch?v=eiHTMU6a7uQ](https://www.youtube.com/watch?v=eiHTMU6a7uQ)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:36+00:00

Pigweed and Bazel for Embedded Development - Ted Pudlik, Google, LLC

Pigweed is an open-source collection of embedded libraries. We aim to make Bazel the best build system for developing microcontroller firmware. In this talk, I'll discuss how Pigweed leverages Bazel's build configuration APIs and platforms to solve common problems in building embedded firmware: building binaries for multiple cores in one Bazel invocation, compiling flasher scripts that embed the firmware, creating libraries with platform-specific implementations, and more!

## Spotify's Journey to Releasing One of the World's Largest Apps wit... Luka Cindro & Gabriel Borglund
 - [https://www.youtube.com/watch?v=gN-DLmX00mk](https://www.youtube.com/watch?v=gN-DLmX00mk)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:36+00:00

Spotify's Journey to Releasing One of the World's Largest Apps with Bazel - Luka Cindro & Gabriel Borglund, Spotify

At Spotify, we migrated the Android Music app, consisting of 5 million lines of Kotlin, Java and C++ code, from Gradle to Bazel. This talk covers the how we did it, the challenges we faced and how we overcame them. We'll go into how we used a hybrid build to migrate the codebase iteratively, the various patches and performance improvements we made to Bazel and the features we implemented to release the app to end users.

## BazelCon Keynote - Mícheál Ó Foghlú & Tobias Werth, Alex Eagle, Helen Altshuler, Chuck Grindel
 - [https://www.youtube.com/watch?v=-0DRS99dSU4](https://www.youtube.com/watch?v=-0DRS99dSU4)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

BazelCon Keynote - Mícheál Ó Foghlú & Tobias Werth, Google; Alex Eagle, Aspect Build Systems; Helen Altshuler, EngFlow; Chuck Grindel, Reveal Technology

## Bazel’s Take on (Cc) Shared Libraries - Claudio Bley, Modus Create
 - [https://www.youtube.com/watch?v=Y7qh-RGtkjg](https://www.youtube.com/watch?v=Y7qh-RGtkjg)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

Bazel’s Take on (Cc) Shared Libraries - Claudio Bley, Modus Create

It took me a while to understand how cc_shared_library works in Bazel. After fighting the system and having reached every possible error message, I took a deep dive into the underlying logic and discovered how powerful that rule is once you understand its opinionated view on shared libraries and the mindset behind the design of the rule. I was also surprised to discover that it relies on Bazel aspects. To the best of my knowledge it is the only core rule that does so. In this presentation I will convey my insights using diagrams depicting how one should reason about cc_shared_library. This will cover how shared libraries are assembled from cc_libraries, how they interact as dependencies of other cc_* rules, and some interesting aspects of the implementation based on… aspects!

## Introducing Remote Bazel - Maggie Lou, BuildBuddy
 - [https://www.youtube.com/watch?v=BM2gsH2Ao04](https://www.youtube.com/watch?v=BM2gsH2Ao04)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

Introducing Remote Bazel - Maggie Lou, BuildBuddy

Many at this conference are familiar with Remote Caching and Remote Execution. Over at BuildBuddy, we’re excited to introduce Remote Bazel - running the Bazel client server and command remotely as well, making your builds even faster and more correct. Even if your builds are triggered by ephemeral CI runners, Remote Bazel will guarantee your builds always run with a warm analysis and repository cache, and remove the need to pull images, install dependencies, and clone git repos on each run. Running builds in the same datacenter as the remote cache and executors also reduces network bottlenecks and egress costs. Even if your company’s developers use machines with different operating systems or versions of tools or don’t even have Bazel installed, Remote Bazel will guarantee that important builds are run in the exact same environment every time. This talk will provide a quick overview of how we built this and the many applications we’r

## Perfect Sandboxing in Bazel - Rahul Butani, Intel
 - [https://www.youtube.com/watch?v=TxVEJ3gycUw](https://www.youtube.com/watch?v=TxVEJ3gycUw)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

Perfect Sandboxing in Bazel - Rahul Butani, Intel

Complete dependency graphs are at the heart of what gives Bazel its power and sandboxing plays a key role in keeping these graphs correct. However: Bazel's approach to sandboxing makes some concessions. With cooperation from tools this works well, but — what happens when your tools aren't well-behaved? In this talk, we detail how we — in service of migrating a 20 year old codebase to Bazel — extended Bazel and its sandbox to encode and enforce all host filesystem dependencies in Bazel's dependency graph. We'll cover the changes we had to make to use existing rulesets, how this compares with alternative solutions to this problem, lessons we learned along the way, and some takeaways for the broader ecosystem.

## Performant Bazel Builds for Web Monorepos at Scale - Sharmila Jesupaul, Airbnb
 - [https://www.youtube.com/watch?v=7gla337tfV0](https://www.youtube.com/watch?v=7gla337tfV0)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

Performant Bazel Builds for Web Monorepos at Scale - Sharmila Jesupaul, Airbnb

In this talk, you'll gain practical insights from our experience migrating Airbnb's web monorepo (which houses millions of lines of TS/JS code) to Bazel. We developed methods and tooling to trim down input sizes, share the cache between MacOS and Linux, persist caches through local and remote builds, catch and fix non-deterministic builds, and automatically generate BUILD files from JS/TS code. This helped us create a robust system for adopting Bazel without compromising on developer experience. These insights are designed to help you navigate similar migrations, improve build performance, and reuse builds across platforms.

## Post Mortems for 4 Years of Remote Execution - Ulf Adams, EngFlow Inc.
 - [https://www.youtube.com/watch?v=2c_SaHI3KLs](https://www.youtube.com/watch?v=2c_SaHI3KLs)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

Post Mortems for 4 Years of Remote Execution - Ulf Adams, EngFlow Inc.

We have been running RE for several years. In this talk, we present what we have learned - the hard way - during this time, with the hope that this will help others who are building or operating a remote execution service prevent similar issues. We will cover these themes: cloud infrastructure limits, memory management pitfalls, software architecture oh-nos, and monitoring mistakes.

## Running a Start-up on Bazel - Prasanna Swaminathan, Ergatta
 - [https://www.youtube.com/watch?v=BSw7HhF9jRM](https://www.youtube.com/watch?v=BSw7HhF9jRM)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

Running a Start-up on Bazel - Prasanna Swaminathan, Ergatta

Bazel is typically described as a build system meant for large-scale systems. It's also described as a build system meant for teams with dedicated help to Bazel. But...what if you have neither? What if you are a small-scale start-up? Start-ups, by their nature, rarely have a spare headcount to devote to a build systems engineer. Their codebases are also usually pretty small. Why on Earth would you use Bazel in that context? Ergatta *is* using Bazel in that context. Ergatta has 1 MM LOC. Ergatta does not have the headcount to devote an engineer to Bazel. How does it work? How does a start-up with a 10-person engineering team work with a system that notoriously requires so much maintenance? In this talk, I'll talk about why we would ever entertain such a notion, what makes Bazel work for us, and how we remain productive in these times.

## State of the Union - Tobias Werth & John Field, Google
 - [https://www.youtube.com/watch?v=-rjIX5AVF5A](https://www.youtube.com/watch?v=-rjIX5AVF5A)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

State of the Union - Tobias Werth & John Field, Google

## The Classics Never Go Out of Style: An Empirical Study of Downgrades from Bazel - Shane McIntosh
 - [https://www.youtube.com/watch?v=Yu281P45NsA](https://www.youtube.com/watch?v=Yu281P45NsA)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:35+00:00

The Classics Never Go Out of Style: An Empirical Study of Downgrades from Bazel - Shane McIntosh, University of Waterloo

Enticed by advanced features, several software teams have migrated their build systems to a modern generation of build technologies, such as Bazel. However, not all migrations lead to perceived improvements, ultimately culminating in abandonment of the build technology. In this talk, we will present the results of our recent empirical study of 542 open-source projects that adopt Bazel. We observed that (1) 61 projects (11.2%) have abandoned Bazel; and (2) abandonment tends to occur after investing in Bazel for a substantial amount of time (a median of 638 days). Thematic analysis reveals seven recurring reasons for abandonment, such as technical challenges, lack of platform integration, team coordination issues, and upstream trends. After abandoning Bazel, the studied projects have adopted a broad set of alternatives, spanning from language-specific tools like Go 

## Lessons from a Large JVM Monorepo - Janusz Kudelka, Airbnb
 - [https://www.youtube.com/watch?v=-aoFq_rh1QQ](https://www.youtube.com/watch?v=-aoFq_rh1QQ)
 - RSS feed: $source
 - date published: 2024-10-26T06:39:34+00:00

Lessons from a Large JVM Monorepo - Janusz Kudelka, Airbnb

Airbnb's JVM monorepo hosts 10s of millions of lines of Java, Kotlin and Scala. Each language posing unique challenges. This talk will show how we solved many of them, examples include: * importance of Remote Persistent Workers for RBE and how to maintain them * supporting cross-platform builds (mac and linux, x86 and arm) with universal binaries allowing cache sharing and dynamic execution across * safe and efficient usage of multiple source and runtime versions: mixed java 8 and 17, gradual runtime migrations, supporting multiple scala versions * our approach to compilation avoidance * straight to bytecode codegen when all other optimizations are not enough * what we tried that didn't work * ... and more

