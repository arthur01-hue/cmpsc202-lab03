## Lynsey Arthur

## Problem 1 Reponses:

1. $T(n)$ is $\mathcal{O}(n^2)$


    False. $(n^2)$ has a slower growth than $(n^3)$, and since the upper bound is $\mathcal{O}(n^3)$, it can not grow any slower than that.


2. $T(n)$ is $\Theta(n^3)$


    Could be true or false. The upper bound of $T(n)$ is $\mathcal{O}(n^3)$ and the lower bound is $\Omega(n^2)$, so $\Theta$ is in the range of those two bounds and could either be $\Theta(n^3)$ or $\Theta(n^2)$.


3. $T(n)$ is $\Omega(n)$


    True. $(n)$ has a slower growth than $(n^2)$, and since the lower bound is $\Omega(n^2)$, which means it could grow at least this slow, it could grow slower than this.


4. $T(n)$ is $\Theta(n^{1.5})$


    False. The upper bound of $T(n)$ is $\mathcal{O}(n^3)$ and the lower bound is $\Omega(n)$. $(n^{1.5})$ is not in the range between the given lower bounds and upper bounds.


5. $T(n)$ is $\mathcal{O}(n)$

    False. The upper bound of $T(n)$ is $\mathcal{O}(n^3)$. $\mathcal{O}(n)$ has a slower growth than this, and since $\mathcal{O}(n^3)$ is the upper bound, $\mathcal{O}$ can not be any slower than this.


6. $T(n)$ is $\Theta(n^2 \log n)$

    False. $\Theta(n^2 \log n)$ is not in the range of $(n^3)$ and $(n^2)$, given from the upper and lower bounds.


## Problem 2 Response:

Mystery Algorithm
Input: An array of int $A$ of length $n$.
Output: int sum
    n = |A|
    sum = 0
    for i = 1 to n:
        for j = 1 to n:
            sum += f(A, i, j)


The running times in terms of $(n)$ would be at least $\Omega(n^2)$. This is because the two loops would both be $(n)$, which would total $(n^2)$. We know the lower bounds of any algorithm is at the very least $\Omega(1)$, and this would happen at least $(n^2)$ amount of times in this algorithm. We would not be able to find the upper bound because we don't know what f does, but the lower bound would be $\Omega(n^2)$.