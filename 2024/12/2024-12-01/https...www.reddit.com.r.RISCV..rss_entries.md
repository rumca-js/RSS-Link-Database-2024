# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Help with Branch and Jump Implementation in RISC-V Processor (Chisel/Scala)
 - [https://www.reddit.com/r/RISCV/comments/1h4cpzi/help_with_branch_and_jump_implementation_in_riscv](https://www.reddit.com/r/RISCV/comments/1h4cpzi/help_with_branch_and_jump_implementation_in_riscv)
 - RSS feed: $source
 - date published: 2024-12-01T20:31:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I&#39;m currently working on building a simple 5-stage RISC-V processor and have successfully implemented some basic vector instructions (vadd, vload, vstore). However, I messed up the code and ran into some problems when I started adding branch and jump instructions.</p> <p>I am pretty new to Chisel and Scala. I&#39;ve spent hours debugging without much progress and am now stuck.</p> <p>Here&#39;s the main issue: when data is in the EXE stage, in the very next clock cycle, it shows up in the WB stage and skips the MEM stage. I think I still haven&#39;t figured out how clock cycles and register updates work.</p> <p>Any input is greatly appreciated!</p> <p>Thanks in advance!</p> <pre><code>package simd import chisel3._ import chisel3.util._ class Processor extends Module { val io = IO(new Bundle { val instruction = Output(UInt(32.W)) val pc = Output(SInt(32.W)) val debug = new DebugModule() }) object InstructionType { val ADDI =

## Does RISC-V toolchain provided clang not work with newlib nano?
 - [https://www.reddit.com/r/RISCV/comments/1h4061l/does_riscv_toolchain_provided_clang_not_work_with](https://www.reddit.com/r/RISCV/comments/1h4061l/does_riscv_toolchain_provided_clang_not_work_with)
 - RSS feed: $source
 - date published: 2024-12-01T10:04:30+00:00

<!-- SC_OFF --><div class="md"><p>I built the toolchain for the rv32i_zicsr_zifencei architecture and ilp32 abi and llvm enabled. When I tried to compile using<br/> -specs=nano.specs and -specs=nosys.specs the compiler ignored these flags and created a huge executable that could not fit into my memory.</p> <p><code>./configure --prefix=/opt/riscv --with-arch= rv32i_zicsr_zifencei --with-abi=ilp32 --enable-llvm</code></p> <p>Is newlib-nano supported by clang? Did I do something wrong with the configuration ?</p> <p>I use the following configuration for building my elf file</p> <pre><code>CC = riscv32-unknown-elf-clang CFLAGS = \ -march=rv32i_zicsr_zifencei \ -mabi=ilp32 \ -O0 \ -I ./src LDFLAGS = \ -march=rv32i_zicsr_zifencei \ -mabi=ilp32 \ -specs=nano.specs \ -specs=nosys.specs \ -fno-common \ -fverbose-asm \ -nostartfiles \ -mstrict-align \ -mcmodel=medany \ -fno-builtin \ -fsigned-char \ -fdata-sections \ -ffunction-sections \ -Wno-unused \ -T ./link.ld \ -Wl,--gc-sections riscv32

## Questions about standard/official syntax
 - [https://www.reddit.com/r/RISCV/comments/1h4051x/questions_about_standardofficial_syntax](https://www.reddit.com/r/RISCV/comments/1h4051x/questions_about_standardofficial_syntax)
 - RSS feed: $source
 - date published: 2024-12-01T10:02:30+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I am currently writing a toy assembler for RISCV ISA and I had some queries about the validity of these lines<br/> 1. lb x10, valid_label_name(x9)</p> <ol> <li><p>lb x10, data_label is valid - so is lb x10, immediate also valid</p></li> <li><p>addi x10, x0, valid_label_name</p></li> <li><p>lui x10, valid_label_name</p></li> </ol> <p>TLDR: can we interchange label reference and immediate</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Protection_Same"> /u/Protection_Same </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1h4051x/questions_about_standardofficial_syntax/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1h4051x/questions_about_standardofficial_syntax/">[comments]</a></span>

## opensource board
 - [https://www.reddit.com/r/RISCV/comments/1h3w4tq/opensource_board](https://www.reddit.com/r/RISCV/comments/1h3w4tq/opensource_board)
 - RSS feed: $source
 - date published: 2024-12-01T05:25:01+00:00

<!-- SC_OFF --><div class="md"><p>I would like to try a risc-v board for desktop use without too much performance demands.</p> <p>However, what I&#39;m curious about risc-v is that completely opensource/openhardware implementations are possible.</p> <p>What boards I wonder have this feature without contains closed blobs within the firmware and elsewhere?</p> <p>For example the visionfive 2 ? <a href="https://www.amazon.it/VisionFive2-Quad-core-StarFive-JH7110-OpenCL3-0/dp/B0C7Q189T2">https://www.amazon.it/VisionFive2-Quad-core-StarFive-JH7110-OpenCL3-0/dp/B0C7Q189T2</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gromebar"> /u/gromebar </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1h3w4tq/opensource_board/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1h3w4tq/opensource_board/">[comments]</a></span>

## I think I've found... shall we say "quirk", in how LR/SC atomics work and are handled on e.g. microcontrollers.
 - [https://www.reddit.com/r/RISCV/comments/1h3qxew/i_think_ive_found_shall_we_say_quirk_in_how_lrsc](https://www.reddit.com/r/RISCV/comments/1h3qxew/i_think_ive_found_shall_we_say_quirk_in_how_lrsc)
 - RSS feed: $source
 - date published: 2024-12-01T00:42:07+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve written up my findings <a href="https://gist.github.com/ExplodingWaffle/633ea2a9479cd70ab67732a9fa64cbec">here</a> (sorry for making you click a link but reddit&#39;s formatting is too annoying to bother with).</p> <p>TL;DR is that the interaction of load reservations and single-core preemption (caused by traps, but includes trap/interrupt handlers as well as preemptively scheduled OS threads on a single core) is rather subtle, and while this is sort of pointed out in both ISA specs it isn&#39;t exactly given much weight considering how subtle it is. If not properly handled (clearing the reservation with a dummy SC) this can lead to SCs succeeding when, while thinking about your software threads/preemption in the same way as other harts, they should not.</p> <p>In my experience, no one told me to put a dummy SC in my interrupt handlers! Atomics are a good way of communicating between a main thread and interrupt handler (see <a href="https://

