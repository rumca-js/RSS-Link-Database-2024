# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## DC-ROMA RISC-V Laptop II
 - [https://www.reddit.com/r/RISCV/comments/1epn9ze/dcroma_riscv_laptop_ii](https://www.reddit.com/r/RISCV/comments/1epn9ze/dcroma_riscv_laptop_ii)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-11T15:19:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1epn9ze/dcroma_riscv_laptop_ii/"> <img alt="DC-ROMA RISC-V Laptop II" src="https://external-preview.redd.it/5WGYa9f0j3TnnHJb3kJH6MPR0GfZ-3TNLxDM2ZycUMw.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=f6e640efa50bee7695fc36916e2294725ca14dee" title="DC-ROMA RISC-V Laptop II" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/archanox"> /u/archanox </a> <br /> <span><a href="https://youtu.be/3mhd98AGNXQ?si=_O3g_mKIOEu_CQf8">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1epn9ze/dcroma_riscv_laptop_ii/">[comments]</a></span> </td></tr></table>

## Working on an OSHW control board with the CH32V00F3, anyone want to take a look at my PCB layout?
 - [https://www.reddit.com/r/RISCV/comments/1epa1mc/working_on_an_oshw_control_board_with_the](https://www.reddit.com/r/RISCV/comments/1epa1mc/working_on_an_oshw_control_board_with_the)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-11T02:33:31+00:00

<!-- SC_OFF --><div class="md"><p>So, the idea here is that you have a 35x70mm I2C addon board, with: </p> <p>* 7(plus one that's also reset) GPIO, protected by 220 ohm resistors and spark gaps, all on 0.1 headers(Not sure anything better fits...)</p> <p>* 3 protected 12v power switches for 1-2A loads, on 5.08mm phoenix connectors</p> <p>* A buck converter that will provide 5V to the main board.</p> <p>* Open load detect and short detect (A 1M resistor and 0.5v lets you roughly sense the voltage at the switch)</p> <p>* Reset/Single wire debug/power in header</p> <p>But my issues so far are:</p> <p>* I'm not at all confident in my I2C routing, or the routing in general. SDA and SCL take long and winding paths all over the board, and go near a (shielded) inductor. </p> <p>* My switching reg layout is not exactly the one from the datasheet, and I've only done this a few times. I used 0603s in parallel and 0805s in series for redundancy against short circuits.</p> <p>* I'm not sure what k

