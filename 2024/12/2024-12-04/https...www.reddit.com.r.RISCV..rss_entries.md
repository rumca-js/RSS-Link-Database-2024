# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## SOMEONE KNOWS TO PASS THIS N-QUEENS PROBLEM TO RISC32 TO WORK ON RARS? (help)
 - [https://www.reddit.com/r/RISCV/comments/1h6t03g/someone_knows_to_pass_this_nqueens_problem_to](https://www.reddit.com/r/RISCV/comments/1h6t03g/someone_knows_to_pass_this_nqueens_problem_to)
 - RSS feed: $source
 - date published: 2024-12-04T22:20:32+00:00

<!-- SC_OFF --><div class="md"><h1>include &lt;stdio.h&gt;</h1> <pre><code>#include &lt;stdbool.h&gt; #define MAX_N 8 // Tamaño máximo del tablero // Función que verifica si es seguro colocar una reina en una posición específica bool is_safe(int board[MAX_N], int row, int col) { for (int i = 0; i &lt; row; i++) { // Verifica si hay una reina en la misma columna o en diagonales if (board[i] == col || board[i] - i == col - row || board[i] + i == col + row) { return false; // No es seguro colocar la reina aquí } } return true; // Es seguro colocar la reina } // Función recursiva para resolver el problema de N-reinas void solve_n_queens(int board[MAX_N], int row, int N, int *count, bool *first_found, int *first_solution) { if (row == N) { // Si hemos colocado reinas en todas las filas if (!(*first_found)) { for (int i = 0; i &lt; N; i++) { first_solution[i] = board[i]; // Guardamos la primera solución } *first_found = true; // Marcamos que se encontró la primera solución } (*count)++; //

## Current landscape of vector cores.
 - [https://www.reddit.com/r/RISCV/comments/1h6nxvv/current_landscape_of_vector_cores](https://www.reddit.com/r/RISCV/comments/1h6nxvv/current_landscape_of_vector_cores)
 - RSS feed: $source
 - date published: 2024-12-04T18:55:34+00:00

<!-- SC_OFF --><div class="md"><p>What&#39;s up.</p> <p>For the second semester of my independent study project I want to move from qemu to real hardware and add graphics (even if it&#39;s just 480p or something). I figured a core with the vector extension might be useful for this. But clearly there&#39;s not much available on this front either in softcores or devboards. What are my options? Does this approach even make sense or should I try to glue a display driver core onto a imafdc softcore instead? Or something else entirely.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/grobblefip746"> /u/grobblefip746 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1h6nxvv/current_landscape_of_vector_cores/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1h6nxvv/current_landscape_of_vector_cores/">[comments]</a></span>

## I just received my Milk-V Mars!
 - [https://www.reddit.com/r/RISCV/comments/1h6ex7l/i_just_received_my_milkv_mars](https://www.reddit.com/r/RISCV/comments/1h6ex7l/i_just_received_my_milkv_mars)
 - RSS feed: $source
 - date published: 2024-12-04T12:33:42+00:00

<!-- SC_OFF --><div class="md"><p>I just received my Milk-V Mars development board. I ordered (from Arace) the 8GB model and got the 4GB model instead... it was never going to be the other way around, was it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Grouchy_Way_2881"> /u/Grouchy_Way_2881 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1h6ex7l/i_just_received_my_milkv_mars/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1h6ex7l/i_just_received_my_milkv_mars/">[comments]</a></span>

