# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Tenstorrent Wormhole Series Part 6: Vector instruction set
 - [https://www.reddit.com/r/RISCV/comments/1g0uybn/tenstorrent_wormhole_series_part_6_vector](https://www.reddit.com/r/RISCV/comments/1g0uybn/tenstorrent_wormhole_series_part_6_vector)
 - RSS feed: $source
 - date published: 2024-10-10T22:24:28+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://www.corsix.org/content/tt-wh-part6">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g0uybn/tenstorrent_wormhole_series_part_6_vector/">[comments]</a></span>

## Hi everyone , I'm facing the issue while generating a bit stream of Ariane can anyone tell me why line 63 is showing the error of the integer overflow ?????????????
 - [https://www.reddit.com/r/RISCV/comments/1g0lbja/hi_everyone_im_facing_the_issue_while_generating](https://www.reddit.com/r/RISCV/comments/1g0lbja/hi_everyone_im_facing_the_issue_while_generating)
 - RSS feed: $source
 - date published: 2024-10-10T15:22:32+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1g0lbja/hi_everyone_im_facing_the_issue_while_generating/"> <img src="https://b.thumbs.redditmedia.com/Re1VolokwApp13uAE5IQI4_Da_AHAG6HMQWdITOUTTE.jpg" alt="Hi everyone , I'm facing the issue while generating a bit stream of Ariane can anyone tell me why line 63 is showing the error of the integer overflow ?????????????" title="Hi everyone , I'm facing the issue while generating a bit stream of Ariane can anyone tell me why line 63 is showing the error of the integer overflow ?????????????" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ChanceStuff21"> /u/ChanceStuff21 </a> <br/> <span><a href="https://www.reddit.com/gallery/1g0lbja">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g0lbja/hi_everyone_im_facing_the_issue_while_generating/">[comments]</a></span> </td></tr></table>

## Software-defined processors: the promise of RISC-V
 - [https://www.reddit.com/r/RISCV/comments/1g0h0s8/softwaredefined_processors_the_promise_of_riscv](https://www.reddit.com/r/RISCV/comments/1g0h0s8/softwaredefined_processors_the_promise_of_riscv)
 - RSS feed: $source
 - date published: 2024-10-10T11:54:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1g0h0s8/softwaredefined_processors_the_promise_of_riscv/"> <img src="https://external-preview.redd.it/wr_7syVJxDEAgiSR0si9ktwd0m0WM80tdIpxUzMYm3w.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=718617485a20202ad42e8b063e87f8c2468714ff" alt="Software-defined processors: the promise of RISC-V" title="Software-defined processors: the promise of RISC-V" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://next.redhat.com/2024/10/09/software-defined-processors-the-promise-of-risc-v/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g0h0s8/softwaredefined_processors_the_promise_of_riscv/">[comments]</a></span> </td></tr></table>

## Weird segfault: am I missing something?
 - [https://www.reddit.com/r/RISCV/comments/1g08hrx/weird_segfault_am_i_missing_something](https://www.reddit.com/r/RISCV/comments/1g08hrx/weird_segfault_am_i_missing_something)
 - RSS feed: $source
 - date published: 2024-10-10T02:11:29+00:00

<!-- SC_OFF --><div class="md"><p>I have this C++ code:</p> <pre><code>#include &lt;iostream&gt; #include &lt;vector&gt; int myRiscvFunc(int x) { asm(&quot;.include \&quot;myasm.s\&quot;&quot;); } int main() { std::vector&lt;int&gt; v = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}; for (int &amp;entry : v) { std::cout &lt;&lt; entry &lt;&lt; std::endl; } for (int &amp;entry : v) { entry = myRiscvFunc(entry); } for (int &amp;entry : v) { std::cout &lt;&lt; entry &lt;&lt; std::endl; } asm(&quot;addi a0, zero, 0&quot;); asm(&quot;li a7, 93&quot;); asm(&quot;ecall&quot;); } </code></pre> <p>and this RISC-V assembly:</p> <pre><code>addi t0, a0, 0 addi t1, zero, 7 addi t2, zero, 2 loop: mul t0, t0, t2 addi t1, t1, -1 bnez t1, loop addi a0, t0, 0 ret </code></pre> <p>When I run this code with QEMU, I get the numbers 1-10 and then a segfault. What am I missing here with regards to the function argument passing conventions? What does work is creating a single variable <code>int x</code> and then assigning 

## Clean install Ubuntu on DC Roma II Laptop.
 - [https://www.reddit.com/r/RISCV/comments/1g06b4a/clean_install_ubuntu_on_dc_roma_ii_laptop](https://www.reddit.com/r/RISCV/comments/1g06b4a/clean_install_ubuntu_on_dc_roma_ii_laptop)
 - RSS feed: $source
 - date published: 2024-10-10T00:18:07+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Sorry if this is not the right place to post this but I recently acquired a DC Roma II laptop. It seems to have broken and does not start up any longer. I couldn&#39;t get any key combination to work for accessing the BIOS (I am not even sure it has a BIOS). Is there anyway to clean install Ubuntu (or any RISC-V compatible OS) on to my machine so it will start up again?</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cs61bredditaccount"> /u/cs61bredditaccount </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1g06b4a/clean_install_ubuntu_on_dc_roma_ii_laptop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g06b4a/clean_install_ubuntu_on_dc_roma_ii_laptop/">[comments]</a></span>

