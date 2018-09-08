## Caltech ML HW1

#### The Learning Problem
1. [d] (i) Not learning, (ii) Supervised Learning, (iii) Reinforcement Learning
2. [a] (ii) & (iv)

#### Bins and  Marbles
3. [d]
$$\begin{split}
P[\text{2nd ball black}|\text{1st ball black}] &= P[\text{pick the all black bag}|\text{1st ball black}] \\
&= \frac{P[\text{1st ball balak|pick the all black bag}] \cdot P[\text{pick the all black bag}]}{P[\text{1st ball black}]} \\
&= \frac{1\cdot 1/2}{1/2\cdot 1/2 + 1/2} \\
&= \frac{2}{3}
\end{split}$$
4. [b] $3.405\times10^{−4}$. $P[\text{one sample has } \nu = 0] = (1-0.55)^{10}=3.405\times10^{−4}$
5. [c] $0.289$.
$$\begin{split} P[\text{at least one of the samples has } \nu = 0] &= 1-P[\text{all samples have } \nu \neq 0] \\
&= 1 - (1 - P[\text{one sample has } \nu = 0])^{1000}\\
&= 1 - (1 - 3.405\times10^{−4})^(1000) \\
&= 0.289
\end{split}$$

#### Feasibility of learning
6. [e] They are all equivalent (equal scores for g in [a] through [d]).
All the scores equal to 12.

#### The Perceptron Learning Algorithm
see Jupyter Notebook
