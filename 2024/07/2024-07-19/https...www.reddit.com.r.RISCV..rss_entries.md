# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## help with memory handling issue for a custom OS for Milk-V Duo (256m)
 - [https://www.reddit.com/r/RISCV/comments/1e75zqx/help_with_memory_handling_issue_for_a_custom_os](https://www.reddit.com/r/RISCV/comments/1e75zqx/help_with_memory_handling_issue_for_a_custom_os)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-07-19T15:07:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I'm working on a custom operating system for a Milk-V Duo 256m MCU, which runs OpenSBI, and I've encountered a memory handling issue. The problem comes up in my main.c file:</p> <pre><code>#include &quot;../include/stdint.h&quot; #include &quot;../include/stddef.h&quot; #define UART0_THR (*((volatile uint32_t*)0x04140000)) #define UART0_LSR (*((volatile uint32_t*)0x04140014)) void uart_sendc(char c) { while (!(UART0_LSR &amp; 0x20)); UART0_THR = c; } void uart_send_message(const char *str) { while(*str) { uart_sendc(*str++); } } void main(void) { const char *str = &quot;Hello from C!\n&quot;; uart_send_message(str); uart_sendc('E'); return; } </code></pre> <p>Issue:</p> <p>The uart_sendc function works perfectly, but when trying to print a string through the uart_send_message function, nothing is printed. Only the character 'E' is printed, indicating the string isn't being handled correctly.</p> <p>Printing a string from assembly, 

