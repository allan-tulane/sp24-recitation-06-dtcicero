# CMPS 2200 Recitation 06
## Answers

**Name:** Daniel Cicero
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**  W(n) = 1 if n == 0 or n == 1
-         Otherwise, W(n) = W(n-1) + W(n-2) + 1

          Solved: W(n)= F_n+1 + 1

- **3)**  S(n) = 1 if n == 0 or n == 1
-         Otherwise, S(n) = S(n-1) + S(n-2) + c

          Solved: S(n)=F_n+1 + c

- **4)**
         The values in the counts list increase exponentially in              this case, as this algorithm is not utilizing memorization,          and therefore redundantly making many fibonacci                      calculations it has already made and could have stored for           quicker access.
- **6)**
         The maximum number of times that fib_top_down(i) will be             called for any value $i$ is equal to n. Because of this,             both work and span of this equation are O(n).
- **8)**
         The maximum number of times that $F_i$ will be read for any          value $i$ is 3, with these being F_n itself, F_n-1, and              F_n-2. From this, Work and Span are both O(n).
