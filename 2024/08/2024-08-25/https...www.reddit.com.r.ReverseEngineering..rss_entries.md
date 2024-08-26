# Source:Reverse Engineering, URL:https://www.reddit.com/r/ReverseEngineering/.rss, language:

## Mac executable creation issue
 - [https://www.reddit.com/r/ReverseEngineering/comments/1f0z2yi/mac_executable_creation_issue](https://www.reddit.com/r/ReverseEngineering/comments/1f0z2yi/mac_executable_creation_issue)
 - RSS feed: https://www.reddit.com/r/ReverseEngineering/.rss
 - date published: 2024-08-25T15:33:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello peeps, </p> <p>I'm trying to create binary from x86 code [.S extension] on Apple Mac [2.3 GHz Dual-Core Intel Core i5 processor]. Im getting .o file without any errors. But I couldn't generate binary file from object file. </p> <p>command used and error received: </p> <p>$ clang -o example example.o ld: Undefined symbols: _main, referenced from: &lt;initial-undefines&gt; clang: error: linker command failed with exit code 1 (use -v to see invocation)</p> <p>Piece of code I used to create .o file:</p> <p>.intel_syntax noprefix</p> <p>_main: xor rax, rax<br /> xor rcx, rcx<br /> test rdi, rdi</p> <p>Any suggestions please.. PS: I have tried using ld as well, it gives me same error.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/s4y_ch33s3_"> /u/s4y_ch33s3_ </a> <br /> <span><a href="https://youtu.be/dQw4w9WgXcQ?si=hIIWXoXi0mknFekV">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/ReverseEnginee

