# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Imagination Technologies GPU driver progress
 - [https://www.reddit.com/r/RISCV/comments/1gmtpof/imagination_technologies_gpu_driver_progress](https://www.reddit.com/r/RISCV/comments/1gmtpof/imagination_technologies_gpu_driver_progress)
 - RSS feed: $source
 - date published: 2024-11-08T21:32:40+00:00

<!-- SC_OFF --><div class="md"><p>It looks like the GPU drivers are getting closer.</p> <p>They rewrote the driver from AXE-1-16M specific, to more generic. They send out a patch for the BXS-4-64, and adding support for BXE-2-32 and BXM-4-64 should be &quot;fairly trivial&quot;.</p> <p><a href="https://gitlab.freedesktop.org/imagination/linux-firmware/-/issues/2#note_2643442">https://gitlab.freedesktop.org/imagination/linux-firmware/-/issues/2#note_2643442</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LivingLinux"> /u/LivingLinux </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gmtpof/imagination_technologies_gpu_driver_progress/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gmtpof/imagination_technologies_gpu_driver_progress/">[comments]</a></span>

## RISC-V Vector Extension for Integer Workloads: An Informal Gap Analysis
 - [https://www.reddit.com/r/RISCV/comments/1gmsqwc/riscv_vector_extension_for_integer_workloads_an](https://www.reddit.com/r/RISCV/comments/1gmsqwc/riscv_vector_extension_for_integer_workloads_an)
 - RSS feed: $source
 - date published: 2024-11-08T20:50:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1gmsqwc/riscv_vector_extension_for_integer_workloads_an/"> <img src="https://external-preview.redd.it/DaucjXMGsNHM-CtmdilC9-Be6MC8V2z4ykjVCgOkTFc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=62ca4cb88917f17e7200a6f1c665b5d959713745" alt="RISC-V Vector Extension for Integer Workloads: An Informal Gap Analysis" title="RISC-V Vector Extension for Integer Workloads: An Informal Gap Analysis" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/camel-cdr-"> /u/camel-cdr- </a> <br/> <span><a href="https://gist.github.com/camel-cdr/99a41367d6529f390d25e36ca3e4b626">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gmsqwc/riscv_vector_extension_for_integer_workloads_an/">[comments]</a></span> </td></tr></table>

## Looking for Guidance on Accessing Exception CSRs in RISC-V Using QEMU
 - [https://www.reddit.com/r/RISCV/comments/1gmgd59/looking_for_guidance_on_accessing_exception_csrs](https://www.reddit.com/r/RISCV/comments/1gmgd59/looking_for_guidance_on_accessing_exception_csrs)
 - RSS feed: $source
 - date published: 2024-11-08T11:27:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I’m a firmware engineer trainee, and I’m currently diving into RISC-V programming, specifically focusing on accessing the exception control and status registers (CSRs) in RISC-V. I have a basic understanding of RISC-V assembly programming, but I’m new to handling exceptions and interacting with CSRs in a real environment.</p> <p>I’m working on a project where I need to write code to access the exception CSRs in a RISC-V system using QEMU, but I’m not sure where to start or how to approach this.</p> <p>Could anyone share resources, tutorials, or tips on:</p> <ol> <li>Accessing exception CSRs in RISC-V (like <code>mepc</code>, <code>mcause</code>, etc.)</li> <li>How exceptions are triggered and handled in RISC-V</li> <li>Any useful steps to follow in setting this up in QEMU for bare-metal development</li> </ol> <p>I would really appreciate any guidance, especially in terms of where to start and any example code or documentation.</p> <p>T

## How to add MMIO devices to spike simulator?
 - [https://www.reddit.com/r/RISCV/comments/1gmcui5/how_to_add_mmio_devices_to_spike_simulator](https://www.reddit.com/r/RISCV/comments/1gmcui5/how_to_add_mmio_devices_to_spike_simulator)
 - RSS feed: $source
 - date published: 2024-11-08T07:07:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I&#39;m working on a project that requires me to add an MMIO device to spike. What I basically need is something like this:</p> <ul> <li><p>The device should have a buffer that is memory mapped. Basically, if I do a load or a store on that device with a particular address, there is going to be a bound-checked load or store happening in the memory as well. Bound checked because I don&#39;t want to go past the mapped region.</p></li> <li><p>The device should have a memory mapped register (mapped at 0x50000000) which when written to should lead to a change in some property of the device (Mainly the length of the memory mapped region in this case).</p></li> </ul> <p>I came across <a href="https://github.com/ucb-bar/spike-devices/blob/master/src/sifive_uart.h">this</a> but I&#39;m not really sure where this device is getting mapped to or how it interacts with everything else, especially memory.</p> <p>I also wrote a device of my own that was 

## Automotive RISC V board
 - [https://www.reddit.com/r/RISCV/comments/1gmcl7x/automotive_risc_v_board](https://www.reddit.com/r/RISCV/comments/1gmcl7x/automotive_risc_v_board)
 - RSS feed: $source
 - date published: 2024-11-08T06:48:29+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone... I wanted to build automotive solution on RISC V based board....So Can you Suggest RISC V based Board to do so? Please avoid Chinese based boards.... </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Polarroute"> /u/Polarroute </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gmcl7x/automotive_risc_v_board/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gmcl7x/automotive_risc_v_board/">[comments]</a></span>

## Question about RISC-V matrix extensions
 - [https://www.reddit.com/r/RISCV/comments/1gmc6re/question_about_riscv_matrix_extensions](https://www.reddit.com/r/RISCV/comments/1gmc6re/question_about_riscv_matrix_extensions)
 - RSS feed: $source
 - date published: 2024-11-08T06:21:16+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m just a spectator to RISC-V spec development, but I&#39;ve been reading the mailing list archives of the Integrated Matrix Extension (IME - matrices stored in vector registers) and the Attached Matrix Extension (AME - matrices stored in new matrix tile registers). I&#39;m trying to figure out where the extensions are headed, and there is one question that I haven&#39;t seen addressed: which of either (or both?) of these extensions is expected to become part of a future RVA profile? If I had to guess, then IME would have a better chance of becoming part of a RVA profile because there is less additional architectural state. However, if that happens, will that require future application processors that want to implement AME to also implement IME?</p> <p>I haven&#39;t seen that discussed yet, but I can imagine that would impose some constraints on one extension or the other to get them to compose efficiently.</p> </div><!-- SC_ON --> &#32; submitt

