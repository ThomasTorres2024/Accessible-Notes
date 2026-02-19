## Chapter 9

## Sequences and Series

$\oint 9.1$ Infinite Sequences

An infinite sequence (or simply a sequence) is simply an infinite (ordered) list of numbers

$$
S_{1}, S_{2}, S_{3}, \ldots, S_{n}, \ldots,
$$

The individual numbers. In are called the terms of the sequence $\left(s_{1}\right.$ is the firat term, $s_{2}$ the second term and so on).

A common way of writing a sequence is

$$
\left\{S_{n}\right\}_{n=1}^{\infty}
$$

(not used in the textbook, but very standard none theless).

Examples

1) $S_{n}=1$, for erery $n \geqslant 1$

Get $\{1\}_{n=1}^{\infty}=1,1,1,1$,
2) $s_{n}=(-1)^{n}, n \geqslant 1$

Get

$$
\left\{(-1)^{n}\right\}_{n=1}^{\infty}=-1,1,-1,1,-1,
$$

3) $S_{n}=\frac{1}{n}, \quad n \geqslant 1$

Gel

$$
\left\{\frac{1}{n}\right\}_{n=1}^{\infty}=1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4},
$$

The above are all examples of one of the main ways of representing a sequence - using a formula in $n$.

A common problem is to find a suitable formula when you're given the first several terms of the sequence.

Ex
a) $3,6,12,24,48,96,192,384$,

What we notice here first is that each term is double the previous one.
This suggests that $2^{n}$ should be part of our formula.

Also, the first term is 3 while all the terms are divisible by 3. This suggests there should be a 3 in our fermula.

Try $S_{n}=3(2)^{n}$
This fits all the terms we were given and so (as far as we can tell) this is a formula for our sequence.
b) $\frac{7}{2}, \frac{7}{5}, \frac{7}{8}, \frac{7}{11}, \frac{1}{2}, \frac{7}{17}$,

Here the $\frac{1}{2}$ term lonks like the rest but if we write $\frac{1}{2}$ as $\frac{7}{14}$, we get

$$
\frac{7}{2}, \frac{7}{5}, \frac{7}{8}, \frac{7}{11}, \frac{7}{14}, \frac{7}{17}, \ldots
$$

and the pattern is more evident.

The general term should obviously be a fraction whose numerater is 7.

Also the denominator clearly increases by 3 as we go from ane tem to the next while the first term is 2 .

Suggests the denominator is of the form

$$
3 n+k
$$

and since at 1 , we must have $3(1)+k=2$, we get $k=-1$, and so we get $3 n-1$.

A Jormula which fits our data is then

$$
s_{n}=\frac{7}{3 n-1}, n \geqslant 1
$$

Consrder now the sequence

$$
1,1,2,3,5,8,13,21,34,55,
$$

This is the famous Fibonacci Sequence where cach term is the sum of the preceding two. More preciely,

$$
s_{1}=1, s_{2}=1, \quad s_{n}=s_{n-1}+s_{n-2}, \quad n \geqslant 3 .
$$

This is an example of the second main way of defining a sequence which is recursively where the formula for each term (except possibly the first feer) invulves previous terms. We generally also need to specify the first few terms to get the recursion started (eg. Jor Fibonaci, we needed to first give $s_{1}$ and $s_{2}$ ).

Ex. Find a recursire formula for each of the following.
a) $1,2,6,24,120,720,5040$,

Here we notice that each term $s_{n}$ is $n$ times the prevous one - e.g. $6=3(2), 720=6(120)$, A recursive formula is then

$$
s_{1}=1, \quad s_{n}=n s_{n-1}, \quad n>1
$$

Noto that here $S_{n}$ is the famous factorial of $n$, $n$ ! where

$$
n!=1 \cdot 2 \cdot 3 \cdot(n-1)(n)
$$

the product of the first $n$ natural numbers.
b) $1,3,7,15,31,63,127, \ldots$

Here the first term is 1 while each term is obtained from the last one by doubling and adding 1 leig.

$$
7=2(3)+1, \quad 127=2(63)+11 .
$$

A recursire depa which fits is then

$$
s_{1}=1, \quad s_{n}=2 s_{n-1}+1, \quad n>1 .
$$

Convergence of Sequences
Consider the sequence

$$
\left\{\frac{1}{n}\right\}_{n=1}^{\infty}=1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \frac{1}{5},
$$

