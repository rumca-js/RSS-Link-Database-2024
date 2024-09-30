# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Help on riscv inline assembly
 - [https://www.reddit.com/r/RISCV/comments/1fs4aih/help_on_riscv_inline_assembly](https://www.reddit.com/r/RISCV/comments/1fs4aih/help_on_riscv_inline_assembly)
 - RSS feed: $source
 - date published: 2024-09-29T13:25:10+00:00

<!-- SC_OFF --><div class="md"><p>I am trying some basic riscv inline assembly:</p> <pre><code>int main() { int n1 = 3; int n2 = 5; int sum = -1; int prod = -1; asm volatile( &quot;add %0, %2, %3\n&quot; &quot;mul %1, %2, %3\n&quot; :&quot;=r&quot;(sum),&quot;=r&quot;(prod) :&quot;r&quot;(n1),&quot;r&quot;(n2) : ); printf(&quot;%d plus %d equals %d\n&quot;, n1, n2,sum); printf(&quot;%d times %d equals %d\n&quot;, n1, n2,prod); return 0; } Assembly listing: ================== 10438: 478d li a5,3 1043a: fef42023 sw a5,-32(s0) 1043e: 4795 li a5,5 10440: fef42223 sw a5,-28(s0) ... ... 10450: fe042783 lw a5,-32(s0) 10454: fe442703 lw a4,-28(s0) 10458: 973e add a4,a4,a5 1045a: 02e787b3 mul a5,a5,a4 1045e: fee42423 sw a4,-24(s0) 10462: fef42623 sw a5,-20(s0) </code></pre> <p>The assembly listing shows the sum in <code>a4</code> <code>pc=0x10458</code> is used as the source for the next <code>mul</code> instruction. The output I get looks like this:</p> <pre><code>3 plus 5 equals 8 3 times 5 

## I built a tool to decode register values (e.g. what does 0x40141104 mean in misa?). I've got a bunch of RISC-V registers added already. Which other ones should I include?
 - [https://www.reddit.com/r/RISCV/comments/1frvqsb/i_built_a_tool_to_decode_register_values_eg_what](https://www.reddit.com/r/RISCV/comments/1frvqsb/i_built_a_tool_to_decode_register_values_eg_what)
 - RSS feed: $source
 - date published: 2024-09-29T03:50:19+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/redfroody"> /u/redfroody </a> <br/> <span><a href="https://regviz.com/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1frvqsb/i_built_a_tool_to_decode_register_values_eg_what/">[comments]</a></span>

