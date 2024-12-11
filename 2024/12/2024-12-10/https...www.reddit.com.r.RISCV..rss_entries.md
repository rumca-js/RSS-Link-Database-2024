# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Compiler is tripping (most likely I am)
 - [https://www.reddit.com/r/RISCV/comments/1hb7xhb/compiler_is_tripping_most_likely_i_am](https://www.reddit.com/r/RISCV/comments/1hb7xhb/compiler_is_tripping_most_likely_i_am)
 - RSS feed: $source
 - date published: 2024-12-10T18:03:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone.</p> <p>I am writing some assembly for a custom core and figure using a compiler was a good idea to automate the HEX conversion process.</p> <p>Here is my original program :</p> <pre><code>_start: # Initialization lui x6, 0x2 # Load GPIO base address # 00002337 addi x19, x0, 0x0 # Set offset to 0 # 00000993 addi x18, x0, 0x1 # Set data to be written to 1 # 00100913 addi x20, x0, 0x80 # Set offest limit to 128 (ie cache size) # 07f00a13 # Main loop sw x18, 0(x6) # Store data in offested memory # 01232023 addi x6, x6, 0x4 # Increment memory address # 00430313 addi x19, x19, 0x1 # Keep track of offset : offset++ # 00198993 bne x19, x20, -0xC # if offset != 128, restart loop # FF499AE3 lw x18, 0(x0) # Done ! create a cache miss to write back. # 00002903 # Exit strategy : Infinite loop addi x0, x0, 0x0 # NOP # 00000013 beq x0, x0, -0x4 # Repeat # FE000EE3 </code></pre> <p>The thing is, when converted to Hex (objdumb), I get a program that..

## Pipelining RISCV
 - [https://www.reddit.com/r/RISCV/comments/1haw23y/pipelining_riscv](https://www.reddit.com/r/RISCV/comments/1haw23y/pipelining_riscv)
 - RSS feed: $source
 - date published: 2024-12-10T06:58:35+00:00

<!-- SC_OFF --><div class="md"><p>I converted a riscv single cycle cpu into a pipelined cpu and the rv32 instruction set is being checked with the PCW but the input to the controller according to image in books is from instrD which is pipelined instrF through PCF.</p> <p>So there&#39;s a 3 cycle delay in the input and the checked output.How can this be solved in order to synchronise the input and output.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/boredDODO"> /u/boredDODO </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1haw23y/pipelining_riscv/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1haw23y/pipelining_riscv/">[comments]</a></span>

## Bare-Metal Embedded Programming on K230 Using Rust
 - [https://www.reddit.com/r/RISCV/comments/1hatm48/baremetal_embedded_programming_on_k230_using_rust](https://www.reddit.com/r/RISCV/comments/1hatm48/baremetal_embedded_programming_on_k230_using_rust)
 - RSS feed: $source
 - date published: 2024-12-10T04:27:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1hatm48/baremetal_embedded_programming_on_k230_using_rust/"> <img src="https://external-preview.redd.it/gd0K6xw12D6DGUVmekb37FF_h3-An86lA9Y8IQUlhYE.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=db4ec4ebb2a42a6fa201fe213fc6f90ea30b204a" alt="Bare-Metal Embedded Programming on K230 Using Rust" title="Bare-Metal Embedded Programming on K230 Using Rust" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/andelf"> /u/andelf </a> <br/> <span><a href="https://dev.to/andelf/bare-metal-embedded-programming-on-k230-using-rust-4h4g">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1hatm48/baremetal_embedded_programming_on_k230_using_rust/">[comments]</a></span> </td></tr></table>

