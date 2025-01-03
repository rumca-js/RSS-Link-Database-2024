# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Paging on JH7110
 - [https://www.reddit.com/r/RISCV/comments/1h1wkn0/paging_on_jh7110](https://www.reddit.com/r/RISCV/comments/1h1wkn0/paging_on_jh7110)
 - RSS feed: $source
 - date published: 2024-11-28T14:01:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a xv6 port to MilkV mars SBC. You can find my code <a href="https://github.com/GerfautGE/xv6-mars">here</a></p> <p>I&#39;m stuck with paging. When I write to <code>satp</code> in <code>kvminithart()</code> to enable <strong>sv39</strong>, the hart jumps out of the kernel memory on <code>sfence.vma</code> instruction (U-Boot Trap handling on page fault ?).</p> <p>On QEMU virt, everything works perfectly and I have a complete boot sequence.</p> <p>My intuition is that xv6 emulates sv39 in a way and when I run it on real hardware, the MMU doesn&#39;t appreciate... Moreover, I&#39;ve manage to get a full kernel boot by &quot;disabling&quot; real sv39 with this <a href="https://github.com/GerfautGE/xv6-mars/commit/321bb64be951c22fa8facb17762401d75a24ad35">commit</a> but this blocks the user space virtual memory addressing.</p> <p>I think I&#39;m missing something here ...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https:

## LLVM Merges Support The For Tenstorrent TT-Ascalon-D8 RISC-V CPU
 - [https://www.reddit.com/r/RISCV/comments/1h1vc86/llvm_merges_support_the_for_tenstorrent](https://www.reddit.com/r/RISCV/comments/1h1vc86/llvm_merges_support_the_for_tenstorrent)
 - RSS feed: $source
 - date published: 2024-11-28T12:54:52+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1h1vc86/llvm_merges_support_the_for_tenstorrent/"> <img src="https://external-preview.redd.it/VxUno3p_oR8XFyom4RZB2UOhxJ3vRG_xz916s0UGzMM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=0c113a595952d5f552c4c60d7a9cb17303e9bfe3" alt="LLVM Merges Support The For Tenstorrent TT-Ascalon-D8 RISC-V CPU" title="LLVM Merges Support The For Tenstorrent TT-Ascalon-D8 RISC-V CPU" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/3G6A5W338E"> /u/3G6A5W338E </a> <br/> <span><a href="https://www.phoronix.com/news/LLVM-20-Tenstorrent-Ascalon">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1h1vc86/llvm_merges_support_the_for_tenstorrent/">[comments]</a></span> </td></tr></table>

