# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Meet Akeana at the RISC-V Summit; FPGA demo of high performance out-of-order core from the 5000-series
 - [https://www.reddit.com/r/RISCV/comments/1fwb3p1/meet_akeana_at_the_riscv_summit_fpga_demo_of_high](https://www.reddit.com/r/RISCV/comments/1fwb3p1/meet_akeana_at_the_riscv_summit_fpga_demo_of_high)
 - RSS feed: $source
 - date published: 2024-10-04T22:02:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1fwb3p1/meet_akeana_at_the_riscv_summit_fpga_demo_of_high/"> <img src="https://external-preview.redd.it/MCcbBErw900w7lO_Ns2C0jI9qk_-6-sPe3q96YjvK1g.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=84a699698638b83d3bf405d5f79f3d32d47cc55e" alt="Meet Akeana at the RISC-V Summit; FPGA demo of high performance out-of-order core from the 5000-series" title="Meet Akeana at the RISC-V Summit; FPGA demo of high performance out-of-order core from the 5000-series" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/camel-cdr-"> /u/camel-cdr- </a> <br/> <span><a href="https://www.akeana.com/meet-akeana-at-the-risc-v-summit-north-america/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fwb3p1/meet_akeana_at_the_riscv_summit_fpga_demo_of_high/">[comments]</a></span> </td></tr></table>

## VisionFive 2 router
 - [https://www.reddit.com/r/RISCV/comments/1fwa0sd/visionfive_2_router](https://www.reddit.com/r/RISCV/comments/1fwa0sd/visionfive_2_router)
 - RSS feed: $source
 - date published: 2024-10-04T21:14:37+00:00

<!-- SC_OFF --><div class="md"><p>I built a simple router on my VF2 using StarFive&#39;s Debian image and systemd-networkd as a configuration manager. I haven&#39;t put this thing through any real stress testing but it is handling my 400mbps home connection plenty fine. </p> <p>What&#39;s more I am currently compiling the latest kernel from Starfive&#39;s public repos, because I want to include the 8021q module for VLAN support. All four cores are at 100% load and network performance has not degraded at all. I know the JH7110 isn&#39;t the best SoC <em>on paper</em> but in this case it&#39;s soldiering on. </p> <p>So, yeah. This thing rocks and I&#39;m happy I found a real use for it. Thank you for reading.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/flmontpetit"> /u/flmontpetit </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fwa0sd/visionfive_2_router/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/

## Confusion about Implementing .aq, .rl, and .aqrl in RISC-V AMO Instructions
 - [https://www.reddit.com/r/RISCV/comments/1fw8g5l/confusion_about_implementing_aq_rl_and_aqrl_in](https://www.reddit.com/r/RISCV/comments/1fw8g5l/confusion_about_implementing_aq_rl_and_aqrl_in)
 - RSS feed: $source
 - date published: 2024-10-04T20:05:27+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a RISC-V implementation and am a bit confused about how the <code>amoadd.w</code> instruction works when using <code>.aq</code>, <code>.rl</code>, and <code>.aqrl</code> bits. From what I understand, <code>amoadd.w</code> first reads the value from the memory address pointed to by <code>rs1</code>, loads that into <code>rd</code>, adds <code>rs2</code> to it, and then writes the result back to the same memory address.</p> <p>Could someone clarify the differences between:</p> <ul> <li><code>amoadd.w.aq</code> (acquire bit set)</li> <li><code>amoadd.w.rl</code> (release bit set)</li> <li><code>amoadd.w.aqrl</code> (both acquire and release bits set)</li> </ul> <p>I understand these bits affect memory ordering, but I&#39;m not sure how to properly implement them in hardware. How does each variant ensure proper synchronization and memory access in a multicore environment?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https:

## Bianbu OS 2.0 rc2 on Banana Pi BPI-F3
 - [https://www.reddit.com/r/RISCV/comments/1fvywnx/bianbu_os_20_rc2_on_banana_pi_bpif3](https://www.reddit.com/r/RISCV/comments/1fvywnx/bianbu_os_20_rc2_on_banana_pi_bpif3)
 - RSS feed: $source
 - date published: 2024-10-04T13:17:03+00:00

<!-- SC_OFF --><div class="md"><p>I flashed Bianbu OS 2.0 rc2 to a SD card, and put it into my Banana Pi BPI-F3.</p> <ul> <li>smooth initial boot process</li> <li>smooth desktop GUI</li> <li>Linux 6.6.36 #2.0~rc7.2. Whereas Bianbu OS 1.0.12 uses linux 6.1.15</li> <li>default shell is zsh ... first time I&#39;m using that.</li> <li>AFAIK not faster. Performance parameters not improved</li> <li>My guess: based on Ubuntu 24.04. But corrections welcome.</li> <li>when I do &quot;sudo apt update&quot; ... no updates. That&#39;s a bit strange</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/superkoning"> /u/superkoning </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fvywnx/bianbu_os_20_rc2_on_banana_pi_bpif3/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fvywnx/bianbu_os_20_rc2_on_banana_pi_bpif3/">[comments]</a></span>

## Samsung Highlights Work to Bring RISC-V to Tizen
 - [https://www.reddit.com/r/RISCV/comments/1fvwu2d/samsung_highlights_work_to_bring_riscv_to_tizen](https://www.reddit.com/r/RISCV/comments/1fvwu2d/samsung_highlights_work_to_bring_riscv_to_tizen)
 - RSS feed: $source
 - date published: 2024-10-04T11:26:34+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1fvwu2d/samsung_highlights_work_to_bring_riscv_to_tizen/"> <img src="https://external-preview.redd.it/Mj4eBdd1ZFjfmyeiUYw0zYZI95SXpO5ttpsSmmyWpsc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b20b4fc3118218b4abb40033b4a121d55cd2ba50" alt="Samsung Highlights Work to Bring RISC-V to Tizen" title="Samsung Highlights Work to Bring RISC-V to Tizen" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://www.design-reuse.com/industryexpertblogs/56867/samsung-risc-v-tizen.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fvwu2d/samsung_highlights_work_to_bring_riscv_to_tizen/">[comments]</a></span> </td></tr></table>

## What if I tried to lw from a misaligned address.
 - [https://www.reddit.com/r/RISCV/comments/1fvw8cm/what_if_i_tried_to_lw_from_a_misaligned_address](https://www.reddit.com/r/RISCV/comments/1fvw8cm/what_if_i_tried_to_lw_from_a_misaligned_address)
 - RSS feed: $source
 - date published: 2024-10-04T10:49:16+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/khushiforyou"> /u/khushiforyou </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fvw8cm/what_if_i_tried_to_lw_from_a_misaligned_address/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fvw8cm/what_if_i_tried_to_lw_from_a_misaligned_address/">[comments]</a></span>

## Seeking HiFive Unleashed Board for RISC-V Project
 - [https://www.reddit.com/r/RISCV/comments/1fvufca/seeking_hifive_unleashed_board_for_riscv_project](https://www.reddit.com/r/RISCV/comments/1fvufca/seeking_hifive_unleashed_board_for_riscv_project)
 - RSS feed: $source
 - date published: 2024-10-04T08:36:58+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I&#39;m working on a server software project and NEED a HiFive Unleashed board. It fits all my requirements, but it&#39;s DISCONTINUED. If anyone is willing to LEND or SELL theirs, I’d greatly appreciate it to help PROMOTE RISC-V development! Thank you! ❤️</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/riscvprojector"> /u/riscvprojector </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fvufca/seeking_hifive_unleashed_board_for_riscv_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fvufca/seeking_hifive_unleashed_board_for_riscv_project/">[comments]</a></span>

## SG2042 Newsletter (2024-10-04 #062)
 - [https://www.reddit.com/r/RISCV/comments/1fvtly2/sg2042_newsletter_20241004_062](https://www.reddit.com/r/RISCV/comments/1fvtly2/sg2042_newsletter_20241004_062)
 - RSS feed: $source
 - date published: 2024-10-04T07:32:45+00:00

<!-- SC_OFF --><div class="md"><h2>Editor&#39;s Note</h2> <p>Welcome to the sixty-second issue of the SG2042 Newsletter. After a month of intense competition, 15 days of thorough result validation and expert reviews, and a 7-day public announcement period, the winner of the extended round of the 2nd RISC-V Software Porting and Optimization Championship has been announced. For more details, please refer to our <a href="#Events-and-Games">Events and Games</a> section.</p> <h2>Highlights</h2> <ul> <li><p>On September 27, the 2024 China Computing Power Conference opened in Zhengzhou, Henan Province. At the main forum, SOPHGO made a significant impact by unveiling its cloud-based intelligent computing card, the SC11 FP300, which captured widespread attention.</p> <p><a href="https://mp.weixin.qq.com/s/nuw3uzYDPMGmCH-_lGze5Q">Related news</a></p></li> </ul> <h2>Upstream</h2> <p>Most of the code is already open-source and can be obtained from repositories such as github.com/SOPHGO. The follo

## 新しい RISC-V マイコンボード Suzuno32RV 発売です♪
 - [https://www.reddit.com/r/RISCV/comments/1fvp8px/新しい_riscv_マイコンボード_suzuno32rv_発売です](https://www.reddit.com/r/RISCV/comments/1fvp8px/新しい_riscv_マイコンボード_suzuno32rv_発売です)
 - RSS feed: $source
 - date published: 2024-10-04T02:46:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1fvp8px/新しい_riscv_マイコンボード_suzuno32rv_発売です/"> <img src="https://external-preview.redd.it/x_dPsgV9MMus66U5JL1t2I2Y1vtBcAMxvWtXS7Zcaok.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=2455881d2ff0de264a028e97b4f7a989c5e518c9" alt="新しい RISC-V マイコンボード Suzuno32RV 発売です♪" title="新しい RISC-V マイコンボード Suzuno32RV 発売です♪" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/3G6A5W338E"> /u/3G6A5W338E </a> <br/> <span><a href="http://x.com/AkiraTsukamoto/status/1840347526912000089">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fvp8px/新しい_riscv_マイコンボード_suzuno32rv_発売です/">[comments]</a></span> </td></tr></table>

