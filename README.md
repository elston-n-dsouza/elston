<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# We finally have the equation $$e^{i\pi} + 1 = 0$$
Let us try inline \(x^2\) 
`\( f(z) = \frac{1}{2\pi i } \int_{0}^{\infty} \frac{f(\zeta)d\zeta}{\zeta - z} \)`

 `\(x_1 = 132\)` and `\(x_2 = 370\)` and so .
 
 <p>
\[ \varphi(X)= X^2 \]
</p>
`$x^2$`

$$  \varphi(X)= X^2 $$






<p>This page is for testing MathJax in my blog.  I wrote some custom
shorthand like $\zeros \in \R^n$.</p>

<h2>Problem</h2>

<p>For sequences of numbers, <em>limit inferior</em> and <em>limit
superior</em> are defined as $\liminf (a_n):=\sup\{\inf\{a_k:k \ge
n\}\}$ and $\limsup (a_n):=\inf\{\sup\{a_k:k \ge n\}\}$ respectively;
for sequences of sets, they are defined as $\displaystyle
\bigcup_{n=1}^{\infty} \bigcap_{k=n}^{\infty} A_k$ and $\displaystyle
\bigcap_{n=1}^{\infty} \bigcup_{k=n}^{\infty} A_k$ respectively.</p>

<p><strong>Why are they consistent?</strong></p>

<h2>Discussion</h2>

<p>It suffices to find a relation between '&lt;' and '&sube;': $\{x
\le a\} \subseteq \{x \le b\} \iff a \le b$.</p>

<p>Claim: $\displaystyle \bigcup_{a \in A} \{x \le a\} = \{x \le \sup
A\}$.</p>


\[
  \begin{aligned}
    & x \in \bigcup_{a \in A} \{x \le a\} \\
    \iff& x \le a \;\forall a \in A \\
    \iff& x \text{ is a lower bound of } A \\
    \iff& x \le \inf A
  \end{aligned}
\]



\[
  \begin{aligned}
    & \bigcap_{n=1}^{\infty} \bigcup_{k=n}^{\infty} \{x \le a_k\} \\
    =& \bigcap_{n=1}^{\infty} \bigcup_{a \in \{a_k:k \ge n\}} \{x \le a\} \\
    =& \bigcap_{n=1}^{\infty} \{ x \le \sup \{a_k:k \ge n\}\} \\
    =& \{x \le \inf\sup \{a_k:k \ge n\}\}
  \end{aligned}
\]
