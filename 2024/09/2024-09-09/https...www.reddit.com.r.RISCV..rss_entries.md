# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## LINUX FUNCTION TRACER SUPPORT
 - [https://www.reddit.com/r/RISCV/comments/1fco9ft/linux_function_tracer_support](https://www.reddit.com/r/RISCV/comments/1fco9ft/linux_function_tracer_support)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-09T12:30:46+00:00

<!-- SC_OFF --><div class="md"><p>I am currently working with a RISC-V kernel and i am interested in enabling function tracing. However, I noticed that <code>CONFIG_FUNCTION_TRACER</code> is not present in my kernel configuration. </p> <p>I am running BCC tools for riscv in qemu in which i got the following error:<br/> FileNotFoundError: [Errno 2] No such file or directory: &#39;/sys/kernel/debug/tracing/available_filter_functions&#39;<br/> after investigating i came know that its due to <code>CONFIG_FUNCTION_TRACER</code> is not present in my kernel configuration.</p> <p>Does the Function Tracer (<a href="https://www.kernel.org/doc/Documentation/trace/ftrace.txt">https://www.kernel.org/doc/Documentation/trace/ftrace.txt 13</a>) work in RISC-V Linux? </p> <p>Is <code>CONFIG_FUNCTION_TRACER</code> supported on the RISC-V architecture in the current kernel versions?</p> <p>Thanks,<br/> Harish</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HarishSa

