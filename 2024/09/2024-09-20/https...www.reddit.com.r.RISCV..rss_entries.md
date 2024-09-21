# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## SG2042 Newsletter (2024-09-20 #060)
 - [https://www.reddit.com/r/RISCV/comments/1fl6nrz/sg2042_newsletter_20240920_060](https://www.reddit.com/r/RISCV/comments/1fl6nrz/sg2042_newsletter_20240920_060)
 - RSS feed: $source
 - date published: 2024-09-20T07:48:57+00:00

<!-- SC_OFF --><div class="md"><h2>Editor&#39;s Note</h2> <p>Welcome to the sixtieth issue of the SG2042 Newsletter. In this issue, we bring you the latest updates on SG2042 and provide a series of tutorials over Milk-V Duo. Hope you will enjoy this update.</p> <h2>Highlights</h2> <ul> <li><p>SOPHGO has donated 22 sets of Milk-V Duo S development boards to the Wandering Project, supporting the development of the Jiachen Project&#39;s ecosystem.</p> <p><a href="https://mp.weixin.qq.com/s/gzkPemhW8p7Z8duRN53XvQ">Related news</a></p></li> </ul> <h2>Upstream</h2> <p>Most of the code is already open-source and can be obtained from repositories such as github.com/SOPHGO. The following are some useful repo resources:</p> <h3>Linux kernel</h3> <ul> <li><p>Sophgo Community work: <a href="https://github.com/sophgo/linux-riscv">https://github.com/sophgo/linux-riscv</a></p> <ul> <li>No commits this week</li> </ul></li> <li><p>Linux Official Community Upstream work: <a href="https://github.com/sop

## VLIW RISC-V compiler support
 - [https://www.reddit.com/r/RISCV/comments/1fl60ps/vliw_riscv_compiler_support](https://www.reddit.com/r/RISCV/comments/1fl60ps/vliw_riscv_compiler_support)
 - RSS feed: $source
 - date published: 2024-09-20T07:00:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Does GCC/LLVM support RISC-V target with VLIW, or any plan to support it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zhongchengyong"> /u/zhongchengyong </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fl60ps/vliw_riscv_compiler_support/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fl60ps/vliw_riscv_compiler_support/">[comments]</a></span>

## cssr t0, mstatus kernel crash
 - [https://www.reddit.com/r/RISCV/comments/1fl2fql/cssr_t0_mstatus_kernel_crash](https://www.reddit.com/r/RISCV/comments/1fl2fql/cssr_t0_mstatus_kernel_crash)
 - RSS feed: $source
 - date published: 2024-09-20T03:06:20+00:00

<!-- SC_OFF --><div class="md"><p>hello, beginner osdev here,</p> <p>my kernel is working normally till i&#39;m calling csrr t0, mstatus for reading mstatus</p> <p>after i do it the kernel crashes and reboots itself again and again</p> <p>here&#39;s my function in ziglang </p> <pre><code>pub fn mstatus_read() usize { var result: usize = 0; asm volatile (&quot;csrr %[result], mstatus&quot; : [result] &quot;=r&quot; (result), ); return result; } // kernel.zig export fn kmain() void { uart.init(); uart.print(&quot;Hello from myos&quot;); const mstatus = _asm.mstatus_read(); _ = mstatus; while (true) {} } </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SuperbBreadfruit6006"> /u/SuperbBreadfruit6006 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fl2fql/cssr_t0_mstatus_kernel_crash/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fl2fql/cssr_t0_mstatus_kernel_crash/">[comments]</a></span>

