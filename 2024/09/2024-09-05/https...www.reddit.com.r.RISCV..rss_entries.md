# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Ubuntu 24.04.1 server install guide for the MangoPI MQ Pro
 - [https://www.reddit.com/r/RISCV/comments/1f9k96j/ubuntu_24041_server_install_guide_for_the_mangopi](https://www.reddit.com/r/RISCV/comments/1f9k96j/ubuntu_24041_server_install_guide_for_the_mangopi)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-05T11:37:37+00:00

<!-- SC_OFF --><div class="md"><p>Ubuntu <code>24.04.1</code> was released recently, and they have provided new images for all their <a href="https://ubuntu.com/download/risc-v">risc-v platforms</a>. Unfortunately the associated Wiki&#39;s are hopelessly out of date.</p> <p>The MQ Pro is not on the list, but the SiPeed Lichee RV is; and the image for that boots well on the MQ-Pro. Wifi adapter is detected and it has a working HDMI console.</p> <p>I have totally re-written my MQ-Pro device tree guide for this Release; It covers the full install steps, including pre-configuring WiFi on the SD card and first boot.</p> <p><a href="https://github.com/easytarget/MQ-Pro-IO">https://github.com/easytarget/MQ-Pro-IO</a></p> <p>It then shows how to use <a href="https://manpages.debian.org/testing/flash-kernel/flash-kernel.8.en.html">flash-kernel </a>to select the correct MQ-Pro device tree by default instead of the Lichee one at <code>init</code>. The <code>kernel-modules-XXX</code> packages alr

## address translation in M Mode
 - [https://www.reddit.com/r/RISCV/comments/1f9hcm2/address_translation_in_m_mode](https://www.reddit.com/r/RISCV/comments/1f9hcm2/address_translation_in_m_mode)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-05T08:23:29+00:00

<!-- SC_OFF --><div class="md"><p>WHEN TVM is set to 1 does that mean we need address translation in Machine mode also? Translation is only needed i superisor and user mode only</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/khushiforyou"> /u/khushiforyou </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1f9hcm2/address_translation_in_m_mode/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1f9hcm2/address_translation_in_m_mode/">[comments]</a></span>

