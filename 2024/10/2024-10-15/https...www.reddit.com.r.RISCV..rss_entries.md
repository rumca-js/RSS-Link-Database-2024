# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Misc / RFC: Working on a "cheap" FPU SIMD design
 - [https://www.reddit.com/r/RISCV/comments/1g4l4tp/misc_rfc_working_on_a_cheap_fpu_simd_design](https://www.reddit.com/r/RISCV/comments/1g4l4tp/misc_rfc_working_on_a_cheap_fpu_simd_design)
 - RSS feed: $source
 - date published: 2024-10-15T23:08:18+00:00

<!-- SC_OFF --><div class="md"><p>So, I was faced with another issue: * I am wanting to be able to support FPU SIMD in my implementation of RV64; * The V extension looks rather expensive to implement (mostly targeting FPGA); * My core already had basic FPU SIMD, for my own ISA, but it was different from V. * If anything, what I had already had more in common with the P extension.</p> <p>The cost concern in my case for V mostly relates to the larger register file and increased architectural state (more so than the cost of the operations themselves). Granted, V is an arguably more powerful extension.</p> <p>Ironically, the way I had originally implemented the Binary32 scalar ops in my implementation if the F extension was to use the SIMD operations from my own ISA, but just pass them off as scalar operations (my own ISA actually lacked support for Binary32 scalar operations, having used exclusively Binary64 for scalar operations, and only provided Binary32 ops in SIMD form).</p> <p>The 

## TockOS
 - [https://www.reddit.com/r/RISCV/comments/1g41wsg/tockos](https://www.reddit.com/r/RISCV/comments/1g41wsg/tockos)
 - RSS feed: $source
 - date published: 2024-10-15T07:04:28+00:00

<!-- SC_OFF --><div class="md"><p>I just noticed that TockOS supports RISC-V (It is a secure embedded operating system designed for running multiple concurrent, mutually distrustful applications on low-memory and low-power microcontrollers). It only supports two boards (so far) - esp32-c3-devkitM-1 and SiFive HiFive1. But for a Rust based operating system I think that it is an interesting project.</p> <p><a href="https://tockos.org/">https://tockos.org/</a></p> <p><a href="https://github.com/tock/tock/">https://github.com/tock/tock/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/m_z_s"> /u/m_z_s </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1g41wsg/tockos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g41wsg/tockos/">[comments]</a></span>

