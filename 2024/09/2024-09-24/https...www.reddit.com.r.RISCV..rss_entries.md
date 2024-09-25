# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## youtube SiFive Product Update
 - [https://www.reddit.com/r/RISCV/comments/1foll7c/youtube_sifive_product_update](https://www.reddit.com/r/RISCV/comments/1foll7c/youtube_sifive_product_update)
 - RSS feed: $source
 - date published: 2024-09-24T19:49:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1foll7c/youtube_sifive_product_update/"> <img src="https://external-preview.redd.it/xu8JYkNYgn1Y-KsFa1mnpsGg0h2PsMfH5AyxFAtAJdI.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=7570dc1df57f291b277194390f7e4d11b78fae67" alt="youtube SiFive Product Update" title="youtube SiFive Product Update" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jacko10101010101"> /u/Jacko10101010101 </a> <br/> <span><a href="https://www.youtube.com/watch?v=p94V2T_mRxo">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1foll7c/youtube_sifive_product_update/">[comments]</a></span> </td></tr></table>

## How to print the content of a vector
 - [https://www.reddit.com/r/RISCV/comments/1fofrvx/how_to_print_the_content_of_a_vector](https://www.reddit.com/r/RISCV/comments/1fofrvx/how_to_print_the_content_of_a_vector)
 - RSS feed: $source
 - date published: 2024-09-24T15:49:42+00:00

<!-- SC_OFF --><div class="md"><p>From this example: <a href="https://github.com/riscv-non-isa/rvv-intrinsic-doc/blob/main/examples/rvv_saxpy.c">https://github.com/riscv-non-isa/rvv-intrinsic-doc/blob/main/examples/rvv_saxpy.c</a>, once we have loaded a portion of the x array into vx, ie:</p> <pre><code>vfloat32m8_t vx = __riscv_vle32_v_f32m8(x, vl); </code></pre> <p>what&#39;s the proper way to display the contents of vx? (if it&#39;s possible at all).<br/> I managed to do it with some pointer evilness but i&#39;ve been told it was UB, ie:</p> <pre><code>float* pointer_to_vx = &amp;vx; double thing = pointer_to_vx[0]; printf(&quot;%f\n&quot;, thing); </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Conscious-Week8326"> /u/Conscious-Week8326 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fofrvx/how_to_print_the_content_of_a_vector/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fofrvx

## What's the latest on the Eswin EIC7700 boards and the SG2380 SoC?
 - [https://www.reddit.com/r/RISCV/comments/1fo0obn/whats_the_latest_on_the_eswin_eic7700_boards_and](https://www.reddit.com/r/RISCV/comments/1fo0obn/whats_the_latest_on_the_eswin_eic7700_boards_and)
 - RSS feed: $source
 - date published: 2024-09-24T01:13:38+00:00

<!-- SC_OFF --><div class="md"><p>I thought the Eswin boards were supposed to be out in July but that doesn&#39;t seem to have happened (e.g. HiFive Premier, LicheePi 5A, Milk-V Megrez).</p> <p>Also, the SG2380 was supposed to tape out by the end of July, and before that in May, and before that in March. I&#39;d rather it was delayed and good once it arrived (like the JH7110), not rushed and deeply flawed, but what is the status?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fo0obn/whats_the_latest_on_the_eswin_eic7700_boards_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fo0obn/whats_the_latest_on_the_eswin_eic7700_boards_and/">[comments]</a></span>

