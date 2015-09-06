##Stochastic Processes
A stochastic process is a special type of probability model in which the sample points represent func- tions in time.
- It often can be viewed as a sequence of random variables evolving in time. Often there is a continuum of random variables, one for each real valued instant of time.
- A discrete stochastic process is a stochastic process where either the random variables are discrete in time or the set of possible sample values is discrete.

###Random Variable

A Random variable $(X$ or $X(\omega))$ is a map/function from the sample space $\Omega$ to $\mathbb{R}$.

This function must satisfy the constraint that $\{ \omega :   X(\omega) \leq a\}$ is an event for all $a \in \mathbb R$

Each Random variable has a distribution function $$F_X (x) = Pr \{ X \leq x \}$$ It is a non decreasing (constant or increasing) function from 0 to 1.

**Discrete Random Variables**

If X maps only into a finite or countable set of val- ues, it is discrete and has a *probability mass function* where $p_X (x) = Pr \{ X = x \} $

**Continuous Random Variables**

If $dF_X(x)/dx$ exists and is finite for all x, then X is continuous and has a density, $f_X(x) = dF_X(x)/dx$.

**Mixed Random Variables**

If X has discrete and continuous components, it’s sometimes useful to view it as a density with impulses.

In general, $F_X(x) = Pr\{X \leq x\}$ always exists. Because $X = x$ is included in $X \leq x$, we see that if $F_X(x)$ has a jump at $x$, then $F_X(x)$ is the value at the top of the jump.