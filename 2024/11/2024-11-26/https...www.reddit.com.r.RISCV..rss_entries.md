# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## work around 32 bit sign extension of a constant
 - [https://www.reddit.com/r/RISCV/comments/1h0kaxo/work_around_32_bit_sign_extension_of_a_constant](https://www.reddit.com/r/RISCV/comments/1h0kaxo/work_around_32_bit_sign_extension_of_a_constant)
 - RSS feed: $source
 - date published: 2024-11-26T19:23:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi. Looking for an answer and can&#39;t find it. I have an embedded app that has a function that returns a 32 bit unsigned value. When I try to compare the output of that function with an unsigned constant, the comparison fails. It looks like the sign is extended to 64 bits and therefore the they do not match.</p> <p>Code looks like</p> <p>```</p> <p>extern unsigned myfunc() { return 0xaa00aa00;}</p> <p>...</p> <p>if(myfunc() != (unsigned) 0xaa00aa00u) { printf(&quot;Fail&quot;)}</p> <p>```</p> <p>On a simulator, the constant 0xaa00aa00u becomes 0xffffffffaa00aa00 and the compiler I am using compares a 64 bit value 0xaa00aa00 with 0xfffffffaa00aa00 and it fails. the only thing I have been able to see work is making temp variables with 64 bit sizes and printing the expected and actual. My understanding of the C language is that unsigned values have no sign, so why is the compiler producing code that extends the sign? I understand RISCV processors love

## Theory question about exceptions on 5-stage belt
 - [https://www.reddit.com/r/RISCV/comments/1h09tku/theory_question_about_exceptions_on_5stage_belt](https://www.reddit.com/r/RISCV/comments/1h09tku/theory_question_about_exceptions_on_5stage_belt)
 - RSS feed: $source
 - date published: 2024-11-26T11:37:27+00:00

<!-- SC_OFF --><div class="md"><ol> <li><p>There is a 5-stage conveyor belt.</p></li> <li><p>Fully loaded.</p></li> <li><p>No branching, stall&#39;s or anything else.</p></li> <li><p>On one clock cycle:</p></li> </ol> <p>4.1. page fault occurs in fetch.</p> <p>4.2. decode - illegal instruction.</p> <p>4.3. execute - div by zero.</p> <p>4.4. memory access - still page fault, but at a different address.</p> <p>4.5. write back - normal.</p> <p>How will such a tact be handled by exceptions? There are 4 of three kinds of exceptions.<br/> And how i can try emulate and write tests to it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dallik_justlive"> /u/Dallik_justlive </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1h09tku/theory_question_about_exceptions_on_5stage_belt/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1h09tku/theory_question_about_exceptions_on_5stage_belt/">[comments]</a></span>

## Raspberry Pi Pico 2 (Hazard 3 RISC-V Cores) now has a wi-fi variant!
 - [https://www.reddit.com/r/RISCV/comments/1h04ck5/raspberry_pi_pico_2_hazard_3_riscv_cores_now_has](https://www.reddit.com/r/RISCV/comments/1h04ck5/raspberry_pi_pico_2_hazard_3_riscv_cores_now_has)
 - RSS feed: $source
 - date published: 2024-11-26T05:18:42+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/PlatimaZero"> /u/PlatimaZero </a> <br/> <span><a href="https://www.raspberrypi.com/news/raspberry-pi-pico-2-w-on-sale-now/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1h04ck5/raspberry_pi_pico_2_hazard_3_riscv_cores_now_has/">[comments]</a></span>