The bigger $n$ is, the smaller $\frac{1}{n}$ becomes and we can clearly make $\frac{1}{n}$ as small as we like by taking $n$ large enough.
This motivates the following defs.
Defn. The sequence $\left\{s_{n}\right\}_{n=1}^{\infty}=s_{1}, s_{2}, s_{3}, \ldots$ has a limit L, written

$$
\lim _{n \rightarrow \infty} 5_{n}=L
$$

if $S_{n}$ is as close to $L$ as we please whenever $n$ is sufficiently large. If a limit $L$ exists, we say the sequence converges to $L$. Otherwise, it no limit exists, we say the sequence diverges.

Important Examples

I $\quad s_{n}=x^{n}$

If $|x|<1$, then $\left\{x^{n}\right\}_{n=1}^{\infty}$ converges to 0
e.g if $x=\frac{1}{2}$, we get $\frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \frac{1}{16}, \ldots$.

If $|x|>1$, then $\left\{x_{n}\right\}_{n=1}^{\infty}$ diverges
o.g it $x=-3$, we get $-3,9,-27,81, \ldots \ldots$

If $x=1$, then $\left\{x_{n}\right\}_{n=1}^{\infty}$ is just the sequence $1,1,1,1, \ldots$ which (trivially) converges to 1 .

Finally, if $x=-1$, then $\left\{x_{n}\right\}_{n=1}^{\infty}$ is the sequence $-1,1,-1,1,-1,1$. which diverges.

II $S_{n}=\frac{1}{n^{\rho}} \quad(\rho$ fixed $)$.

If $p>0$, then $\left\{\frac{1}{n^{p}}\right\}_{n=1}^{\infty}$ clearly converges to $O$ (e.g. if $p=\frac{1}{2}$, we get
$1, \frac{1}{\sqrt{2}}, \frac{1}{\sqrt{3}}, \frac{1}{2}, \frac{1}{\sqrt{5}}, \ldots$

If $p<0$ then $\frac{1}{n^{p}}=n^{-p}$ gets large as $n \rightarrow \infty \operatorname{sinc} \theta-p>0$. In this case $\left\{\frac{1}{n^{\rho}}\right\}_{n=1}^{\infty}$ diverges.

Finally, if $p=0 \quad \frac{1}{n^{0}}=1$ for every $n$ and so we just have the sequence

$$
1,1,1,
$$

which is convergent to 1 .

Ex.
a) $S_{n}=(0.8)^{n}$.

This is of the type in Ex I with $|0.8|<1$ and so converges to 0 .
b) $S_{n}=\frac{1-e^{-n}}{1+e^{-n}}$.

Since $\quad\left|e^{-1}\right|<1, \lim _{n \rightarrow \infty} e^{-n}=0$ and so

$$
\lim _{n \rightarrow \infty} s_{n}=\frac{1-0}{1+0}=1
$$

c) $S_{n}=\frac{1+e^{n}}{1-e^{n}}$.

Here we divide above and belew by $e^{n}$ and remember that $\frac{1}{e^{n}}=e^{n}$ to $g t$

$$
s_{n}=\frac{e^{-n}+1}{e^{-n}-1}
$$

Similarly to b), we then see that $\lim _{n \rightarrow \infty} s_{n}=-1$.

Facts about Sequences

A sequence $\left\{S_{n}\right\}_{n-1}^{\infty}$ is called bounded if we can find numbers $K$ and $M$ such that

$$
K \leq s_{n} \leq M \text { for every } n \text {. }
$$

Fact
A convergent sequence is bounded.

Idea. If $\left\{s_{n}\right\}$ is convergent with limit $L$, then eventually $S_{n}$ is close to $L$ (e.g. between $L-1$ and L-1) for all sufficiently large $n$, and so ot least these later terms of the sequence are bounded.

The remaining tems are the early oner, but as there are anly finitely many of them, they will not affect whether the sequence is bounded.

A sequence $\left\{s_{n}\right\}_{n=1}^{\infty}$ is called monotone if It is either increasing, i.e.

$$
s_{n}<s_{n+1} \quad \forall n \geqslant 1
$$

or it is decreasing

$$
s_{n}>s_{n+1} \quad \forall n \geqslant 1 .
$$

Fact.
If $\left\{s_{n}\right\}_{n=1}^{\infty}$ is a sequence which is bounded and monotone, then it is convergent.

Ex. If $s_{n}=\left(1+\frac{1}{n}\right)^{n}$, one can show that $S_{n}$ is increasing and that $S_{n}<3$ for every $n$, so that we have a bounded sequence.

By the above dact $S_{n}$ is then convergent. In fact we already know the limil of this sequence is $e$ using Hitapital's rule.

