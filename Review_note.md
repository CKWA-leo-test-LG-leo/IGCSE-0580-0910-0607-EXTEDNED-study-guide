# 📘 IGCSE 0607 Extended Mathematics — Part 2

---

# 2. Algebra and Graphs 📊

---

## 2.1 Algebraic Manipulation 🧮

### 2.1.1 Collect Like Terms & Expand Brackets

**Collecting like terms:** Combine terms with the same variable and power.

> **Example:**
> $$
> 3x + 5y - 2x + 3y = (3x - 2x) + (5y + 3y) = x + 8y
> $$

**Expanding brackets:** Use the distributive law $a(b+c) = ab + ac$.

> **Example:**
> $$
> \begin{aligned}
> (x + 2)(x + 5) &= x(x+5) + 2(x+5) \\
> &= x^2 + 5x + 2x + 10 \\
> &= x^2 + 7x + 10
> \end{aligned}
> $$

### 2.1.2 Factorisation

**Taking out common factors:**

> **Example:** $6x^2 + 9x = 3x(2x + 3)$

**Difference of squares:** $a^2 - b^2 = (a+b)(a-b)$

> **Example:** $x^2 - 25 = (x+5)(x-5)$

**Perfect square:** $a^2 \pm 2ab + b^2 = (a \pm b)^2$

> **Example:** $x^2 + 6x + 9 = (x+3)^2$

**Quadratic trinomials:** $x^2 + bx + c = (x+p)(x+q)$ where $p+q=b$ and $pq=c$

> **Example:** $x^2 + 7x + 12 = (x+3)(x+4)$

**Factorisation by grouping:**

> **Example:**
> $$
> \begin{aligned}
> ax + ay + bx + by &= a(x+y) + b(x+y) \\
> &= (a+b)(x+y)
> \end{aligned}
> $$

### 2.1.3 Completing the Square

Rewrite $ax^2 + bx + c$ as $a(x + h)^2 + k$.

> **Example:** Complete the square for $2x^2 - 8x + 5$.
>
> **Solution:**
> $$
> \begin{aligned}
> 2x^2 - 8x + 5 &= 2(x^2 - 4x) + 5 \\
> &= 2[(x-2)^2 - 4] + 5 \\
> &= 2(x-2)^2 - 8 + 5 \\
> &= 2(x-2)^2 - 3
> \end{aligned}
> $$
>
> Vertex: $(2, -3)$, axis of symmetry: $x = 2$, minimum value: $-3$.

---

### ⭐ Paper 4 — Worked Example

**Question:** Factorise completely $6x^2 - 11x - 10$.

**Solution:**

Using the cross-multiplication or grouping method:

$$
\begin{aligned}
6x^2 - 11x - 10 &= 6x^2 - 15x + 4x - 10 \\
&= 3x(2x - 5) + 2(2x - 5) \\
&= (2x - 5)(3x + 2)
\end{aligned}
$$

**Check:** $(2x - 5)(3x + 2) = 6x^2 + 4x - 15x - 10 = 6x^2 - 11x - 10$ ✅

---

### ⭐ Paper 6 — Investigation

**Question:** Observe the factorisation patterns:

$$
\begin{aligned}
x^2 - 1 &= (x-1)(x+1) \\
x^3 - 1 &= (x-1)(x^2 + x + 1) \\
x^4 - 1 &= (x-1)(x^3 + x^2 + x + 1)
\end{aligned}
$$

**(a)** Write down the factorisation of $x^5 - 1$ and $x^6 - 1$.

**(b)** Hence deduce the formula: $x^n - 1 = (x-1)(x^{n-1} + x^{n-2} + \cdots + x + 1)$.

**(c)** Use this formula to evaluate $2^7 + 2^6 + 2^5 + 2^4 + 2^3 + 2^2 + 2 + 1$.

**Solution:**

**(a)**
$$
\begin{aligned}
x^5 - 1 &= (x-1)(x^4 + x^3 + x^2 + x + 1) \\
x^6 - 1 &= (x-1)(x^5 + x^4 + x^3 + x^2 + x + 1)
\end{aligned}
$$

**(b)** The pattern generalises to:
$$
x^n - 1 = (x-1)(x^{n-1} + x^{n-2} + \cdots + x + 1)
$$

**(c)** Let $x = 2$ and $n = 8$:
$$
\begin{aligned}
2^8 - 1 &= (2-1)(2^7 + 2^6 + \cdots + 2 + 1) \\
256 - 1 &= 1 \times S \\
S &= 255
\end{aligned}
$$

---

## 2.2 Algebraic Fractions 🍕

### 2.2.1 Operations with Algebraic Fractions

**Addition and subtraction:** Find a common denominator first.

> **Example:**
> $$
> \frac{2}{x} + \frac{3}{x+1} = \frac{2(x+1)}{x(x+1)} + \frac{3x}{x(x+1)} = \frac{5x+2}{x(x+1)}
> $$

**Multiplication:** Multiply numerators and denominators separately.

**Division:** Multiply by the reciprocal.

> **Example:**
> $$
> \frac{x}{2} \div \frac{x+1}{3} = \frac{x}{2} \times \frac{3}{x+1} = \frac{3x}{2(x+1)}
> $$

### 2.2.2 Simplifying Rational Expressions

Factorise both numerator and denominator, then cancel common factors.

> **Example:**
> $$
> \frac{x^2 - 9}{x^2 + 5x + 6} = \frac{(x+3)(x-3)}{(x+2)(x+3)} = \frac{x-3}{x+2}
> $$

---

### ⭐ Paper 4 — Worked Example

**Question:** Simplify $\displaystyle \frac{x^2 - 16}{x^2 + 3x - 4} \times \frac{x^2 - 1}{x^2 + 4x}$.

**Solution:**

$$
\begin{aligned}
&= \frac{(x+4)(x-4)}{(x+4)(x-1)} \times \frac{(x+1)(x-1)}{x(x+4)} \\[4pt]
&= \frac{x-4}{x-1} \times \frac{x+1}{x} \quad (\text{cancel } x+4 \text{ and } x-1)\\[4pt]
&= \frac{(x-4)(x+1)}{x(x-1)}
\end{aligned}
$$

---

### ⭐ Paper 4 — Worked Example 2

**Question:** Solve $\displaystyle \frac{3}{x-2} + \frac{4}{x+3} = 2$.

**Solution:**

$$
\begin{aligned}
\frac{3(x+3) + 4(x-2)}{(x-2)(x+3)} &= 2 \\[4pt]
\frac{3x + 9 + 4x - 8}{(x-2)(x+3)} &= 2 \\[4pt]
\frac{7x + 1}{(x-2)(x+3)} &= 2 \\[4pt]
7x + 1 &= 2(x-2)(x+3) \\[4pt]
7x + 1 &= 2(x^2 + x - 6) \\[4pt]
7x + 1 &= 2x^2 + 2x - 12 \\[4pt]
0 &= 2x^2 - 5x - 13
\end{aligned}
$$

Using the quadratic formula:

$$
x = \frac{5 \pm \sqrt{25 + 104}}{4} = \frac{5 \pm \sqrt{129}}{4}
$$

**Check:** $x \neq 2$ and $x \neq -3$, so both solutions are valid. ✅

---

## 2.3 Equations ⚖️

### 2.3.1 Linear & Fractional Equations

> **Example:**
> $$
> \frac{x}{3} + \frac{2x}{5} = 4
> $$
>
> Multiply both sides by 15:
> $$
> 5x + 6x = 60 \implies 11x = 60 \implies x = \frac{60}{11}
> $$

### 2.3.2 Simultaneous Equations

| Type | Method | Example |
|:---:|:---:|:---:|
| Linear + Linear | Substitution / Elimination | $y = 2x + 1$, $3x + y = 11$ |
| Linear + Quadratic | Substitution | $y = x + 2$, $y = x^2$ |

> **Example (Linear + Quadratic):**
> $$
> \begin{cases}
> y = x + 2 \\
> y = x^2
> \end{cases}
> $$
>
> $$
> \begin{aligned}
> x + 2 &= x^2 \\
> x^2 - x - 2 &= 0 \\
> (x-2)(x+1) &= 0
> \end{aligned}
> $$
>
> Solutions: $(2,4)$ and $(-1,1)$.

### 2.3.3 Solving Quadratic Equations

| Method | When to Use | Example |
|:---:|:---:|:---:|
| Factorising | When factorable | $x^2 - 5x + 6 = 0 \implies (x-2)(x-3)=0 \implies x=2,3$ |
| Completing the Square | All cases | $x^2 + 6x + 5 = 0 \implies (x+3)^2 = 4 \implies x = -1, -5$ |
| Quadratic Formula | **Universal** | $x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ |

**The Discriminant:** $\Delta = b^2 - 4ac$

- $\Delta > 0$: two distinct real roots
- $\Delta = 0$: one repeated root
- $\Delta < 0$: no real roots

### 2.3.4 Equations Involving Parameters

> **Example:** The quadratic equation $kx^2 + 6x + k = 0$ has equal roots. Find $k$.
>
> **Solution:**
> $$
> \Delta = 6^2 - 4(k)(k) = 36 - 4k^2 = 0 \implies k^2 = 9 \implies k = \pm 3
> $$
>
> - When $k = 3$: $3x^2 + 6x + 3 = 3(x+1)^2 = 0$, root $x = -1$.
> - When $k = -3$: $-3x^2 + 6x - 3 = -3(x-1)^2 = 0$, root $x = 1$.

---

### ⭐ Paper 4 — Worked Example

**Question:** Solve the simultaneous equations:

$$
\begin{cases}
y = 2x^2 - 3x + 1 \\
y = 5x - 7
\end{cases}
$$

**Solution:**

