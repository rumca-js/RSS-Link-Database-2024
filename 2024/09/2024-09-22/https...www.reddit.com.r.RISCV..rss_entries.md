# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## A functional computer architeture
 - [https://www.reddit.com/r/RISCV/comments/1fn1pc7/a_functional_computer_architeture](https://www.reddit.com/r/RISCV/comments/1fn1pc7/a_functional_computer_architeture)
 - RSS feed: $source
 - date published: 2024-09-22T19:41:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve started learning a bit about RISC since a professor of mine asked the whole class to read about the 2017 turing award. Reading through some material, i found out that some architectures were built for object oriented programming. And this got me thinking that most computer architectures were meant for object oriented programming.</p> <p>Is there any project for a functional computer architecture? Or even is there room for this in RISC-V project?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_Jarrisonn"> /u/_Jarrisonn </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fn1pc7/a_functional_computer_architeture/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fn1pc7/a_functional_computer_architeture/">[comments]</a></span>

## 2 semesters long final project
 - [https://www.reddit.com/r/RISCV/comments/1fmn1km/2_semesters_long_final_project](https://www.reddit.com/r/RISCV/comments/1fmn1km/2_semesters_long_final_project)
 - RSS feed: $source
 - date published: 2024-09-22T06:42:17+00:00

<!-- SC_OFF --><div class="md"><p>I am currently in the process of writing my proposal this semester, and I was thinking of doing a portfolio—three small related projects into one—that involves designing a 64-bit RISC V processor.</p> <p>The closest project I’ve done is designing an ALU with 8 operations and an FSM on a circuit simulator such as Falstad, and programming it in SystemVerilog. Our lab FPGAs were broken, so unfortunately, I don’t know much about implementing it on one. I also have never taken any computer architecture class. I’ll hopefully be taking one next semester, but I just realized that we might not have one anymore. Although, I am taking a digital system and computer design class.</p> <p>Is this a feasible project within one year if I plan to implement the RV64I ISA, add additional extensions, and get it running on an FPGA? I was thinking of chopping it into three parts for my portfolio.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.

## Vector Indexed Loads with varying VLEN
 - [https://www.reddit.com/r/RISCV/comments/1fmn0o1/vector_indexed_loads_with_varying_vlen](https://www.reddit.com/r/RISCV/comments/1fmn0o1/vector_indexed_loads_with_varying_vlen)
 - RSS feed: $source
 - date published: 2024-09-22T06:40:27+00:00

<!-- SC_OFF --><div class="md"><p>I have one question regarding the behavior of indexed store/load instructions like vluxei32.v depending on the VLEN. I have two boards here: - SpacemiT K1 (VLEN=256) - C908 (VLEN=128)</p> <p>I run this instruction sequence on both boards: <code>asm li t0, 16 vsetvli x0, t0, e8, m1 vluxei32.v v0, 0(ra), v4 </code></p> <p>I observe that the results in v0 differ between these boards. The K1 uses the upper 16 bytes of register v4 as the second half of the 16 (2 byte) offsets while the C908 uses v4 and v5. Therefore the results differ on the boards. I observe the same behavior with QEMU v9 (VLEN=256, VLEN=128 respectively).</p> <p>My initial feeling was that this is illegal behavior since I expected these CPUs to produce the same results with the same inputs, but I found this in the specification: &quot;Vector indexed operations add the contents of each element of the vector offset operand specified by vs2 to the base effective address to give the effectiv

