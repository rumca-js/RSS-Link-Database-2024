# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## My Lichee PI 3A 8GB just arrived, first impressions as a SBC enthusiast
 - [https://www.reddit.com/r/RISCV/comments/1fq9i9i/my_lichee_pi_3a_8gb_just_arrived_first](https://www.reddit.com/r/RISCV/comments/1fq9i9i/my_lichee_pi_3a_8gb_just_arrived_first)
 - RSS feed: $source
 - date published: 2024-09-26T22:59:41+00:00

<!-- SC_OFF --><div class="md"><p>First i have to say that i like, very much, that the included fan has speed control and even fan stop with just two wires instead of being yet another fixed 5V fan that is ridiculously noisy even at 3.3v. </p> <p>I also like the included case, but its too bad it would not close with the fan installed, it is just a few mm too tall, it can be still be closed but you put too much presion to the module.</p> <p>It comes with Bianbu OS 0.6 pre-installed on the emmc, the bad thing about this is that it is an old version after running the upgrade feature it failed and never booted again. No problem i just followed the guide on the sipeed wiki to download the burner and a new image and flash it to the emmc very easily. This actually suprised me how easy this was. Or maybe i was just used to have a tons of problems at every step.</p> <p>Now about performance, im not sure of how i could messure performance here in a objective way, i think this is faster than any

## RISC-V Bianbu Cloud Open For Trial
 - [https://www.reddit.com/r/RISCV/comments/1fq52sj/riscv_bianbu_cloud_open_for_trial](https://www.reddit.com/r/RISCV/comments/1fq52sj/riscv_bianbu_cloud_open_for_trial)
 - RSS feed: $source
 - date published: 2024-09-26T19:45:19+00:00

<!-- SC_OFF --><div class="md"><p>Saw this on the Banana Pi forum: <a href="https://forum.banana-pi.org/t/the-risc-v-cloud-platform-bianbu-cloud-is-open-for-trial/19087">https://forum.banana-pi.org/t/the-risc-v-cloud-platform-bianbu-cloud-is-open-for-trial/19087</a></p> <p>The interface is in Chinese, so I didn&#39;t check any details. <a href="https://cloud.spacemit.com/">https://cloud.spacemit.com/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LivingLinux"> /u/LivingLinux </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fq52sj/riscv_bianbu_cloud_open_for_trial/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fq52sj/riscv_bianbu_cloud_open_for_trial/">[comments]</a></span>

## Bendable non-silicon RISC-V CPU demoed running while wrapped around a pencil
 - [https://www.reddit.com/r/RISCV/comments/1fq4yes/bendable_nonsilicon_riscv_cpu_demoed_running](https://www.reddit.com/r/RISCV/comments/1fq4yes/bendable_nonsilicon_riscv_cpu_demoed_running)
 - RSS feed: $source
 - date published: 2024-09-26T19:40:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1fq4yes/bendable_nonsilicon_riscv_cpu_demoed_running/"> <img src="https://external-preview.redd.it/gTv67qBDXjsYgbSA5rl-BG1HTGgOh8UEUkVXSbZ2D9c.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=bd6dfb4a1c90a4b06bd523bd3d57430c446672d9" alt="Bendable non-silicon RISC-V CPU demoed running while wrapped around a pencil" title="Bendable non-silicon RISC-V CPU demoed running while wrapped around a pencil" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jacko10101010101"> /u/Jacko10101010101 </a> <br/> <span><a href="https://www.tomshardware.com/pc-components/cpus/bendable-non-silicon-risc-v-cpu-demonstrated-while-being-wrapped-around-a-pencil">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fq4yes/bendable_nonsilicon_riscv_cpu_demoed_running/">[comments]</a></span> </td></tr></table>

## Trying to infer info about the SG2380 status
 - [https://www.reddit.com/r/RISCV/comments/1fq1prq/trying_to_infer_info_about_the_sg2380_status](https://www.reddit.com/r/RISCV/comments/1fq1prq/trying_to_infer_info_about_the_sg2380_status)
 - RSS feed: $source
 - date published: 2024-09-26T17:24:06+00:00

<!-- SC_OFF --><div class="md"><p>We haven&#39;t really gotten any communication from Sophgo about the SG2380, and until quite recently it seems like Milk-V hadn&#39;t either (I&#39;m not sure if they&#39;re still not getting any communication from Sophgo).</p> <p>I&#39;m wondering if we can infer anything about the SG2380 status from some of Sophgo&#39;s public repositories, like whether they&#39;ve got some real hardware in their hands. For example there is a <a href="https://github.com/sophgo/zsbl/commits/sg2380-pld/">sg2380-pld branch in the sophgo/zsbl repository</a>. Looking at some of the recent commits, I get the feeling they&#39;re developing on an FPGA rather than real hardware maybe?</p> <p>On the other hand, in the <a href="https://github.com/sophgo/tpu-mlir/commits/master">sophgo/tpu-mlir master branch</a> the number of SG2380 related commits has increased significantly in September.</p> <p>Thoughts? Pointless speculation maybe?</p> </div><!-- SC_ON --> &#32; submitted by

## Atomic test for MultiCore
 - [https://www.reddit.com/r/RISCV/comments/1fq12ka/atomic_test_for_multicore](https://www.reddit.com/r/RISCV/comments/1fq12ka/atomic_test_for_multicore)
 - RSS feed: $source
 - date published: 2024-09-26T16:57:30+00:00

<!-- SC_OFF --><div class="md"><p>HI, I’m trying to perform a basic atomic test on two cores using Spike. In this program, core 0 does a load-reserved (<code>lr.w</code>) on an address (<code>0x80000000</code>), then core 1 does a store-conditional (<code>sc.w</code>) to the same address. Here&#39;s the code I wrote:</p> <pre><code>.section .data .align 4 atomic_var: .word 0 .section .text .globl _start _start: lui t2, 0x80000 lr.w t3, (t2) j core_done core1_work: lui t2, 0x80000 li t4, 1 sc.w t5, t4, (t2) core_done: li a7, 10 ecall </code></pre> <p>I run this with<br/> <code>riscv64-unknown-elf-gcc -march=rv32g -mabi=ilp32f -static -mcmodel=medany -fvisibility=hidden -nostdlib -nostartfiles -DENTROPY=0xdeadbeef -DLFSR_BITS=9 -fno-tree-loop-distribute-patterns -T link.ld test.S -o test</code></p> <p><code>spike --isa=rv32g -p2 -d --log-commits test &amp;&gt; test.log</code></p> <p>to simulate two cores, but in log file core is not jumping from core0 to core1</p> </div><!-- SC_ON --> &

## RISC-V Wires Up More Kernel Features With Linux 6.12
 - [https://www.reddit.com/r/RISCV/comments/1fpvnlx/riscv_wires_up_more_kernel_features_with_linux_612](https://www.reddit.com/r/RISCV/comments/1fpvnlx/riscv_wires_up_more_kernel_features_with_linux_612)
 - RSS feed: $source
 - date published: 2024-09-26T13:02:48+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1fpvnlx/riscv_wires_up_more_kernel_features_with_linux_612/"> <img src="https://external-preview.redd.it/PCG8Fyt5XdJo2iR0ho0S8XLdoEljSCOXKLJ0EmzkIQ8.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=7e6e6501d7a2bb71adc220509881905f066670eb" alt="RISC-V Wires Up More Kernel Features With Linux 6.12" title="RISC-V Wires Up More Kernel Features With Linux 6.12" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/archanox"> /u/archanox </a> <br/> <span><a href="https://www.phoronix.com/news/Linux-6.12-RISC-V">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fpvnlx/riscv_wires_up_more_kernel_features_with_linux_612/">[comments]</a></span> </td></tr></table>

## RISC-V board recommendations
 - [https://www.reddit.com/r/RISCV/comments/1fpmf2k/riscv_board_recommendations](https://www.reddit.com/r/RISCV/comments/1fpmf2k/riscv_board_recommendations)
 - RSS feed: $source
 - date published: 2024-09-26T02:54:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I want to get into RISC-V and am wondering which board to get. The only special requirement I have is for it to have 2 PCIe nvme slots on it or 1 PCIe nvme slot and a PCIe x4 slot, as I would like to use a nvme SSD and a dedicated GPU for playing around with graphics on it.</p> <p>Any recommendations would be appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrafterJunkie1"> /u/CrafterJunkie1 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fpmf2k/riscv_board_recommendations/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fpmf2k/riscv_board_recommendations/">[comments]</a></span>

## Building SOC using RISC-V
 - [https://www.reddit.com/r/RISCV/comments/1fpkr0h/building_soc_using_riscv](https://www.reddit.com/r/RISCV/comments/1fpkr0h/building_soc_using_riscv)
 - RSS feed: $source
 - date published: 2024-09-26T01:25:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1fpkr0h/building_soc_using_riscv/"> <img src="https://preview.redd.it/fr8bgmo432rd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=0089da6804bbc3eedccdd73e0aa7f0db8cb273af" alt="Building SOC using RISC-V" title="Building SOC using RISC-V" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello everyone ❤️ I was working on implementing SOC using riscv core i used this RTL Code provided by bruno as that in github link</p> <p><a href="https://github.com/BrunoLevy/learn-fpga/blob/master/FemtoRV/RTL/PROCESSOR/femtorv32_quark.v">https://github.com/BrunoLevy/learn-fpga/blob/master/FemtoRV/RTL/PROCESSOR/femtorv32_quark.v</a></p> <p>I tried to use icarus verilog to run it but always i get those error which was mainly due to declaration after use as provided in the screenshot so does it make sense to keep changing in the RTL code or there another way could be more helpful </p> <p>Thank you all❤️</p> </div><!-- SC_ON --> &#32