$$
\begin{aligned}
2x^2 - 3x + 1 &= 5x - 7 \\
2x^2 - 8x + 8 &= 0 \\
x^2 - 4x + 4 &= 0 \\
(x-2)^2 &= 0 \\
x &= 2
\end{aligned}
$$

Substitute $x = 2$: $y = 5(2) - 7 = 3$.

Only **one** intersection point: $(2, 3)$ — the line is tangent to the parabola! 🔵

---

### ⭐ Paper 6 — Investigation

**Question:** A rectangular garden has a perimeter of 40 m. If the length is increased by 2 m and the width is decreased by 1 m, the area remains unchanged.

**(a)** Let the original length be $x$ m. Express the original width in terms of $x$.

**(b)** Form an equation and find the original length and width.

**(c)** If both length and width are increased by the same amount $d$ m, and the new area is 50 m² larger than the original area, find $d$.

**Solution:**

**(a)** Perimeter $= 2(x + w) = 40 \implies x + w = 20 \implies w = 20 - x$

**(b)** Original area: $A = x(20 - x)$

New length: $x + 2$, new width: $(20 - x) - 1 = 19 - x$

$$
\begin{aligned}
(x + 2)(19 - x) &= x(20 - x) \\
19x - x^2 + 38 - 2x &= 20x - x^2 \\
17x + 38 &= 20x \\
38 &= 3x \\
x &= \frac{38}{3} \approx 12.67
\end{aligned}
$$

Original length $= \dfrac{38}{3}$ m, original width $= 20 - \dfrac{38}{3} = \dfrac{22}{3}$ m ✅

**(c)** New length $= \dfrac{38}{3} + d$, new width $= \dfrac{22}{3} + d$

Original area: $A = \dfrac{38}{3} \times \dfrac{22}{3} = \dfrac{836}{9}$

$$
\begin{aligned}
\left(\frac{38}{3} + d\right)\left(\frac{22}{3} + d\right) &= \frac{836}{9} + 50 \\[4pt]
\frac{836}{9} + \frac{38}{3}d + \frac{22}{3}d + d^2 &= \frac{836}{9} + 50 \\[4pt]
\frac{60}{3}d + d^2 &= 50 \\[4pt]
20d + d^2 &= 50 \\[4pt]
d^2 + 20d - 50 &= 0
\end{aligned}
$$

$$
d = \frac{-20 \pm \sqrt{400 + 200}}{2} = \frac{-20 \pm \sqrt{600}}{2} = \frac{-20 \pm 10\sqrt{6}}{2} = -10 \pm 5\sqrt{6}
$$

Since $d > 0$: $d = -10 + 5\sqrt{6} \approx 2.25$ m ✅

---

## 2.4 Inequalities 🚦

### 2.4.1 Linear & Quadratic Inequalities

> **Linear Example:** $2x - 3 > 5$
> $$
> 2x > 8 \implies x > 4
> $$
> On a number line: open circle at 4, arrow to the right.

> **Quadratic Example:** $x^2 - 5x + 6 < 0$
>
> Solve $(x-2)(x-3) = 0 \implies x = 2$ or $x = 3$
>
> Since $a > 0$ (opens upward), the region **below** the x-axis is between the roots:
> $$
> 2 < x < 3
> $$

### 2.4.2 Linear Inequalities in Two Variables

Shade the **unwanted** region to show the feasible region.

> **Example:**
> $$
> \begin{cases}
> y \ge 2x - 4 \\
> y < -\dfrac{1}{2}x + 2 \\
> x \ge 0
> \end{cases}
> $$

---

### ⭐ Paper 4 — Worked Example

**Question:** Solve $x^2 - 2x - 15 \le 0$ and represent the solution on a number line.

**Solution:**

$$
x^2 - 2x - 15 = (x-5)(x+3) \le 0
$$

Roots: $x = -3$ and $x = 5$

Test intervals:

| Interval | $x < -3$ | $-3 < x < 5$ | $x > 5$ |
|:---:|:---:|:---:|:---:|
| Sign of $(x+3)(x-5)$ | $(-)(-) = +$ | $(+)(-) = -$ | $(+)(+) = +$ |
| Satisfies $\le 0$? | ❌ | ✅ | ❌ |

Solution set: $-3 \le x \le 5$

Number line:
```
←——●━━━━━━━━━●——→
   -3         5
```

---

### ⭐ Paper 4 — Worked Example 2

**Question:** A rectangular region is defined by:

$$
\begin{cases}
y \ge 2x - 4 \\
y < -\dfrac{1}{2}x + 2 \\
x \ge 0
\end{cases}
$$

Find the vertices of the feasible region.

**Solution:**

| Boundary | Line type |
|:---:|:---:|
| $y = 2x - 4$ | Solid (inclusive) |
| $y = -\frac{1}{2}x + 2$ | Dashed (exclusive) |
| $x = 0$ | Solid (inclusive) |

Vertices (intersection points):

- **A:** $x = 0$, $y = 2x - 4 = -4$ → $A(0, -4)$
- **B:** $x = 0$, $y = -\frac{1}{2}x + 2 = 2$ → $B(0, 2)$
- **C:** Intersection of $y = 2x - 4$ and $y = -\frac{1}{2}x + 2$:
  $$
  2x - 4 = -\frac{1}{2}x + 2 \implies 2.5x = 6 \implies x = 2.4,\; y = 0.8
  $$
  → $C(2.4, 0.8)$

The feasible region is $\triangle ABC$ (including boundary $y \ge 2x-4$ and $x \ge 0$, excluding $y = -\frac{1}{2}x + 2$). ✅

---

## 2.5 Sequences 🔢

### 2.5.1 Linear Sequences (Arithmetic)

General term: $u_n = a + (n-1)d$, where $a$ is the first term and $d$ is the common difference.

> **Example:** $2, 5, 8, 11, \ldots$
>
> $a = 2$, $d = 3$ → $u_n = 2 + 3(n-1) = 3n - 1$

### 2.5.2 Quadratic Sequences

General term: $u_n = an^2 + bn + c$, where $2a$ is the constant second difference.

> **Example:** $3, 6, 11, 18, 27, \ldots$
>
> First differences: $3, 5, 7, 9$ (linear)
> Second differences: $2, 2, 2$ (constant)
>
> $2a = 2 \implies a = 1$. Then solve for $b$ and $c$ using the first two terms.

### 2.5.3 Exponential Sequences

> **Example:** $2, 4, 8, 16, 32, \ldots$
>
> $u_n = 2^n$

### 2.5.4 Term-to-Term Rules (Recurrence)

> **Example:** $u_{n+1} = 2u_n + 1$, $u_1 = 1$
>
> $$
> u_2 = 2(1) + 1 = 3,\quad u_3 = 2(3) + 1 = 7,\quad u_4 = 2(7) + 1 = 15,\; \ldots
> $$

---

### ⭐ Paper 4 — Worked Example

**Question:** A quadratic sequence has first four terms:

$$
7,\; 14,\; 25,\; 40,\; \ldots
$$

**(a)** Find the $n^{\text{th}}$ term formula.

**(b)** Find the value of the $10^{\text{th}}$ term.

**(c)** Determine whether 214 is a term in the sequence.

**Solution:**

**(a)**

| $n$ | 1 | 2 | 3 | 4 |
|:---:|:---:|:---:|:---:|:---:|
| $u_n$ | 7 | 14 | 25 | 40 |
| 1st diff | | 7 | 11 | 15 |
| 2nd diff | | | 4 | 4 |

Second difference is constant $= 4 = 2a \implies a = 2$.

Using $u_n = an^2 + bn + c$:

- $n = 1$: $2 + b + c = 7 \implies b + c = 5$ ...①
- $n = 2$: $8 + 2b + c = 14 \implies 2b + c = 6$ ...②

② $-$ ①: $b = 1$

Substitute into ①: $1 + c = 5 \implies c = 4$

$$
\therefore u_n = 2n^2 + n + 4
$$

**(b)** $u_{10} = 2(100) + 10 + 4 = 214$

**(c)** Let $2n^2 + n + 4 = 214$:

$$
2n^2 + n - 210 = 0
$$

$$
n = \frac{-1 \pm \sqrt{1 + 1680}}{4} = \frac{-1 \pm 41}{4}
$$

$n = 10$ or $n = -10.5$ (reject).

Yes, **214 is the 10th term**! ✅

---

### ⭐ Paper 6 — Investigation (Triangular Numbers)

**Question:** Triangular numbers: $1, 3, 6, 10, 15, \ldots$

```
●       ●       ●       ●
        ●●      ●●      ●●
                ●●●     ●●●
                       ●●●●
T₁=1    T₂=3    T₃=6    T₄=10
```

**(a)** Find a formula for the $n^{\text{th}}$ triangular number $T_n$.

**(b)** Prove that the sum of any two consecutive triangular numbers is a perfect square.

**(c)** If $T_p = 210$, find $p$.

**(d)** Given $T_{20} = 210$, find $T_{30}$ and $T_{50}$.

**Solution:**

**(a)**
$$
T_n = 1 + 2 + 3 + \cdots + n = \frac{n(n+1)}{2}
$$

**(b)**
$$
\begin{aligned}
T_n + T_{n+1} &= \frac{n(n+1)}{2} + \frac{(n+1)(n+2)}{2} \\[4pt]
&= \frac{(n+1)(n + n + 2)}{2} \\[4pt]
&= \frac{2(n+1)^2}{2} \\[4pt]
&= (n+1)^2
\end{aligned}
$$

Which is a **perfect square**. ✨

**(c)**
$$
\frac{p(p+1)}{2} = 210 \implies p^2 + p - 420 = 0 \implies (p+21)(p-20) = 0 \implies p = 20
$$

