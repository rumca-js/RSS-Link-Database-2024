# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Unknown relocation type 57
 - [https://www.reddit.com/r/RISCV/comments/1elwjj4/unknown_relocation_type_57](https://www.reddit.com/r/RISCV/comments/1elwjj4/unknown_relocation_type_57)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-06T23:24:35+00:00

<!-- SC_OFF --><div class="md"><p>board is licheerv nano with sg2002 SoC</p> <p>using debian sid with 5.10 kernel (<a href="https://github.com/Fishwaldo/sophgo-sg200x-debian">https://github.com/Fishwaldo/sophgo-sg200x-debian</a>)</p> <p>tried to compile this <a href="https://github.com/namjaejeon/ksmbd">https://github.com/namjaejeon/ksmbd</a></p> <p>used standard 5.10.4 kernel source because i want to compile module out of tree</p> <p>compiler: i'm using icecc with aarch64 on remote(it's just my phone) it has same version of gcc as local and it worked when i compiled curl with it</p> <p>kernel module compiles just fine but shows dmesg error when i tired to load it</p> <p>Unknown relocation type 57</p> <p>i think this might have something to do with compiler options</p> <p>edit: just fixed</p> <p>put CFLAG_MODULE='-fno-asynchronous-unwind-tables -fno-unwind-tables'</p> <p>and it worked</p> <p><a href="https://github.com/cwt-vf2/linux-cwt-starfive-vf2/compare/cwt20-5.10.3-2...cwt21-5.11

## CH582 code examples
 - [https://www.reddit.com/r/RISCV/comments/1eljtu9/ch582_code_examples](https://www.reddit.com/r/RISCV/comments/1eljtu9/ch582_code_examples)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-06T14:52:42+00:00

<!-- SC_OFF --><div class="md"><p>I made available a few code examples to illustrate the use of the CH582 in concrete situations.</p> <p>These are intended to help beginners in their first steps, as manufacturer examples are often not very helpful.</p> <p><a href="https://codeberg.org/20-100/CH582-examples">https://codeberg.org/20-100/CH582-examples</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/1r0n_m6n"> /u/1r0n_m6n </a> <br /> <span><a href="https://www.reddit.com/r/RISCV/comments/1eljtu9/ch582_code_examples/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1eljtu9/ch582_code_examples/">[comments]</a></span>

## Unable to boot linux with qemu for RiscV
 - [https://www.reddit.com/r/RISCV/comments/1elde4m/unable_to_boot_linux_with_qemu_for_riscv](https://www.reddit.com/r/RISCV/comments/1elde4m/unable_to_boot_linux_with_qemu_for_riscv)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-06T09:32:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello people, Need lil help here.</p> <p>I'm following Andestech user guide for building binaries for riscv.</p> <ol> <li>I cross compile opensbl and was able to generate <code>fw-dynamic.elf and .bin</code> in path ~<code>opensbi/build/platform/andes/ae350/firmware/</code></li> <li>Compiled Rootfs (inc busybox) and generated initramfs.devnodes file at ~/rootfs/disk/dev/ , There was a .sh script, I just had to execute that to generate this.</li> <li>Edit .config in linux path with <code>CONFIG_INITRAMFS_SOURCE=&quot;~/rootfs/disk/dev/initramfs.devnodes&quot;</code> and then Build linux by <code>make</code>. This gave me <code>Image.gz and Image</code> files in path <code>~/linux5.4/arch/riscv/boot/</code></li> <li>Compiled u-boot by copying <code>fw_dynamic.*</code> files and linux <code>Image</code> files into <code>u-boot path</code> and then by <code>make ae350_rv64_fastboot_defconfig &amp; make ARCH_FLAGS=&quot;-march=rv64v5&quot;</code>. This gav

## Latest Advancements of RISC-V Architecture in the software ecology. Looks promising!
 - [https://www.reddit.com/r/RISCV/comments/1elcwjo/latest_advancements_of_riscv_architecture_in_the](https://www.reddit.com/r/RISCV/comments/1elcwjo/latest_advancements_of_riscv_architecture_in_the)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-06T08:58:55+00:00

<!-- SC_OFF --><div class="md"><p>As we all know, at the early stage of the development of a new instruction set architecture, it often adopts the method of compatibility with software of other architectures to expand its own ecosystem, such as Apple’s Rosetta 2 and Microsoft’s Arm64EC, which both run the X86 architecture software on top of the ARM architecture system.</p> <p>As an emerging instruction set architecture, RISC-V is in dire need of rapid development and expansion of its software ecosystem. To this end, openKylin community RISC-V SIG has actively carried out binary translation and participated in the development of the open source project box64. Up to now, it has submitted and merged more than 20 PRs, added GTK3, nettle and other dynamic libraries and function packaging, improved the RISC-V dynamic recompile module and other functions, and contributed more than 2,000 lines of code in total.</p> <p>Recently, the same team has successfully run X86 architecture software, inc

## RISC-V!!!(64 CORE)
 - [https://www.reddit.com/r/RISCV/comments/1elc1u9/riscv64_core](https://www.reddit.com/r/RISCV/comments/1elc1u9/riscv64_core)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-06T07:59:54+00:00

<!-- SC_OFF --><div class="md"><p>Who will be interested in buying RISC-V server? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Happy_Monitor5958"> /u/Happy_Monitor5958 </a> <br /> <span><a href="https://www.reddit.com/r/RISCV/comments/1elc1u9/riscv64_core/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1elc1u9/riscv64_core/">[comments]</a></span>

