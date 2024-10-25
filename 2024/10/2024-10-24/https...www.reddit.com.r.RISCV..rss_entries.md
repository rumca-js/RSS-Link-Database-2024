# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Announcing the RISE RISC-V Developer Appreciation Pilot Program: Empowering Developers to Expand RISC-V’s Reach
 - [https://www.reddit.com/r/RISCV/comments/1gbeask/announcing_the_rise_riscv_developer_appreciation](https://www.reddit.com/r/RISCV/comments/1gbeask/announcing_the_rise_riscv_developer_appreciation)
 - RSS feed: $source
 - date published: 2024-10-24T21:46:22+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/camel-cdr-"> /u/camel-cdr- </a> <br/> <span><a href="https://riseproject.dev/2024/10/01/announcing-the-rise-risc-v-developer-appreciation-pilot-program-empowering-developers-to-expand-risc-vs-reach/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gbeask/announcing_the_rise_riscv_developer_appreciation/">[comments]</a></span>

## Nvidia to ship a billion of RISC-V cores in 2024
 - [https://www.reddit.com/r/RISCV/comments/1gbdb1v/nvidia_to_ship_a_billion_of_riscv_cores_in_2024](https://www.reddit.com/r/RISCV/comments/1gbdb1v/nvidia_to_ship_a_billion_of_riscv_cores_in_2024)
 - RSS feed: $source
 - date published: 2024-10-24T21:01:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1gbdb1v/nvidia_to_ship_a_billion_of_riscv_cores_in_2024/"> <img src="https://external-preview.redd.it/HD9SkFLW5tbTggMuF3NAHX3LQUAKiWM379Kus4ZroNg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=4e64ad9161d61e022cbdef3a31b846b5062eb2f9" alt="Nvidia to ship a billion of RISC-V cores in 2024" title="Nvidia to ship a billion of RISC-V cores in 2024" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jacko10101010101"> /u/Jacko10101010101 </a> <br/> <span><a href="https://www.tomshardware.com/pc-components/gpus/nvidia-to-ship-a-billion-of-risc-v-cores-in-2024">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gbdb1v/nvidia_to_ship_a_billion_of_riscv_cores_in_2024/">[comments]</a></span> </td></tr></table>

## Possibel failure in the parameter passing convention
 - [https://www.reddit.com/r/RISCV/comments/1gbcv6k/possibel_failure_in_the_parameter_passing](https://www.reddit.com/r/RISCV/comments/1gbcv6k/possibel_failure_in_the_parameter_passing)
 - RSS feed: $source
 - date published: 2024-10-24T20:42:57+00:00

<!-- SC_OFF --><div class="md"><p>Im doing a program of an integral for a uni project but it gives me Possibel failure in the parameter passing convention in the last line of code every time (jr ra). Can someone help me please.</p> <p>(pow is a library that we are obligated to use that changes all a and t registers so thats why I only use s registers)</p> <p>The code:</p> <p>.data</p> <pre><code>msga: .string &quot;Enter value for a&quot; </code></pre> <p>msgb: .string &quot;Enter value for b&quot;</p> <p>msgp: .string &quot;Enter value for p&quot;</p> <p>msgq: .string &quot;Enter value for q&quot;</p> <p>msgr: .string &quot;Enter value for r&quot;</p> <p>msgN: .string &quot;Enter value for N&quot;</p> <p>msgx: .string &quot;Enter value for x&quot;</p> <p>.text</p> <p>main:</p> <pre><code>\#print and save parameters </code></pre> <p>#a</p> <pre><code>la a0 msga </code></pre> <p>li a7 4</p> <p>ecall</p> <p>li a7 5</p> <p>ecall</p> <p>mv s0 a0</p> <p>#b</p> <p>la a0 msgb</p> <p>li a7 4

## Instruction Latencies (shift, mul, add)
 - [https://www.reddit.com/r/RISCV/comments/1gb5qm9/instruction_latencies_shift_mul_add](https://www.reddit.com/r/RISCV/comments/1gb5qm9/instruction_latencies_shift_mul_add)
 - RSS feed: $source
 - date published: 2024-10-24T15:44:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>New to RISCV here.<br/> I tried some intrinsics to measure the runtimes of vec-vec elementwise add, shift, and mul for int32.<br/> It turned out that all three instructions take almost the same amount of time.<br/> I was expecting a shift operation to be 5 to 6 times faster than a mul operation.</p> <p>I know these specs are implementation-dependent, but almost none of these Chinese SoCs come with a detailed ref manual to specify the latencies.</p> <p>I ran my tests on a BananaPi F3 with and without RVV 1.0.</p> <p>Any advice?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnowyOwl72"> /u/SnowyOwl72 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gb5qm9/instruction_latencies_shift_mul_add/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gb5qm9/instruction_latencies_shift_mul_add/">[comments]</a></span>

## Is it ok to connect nvidia GTX1060 6GB GPU to PCie Gen2X2 slot of Milk-V Jupiter motherboard?
 - [https://www.reddit.com/r/RISCV/comments/1gb599c/is_it_ok_to_connect_nvidia_gtx1060_6gb_gpu_to](https://www.reddit.com/r/RISCV/comments/1gb599c/is_it_ok_to_connect_nvidia_gtx1060_6gb_gpu_to)
 - RSS feed: $source
 - date published: 2024-10-24T15:24:17+00:00

<!-- SC_OFF --><div class="md"><p>I have received my Milk-V Jupiter motherboard today, which works fine with Bianbu. I have an old GTX1060 6GB GPU lying idle. I would like to connect with power from ATX PSU. I know that performance will be very low due to Gen2X2 and lack of nvidia proprietary driver. I would like to double check here for the safety of motherboard since I have paid $250 for this board to import to my country.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/user0user"> /u/user0user </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gb599c/is_it_ok_to_connect_nvidia_gtx1060_6gb_gpu_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gb599c/is_it_ok_to_connect_nvidia_gtx1060_6gb_gpu_to/">[comments]</a></span>

## TTP on Arm/Qualcomm drama!
 - [https://www.reddit.com/r/RISCV/comments/1gayyoh/ttp_on_armqualcomm_drama](https://www.reddit.com/r/RISCV/comments/1gayyoh/ttp_on_armqualcomm_drama)
 - RSS feed: $source
 - date published: 2024-10-24T10:00:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1gayyoh/ttp_on_armqualcomm_drama/"> <img src="https://external-preview.redd.it/xToTwjGVkk1OURQazLbxf-vIy26S_DxD2xIVOMXCe2g.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=a57c76b5290701b359c0a4c517abf0d82d421a96" alt="TTP on Arm/Qualcomm drama!" title="TTP on Arm/Qualcomm drama!" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/indolering"> /u/indolering </a> <br/> <span><a href="https://youtu.be/j6kX7JWMiV0?si=mlHcZrCAyQSfr-03">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gayyoh/ttp_on_armqualcomm_drama/">[comments]</a></span> </td></tr></table>

## TTP's on the ARM/Qualcomm drama!
 - [https://www.reddit.com/r/RISCV/comments/1gayx6t/ttps_on_the_armqualcomm_drama](https://www.reddit.com/r/RISCV/comments/1gayx6t/ttps_on_the_armqualcomm_drama)
 - RSS feed: $source
 - date published: 2024-10-24T09:57:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1gayx6t/ttps_on_the_armqualcomm_drama/"> <img src="https://external-preview.redd.it/xToTwjGVkk1OURQazLbxf-vIy26S_DxD2xIVOMXCe2g.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=a57c76b5290701b359c0a4c517abf0d82d421a96" alt="TTP's on the ARM/Qualcomm drama!" title="TTP's on the ARM/Qualcomm drama!" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/indolering"> /u/indolering </a> <br/> <span><a href="https://youtu.be/j6kX7JWMiV0?si=iCIJ2FbzS32eOset">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gayx6t/ttps_on_the_armqualcomm_drama/">[comments]</a></span> </td></tr></table>

## Recursive hanoi towers in risc-V.
 - [https://www.reddit.com/r/RISCV/comments/1gapt7l/recursive_hanoi_towers_in_riscv](https://www.reddit.com/r/RISCV/comments/1gapt7l/recursive_hanoi_towers_in_riscv)
 - RSS feed: $source
 - date published: 2024-10-24T00:26:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to write a program that runs a recursive Towers of Hanoi algorithm. The objective of the program is to move <em>n</em> number of discs, starting from the first column in ascending order (Value(+0) column). The movement of the discs will be replicated between the Value(+0) column, the Value(+4) column, and finally, they will end in the Value(+8) column.</p> <p>The C code that I used to base my program of is this one: </p> <p>#include &lt;stdio.h&gt;</p> <p>// C recursive function to solve tower of hanoi puzzle</p> <p>void towerOfHanoi(int n, char from_rod, char to_rod, char aux_rod)</p> <p>{</p> <pre><code>if (n == 1) { printf(&quot;\\n Move disk 1 from rod %c to rod %c&quot;, from\_rod, to\_rod); return; } towerOfHanoi(n-1, from\_rod, aux\_rod, to\_rod); printf(&quot;\\n Move disk %d from rod %c to rod %c&quot;, n, from\_rod, to\_rod); towerOfHanoi(n-1, aux\_rod, to\_rod, from\_rod); </code></pre> <p>}</p> <p>int main()</p> <p>{</p> <p