**(d)**
$$
T_{30} = \frac{30 \times 31}{2} = 465,\qquad T_{50} = \frac{50 \times 51}{2} = 1275
$$

---

## 2.6 Proportion and Functions 📊

### 2.6.1 Direct and Inverse Proportion

**Direct proportion:** $y \propto x$ → $y = kx$

> **Example:** $y$ is directly proportional to $x$. When $x = 3$, $y = 12$.
> $$
> k = \frac{y}{x} = \frac{12}{3} = 4 \implies y = 4x
> $$

**Inverse proportion:** $y \propto \frac{1}{x}$ → $y = \frac{k}{x}$

> **Example:** $y$ is inversely proportional to $x$. When $x = 2$, $y = 6$.
> $$
> k = xy = 12 \implies y = \frac{12}{x}
> $$

### 2.6.2 Expressing Proportional Relationships Algebraically

> **Example:** $y$ varies inversely with $x^2$. When $x = 4$, $y = 3$.
>
> $y = \frac{k}{x^2}$ → $3 = \frac{k}{16}$ → $k = 48$
>
> $$
> y = \frac{48}{x^2}
> $$

---

### ⭐ Paper 4 — Worked Example

**Question:** Kinetic energy $E_k$ is directly proportional to mass $m$ and directly proportional to the square of velocity $v$. A 2 kg object moving at 3 m/s has kinetic energy 9 J.

**(a)** Write an expression for $E_k$ in terms of $m$ and $v$.

**(b)** Find the kinetic energy of a 5 kg object moving at 4 m/s.

**(c)** If kinetic energy becomes 4 times greater while mass stays the same, how many times greater is the velocity?

**Solution:**

**(a)** $E_k \propto mv^2$ → $E_k = k \cdot mv^2$

Substitute: $9 = k \cdot 2 \cdot 9$ → $9 = 18k$ → $k = \frac{1}{2}$

$$
\therefore E_k = \frac{1}{2}mv^2
$$

**(b)** $E_k = \frac{1}{2} \times 5 \times 16 = 40$ J ✅

**(c)** Mass constant: $\dfrac{E_{k_2}}{E_{k_1}} = \dfrac{v_2^2}{v_1^2} = 4$ → $v_2 = 2v_1$

Velocity becomes **2 times greater**. ✅

---

## 2.7 Functions 🎯

### 2.7.1 Definition, Domain & Range

A function $f$ maps each input $x$ to exactly one output $f(x)$.

- **Domain:** the set of all possible inputs
- **Range:** the set of all possible outputs

> **Example:** $f(x) = x^2 + 1$, domain $x \in \mathbb{R}$, range $f(x) \ge 1$

### 2.7.2 Composite Functions

$fg(x) = f(g(x))$ — apply $g$ first, then $f$.

> **Example:** $f(x) = 2x$, $g(x) = x + 3$
>
> $$
> fg(x) = f(g(x)) = 2(x+3) = 2x + 6
> $$
> $$
> gf(x) = g(f(x)) = 2x + 3
> $$

### 2.7.3 Inverse Functions

To find $f^{-1}(x)$: let $y = f(x)$, solve for $x$, then swap $x$ and $y$.

> **Example:** $f(x) = 2x + 3$
>
> Let $y = 2x + 3$ → $x = \dfrac{y-3}{2}$ → $f^{-1}(x) = \dfrac{x-3}{2}$

**Key property:** The graph of $f^{-1}(x)$ is the reflection of $f(x)$ in the line $y = x$.

### 2.7.4 Graphs of Functions

| Function Type | Shape | Key Features |
|:---:|:---:|:---:|
| Linear $y = mx + c$ | Straight line | Gradient $m$, $y$-intercept $c$ |
| Quadratic $y = ax^2+bx+c$ | Parabola | Vertex, axis of symmetry |
| Cubic $y = ax^3+\cdots$ | S-shaped curve | Up to 2 turning points |
| Reciprocal $y = k/x$ | Hyperbola | Asymptotes at $x=0$, $y=0$ |
| Exponential $y = a^x$ | Growth/Decay | Asymptote at $y=0$, passes $(0,1)$ |

### 2.7.5 Asymptotes

**Vertical asymptote:** where denominator $= 0$

**Horizontal asymptote:** the value $y$ approaches as $x \to \pm\infty$

> **Example:** $y = \dfrac{1}{x-2} + 3$
>
> Vertical asymptote: $x = 2$
> Horizontal asymptote: $y = 3$

---

### ⭐ Paper 4 — Worked Example

**Question:** Given $f(x) = 2x - 1$, $g(x) = \dfrac{3}{x+1}$, $x \neq -1$.

**(a)** Find $fg(x)$ and $gf(x)$.

**(b)** Find $f^{-1}(x)$ and $g^{-1}(x)$.

**(c)** Solve $f^{-1}(x) = g(x)$.

**Solution:**

**(a)**
$$
fg(x) = f(g(x)) = 2\left(\frac{3}{x+1}\right) - 1 = \frac{6}{x+1} - 1 = \frac{5 - x}{x+1}
$$

$$
gf(x) = g(f(x)) = \frac{3}{(2x-1)+1} = \frac{3}{2x}
$$

**(b)**
$$
f^{-1}(x) = \frac{x+1}{2}
$$

$$
g^{-1}(x) = \frac{3}{x} - 1
$$

**(c)**
$$
\frac{x+1}{2} = \frac{3}{x+1} \implies (x+1)^2 = 6 \implies x+1 = \pm\sqrt{6} \implies x = -1 \pm \sqrt{6}
$$

---

### ⭐ Paper 4 — Worked Example 2

**Question:** $f(x) = \dfrac{2x+3}{x-2}$, $x \neq 2$.

**(a)** Find the range of $f(x)$.

**(b)** Find $f^{-1}(x)$.

**(c)** State the equations of the asymptotes.

**Solution:**

**(a)** Rewrite:
$$
f(x) = \frac{2x+3}{x-2} = \frac{2(x-2) + 7}{x-2} = 2 + \frac{7}{x-2}
$$

Since $\frac{7}{x-2} \neq 0$, $f(x) \neq 2$.

Range: $f(x) \in \mathbb{R},\; f(x) \neq 2$

**(b)** Let $y = \frac{2x+3}{x-2}$:

$$
\begin{aligned}
y(x-2) &= 2x + 3 \\
yx - 2y &= 2x + 3 \\
yx - 2x &= 2y + 3 \\
x(y-2) &= 2y + 3 \\
x &= \frac{2y+3}{y-2}
\end{aligned}
$$

$$
\therefore f^{-1}(x) = \frac{2x+3}{x-2}
$$

Interesting — $f(x)$ is a **self-inverse function**! 🎉

**(c)** Vertical asymptote: $x = 2$  
Horizontal asymptote: $y = 2$

---

## 2.8 Graph Transformations 🎨

### 2.8.1 Translations

| Transformation | Rule | Effect |
|:---:|:---:|:---:|
| Vertical shift | $y = f(x) + a$ | Shift up by $a$ units |
| Horizontal shift | $y = f(x + a)$ | Shift left by $a$ units |

> **Note:** $y = f(x + a)$ shifts **left** (intuitive opposite!)

### 2.8.2 Stretches

| Transformation | Rule | Effect |
|:---:|:---:|:---:|
| Vertical stretch | $y = af(x)$ | Stretch vertically by factor $a$ |
| Horizontal stretch | $y = f(ax)$ | Compress horizontally by factor $\frac{1}{a}$ |

---

### ⭐ Paper 4 — Worked Example

**Question:** The graph of $y = f(x)$ passes through $(0,2)$, $(2,0)$, $(4,4)$.  
Find the new coordinates after:

**(a)** $y = f(x) + 3$

**(b)** $y = f(x - 2)$

**(c)** $y = 2f(x)$

**(d)** $y = f(2x)$

**Solution:**

| Transformation | Rule | New points |
|:---:|:---:|:---:|
| **(a)** $y=f(x)+3$ | Up 3 | $(0,5)$, $(2,3)$, $(4,7)$ |
| **(b)** $y=f(x-2)$ | Right 2 | $(2,2)$, $(4,0)$, $(6,4)$ |
| **(c)** $y=2f(x)$ | Vertical ×2 | $(0,4)$, $(2,0)$, $(4,8)$ |
| **(d)** $y=f(2x)$ | Horizontal ÷2 | $(0,2)$, $(1,0)$, $(2,4)$ |

---

### ⭐ Paper 6 — Investigation

**Question:** Given $f(x) = x^2$, investigate whether the order of transformations affects the final result.

**(a)** Does "$y = f(x) + 2$ then $y = f(x-3)$" give the same result as "$y = f(x-3)$ then $y = f(x) + 2$"?

**(b)** Does "$y = 2f(x)$ then $y = f(x) + 1$" give the same result as "$y = f(x) + 1$ then $y = 2f(x)$"?

**Solution:**

**(a)**
- Order 1: Up 2 → $y = x^2 + 2$, then right 3 → $y = (x-3)^2 + 2$ ✅
- Order 2: Right 3 → $y = (x-3)^2$, then up 2 → $y = (x-3)^2 + 2$ ✅

**Same result!** 🎉 Translations are commutative.

**(b)**
- Order 1: Stretch ×2 → $y = 2x^2$, then up 1 → $y = 2x^2 + 1$ 🅰
- Order 2: Up 1 → $y = x^2 + 1$, then stretch ×2 → $y = 2(x^2 + 1) = 2x^2 + 2$ 🅱

**Different results!** 🅰 ≠ 🅱

**Conclusion:** The order of translations and stretches **matters** — stretches and translations are not commutative! ⚠️

---

## 2.9 Introduction to Calculus 🧠

### 2.9.1 Derivative as a Rate of Change

