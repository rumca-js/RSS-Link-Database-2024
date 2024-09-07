# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Why is the offset of a branch instruction shifted left by one?
 - [https://www.reddit.com/r/RISCV/comments/1farhn2/why_is_the_offset_of_a_branch_instruction_shifted](https://www.reddit.com/r/RISCV/comments/1farhn2/why_is_the_offset_of_a_branch_instruction_shifted)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-06T22:10:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone. I don&#39;t know if this is the right sub, but I&#39;m studying for my Computer Architecture exam and precisely I&#39;m learning about the CPU datapath, implementing a subset of RISC-V instructions. <a href="https://imgur.com/a/oNhkoEq">Here</a> you can find a picture of what I&#39;m talking about. My question is, as the title says, why is the sign-extended offset of a branch instruction shifted left by 1 before going into the adder that calculates the address of the jump?<br/> My hypothesis is the following: I know that the 12 immediate bits of a B-type instructions start from bit number 1 because the 0-th bit is always zero. So maybe the offset is shifted left by one so that the 0-th bit is considered and the offset has the correct value. But I have no idea if I&#39;m right or wrong... Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/asdrubale_2"> /u/asdrubale_2 </a> <br/> <span><

## zip instruction: which one from the description or the operation is correct?
 - [https://www.reddit.com/r/RISCV/comments/1faenrb/zip_instruction_which_one_from_the_description_or](https://www.reddit.com/r/RISCV/comments/1faenrb/zip_instruction_which_one_from_the_description_or)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-06T13:03:36+00:00

<!-- SC_OFF --><div class="md"><p>In the standard page 267 the description of the zip instruction doesn&#39;t match the operation, which is correct?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PColim"> /u/PColim </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1faenrb/zip_instruction_which_one_from_the_description_or/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1faenrb/zip_instruction_which_one_from_the_description_or/">[comments]</a></span>

## SG2042 Newsletter (2024-09-06 #058)
 - [https://www.reddit.com/r/RISCV/comments/1fadl95/sg2042_newsletter_20240906_058](https://www.reddit.com/r/RISCV/comments/1fadl95/sg2042_newsletter_20240906_058)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-06T12:10:29+00:00

<!-- SC_OFF --><div class="md"><h2>Editor&#39;s Note</h2> <p>Welcome to the fifty-eighth issue of the SG2042 Newsletter. In this issue, we bring you the latest updates on SG2042 and provide a series of tutorials over Milk-V Duo. Hope you will enjoy this update.</p> <h2>Highlights</h2> <ul> <li><p>The Milk-V DuoS comes with two camera connectors, GC2083 and OV5647, offering new perspectives for your smart surveillance projects. For details, please refer to the link below.</p> <p><a href="https://mp.weixin.qq.com/s/hqLLlGBx0nW3grnF4skA1g">Detailed Info</a></p></li> </ul> <h2>Upstream</h2> <p>Most of the code is already open-source and can be obtained from repositories such as github.com/SOPHGO. The following are some useful repo resources:</p> <h3>Linux kernel</h3> <ul> <li><p>Sophgo Community work: <a href="https://github.com/sophgo/linux-riscv">https://github.com/sophgo/linux-riscv</a></p> <ul> <li>Driver optimization</li> <li>Performance optimization</li> </ul></li> <li><p>Linux Offi