The derivative $f'(x)$ represents the instantaneous rate of change of $f(x)$ at point $x$. Geometrically, it is the **gradient of the tangent** at that point.

### 2.9.2 Differentiation Rules

**Power rule:** For $f(x) = x^n$, where $n$ is any integer or fraction:

$$
\frac{d}{dx}(x^n) = nx^{n-1}
$$

> **Examples:**
> $$
> f(x) = x^5 \implies f'(x) = 5x^4
> $$
> $$
> f(x) = \sqrt{x} = x^{\frac{1}{2}} \implies f'(x) = \frac{1}{2}x^{-\frac{1}{2}} = \frac{1}{2\sqrt{x}}
> $$

**Polynomial differentiation:**

$$
\frac{d}{dx}(ax^n + bx^m) = anx^{n-1} + bmx^{m-1}
$$

> **Example:** $f(x) = 3x^4 - 2x^3 + 5x - 7$
> $$
> f'(x) = 12x^3 - 6x^2 + 5
> $$

### 2.9.3 Equation of a Tangent

**Steps:**
1. Find gradient $m = f'(x_1)$ at the point
2. Use point-slope form: $y - y_1 = m(x - x_1)$

> **Example:** Tangent to $f(x) = x^2$ at $(2,4)$
> $$
> f'(x) = 2x \implies m = 4
> $$
> $$
> y - 4 = 4(x - 2) \implies y = 4x - 4
> $$

### 2.9.4 Stationary Points & Optimisation

**Stationary points:** where $f'(x) = 0$

**Second derivative test:**
- $f''(x) > 0$ → minimum point 🟢
- $f''(x) < 0$ → maximum point 🔴

> **Example:** $f(x) = x^2 - 6x + 10$
> $$
> f'(x) = 2x - 6 = 0 \implies x = 3
> $$
> $$
> f''(x) = 2 > 0 \implies \text{minimum}
> $$
> Minimum value: $f(3) = 1$

---

### ⭐ Paper 4 — Worked Example

**Question:** Given $f(x) = 2x^3 - 9x^2 + 12x - 5$.

**(a)** Find $f'(x)$.

**(b)** Find the stationary points and determine their nature.

**(c)** Find the equation of the tangent at $x = 1$.

**Solution:**

**(a)**
$$
f'(x) = 6x^2 - 18x + 12
$$

**(b)** Set $f'(x) = 0$:

$$
6x^2 - 18x + 12 = 0 \implies x^2 - 3x + 2 = 0 \implies (x-1)(x-2) = 0
$$

$$
x = 1 \quad \text{or} \quad x = 2
$$

Second derivative: $f''(x) = 12x - 18$

- $x = 1$: $f''(1) = -6 < 0$ → **Maximum** 🔴  
  $f(1) = 2 - 9 + 12 - 5 = 0$ → $(1,0)$
- $x = 2$: $f''(2) = 6 > 0$ → **Minimum** 🟢  
  $f(2) = 16 - 36 + 24 - 5 = -1$ → $(2,-1)$

**(c)** At $x = 1$: $f(1) = 0$, $f'(1) = 0$

Tangent: $y - 0 = 0(x - 1)$ → $y = 0$ (horizontal, since it's a stationary point)

---

### ⭐ Paper 4 — Optimisation Problem

**Question:** A rectangular piece of cardboard measuring 30 cm by 20 cm has squares of side $x$ cm cut from each corner. It is folded to form an open box.

**(a)** Express the volume $V$ of the box in terms of $x$.

**(b)** Find the value of $x$ that maximises the volume, and the maximum volume.

**Solution:**

**(a)** Length $= 30 - 2x$, width $= 20 - 2x$, height $= x$

$$
\begin{aligned}
V(x) &= x(30 - 2x)(20 - 2x) \\
&= x(600 - 100x + 4x^2) \\
&= 4x^3 - 100x^2 + 600x
\end{aligned}
$$

Domain: $0 < x < 10$ (since $20 - 2x > 0$)

**(b)** $V'(x) = 12x^2 - 200x + 600$

Set $V'(x) = 0$:

$$
12x^2 - 200x + 600 = 0 \implies 3x^2 - 50x + 150 = 0
$$

$$
x = \frac{50 \pm \sqrt{2500 - 1800}}{6} = \frac{50 \pm \sqrt{700}}{6} = \frac{50 \pm 10\sqrt{7}}{6}
$$

$$
x_1 = \frac{50 + 10\sqrt{7}}{6} \approx 12.74\;(\text{reject, outside domain})
$$

$$
x_2 = \frac{50 - 10\sqrt{7}}{6} \approx 3.93
$$

**Check:** $V''(x) = 24x - 200$

$V''(3.93) = 24(3.93) - 200 = -105.68 < 0$ → **Maximum** ✅

Maximum volume:
$$
V(3.93) \approx 3.93(30 - 7.86)(20 - 7.86) \approx \mathbf{1056.4 \text{ cm}^3}
$$

---

### ⭐ Paper 6 — Investigation (Rate of Change)

**Question:** A spherical balloon is being inflated. The radius $r$ increases at a constant rate of 2 cm/s.

**(a)** Write the formula for the volume $V$ of the sphere in terms of $r$.

**(b)** Find $\dfrac{dV}{dr}$ and interpret its meaning.

**(c)** Find the rate of change of volume $\dfrac{dV}{dt}$ when $r = 5$ cm.

**(d)** When the volume is $288\pi$ cm³, find $\dfrac{dV}{dt}$.

**Solution:**

**(a)**
$$
V = \frac{4}{3}\pi r^3
$$

**(b)**
$$
\frac{dV}{dr} = 4\pi r^2
$$

Interpretation: This is the **surface area** of the sphere — the rate at which volume increases per unit increase in radius.

**(c)** Using the chain rule: $\dfrac{dV}{dt} = \dfrac{dV}{dr} \times \dfrac{dr}{dt}$

Given $\dfrac{dr}{dt} = 2$ cm/s:

When $r = 5$: $\dfrac{dV}{dr} = 4\pi(25) = 100\pi$

$$
\frac{dV}{dt} = 100\pi \times 2 = 200\pi \text{ cm}^3/\text{s}
$$

**(d)** When $V = 288\pi$:

$$
\frac{4}{3}\pi r^3 = 288\pi \implies r^3 = 216 \implies r = 6
$$

$$
\frac{dV}{dr} = 4\pi(36) = 144\pi
$$

$$
\frac{dV}{dt} = 144\pi \times 2 = 288\pi \text{ cm}^3/\text{s}
$$

**Observation:** When $r = 6$, the rate of change of volume equals the volume itself ($288\pi$)! 🎯

---

# 3. Coordinate Geometry 📐

---

## 3.1 Distance and Midpoint

**Distance between two points:**
$$
d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
$$

**Midpoint:**
$$
M = \left(\frac{x_1 + x_2}{2},\; \frac{y_1 + y_2}{2}\right)
$$

## 3.2 Gradient and Equation of a Straight Line

**Gradient:**
$$
m = \frac{y_2 - y_1}{x_2 - x_1}
$$

**Equation forms:**
- Slope-intercept: $y = mx + c$
- General: $ax + by = c$
- Point-slope: $y - y_1 = m(x - x_1)$

## 3.3 Parallel and Perpendicular Lines

**Parallel:** $m_1 = m_2$

**Perpendicular:** $m_1 \times m_2 = -1$ (i.e. $m_2 = -\dfrac{1}{m_1}$)

## 3.4 Intersection of Line and Curve

Substitute the line equation into the curve equation and solve.

> **Example:** Line $y = x + 2$ and curve $y = x^2$
> $$
> x + 2 = x^2 \implies x^2 - x - 2 = 0 \implies (x-2)(x+1) = 0
> $$
> Intersection points: $(2,4)$ and $(-1,1)$.

---

### ⭐ Paper 4 — Worked Example

**Question:** Points $A(2,3)$, $B(6,5)$, $C(4,8)$, $D(0,6)$ form quadrilateral $ABCD$.

**(a)** Show that $ABCD$ is a parallelogram.

**(b)** Find the intersection point of diagonals $AC$ and $BD$.

**Solution:**

**(a)** Compute slopes:

$$
m_{AB} = \frac{5-3}{6-2} = \frac{1}{2},\qquad m_{DC} = \frac{8-6}{4-0} = \frac{1}{2}
$$

$$
m_{BC} = \frac{8-5}{4-6} = -\frac{3}{2},\qquad m_{AD} = \frac{6-3}{0-2} = -\frac{3}{2}
$$

$AB \parallel DC$ and $BC \parallel AD$ → $ABCD$ is a parallelogram. ✅

**(b)** Midpoint of $AC$:
$$
M_{AC} = \left(\frac{2+4}{2},\; \frac{3+8}{2}\right) = (3, 5.5)
$$

Midpoint of $BD$:
$$
M_{BD} = \left(\frac{6+0}{2},\; \frac{5+6}{2}\right) = (3, 5.5)
$$

Intersection: $(3, 5.5)$ ✅ (Parallelogram diagonals bisect each other.)

---

### ⭐ Paper 4 — Worked Example 2

**Question:** Line $L_1$ passes through $A(3, -2)$ and is perpendicular to $L_2: 2x + 3y = 12$.

**(a)** Find the gradient of $L_2$.

**(b)** Find the equation of $L_1$.

**(c)** Find the intersection of $L_1$ and $L_2$.

**Solution:**

**(a)**
$$
2x + 3y = 12 \implies 3y = -2x + 12 \implies y = -\frac{2}{3}x + 4
$$

$$
m_2 = -\frac{2}{3}
$$

**(b)** Perpendicular condition: $m_1 \times m_2 = -1$

$$
m_1 \times \left(-\frac{2}{3}\right) = -1 \implies m_1 = \frac{3}{2}
$$

Point-slope: $y - (-2) = \frac{3}{2}(x - 3)$

$$
y + 2 = \frac{3}{2}x - \frac{9}{2} \implies y = \frac{3}{2}x - \frac{13}{2}
$$

Or: $3x - 2y = 13$

**(c)** Solve simultaneously:
$$
\begin{cases}
2x + 3y = 12 \quad \text{...①}\\
3x - 2y = 13 \quad \text{...②}
\end{cases}
$$

①×2: $4x + 6y = 24$  
②×3: $9x - 6y = 39$

Add: $13x = 63 \implies x = \dfrac{63}{13}$

Substitute into ①: $2\left(\dfrac{63}{13}\right) + 3y = 12$

$$
\frac{126}{13} + 3y = 12 \implies 3y = \frac{30}{13} \implies y = \frac{10}{13}
$$

Intersection: $\displaystyle \left(\frac{63}{13},\; \frac{10}{13}\right)$ ✅

---

### ⭐ Paper 6 — Investigation (Centroid of a Triangle)

**Question:** Triangle $ABC$ has vertices $A(1,2)$, $B(5,4)$, $C(3,8)$. The centroid $G$ is the intersection of the three medians.

**(a)** Find $M$, the midpoint of $BC$.

**(b)** Find the equation of median $AM$.

**(c)** Find the equation of median $BN$ (where $N$ is the midpoint of $AC$).

**(d)** Find the intersection $G$ of $AM$ and $BN$.

**(e)** State a formula for the centroid in terms of the vertices.

**(f)** Verify that $AG : GM = 2 : 1$.

**Solution:**

**(a)**
$$
M = \left(\frac{5+3}{2},\; \frac{4+8}{2}\right) = (4, 6)
$$

**(b)** Median $AM$ passes through $A(1,2)$ and $M(4,6)$:

$$
m_{AM} = \frac{6-2}{4-1} = \frac{4}{3}
$$

$$
y - 2 = \frac{4}{3}(x - 1) \implies y = \frac{4}{3}x + \frac{2}{3}
$$

**(c)** $N = \left(\frac{1+3}{2},\; \frac{2+8}{2}\right) = (2, 5)$

Median $BN$ passes through $B(5,4)$ and $N(2,5)$:

$$
m_{BN} = \frac{5-4}{2-5} = -\frac{1}{3}
$$

$$
y - 4 = -\frac{1}{3}(x - 5) \implies y = -\frac{1}{3}x + \frac{17}{3}
$$

**(d)** Intersection:
$$
\frac{4}{3}x + \frac{2}{3} = -\frac{1}{3}x + \frac{17}{3} \implies 4x + 2 = -x + 17 \implies 5x = 15 \implies x = 3
$$

$$
y = \frac{4}{3}(3) + \frac{2}{3} = \frac{14}{3}
$$

Centroid $G\left(3,\; \dfrac{14}{3}\right)$ ✅

**(e)**
$$
G = \left(\frac{x_1 + x_2 + x_3}{3},\; \frac{y_1 + y_2 + y_3}{3}\right)
$$

Verify: $\frac{1+5+3}{3} = 3$, $\frac{2+4+8}{3} = \frac{14}{3}$ ✔

**(f)** $A(1,2)$, $G(3,\frac{14}{3})$, $M(4,6)$

$$
AG = \sqrt{(3-1)^2 + \left(\frac{14}{3} - 2\right)^2} = \sqrt{4 + \left(\frac{8}{3}\right)^2} = \sqrt{4 + \frac{64}{9}} = \sqrt{\frac{100}{9}} = \frac{10}{3}
$$

$$
GM = \sqrt{(4-3)^2 + \left(6 - \frac{14}{3}\right)^2} = \sqrt{1 + \left(\frac{4}{3}\right)^2} = \sqrt{1 + \frac{16}{9}} = \sqrt{\frac{25}{9}} = \frac{5}{3}
$$

$$
AG : GM = \frac{10}{3} : \frac{5}{3} = 2 : 1 \quad ✅
$$

---

# 4. Geometry 🟠

---

## 4.1 Geometrical Terms

| Angle Type | Range |
|:---:|:---:|
| Acute | $0^\circ < \theta < 90^\circ$ |
| Right | $\theta = 90^\circ$ |
| Obtuse | $90^\circ < \theta < 180^\circ$ |
| Straight | $\theta = 180^\circ$ |
| Reflex | $180^\circ < \theta < 360^\circ$ |

**Triangle types:** equilateral, isosceles, scalene, right-angled, acute, obtuse  
**Special quadrilaterals:** square, rectangle, parallelogram, rhombus, trapezium, kite  
**Circle parts:** centre, radius, diameter, chord, arc, sector, tangent, segment

## 4.2 Geometrical Constructions

- **Construct a triangle (SSS):** Use compass to draw arcs at given distances
- **Nets:** Know nets of cubes (11 variations), prisms, and pyramids

## 4.3 Similarity and Congruence

### Similarity Criteria

| Criterion | Meaning |
|:---:|:---:|
| AA | Two angles equal |
| SAS | Two sides in proportion and included angle equal |
| SSS | All three sides in proportion |

### Scale Factors

- **Length ratio:** $k$
- **Area ratio:** $k^2$
- **Volume ratio:** $k^3$

## 4.4 Symmetry

**Line symmetry:** Folding along a line produces identical halves

**Rotational symmetry:** The figure looks the same after a rotation of less than $360^\circ$  
**Order:** The number of distinct positions in one full rotation

## 4.5 Angle Properties

- Angles around a point sum to $360^\circ$
- Angles on a straight line sum to $180^\circ$
- Vertically opposite angles are equal
- Parallel lines: corresponding angles equal, alternate angles equal, co-interior angles sum to $180^\circ$
- Triangle interior angle sum: $180^\circ$
- Quadrilateral interior angle sum: $360^\circ$
- **Polygon exterior angle sum: $360^\circ$** (always!)
- Interior angle of a regular $n$-gon: $\dfrac{(n-2) \times 180^\circ}{n}$

---

### ⭐ Paper 4 — Worked Example

**Question:** A regular polygon has interior angle $156^\circ$.

**(a)** Find the number of sides $n$.

**(b)** Find the exterior angle.

**(c)** Find the number of diagonals.

**Solution:**

**(a)**
$$
\frac{(n-2) \times 180^\circ}{n} = 156^\circ \implies 180n - 360 = 156n \implies 24n = 360 \implies n = 15
$$

It's a regular **15-gon**!

**(b)** Exterior angle $= 180^\circ - 156^\circ = 24^\circ$  
(or $\frac{360^\circ}{15} = 24^\circ$) ✅

**(c)** Number of diagonals $= \frac{n(n-3)}{2} = \frac{15 \times 12}{2} = 90$ ✅

---

## 4.6 Circle Theorems 🌀

| # | Theorem | Diagram | Statement |
|:---:|:---:|:---:|:---:|
| 1 | Thales' Theorem | Diameter + point on circle | Angle in semicircle $= 90^\circ$ |
| 2 | Same segment | Two angles on same chord | Angles in same segment are equal |
| 3 | Central angle | Centre + circumference | Central angle $= 2 \times$ inscribed angle |
| 4 | Cyclic quadrilateral | Quadrilateral on circle | Opposite angles sum to $180^\circ$ |
| 5 | Tangent-radius | Tangent at point of contact | Tangent $\perp$ radius |
| 6 | Tangent lengths | Two tangents from a point | Tangent lengths are equal |
| 7 | Alternate segment | Tangent + chord | Angle between tangent and chord $=$ angle in alternate segment |

---

### ⭐ Paper 4 — Worked Example

**Question:** In circle $O$, $AC$ is a diameter. $\angle BAC = 32^\circ$. Points $A$, $B$, $C$, $D$ lie on the circumference.

**(a)** Find $\angle ABC$.

**(b)** Find $\angle BCA$.

**(c)** If $\angle BDC = 58^\circ$, find $\angle CBD$.

**Solution:**

**(a)** $AC$ is diameter → Thales' Theorem:

$$
\angle ABC = 90^\circ
$$

**(b)** In $\triangle ABC$:

$$
\angle BCA = 180^\circ - 90^\circ - 32^\circ = 58^\circ
$$

**(c)** $\angle BAC = 32^\circ$ and $\angle BDC = 58^\circ$  
Both subtend different arcs. In $\triangle BCD$:

$\angle BCD = \angle BCA = 58^\circ$ (same segment $AB$)

In $\triangle BCD$:
$$
\angle CBD = 180^\circ - 58^\circ - 58^\circ = 64^\circ
$$

---

### ⭐ Paper 4 — Worked Example 2 (Tangents)

**Question:** $PA$ and $PB$ are tangents to circle $O$ at $A$ and $B$. $\angle APB = 50^\circ$.

**(a)** Find $\angle AOB$.

**(b)** Find $\angle OAB$.

**(c)** Find $\angle ACB$, where $C$ is a point on the major arc $AB$.

**Solution:**

**(a)** Tangent-radius theorem: $\angle OAP = \angle OBP = 90^\circ$

In quadrilateral $OAPB$:
$$
90^\circ + 90^\circ + 50^\circ + \angle AOB = 360^\circ \implies \angle AOB = 130^\circ
$$

**(b)** $\triangle OAB$ is isosceles ($OA = OB$ = radii):

$$
\angle OAB = \frac{180^\circ - 130^\circ}{2} = 25^\circ
$$

**(c)** Central angle $\angle AOB = 130^\circ$ subtends arc $AB$.

For point $C$ on the major arc, $\angle ACB$ subtends the minor arc $AB$:

$$
\angle ACB = \frac{1}{2} \times 130^\circ = 65^\circ
$$

---

## 4.7 Vectors ➡️

### 4.7.1 Vector Representation

A 2D vector: $\displaystyle \vec{v} = \begin{pmatrix}x\\y\end{pmatrix}$

### 4.7.2 Vector Operations

- **Addition:** $\vec{a} + \vec{b} = \begin{pmatrix}a_1 + b_1\\a_2 + b_2\end{pmatrix}$
- **Subtraction:** $\vec{a} - \vec{b} = \begin{pmatrix}a_1 - b_1\\a_2 - b_2\end{pmatrix}$
- **Scalar multiplication:** $k\vec{a} = \begin{pmatrix}ka_1\\ka_2\end{pmatrix}$
- **Magnitude:** $|\vec{a}| = \sqrt{a_1^2 + a_2^2}$

### 4.7.3 Position Vectors

$\overrightarrow{AB} = \vec{b} - \vec{a}$, where $\vec{a}$ and $\vec{b}$ are position vectors of $A$ and $B$.

**Parallel condition:** $\vec{a} \parallel \vec{b}$ if $\vec{a} = k\vec{b}$ for some scalar $k$.

**Collinear points:** $A$, $B$, $C$ are collinear if $\overrightarrow{AB} = k\overrightarrow{AC}$.

---

### ⭐ Paper 4 — Worked Example

**Question:** Given $\vec{a} = \begin{pmatrix}3\\-2\end{pmatrix}$, $\vec{b} = \begin{pmatrix}-1\\4\end{pmatrix}$.

**(a)** Find $2\vec{a} - 3\vec{b}$.

**(b)** Find $|\vec{a}|$ and $|\vec{b}|$.

**(c)** Find $k$ such that $\vec{a} + k\vec{b}$ is parallel to $\begin{pmatrix}1\\-2\end{pmatrix}$.

**Solution:**

**(a)**
$$
2\vec{a} - 3\vec{b} = 2\begin{pmatrix}3\\-2\end{pmatrix} - 3\begin{pmatrix}-1\\4\end{pmatrix} = \begin{pmatrix}6\\-4\end{pmatrix} - \begin{pmatrix}-3\\12\end{pmatrix} = \begin{pmatrix}9\\-16\end{pmatrix}
$$

**(b)**
$$
|\vec{a}| = \sqrt{3^2 + (-2)^2} = \sqrt{13},\qquad |\vec{b}| = \sqrt{(-1)^2 + 4^2} = \sqrt{17}
$$

**(c)**
$$
\vec{a} + k\vec{b} = \begin{pmatrix}3\\-2\end{pmatrix} + k\begin{pmatrix}-1\\4\end{pmatrix} = \begin{pmatrix}3 - k\\-2 + 4k\end{pmatrix}
$$

Parallel condition: $\begin{pmatrix}3-k\\-2+4k\end{pmatrix} = t\begin{pmatrix}1\\-2\end{pmatrix}$

$$
\frac{3-k}{1} = \frac{-2+4k}{-2} \implies -2(3-k) = -2 + 4k \implies -6 + 2k = -2 + 4k \implies -4 = 2k \implies k = -2
$$

---

### ⭐ Paper 4 — Worked Example 2 (Geometric Proof)

**Question:** In triangle $OAB$, $\overrightarrow{OA} = \vec{a}$, $\overrightarrow{OB} = \vec{b}$.  
$P$ lies on $AB$ such that $AP : PB = 2 : 1$.  
$Q$ lies on $OP$ such that $OQ : QP = 3 : 2$.

**(a)** Express $\overrightarrow{OP}$ in terms of $\vec{a}$ and $\vec{b}$.

**(b)** Express $\overrightarrow{OQ}$ in terms of $\vec{a}$ and $\vec{b}$.

**Solution:**

**(a)** $\overrightarrow{AB} = \vec{b} - \vec{a}$

Since $AP : PB = 2 : 1$, $AP = \frac{2}{3}AB$:

$$
\overrightarrow{OP} = \vec{a} + \frac{2}{3}(\vec{b} - \vec{a}) = \frac{1}{3}\vec{a} + \frac{2}{3}\vec{b}
$$

**(b)** $OQ : QP = 3 : 2$, so $OQ = \frac{3}{5}OP$:

$$
\overrightarrow{OQ} = \frac{3}{5}\left(\frac{1}{3}\vec{a} + \frac{2}{3}\vec{b}\right) = \frac{1}{5}\vec{a} + \frac{2}{5}\vec{b}
$$

---

# 5. Mensuration 📏

---

## 5.1 Unit Conversion

| Conversion | Factor |
|:---:|:---:|
| $1 \text{ m}^2$ | $10\,000 \text{ cm}^2$ |
| $1 \text{ km}^2$ | $1\,000\,000 \text{ m}^2$ |
| $1 \text{ m}^3$ | $1\,000\,000 \text{ cm}^3$ |
| $1 \text{ litre}$ | $1000 \text{ cm}^3$ |

## 5.2 Perimeter and Area

| Shape | Perimeter | Area |
|:---:|:---:|:---:|
| Rectangle | $2(l + w)$ | $lw$ |
| Triangle | $a + b + c$ | $\frac{1}{2}bh$ |
| Parallelogram | $2(a+b)$ | $bh$ |
| Trapezium | $a + b + c + d$ | $\frac{1}{2}(a+b)h$ |
| Circle | $2\pi r$ | $\pi r^2$ |

## 5.3 Arc Length and Sector Area

For a sector with angle $\theta^\circ$:

$$
\text{Arc length} = \frac{\theta}{360} \times 2\pi r,\qquad \text{Sector area} = \frac{\theta}{360} \times \pi r^2
$$

## 5.4 Surface Area and Volume

| Solid | Surface Area | Volume |
|:---:|:---:|:---:|
| Cube | $6s^2$ | $s^3$ |
| Cuboid | $2(lw + wh + lh)$ | $lwh$ |
| Prism | $2A + Ph$ | $Ah$ |
| Cylinder | $2\pi r^2 + 2\pi rh$ | $\pi r^2 h$ |
| Cone | $\pi r^2 + \pi rl$ | $\frac{1}{3}\pi r^2 h$ |
| Sphere | $4\pi r^2$ | $\frac{4}{3}\pi r^3$ |
| Pyramid | $A + \text{sum of lateral faces}$ | $\frac{1}{3}Ah$ |

---

### ⭐ Paper 4 — Worked Example

**Question:** An ice cream consists of a cone (radius 4 cm, height 12 cm) topped with a hemisphere of the same radius.

**(a)** Find the total volume.

**(b)** If the cone is eaten down to half its height, find the remaining volume.

**(c)** If the melted ice cream exactly fills a sphere of radius 3 cm, does the original volume fit?

**Solution:**

**(a)** Cone volume:
$$
V_{\text{cone}} = \frac{1}{3}\pi(4^2)(12) = 64\pi
$$

Hemisphere volume:
$$
V_{\text{hemi}} = \frac{2}{3}\pi(4^3) = \frac{128}{3}\pi
$$

Total:
$$
V = 64\pi + \frac{128}{3}\pi = \frac{320}{3}\pi \approx 335.1 \text{ cm}^3
$$

**(b)** Remaining cone height $= 6$ cm. By similarity, radius $r' = \frac{6}{12} \times 4 = 2$ cm.

Remaining cone volume:
$$
V'_{\text{cone}} = \frac{1}{3}\pi(2^2)(6) = 8\pi
$$

Hemisphere unchanged: $\frac{128}{3}\pi$

Remaining total:
$$
V' = 8\pi + \frac{128}{3}\pi = \frac{152}{3}\pi \approx 159.2 \text{ cm}^3
$$

**(c)** Sphere volume:
$$
V_{\text{sphere}} = \frac{4}{3}\pi(27) = 36\pi \approx 113.1 \text{ cm}^3
$$

Original volume $\frac{320}{3}\pi \approx 335.1 \text{ cm}^3 > 113.1 \text{ cm}^3$

**No, it won't fit!** 😅

---

# 6. Trigonometry 📐

---

## 6.1 Right-Angled Triangles

### Pythagoras' Theorem

$$
a^2 + b^2 = c^2
$$

where $c$ is the hypotenuse.

### SOH CAH TOA

$$
\sin\theta = \frac{\text{opposite}}{\text{hypotenuse}},\quad
\cos\theta = \frac{\text{adjacent}}{\text{hypotenuse}},\quad
\tan\theta = \frac{\text{opposite}}{\text{adjacent}}
$$

### Angles of Elevation/Depression & Bearings

- **Angle of elevation:** measured **up** from horizontal
- **Angle of depression:** measured **down** from horizontal
- **Bearings:** measured clockwise from north, given as three-digit numbers

## 6.2 Exact Trigonometric Values

$$
\begin{array}{c|ccc}
\theta & \sin\theta & \cos\theta & \tan\theta \\ \hline
0^\circ & 0 & 1 & 0 \\
30^\circ & \frac{1}{2} & \frac{\sqrt{3}}{2} & \frac{1}{\sqrt{3}} \\
45^\circ & \frac{\sqrt{2}}{2} & \frac{\sqrt{2}}{2} & 1 \\
60^\circ & \frac{\sqrt{3}}{2} & \frac{1}{2} & \sqrt{3} \\
90^\circ & 1 & 0 & \text{undefined}
\end{array}
$$

## 6.3 Non-Right-Angled Triangles

**Sine Rule:**
$$
\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C}
$$

**Cosine Rule:**
$$
a^2 = b^2 + c^2 - 2bc\cos A
$$

**Area Formula:**
$$
\text{Area} = \frac{1}{2}ab\sin C
$$

**Ambiguous Case (SSA):** When given two sides and a non-included angle, there may be two possible triangles.

## 6.4 Trigonometric Graphs

**Key properties:**
- $\sin x$ and $\cos x$: period $360^\circ$, range $[-1, 1]$
- $\tan x$: period $180^\circ$, range $\mathbb{R}$

**Key points on $y = \sin x$ ($0^\circ$ to $360^\circ$):**

| $x$ | $0^\circ$ | $90^\circ$ | $180^\circ$ | $270^\circ$ | $360^\circ$ |
|:---:|:---:|:---:|:---:|:---:|:---:|
| $\sin x$ | 0 | 1 | 0 | $-1$ | 0 |

**Key points on $y = \cos x$ ($0^\circ$ to $360^\circ$):**

| $x$ | $0^\circ$ | $90^\circ$ | $180^\circ$ | $270^\circ$ | $360^\circ$ |
|:---:|:---:|:---:|:---:|:---:|:---:|
| $\cos x$ | 1 | 0 | $-1$ | 0 | 1 |

### Solving Trigonometric Equations

**General solutions in $0^\circ \le \theta \le 360^\circ$:**

| Equation | Solutions |
|:---:|:---:|
| $\sin\theta = k$ | $\theta_1$ and $180^\circ - \theta_1$ |
| $\cos\theta = k$ | $\theta_1$ and $360^\circ - \theta_1$ |
| $\tan\theta = k$ | $\theta_1$ and $\theta_1 + 180^\circ$ |

where $\theta_1$ is the principal value from the calculator.

## 6.5 Trigonometry in 3D

**Key technique:** Construct right-angled triangles within the 3D solid.

To find:
- **Angle between a line and a plane:** Find the projection of the line onto the plane
- **Angle between two lines:** Translate to form a triangle, then use cosine rule

---

### ⭐ Paper 4 — Worked Example

**Question:** In $\triangle ABC$, $AB = 8$ cm, $BC = 10$ cm, $\angle ABC = 60^\circ$.

**(a)** Find $AC$.

**(b)** Find $\angle BAC$.

**(c)** Find the area of $\triangle ABC$.

**Solution:**

**(a)** Using cosine rule:

$$
\begin{aligned}
AC^2 &= 8^2 + 10^2 - 2(8)(10)\cos 60^\circ \\
&= 64 + 100 - 160 \times \frac{1}{2} \\
&= 164 - 80 = 84
\end{aligned}
$$

$$
AC = \sqrt{84} = 2\sqrt{21} \approx 9.17 \text{ cm}
$$

**(b)** Using sine rule:

$$
\frac{\sin\angle BAC}{10} = \frac{\sin 60^\circ}{\sqrt{84}}
$$

$$
\sin\angle BAC = \frac{10 \times \frac{\sqrt{3}}{2}}{\sqrt{84}} = \frac{5\sqrt{3}}{\sqrt{84}} \approx 0.9449
$$

$$
\angle BAC \approx 70.9^\circ
$$

**(c)**
$$
\text{Area} = \frac{1}{2}(8)(10)\sin 60^\circ = 40 \times \frac{\sqrt{3}}{2} = 20\sqrt{3} \approx 34.64 \text{ cm}^2
$$

---

### ⭐ Paper 4 — Ambiguous Case

**Question:** In $\triangle PQR$, $PQ = 6$ cm, $QR = 8$ cm, $\angle PRQ = 35^\circ$.  
Find the possible values of $\angle PQR$.

**Solution:**

Using sine rule:

$$
\frac{\sin\angle PQR}{8} = \frac{\sin 35^\circ}{6}
$$

$$
\sin\angle PQR = \frac{8\sin 35^\circ}{6} \approx \frac{8 \times 0.5736}{6} \approx 0.7648
$$

**Possible solution 1:** $\angle PQR = \sin^{-1}(0.7648) \approx 49.9^\circ$ ✅

**Possible solution 2:** $\angle PQR = 180^\circ - 49.9^\circ = 130.1^\circ$ ✅  
(Third angle $= 180^\circ - 35^\circ - 130.1^\circ = 14.9^\circ > 0$, valid!)

Two possible triangles exist — this is the **ambiguous case**. 🎯

---

### ⭐ Paper 4 — Trigonometric Equations

**Question:** Solve $2\sin x + 1 = 0$ for $0^\circ \le x \le 360^\circ$.

**Solution:**

$$
2\sin x + 1 = 0 \implies \sin x = -\frac{1}{2}
$$

Principal value: $\sin^{-1}\left(\frac{1}{2}\right) = 30^\circ$

Since sine is negative in QIII and QIV:

$$
x = 180^\circ + 30^\circ = 210^\circ,\qquad x = 360^\circ - 30^\circ = 330^\circ
$$

$$
\therefore x = 210^\circ,\; 330^\circ
$$

---

### ⭐ Paper 4 — Quadratic Trigonometric Equation

**Question:** Solve $3\cos^2 x - \cos x - 2 = 0$ for $0^\circ \le x \le 360^\circ$.

**Solution:** Let $u = \cos x$:

$$
3u^2 - u - 2 = 0 \implies (3u + 2)(u - 1) = 0 \implies u = -\frac{2}{3} \text{ or } u = 1
$$

**Case 1:** $\cos x = 1$ → $x = 0^\circ$ or $x = 360^\circ$

**Case 2:** $\cos x = -\frac{2}{3}$

Principal angle: $\cos^{-1}\left(\frac{2}{3}\right) \approx 48.2^\circ$

Since cosine is negative in QII and QIII:

$$
x = 180^\circ - 48.2^\circ = 131.8^\circ,\qquad x = 180^\circ + 48.2^\circ = 228.2^\circ
$$

$$
\therefore x = 0^\circ,\; 131.8^\circ,\; 228.2^\circ,\; 360^\circ
$$

---

### ⭐ Paper 4 — Trigonometry in 3D

**Question:** A right square pyramid $S-ABCD$ has base $ABCD$ of side 6 cm and slant edges of length 10 cm.

**(a)** Find the height $SO$ (where $O$ is the centre of the base).

**(b)** Find the angle between $SA$ and the base plane.

**(c)** Find the angle between plane $SAB$ and the base plane.

**Solution:**

**(a)** Diagonal of base: $AC = 6\sqrt{2}$, so $AO = 3\sqrt{2}$

In $\triangle SAO$:

$$
SO = \sqrt{SA^2 - AO^2} = \sqrt{100 - 18} = \sqrt{82} \approx 9.06 \text{ cm}
$$

**(b)** Angle between $SA$ and base is $\angle SAO$:

$$
\cos\angle SAO = \frac{AO}{SA} = \frac{3\sqrt{2}}{10} \approx 0.4243
$$

$$
\angle SAO = \cos^{-1}(0.4243) \approx 64.9^\circ
$$

**(c)** Let $M$ be midpoint of $AB$. Then $SM \perp AB$ and $OM \perp AB$, so $\angle SMO$ is the required angle.

$OM = 3$ cm (distance from centre to side)

$SM = \sqrt{SA^2 - AM^2} = \sqrt{100 - 9} = \sqrt{91} \approx 9.54$ cm

$$
\cos\angle SMO = \frac{OM}{SM} = \frac{3}{\sqrt{91}} \approx 0.3145
$$

$$
\angle SMO = \cos^{-1}(0.3145) \approx 71.7^\circ
$$

---

# 7. Transformations and Vectors 🔄

---

## 7.1 Transformations

| Type | Description | Matrix (if applicable) |
|:---:|:---:|:---:|
| Reflection | Mirror image over a line | e.g. $y$-axis: $\begin{pmatrix}-1&0\\0&1\end{pmatrix}$ |
| Rotation | Turn about a centre by $\theta^\circ$ | e.g. $90^\circ$ CCW: $\begin{pmatrix}0&-1\\1&0\end{pmatrix}$ |
| Translation | Slide by vector $\begin{pmatrix}a\\b\end{pmatrix}$ | Vector addition |
| Enlargement | Scale by factor $k$ (can be negative/fractional) | $\begin{pmatrix}k&0\\0&k\end{pmatrix}$ |

## 7.2 Vector Operations & Geometric Proofs

Use vectors to prove:
- **Parallel:** $\overrightarrow{AB} = k\overrightarrow{CD}$
- **Collinear:** $\overrightarrow{AB} = k\overrightarrow{AC}$
- **Ratio points:** Express using section formula

---

### ⭐ Paper 4 — Worked Example

**Question:** Triangle $A$ has vertices $(1,1)$, $(3,1)$, $(2,3)$.

**(a)** Reflect $A$ in the $y$-axis to get $B$. Find $B$'s coordinates.

**(b)** Rotate $B$ $90^\circ$ anticlockwise about the origin to get $C$. Find $C$'s coordinates.

**(c)** Find the single transformation matrix that maps $A$ directly to $C$.

**Solution:**

**(a)** Reflection in $y$-axis: $(x,y) \to (-x,y)$

$$
(1,1) \to (-1,1),\quad (3,1) \to (-3,1),\quad (2,3) \to (-2,3)
$$

**(b)** $90^\circ$ CCW rotation: $(x,y) \to (-y,x)$

$$
(-1,1) \to (-1,-1),\quad (-3,1) \to (-1,-3),\quad (-2,3) \to (-3,-2)
$$

**(c)** Reflection matrix: $R = \begin{pmatrix}-1&0\\0&1\end{pmatrix}$  
Rotation matrix: $M = \begin{pmatrix}0&-1\\1&0\end{pmatrix}$

Composite (rotation then reflection):

$$
\text{Transformation} = M \cdot R = \begin{pmatrix}0&-1\\1&0\end{pmatrix}\begin{pmatrix}-1&0\\0&1\end{pmatrix} = \begin{pmatrix}0&-1\\-1&0\end{pmatrix}
$$

Check: $\begin{pmatrix}0&-1\\-1&0\end{pmatrix}\begin{pmatrix}1\\1\end{pmatrix} = \begin{pmatrix}-1\\-1\end{pmatrix}$ ✅

---

# 8. Probability 🎲

---

## 8.1 Probability Scale

$0 \le P(A) \le 1$

- $P(A) = 0$: impossible
- $P(A) = 1$: certain

## 8.2 Probability Notation

- $P(A)$: probability of event $A$
- $P(A')$: probability of complement of $A$ ($= 1 - P(A)$)
- $P(A \cup B)$: probability of $A$ or $B$ (or both)
- $P(A \cap B)$: probability of $A$ and $B$

## 8.3 Relative & Expected Frequency

$$
\text{Relative frequency} = \frac{\text{frequency}}{\text{total trials}}
$$

$$
\text{Expected frequency} = P(A) \times \text{number of trials}
$$

## 8.4 Combined Events

**Tree diagrams:** Multiply along branches, add for different outcomes

**Venn diagrams:** Visualise intersections and unions

**Sample space diagrams:** Grid for two events

## 8.5 Conditional Probability

$$
P(A|B) = \frac{P(A \cap B)}{P(B)}
$$

---

### ⭐ Paper 4 — Worked Example

**Question:** A bag contains 4 red balls and 6 blue balls. Two balls are drawn without replacement.

**(a)** Find the probability both are red.

**(b)** Find the probability they are the same colour.

**(c)** Find the probability of at least one red.

**Solution:**

**(a)**
$$
P(R,R) = \frac{4}{10} \times \frac{3}{9} = \frac{12}{90} = \frac{2}{15}
$$

**(b)**
$$
P(B,B) = \frac{6}{10} \times \frac{5}{9} = \frac{30}{90} = \frac{1}{3}
$$

$$
P(\text{same}) = \frac{2}{15} + \frac{1}{3} = \frac{2}{15} + \frac{5}{15} = \frac{7}{15}
$$

**(c)**
$$
P(\text{at least one red}) = 1 - P(\text{both blue}) = 1 - \frac{1}{3} = \frac{2}{3}
$$

---

### ⭐ Paper 4 — Conditional Probability

**Question:** In a class of 30 students, 18 like Maths, 15 like Physics, and 10 like both.

**(a)** Draw a Venn diagram.

**(b)** A student is chosen at random. Given they like Maths, find the probability they also like Physics.

**(c)** A student is chosen at random. Given they like exactly one subject, find the probability it is Physics.

**Solution:**

**(a)**
$$
\begin{aligned}
|\text{Maths only}| &= 18 - 10 = 8 \\
|\text{Physics only}| &= 15 - 10 = 5 \\
|\text{neither}| &= 30 - 8 - 10 - 5 = 7
\end{aligned}
$$

**(b)**
$$
P(\text{Physics} \mid \text{Maths}) = \frac{P(M \cap P)}{P(M)} = \frac{10/30}{18/30} = \frac{10}{18} = \frac{5}{9}
$$

**(c)** Exactly one subject: $8 + 5 = 13$ students  
Of these, Physics only: 5 students

$$
P = \frac{5}{13}
$$

---

### ⭐ Paper 6 — Investigation (Monty Hall)

**Question:** Three boxes, one has a prize. You pick one, then the host opens an empty box. You may switch to the remaining box.

**(a)** Find the probability of winning if you **stick**.

**(b)** Find the probability of winning if you **switch**.

**(c)** If there were 5 boxes and the host opens 3 empty ones, what are the probabilities?

**Solution:**

**(a)** Stick: you win only if your initial pick was correct.

$$
P(\text{stick win}) = \frac{1}{3}
$$

**(b)** Switch: you win if your initial pick was wrong.

$$
P(\text{switch win}) = \frac{2}{3}
$$

**Switching doubles your chance!** 🎯

**(c)** With 5 boxes (host opens 3 empties):

$$
P(\text{stick win}) = \frac{1}{5},\qquad P(\text{switch win}) = \frac{4}{5}
$$

**General rule:** With $n$ boxes (host opens $n-2$ empties):
$$
P(\text{stick}) = \frac{1}{n},\qquad P(\text{switch}) = \frac{n-1}{n}
$$

---

# 9. Statistics 📊

---

## 9.1 Classifying and Tabulating Data

- **Discrete data:** countable values (e.g. number of students)
- **Continuous data:** measurable values (e.g. height, time)

## 9.2 Measures of Central Tendency & Spread

| Measure | Definition |
|:---:|:---:|
| Mean | $\bar{x} = \dfrac{\sum fx}{\sum f}$ |
| Median | Middle value when ordered |
| Mode | Most frequent value |
| Range | Highest $-$ lowest |
| Quartiles | $Q_1$ (25%), $Q_2$ (median, 50%), $Q_3$ (75%) |
| IQR | $Q_3 - Q_1$ |

## 9.3 Grouped Data — Estimated Mean

$$
\text{Estimated mean} = \frac{\sum(\text{midpoint} \times \text{frequency})}{\sum\text{frequency}}
$$

## 9.4 Statistical Diagrams

| Diagram | Use |
|:---:|:---:|
| Bar chart | Discrete comparison |
| Pie chart | Proportions |
| Stem-and-leaf | Small data sets |
| Scatter diagram | Correlation |
| Cumulative frequency graph | Median, quartiles, percentiles |
| Histogram | Continuous grouped data (area = frequency) |

## 9.5 Cumulative Frequency

**To find median and quartiles from a cumulative frequency graph:**

1. Total frequency $= n$
2. Median: read $x$ at $\frac{n}{2}$
3. $Q_1$: read $x$ at $\frac{n}{4}$
4. $Q_3$: read $x$ at $\frac{3n}{4}$
5. $IQR = Q_3 - Q_1$

## 9.6 Correlation and Line of Best Fit

- **Positive correlation:** $x$ increases, $y$ increases
- **Negative correlation:** $x$ increases, $y$ decreases
- **No correlation:** no pattern
- **Non-linear correlation:** curved pattern

Draw a **line of best fit** through the mean point $(\bar{x}, \bar{y})$.

---

### ⭐ Paper 4 — Worked Example

**Question:** The table shows test scores.

| Score | Frequency |
|:---:|:---:|
| 0–20 | 4 |
| 20–40 | 8 |
| 40–60 | 12 |
| 60–80 | 10 |
| 80–100 | 6 |

**(a)** Estimate the mean score.

**(b)** Draw a cumulative frequency graph and estimate the median.

**(c)** Find the interquartile range.

**Solution:**

**(a)**

| Class | Midpoint $x$ | $f$ | $fx$ |
|:---:|:---:|:---:|:---:|
| 0–20 | 10 | 4 | 40 |
| 20–40 | 30 | 8 | 240 |
| 40–60 | 50 | 12 | 600 |
| 60–80 | 70 | 10 | 700 |
| 80–100 | 90 | 6 | 540 |
| **Total** | | **40** | **2120** |

$$
\text{Estimated mean} = \frac{2120}{40} = 53
$$

**(b)** Cumulative frequency table:

| Upper bound | Cum. freq. |
|:---:|:---:|
| 20 | 4 |
| 40 | 12 |
| 60 | 24 |
| 80 | 34 |
| 100 | 40 |

Total $n = 40$. Median is at position 20. Reading from the graph:

The 20th value lies in the 40–60 class. Position within class: $20 - 12 = 8$ out of 12.

$$
\text{Median} \approx 40 + \frac{8}{12} \times 20 \approx 53.3
$$

**(c)**
- $Q_1$ (position 10): in 20–40 class, position $10 - 4 = 6$ out of 8  
  $Q_1 \approx 20 + \frac{6}{8} \times 20 = 35$

- $Q_3$ (position 30): in 60–80 class, position $30 - 24 = 6$ out of 10  
  $Q_3 \approx 60 + \frac{6}{10} \times 20 = 72$

$$
IQR = Q_3 - Q_1 = 72 - 35 = 37
$$

---

### ⭐ Paper 4 — Correlation & Line of Best Fit

**Question:** Study time (hours) and test scores for 8 students:

| $x$ (hours) | 2 | 4 | 5 | 6 | 8 | 9 | 10 | 12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| $y$ (score) | 45 | 55 | 60 | 65 | 70 | 78 | 80 | 85 |

**(a)** Describe the correlation.

**(b)** Find the equation of the line of best fit.

**(c)** Predict the score for 7 hours of study.

**Solution:**

**(a)** **Strong positive correlation** ✅ — as study time increases, score increases roughly linearly.

**(b)**
$$
\bar{x} = \frac{56}{8} = 7,\qquad \bar{y} = \frac{538}{8} = 67.25
$$

Gradient:
$$
m = \frac{\sum(x - \bar{x})(y - \bar{y})}{\sum(x - \bar{x})^2}
$$

$$
\begin{aligned}
\sum(x - \bar{x})(y - \bar{y}) &= (-5)(-22.25) + (-3)(-12.25) + (-2)(-7.25) + (-1)(-2.25) \\
&\quad + (1)(2.75) + (2)(10.75) + (3)(12.75) + (5)(17.75) \\
&= 111.25 + 36.75 + 14.5 + 2.25 + 2.75 + 21.5 + 38.25 + 88.75 \\
&= 316
\end{aligned}
$$

$$
\sum(x - \bar{x})^2 = 25 + 9 + 4 + 1 + 1 + 4 + 9 + 25 = 78
$$

$$
m = \frac{316}{78} \approx 4.05,\qquad y - 67.25 = 4.05(x - 7)
$$

$$
y = 4.05x + 38.9
$$

**(c)** For $x = 7$:
$$
y = 4.05(7) + 38.9 = 67.25
$$

This is exactly the mean — as expected, the line passes through $(\bar{x}, \bar{y})$! ✅

