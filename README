#### 1.(a)
##### Answer：
To prove that almost every sample path of B has finite p-variation for every\ p\ >\ 2, we will use the properties of Brownian motion and the definition of p-variation.
Let B be a standard one-dimensional Brownian motion adapted to a filtration (Ft)t≥0. Let T > 0 be a fixed finite time, and p > 2. We want to prove that almost every sample path of B has finite p-variation, that is,
$$||B||p\ =\ \sup{\pi}\ \sum_{i=0}^{N-1}\ |B_{t_{i+1}}\ -\ B_{t_i}|^p\ <\ \infty$$
where the supremum is taken over all possible finite partitions π = {0 = t0 < t1 < ... < tN = T} of the interval [0, T].
Since B has independent and stationary increments, for any 0 ≤ s < t, the random variable B(t) - B(s) is normally distributed with mean 0 and variance t - s. Then, we have:

$$\mathbb{E}[(B_{t_{i+1}} - B_{t_i})^p] = \int_{-\infty}^{\infty} x^p \frac{1}{\sqrt{2\pi(t_{i+1} - t_i)}} e^{-\frac{x^2}{2(t_{i+1} - t_i)}} dx$$

Using substitution, let u = x / √(t_{i+1} - t_i), then x = u √(t_{i+1} - t_i), and dx = √(t_{i+1} - t_i) du. Therefore, we have:
$$\mathbb{E}[(B_{t_{i+1}} - B_{t_i})^p] = (t_{i+1} - t_i)^\frac{p}{2} \int_{-\infty}^{\infty} u^p \frac{1}{\sqrt{2\pi}} e^{-\frac{u^2}{2}} du$$

Now, since p > 2, the integral converges, and we can apply the dominated convergence theorem to interchange the expectation and the supremum:

$$\mathbb{E}[||B||p] = \mathbb{E}[\sup{\pi} \sum_{i=0}^{N-1} |B_{t_{i+1}} - B_{t_i}|^p] \leq \sup_{\pi} \sum_{i=0}^{N-1} \mathbb{E}[|B_{t_{i+1}} - B_{t_i}|^p] < \infty$$

Since the expectation of the p-variation is finite, it follows that the p-variation itself is finite almost surely. Therefore, almost every sample path of B has finite p-variation for every p > 2.

We have shown that almost every sample path of B has finite p-variation for every p > 2. This result can be useful in various applications, such as the analysis of stochastic processes, option pricing, and risk management. It highlights the roughness of Brownian motion paths and provides insight into the behavior of sample paths in the context of p-variation.

In particular, the fact that Brownian motion has finite p-variation for p > 2 has implications for the understanding of the regularity and irregularity of its paths. Brownian motion is known to be nowhere differentiable, and this result shows that its paths are quite rough and irregular as the p-variation is infinite when p ≤ 2.

Moreover, the result is also useful in the study of stochastic calculus and the development of stochastic integration theory. For example, it plays a role in the construction of the Itô integral, which is a widely used tool in the analysis of stochastic differential equations and various applications in finance and other fields.

In summary, the finding that almost every sample path of Brownian motion has finite p-variation for every p > 2 provides valuable insight into the properties and behavior of Brownian motion, which can be useful in understanding its impact on a wide range of applications in mathematics, finance, and other areas.


#### 1.(b)
##### Answer：
To prove that almost every sample path of B has infinite p-variation for every p ∈ [1, 2), we can use the fact that Brownian motion paths are almost surely locally α-Hölder continuous for any α ∈ (0, 1/2).

Let B be a standard one-dimensional Brownian motion, and let x(t) = B(t) for a fixed sample path. Fix p ∈ [1, 2). Since 1/p < 1/2, there exists α ∈ (1/p, 1/2) such that the sample path is almost surely locally α-Hölder continuous.

Now, consider a partition π = {0 = t0 < t1 < ... < tN = T} of the interval [0, T]. For each i = 0, ..., N-1, we have:

$$|x(t_{i+1}) - x(t_i)| \le C|t_{i+1} - t_i|^\alpha$$

By choosing a sufficiently fine partition with mesh size tending to zero, we can make the right-hand side arbitrarily small. Raise both sides to the power p:

$$(|x(t_{i+1}) - x(t_i)|)^p \le C^p |t_{i+1} - t_i|^{p\alpha}$$

Now, sum over all i:

$$\sum_{i=0}^{N-1}(|x(t_{i+1}) - x(t_i)|)^p \le C^p \sum_{i=0}^{N-1} |t_{i+1} - t_i|^{p\alpha}$$

Since pα < 1 (as α < 1/p), when we take the supremum over all possible partitions, the right-hand side will become infinite. Therefore:

$$||x||{p\text{-var}} = \left(\sup{\text{partitions }\pi} \sum_{i=0}^{N-1}(|x(t_{i+1}) - x(t_i)|)^p\right)^{1/p} = \infty$$

Thus, almost every sample path of B has infinite p-variation for every p ∈ [1, 2).

For parts (c)-(e), we have a function f: ℝ → ℝ that is β-continuous. This means there exists a constant C > 0 such that:

$$|f(x) - f(y)| \le C|x - y|^\beta \quad \text{ for all } x, y \in \mathbb{R}$$

This property will be helpful for analyzing the regularity of the function and understanding how it behaves under transformations and when used in the context of stochastic processes.


#### 1.(c)
##### Answer：
To show the equality, we will use the properties of Brownian motion and its increments. Recall that the increments of Brownian motion are normally distributed, independent, and have a mean of 0. Specifically, for s < t, the increment B_t - B_s is normally distributed with mean 0 and variance t - s.

Let's compute the expectation:

$$E[|B_t - B_s|^{2\beta}] = E[((B_t - B_s)^2)^{\beta}]$$

Since (B_t - B_s) is normally distributed with mean 0 and variance t - s, we have that (B_t - B_s)^2 is chi-squared distributed with one degree of freedom and its expected value is equal to the variance, which is t - s.

Let Y = (B_t - B_s)^2. Then:

$$E[((B_t - B_s)^2)^{\beta}] = E[Y^{\beta}]$$

Now, let's scale time by considering the Brownian motion at time 1. Define Z = (B_1 - B_0)^2. Since B_1 - B_0 is normally distributed with mean 0 and variance 1, Z is also chi-squared distributed with one degree of freedom and has an expected value of 1.

We can relate Y and Z through scaling. Observe that:

$$Y = (B_t - B_s)^2 = (t - s)((B_t - B_s) / \sqrt{t - s})^2 = (t - s)Z$$

Taking expectations, we have:

$$E[Y^{\beta}] = E[((t - s)Z)^{\beta}] = (t - s)^{\beta} E[Z^{\beta}]$$

Therefore:

$$E[|B_t - B_s|^{2\beta}] = E[((B_t - B_s)^2)^{\beta}] = (t - s)^{\beta} E[Z^{\beta}] = (t - s)^{\beta} E[|B_1|^ {2\beta}]$$

This demonstrates the desired equality.


#### 1.(d)
##### Answer：
We are given a function f that is β-continuous, meaning there exists a constant C > 0 such that:

$$|f(x) - f(y)| \le C|x - y|^{\beta} \quad \forall x, y \in \mathbb{R}$$

We want to show that the following expectation is finite:

$$E\left[\int_0^t |f(B_s)|^2 ds\right] < \infty$$

Now, observe that since f is β-continuous, it is also bounded on any bounded interval. Therefore, there exists a constant M > 0 such that:

$$|f(x)| \le M \quad \forall x \in [B_0 - L, B_0 + L]$$

for some L > 0. Since Brownian motion is almost surely continuous, it is almost surely bounded on any finite interval [0, t]. Thus, almost surely, there exists some L > 0 such that B_s is contained in the interval [B_0 - L, B_0 + L] for all s in [0, t].

Now, we can bound the integrand:

$$|f(B_s)|^2 \le M^2 \quad \forall s \in [0, t]$$

Integrating over [0, t], we get:

$$\int_0^t |f(B_s)|^2 ds \le \int_0^t M^2 ds = M^2 t$$

Taking expectations, we have:

$$E\left[\int_0^t |f(B_s)|^2 ds\right] \le E[M^2 t] = M^2 t < \infty$$

Thus, the expectation is finite.

#### 1.(e)
##### Answer：
We know that the stochastic integral $$\int_0^t f(B_s) dB_s$$ exists, and we want to show that it is given by:

$$\int_0^t f(B_s) dB_s = \lim_{n \to 0} \sum_{i=0}^{N-1} f(B_{t_i})(B_{t_{i+1}} - B_{t_i})$$

where the limit exists in $$L^2(\Omega)$$, and may be taken over any sequence of partitions π of the interval [0, t] with vanishing mesh size.

Let $$\pi^n = {0 = t_0^n < t_1^n < \dots < t_{N_n}^n = t}$$ be a sequence of partitions of the interval [0, t] with vanishing mesh size as n → ∞. Let $$\Delta B_i^n = B_{t_{i+1}^n} - B_{t_i^n}$$ and $$\Delta t_i^n = t_{i+1}^n - t_i^n$$.

We define the simple process $$X_s^n = \sum_{i=0}^{N_n-1} f(B_{t_i^n}) \mathbb{1}{[t_i^n, t{i+1}^n)}(s)$$.

Now, consider the Riemann sum:

$$S_n = \sum_{i=0}^{N_n-1} f(B_{t_i^n}) \Delta B_i^n$$

Using the Ito isometry and the definition of our simple process, we have:

$$E\left[\left(\int_0^t f(B_s) dB_s - S_n\right)^2\right] = E\left[\left(\int_0^t (f(B_s) - X_s^n) dB_s\right)^2\right]$$

Applying the Ito isometry, we get:

$$E\left[\int_0^t (f(B_s) - X_s^n)^2 ds\right]$$

Now, as n → ∞, the mesh size of the partition π tends to 0, and we know that the paths of Brownian motion are almost surely continuous. Consequently, for each fixed s, $$X_s^n \to f(B_s)$$ almost surely.

Using the bounded convergence theorem, since f is bounded on any bounded interval, we have:

$$\lim_{n \to \infty} E\left[\int_0^t (f(B_s) - X_s^n)^2 ds\right] = \int_0^t E\left[\lim_{n \to \infty} (f(B_s) - X_s^n)^2\right] ds = 0$$

Thus, we have shown that:

$$\lim_{n \to 0} \sum_{i=0}^{N-1} f(B_{t_i})(B_{t_{i+1}} - B_{t_i}) = \int_0^t f(B_s) dB_s$$

where the limit exists in $$L^2(\Omega)$$, and may be taken over any sequence of partitions π of the interval [0, t] with vanishing mesh size.


### 2. 
#### 2.(a)
For some T > 0, let $$f : [ 0 , T ] \times R \rightarrow R$$ be a function which is twice continuously differentiable with uniformly bounded derivatives. Let $$\lambda  \gt 0$$, let B be a Brownian motion, and let X be the stochastic process given by
$$X _ { t } = e ^ { - N t } f ( t , B _ { t } ) \quad  \quad t E [ 0 , T ]$$
By first applying It^o's formula to the function $$e ^ { -\lambda t } f ( t , x )$$, show that X is a martingale if and only if the function f satisfies the partial differential equation:
$$\frac { \partial f } { \partial t } ( t , x ) + \frac { 1 } { 2 } \frac { \partial ^ { 2 } f } { \partial x ^ { 2 } } ( t , x ) - \lambda  f ( t , x ) = 0$$

##### Answer：
First, let's apply Ito's formula to the function $$g(t, x) = e^{-\lambda t} f(t, x)$$ where $$X_t = g(t, B_t)$$. By Ito's formula, we have:

$$dX_t = d(e^{-\lambda t} f(t, B_t)) = \left(\frac{\partial g}{\partial t} + \frac{1}{2} \frac{\partial^2 g}{\partial x^2}\right) dt + \frac{\partial g}{\partial x} dB_t$$

Now, we compute the partial derivatives of g:

$$\frac{\partial g}{\partial t} = -\lambda e^{-\lambda t} f(t, x) + e^{-\lambda t} \frac{\partial f}{\partial t}(t, x) = -\lambda g(t, x) + e^{-\lambda t} \frac{\partial f}{\partial t}(t, x)$$

$$\frac{\partial g}{\partial x} = e^{-\lambda t} \frac{\partial f}{\partial x}(t, x)$$

$$\frac{\partial^2 g}{\partial x^2} = e^{-\lambda t} \frac{\partial^2 f}{\partial x^2}(t, x)$$

Plug these derivatives back into Ito's formula:

$$dX_t = \left(-\lambda g(t, B_t) + e^{-\lambda t} \frac{\partial f}{\partial t}(t, B_t) + \frac{1}{2} e^{-\lambda t} \frac{\partial^2 f}{\partial x^2}(t, B_t)\right) dt + e^{-\lambda t} \frac{\partial f}{\partial x}(t, B_t) dB_t$$

Now, recall that X is a martingale if and only if the dt term vanishes:

$$-\lambda g(t, B_t) + e^{-\lambda t} \frac{\partial f}{\partial t}(t, B_t) + \frac{1}{2} e^{-\lambda t} \frac{\partial^2 f}{\partial x^2}(t, B_t) = 0$$

Since $$g(t, B_t) = e^{-\lambda t} f(t, B_t)$$, we can divide both sides by $$e^{-\lambda t}$$:

$$-\lambda f(t, B_t) + \frac{\partial f}{\partial t}(t, B_t) + \frac{1}{2} \frac{\partial^2 f}{\partial x^2}(t, B_t) = 0$$

As this equation must hold for all t and B_t, we can replace $$B_t$$ by x:

$$\frac{\partial f}{\partial t}(t, x) + \frac{1}{2} \frac{\partial^2 f}{\partial x^2}(t, x) - \lambda f(t, x) = 0$$

Therefore, X is a martingale if and only if the function f satisfies the given partial differential equation.

#### 2.(b)
By identifying a suitable value of $$\lambda $$ and a suitable function f, deduce from part (a) that, for any $$\gamma \in  R$$, the process given by $$e ^ { \gamma B_t - \gamma ^ { 2 }t / 2 } \quad  \quad t \in  [ 0 , T ]$$

##### Answer：
To deduce that the given process is a martingale, we need to find a suitable value for $$\lambda$$ and a function f such that the process can be written in the form of $$X_t = e^{-\lambda t} f(t, B_t)$$.

Given the process $$Y_t = e^{\gamma B_t - \frac{\gamma^2 t}{2}}$$, we can choose $$\lambda = \frac{\gamma^2}{2}$$ and $$f(t, x) = e^{\gamma x}$$. Then, the process can be written as:

$$Y_t = e^{-\frac{\gamma^2 t}{2}} e^{\gamma B_t}$$

Now, we need to check if the function f satisfies the partial differential equation derived in the previous part:

$$\frac{\partial f}{\partial t}(t, x) + \frac{1}{2} \frac{\partial^2 f}{\partial x^2}(t, x) - \lambda f(t, x) = 0$$

Let's compute the derivatives for the function $$f(t, x) = e^{\gamma x}$$:

$$\frac{\partial f}{\partial t}(t, x) = 0$$

$$\frac{\partial f}{\partial x}(t, x) = \gamma e^{\gamma x}$$

$$\frac{\partial^2 f}{\partial x^2}(t, x) = \gamma^2 e^{\gamma x}$$

Plug these derivatives back into the PDE:

$$0 + \frac{1}{2}(\gamma^2 e^{\gamma x}) - \frac{\gamma^2}{2}(e^{\gamma x}) = 0$$

The equation holds true, so the function f satisfies the partial differential equation. Thus, we can conclude that the process $$Y_t = e^{\gamma B_t - \frac{\gamma^2 t}{2}}$$ is a martingale for any $$\gamma \in \mathbb{R}$$ and for $$t \in [0, T]$$.


#### 2.(c)
Now consider a Black{Scholes model with a risk-free bond with price process , and
a stock with price process S, which satisfy
$$\left. \begin{array}  { l  }  { d \beta _ { t } = r \beta _ { t } d t } \\ { d S _ { t } = \alpha S _ { t } d t + \sigma  S _ { t } d B _ { t } } \end{array} \right.$$
where $$\alpha E R , g \gt 0$$, and $$r \in R $$ is the rate of continuously compounded interest.
Assume that the price of an option is given by a process V , which may be written as
$$V _ { t } = u ( t , S _ { t } )$$
for some function $$u : [ 0 , T ] \times ( 0 , \infty ) \rightarrow R ,$$, which is twice continuously differentiable
with uniformly bounded derivatives.
Suppose that an investor decides to hold one option, a number at of stocks, and a
number bt of bonds, so that the wealth of their portfolio is given by $$W _ { t } = V _ { t } + a _ { t } S _ { t } + b _ { t } \beta _ { t }$$
We assume that this portfolio is self-financing, so that its dynamics are given by
$$d W _ { t } = d V _ { t } + a _ { t } d S _ { t } + b _ { t } d \beta _ { t }$$
Show that
$$d W _ { t } = ( \frac { \partial u } { \partial t } ( t , S _ { t } ) + \frac { 1 } { 2 } \sigma  ^ { 2 } S _ { t } ^ { 2 } \frac { \partial ^ { 2 } u } { \partial x ^ { 2 } } ( t , S _ { t } ) + b _ { t } r { \beta _t }  ) d t + ( \frac { \partial u } { \partial x } ( t , S _ { t } ) + a _ { t } ) d S _ { t }$$

##### Answer：
To show the desired equation, we start by applying Ito's formula to the function $$u(t, S_t)$$:

$$d(u(t, S_t)) = \frac{\partial u}{\partial t}(t, S_t) dt + \frac{\partial u}{\partial x}(t, S_t) dS_t + \frac{1}{2} \frac{\partial^2 u}{\partial x^2}(t, S_t) (dS_t)^2$$

We know that:

$$dS_t = \alpha S_t dt + \sigma S_t dB_t$$

So, the quadratic variation term, $(dS_t)^2$, can be computed as:

$$(dS_t)^2 = (\alpha S_t dt + \sigma S_t dB_t)^2 = \sigma^2 S_t^2 (dB_t)^2$$

Since Brownian motion has a quadratic variation of $$t$$, we have:

$$(dB_t)^2 = dt$$

So, the quadratic variation term becomes:

$$(dS_t)^2 = \sigma^2 S_t^2 dt$$

Now, substitute the expressions for $$d(u(t, S_t))$$ and $$(dS_t)^2$$ back into the Ito's formula:

$$dV_t = \left(\frac{\partial u}{\partial t}(t, S_t) + \frac{1}{2} \sigma^2 S_t^2 \frac{\partial^2 u}{\partial x^2}(t, S_t)\right) dt + \frac{\partial u}{\partial x}(t, S_t) dS_t$$

The dynamics of the portfolio are given by:

$$dW_t = dV_t + a_t dS_t + b_t d\beta_t$$

Substitute the expressions for $$dV_t$$, $$dS_t$$, and $$d\beta_t$$:

$$dW_t = \left(\frac{\partial u}{\partial t}(t, S_t) + \frac{1}{2} \sigma^2 S_t^2 \frac{\partial^2 u}{\partial x^2}(t, S_t)\right) dt + \frac{\partial u}{\partial x}(t, S_t) dS_t + a_t (\alpha S_t dt + \sigma S_t dB_t) + b_t (r\beta_t dt)$$

Rearrange the terms to get the desired equation:

$$dW_t = \left(\frac{\partial u}{\partial t}(t, S_t) + \frac{1}{2} \sigma^2 S_t^2 \frac{\partial^2 u}{\partial x^2}(t, S_t) + b_t r \beta_t\right) dt + \left(\frac{\partial u}{\partial x}(t, S_t) + a_t\right) dS_t$$

#### 2.(d)
We can make this portfolio risk-free by setting
$$\frac { \partial u } { \partial x } ( t , S _ { t } ) + a _ { t } = 0$$
Since the portfolio is now risk-free, you may assume that its dynamics also satisfy
$$d W _ { t } = k W _ { t } d t$$
for some $$k \in R$$
By using the principle of absence of arbitrage, explain why we must have that k = r.

##### Answer：
When set $$\frac{\partial u}{\partial x}(t, S_t) + a_t = 0$$, the portfolio becomes risk-free as it eliminates the stochastic term in the portfolio dynamics. In other words, the portfolio value does not depend on the randomness of the stock price anymore:

$$a_t = -\frac{\partial u}{\partial x}(t, S_t)$$

The dynamics of the risk-free portfolio, $$W_t$$, become:

$$dW_t = \left(\frac{\partial u}{\partial t}(t, S_t) + \frac{1}{2} \sigma^2 S_t^2 \frac{\partial^2 u}{\partial x^2}(t, S_t) + b_t r \beta_t\right) dt$$

We are given that the risk-free portfolio dynamics also satisfy:

$$dW_t = kW_t dt$$

Now, let's consider the principle of absence of arbitrage. According to this principle, two risk-free assets must provide the same return; otherwise, there would be an opportunity for arbitrage. In our case, we have two risk-free assets: the risk-free bond with price process $$\beta_t$$ and the risk-free portfolio $$W_t$$.

The risk-free bond has a return given by:

$$d\beta_t = r\beta_t dt$$

Since the risk-free portfolio should also provide the same return as the risk-free bond to prevent arbitrage opportunities, we must have:

$$kW_t dt = r\beta_t dt$$

Dividing both sides by $$W_t dt$$, we obtain:

$$k = r$$

So, we must have that $$k = r$$ to ensure the absence of arbitrage opportunities in the market.

#### 2.(e)
By using parts (c) and (d), show that the function u satisfies the Black-Scholes
equation:
$$\frac { \partial u } { \partial t } ( t , x ) + \frac { 1 } { 2 } \sigma ^ { 2 } x ^ { 2 } \frac { \partial ^ { 2 } u } { \partial x ^ { 2 } } ( t , x ) + r x \frac { \partial u } { \partial x } ( t , x ) - r u ( t , x ) = 0$$
##### Answer：
In part (c), we found that the risk-free portfolio dynamics are given by:

$$dW_t = \left(\frac{\partial u}{\partial t}(t, S_t) + \frac{1}{2} \sigma^2 S_t^2 \frac{\partial^2 u}{\partial x^2}(t, S_t) + b_t r \beta_t\right) dt$$

In part (d), we showed that by setting $$\frac{\partial u}{\partial x}(t, S_t) + a_t = 0$$, the portfolio becomes risk-free, and we also found that the risk-free rate of return should be equal to $$k = r$$, which means:

$$dW_t = rW_t dt$$

Recall that the wealth of the risk-free portfolio is given by:

$$W_t = V_t + a_t S_t + b_t \beta_t = u(t, S_t) - \frac{\partial u}{\partial x}(t, S_t) S_t + b_t \beta_t$$

Now, we substitute this expression of wealth into the equation $$dW_t = rW_t dt$$:

$$\left(\frac{\partial u}{\partial t}(t, S_t) + \frac{1}{2} \sigma^2 S_t^2 \frac{\partial^2 u}{\partial x^2}(t, S_t) + b_t r \beta_t\right) dt = r \left(u(t, S_t) - \frac{\partial u}{\partial x}(t, S_t) S_t + b_t \beta_t\right) dt$$

Now, we can simplify the equation and cancel out the $$b_t r \beta_t$$ terms:

$$\frac{\partial u}{\partial t}(t, S_t) + \frac{1}{2} \sigma^2 S_t^2 \frac{\partial^2 u}{\partial x^2}(t, S_t) = r u(t, S_t) - r x \frac{\partial u}{\partial x}(t, S_t)$$

Rearranging the terms, we arrive at the Black-Scholes equation:

$$\frac{\partial u}{\partial t}(t, x) + \frac{1}{2} \sigma^2 x^2 \frac{\partial^2 u}{\partial x^2}(t, x) + r x \frac{\partial u}{\partial x}(t, x) - r u(t, x) = 0$$

### 3
#### 3.(ai)
Let $$X \sim N ( 0 , 1 )$$ and f be any function. Define $$g ( X ) : = \frac { f ( X ) + f ( - X ) } { 2 }$$

(a) For an i.i.d sample $$X_i$$,  $$1 \leq i \leq M$$ of X, define
$$\widehat{I _ { M }} = \frac { 1 } { M } \sum _ { i = 1 } ^ { M } g ( X _ { i } )$$
(i) Show that if E[f(X)] exists nitely, then $$\widehat{I _ { M }}$$ is both consistent and unbiased as
an estimator of f(X). [State clearly any theorem that you are using.]

##### Answer：
Let $$X \sim N ( 0 , 1 )$$ and f be any function. Define $$g ( X ) : = \frac { f ( X ) + f ( - X ) } { 2 }$$

(a) For an i.i.d sample $$X_i$$,  $$1 \leq i \leq M$$ of X, define
$$\widehat{I _ { M }} = \frac { 1 } { M } \sum _ { i = 1 } ^ { M } g ( X _ { i } )$$
(i) Show that if E[f(X)] exists nitely, then $$\widehat{I _ { M }}$$ is both consistent and unbiased as
an estimator of f(X). [State clearly any theorem that you are using.]

To prove that $$\widehat{I_M}$$ is consistent and unbiased, we need to show that its expected value is equal to $$E[f(X)]$$ and that its variance converges to 0 as the sample size $$M$$ goes to infinity.

(i) Unbiasedness:

First, let's find the expected value of $$g(X)$$:

$$E[g(X)] = E\left[\frac{f(X) + f(-X)}{2}\right]$$

Since $$X$$ and $$-X$$ are symmetric with respect to the origin, and both are standard normal random variables, we can write:

$$E[g(X)] = \frac{1}{2} E[f(X) + f(-X)] = \frac{1}{2} (E[f(X)] + E[f(-X)])$$

Since the standard normal distribution is symmetric around zero, we have:

$$E[f(X)] = E[f(-X)]$$

Thus,

$$E[g(X)] = \frac{1}{2} (E[f(X)] + E[f(X)]) = E[f(X)]$$

Now, let's find the expected value of $$\widehat{I_M}$$:

$$E[\widehat{I_M}] = E\left[\frac{1}{M} \sum_{i=1}^M g(X_i)\right]$$

By the linearity of expectation and the fact that the $$X_i$$ are identically distributed, we have:

$$E[\widehat{I_M}] = \frac{1}{M} \sum_{i=1}^M E[g(X_i)] = \frac{1}{M} \sum_{i=1}^M E[f(X)] = E[f(X)]$$

This shows that $$\widehat{I_M}$$ is an unbiased estimator of $$E[f(X)]$$.

(ii) Consistency:

For consistency, we need to show that the variance of $$\widehat{I_M}$$ converges to 0 as $$M$$ goes to infinity. The variance of $$\widehat{I_M}$$ is given by:

$$\text{Var}(\widehat{I_M}) = \text{Var}\left(\frac{1}{M} \sum_{i=1}^M g(X_i)\right)$$

Since the $$X_i$$ are independent and identically distributed, we can write:

$$\text{Var}(\widehat{I_M}) = \frac{1}{M^2} \sum_{i=1}^M \text{Var}(g(X_i)) = \frac{1}{M} \text{Var}(g(X))$$

As $$M \to \infty$$, we have:

$$\lim_{M \to \infty} \text{Var}(\widehat{I_M}) = \lim_{M \to \infty} \frac{1}{M} \text{Var}(g(X)) = 0$$

This shows that $$\widehat{I_M}$$ is a consistent estimator of $$E[f(X)]$$.

In conclusion, $$\widehat{I_M}$$ is both an unbiased and consistent estimator of $$E[f(X)]$$ if $$E[f(X)]$$ exists finitely.


#### 3.(aii)
If Var (f(X)) exists nitely, then nd Var（$$\widehat{I _ { M }}$$）
in terms of variance and covariance
of f(X) and f(-X). [Hint: How can you calculate Var (g(X))?]
##### Answer：
To find the variance of $$\widehat{I_M}$$ in terms of the variance and covariance of $$f(X)$$ and $$f(-X)$$, we first need to find the variance of $$g(X)$$.

Recall that:

$$g(X) = \frac{f(X) + f(-X)}{2}$$

Now, let's compute the variance of $$g(X)$$:

$$\text{Var}(g(X)) = E[g(X)^2] - (E[g(X)])^2$$

First, let's find $$E[g(X)^2]$$:

$$E[g(X)^2] = E\left[\left(\frac{f(X) + f(-X)}{2}\right)^2\right] = \frac{1}{4}E\left[f(X)^2 + 2f(X)f(-X) + f(-X)^2\right]$$

Now, we need to express this expectation in terms of the variance and covariance of $$f(X)$$ and $$f(-X)$$.

Recall that:

$$\text{Var}(f(X)) = E[f(X)^2] - (E[f(X)])^2$$
$$\text{Var}(f(-X)) = E[f(-X)^2] - (E[f(-X)])^2$$
$$\text{Cov}(f(X), f(-X)) = E[f(X)f(-X)] - E[f(X)]E[f(-X)]$$

Since $$E[f(X)] = E[f(-X)]$$, we can rewrite the covariance as:

$$\text{Cov}(f(X), f(-X)) = E[f(X)f(-X)] - (E[f(X)])^2$$

Now, we can rewrite the expectation of the product of $$f(X)$$ and $$f(-X)$$ as:

$$E[f(X)f(-X)] = \text{Cov}(f(X), f(-X)) + (E[f(X)])^2$$

Substitute this back into the expression for $$E[g(X)^2]$$:

$$E[g(X)^2] = \frac{1}{4}\left(E[f(X)^2] + 2E[f(X)f(-X)] + E[f(-X)^2]\right)$$
$$= \frac{1}{4}\left((\text{Var}(f(X)) + (E[f(X)])^2) + 2(\text{Cov}(f(X), f(-X)) + (E[f(X)])^2) + (\text{Var}(f(-X)) + (E[f(-X)])^2)\right)$$

Now, let's find $$(E[g(X)])^2$$:

$$(E[g(X)])^2 = (E[f(X)])^2$$

Substitute the expressions for $$E[g(X)^2]$$ and $$(E[g(X)])^2$$ back into the formula for the variance of $$g(X)$$:

$$\text{Var}(g(X)) = E[g(X)^2] - (E[g(X)])^2$$
$$= \frac{1}{4}\left(\text{Var}(f(X)) + 2\text{Cov}(f(X), f(-X)) + \text{Var}(f(-X))\right)$$

Finally, let's find the variance of $$\widehat{I_M}$$:


#### 3.(b)
The basis of the antithetic method is a theoretical upper bound on Var (g(X)) in terms
of the function f. State this upper bound. Give an example of a monotone function
f that shows the theoretically guaranteed bound is the best possible in general.
##### Answer：
The basis of the antithetic method is that the variance of $$g(X)$$ is upper bounded by the average of the variances of $$f(X)$$ and $$f(-X)$$, which can be expressed as:

$$\text{Var}(g(X)) \le \frac{1}{2}(\text{Var}(f(X)) + \text{Var}(f(-X)))$$

This upper bound is derived from the fact that the covariance term is always non-negative for an antithetic variable:

$$\text{Cov}(f(X), f(-X)) \ge 0$$

An example of a monotone function $$f$$ that shows the theoretically guaranteed bound is the best possible in general is the identity function $$f(x) = x$$. In this case, $$f(X) = X$$ and $$f(-X) = -X$$, where $$X \sim N(0,1)$$.

For this function, we have:

$$\text{Var}(f(X)) = \text{Var}(X) = 1$$
$$\text{Var}(f(-X)) = \text{Var}(-X) = 1$$
$$\text{Cov}(f(X), f(-X)) = \text{Cov}(X, -X) = -\text{Var}(X) = -1$$

Now, let's compute $$g(X)$$ and its variance:

$$g(X) = \frac{f(X) + f(-X)}{2} = \frac{X - X}{2} = 0$$

Since $$g(X)$$ is a constant function, its variance is 0:

$$\text{Var}(g(X)) = 0$$

In this case, the theoretically guaranteed bound is achieved, as the variance of $$g(X)$$ equals the lower bound of the average of the variances of $$f(X)$$ and $$f(-X)$$:

$$\text{Var}(g(X)) = 0 = \frac{1}{2}(\text{Var}(f(X)) + \text{Var}(f(-X))) - \text{Cov}(f(X), f(-X))$$

#### 3.(c)
Let Y be a random variable with nite positive variance. Dene $$Z _ { \theta } : = X + \theta ( E [ Y ] - Y )$$
Prove that the Var($$Z _ { \theta }$$) is minimised by $$\theta _ { m i n } = \frac { \operatorname { C o v } ( X , Y ) } { V _ { \operatorname { a r } ( Y ) } }$$
. Justify each step of your proof.
##### Answer：
To find the value of $$\theta$$ that minimizes the variance of $$Z_\theta$$, we'll first compute the variance of $$Z_\theta$$ and then find the value of $$\theta$$ that minimizes it.

The variance of $$Z_\theta$$ can be computed as follows:

$$\text{Var}(Z_\theta) = \text{Var}(X + \theta(E[Y] - Y))$$
$$= \text{Var}(X) - 2\theta\text{Cov}(X, Y) + \theta^2\text{Var}(Y)$$

Now, to find the minimum variance, we'll differentiate the expression with respect to $$\theta$$ and set the derivative to zero:

$$\frac{d\text{Var}(Z_\theta)}{d\theta} = -2\text{Cov}(X, Y) + 2\theta\text{Var}(Y)$$

Setting the derivative to zero:

$$-2\text{Cov}(X, Y) + 2\theta\text{Var}(Y) = 0$$

Solving for $$\theta$$:

$$\theta_{min} = \frac{\text{Cov}(X, Y)}{\text{Var}(Y)}$$

This is the value of $$\theta$$ that minimizes the variance of $$Z_\theta$$, and we've justified each step by computing the variance and differentiating it with respect to $$\theta$$.


#### 3.(di)
For an $$m \times m$$ real matrix $$A = ( ( a _ { i j } ) )$$, define
$$| | A | | _ { \alpha } : = m a x \sum _ { j = 1 } ^ { m } | a _ { i j } |$$
and
$$| | A | | _ { 1 } : = m a x \sum _ { j = 1 } ^ { m } | a _ { i j } |$$
(i) For any two real matrices A; B, show that $$| | A + B | | | \infty \leq | | A | | _ { \infty } + | | | B | | \infty$$.

##### Answer：
Given two real matrices $$A$$ and $$B$$ of size $$m \times m$$, we want to show that:

$$|A + B|\infty \le |A|\infty + |B|_\infty$$

The infinity norm of a matrix is defined as:

$$|A|\infty = \max_i \sum{j=1}^m |a_{ij}|$$

Now, let's look at the infinity norm of the sum of the two matrices, $$A + B$$:

$$|(A + B)|\infty = \max_i \sum{j=1}^m |(a_{ij} + b_{ij})|$$

Using the triangle inequality for absolute values, we get:

$$|a_{ij} + b_{ij}| \le |a_{ij}| + |b_{ij}|$$

Summing over j:

$$\sum_{j=1}^m |(a_{ij} + b_{ij})| \le \sum_{j=1}^m (|a_{ij}| + |b_{ij}|)$$

Applying the triangle inequality for summation:

$$\sum_{j=1}^m |(a_{ij} + b_{ij})| \le \sum_{j=1}^m |a_{ij}| + \sum_{j=1}^m |b_{ij}|$$

Now, we want to find the maximum of this sum over all i:

$$\max_i \sum_{j=1}^m |(a_{ij} + b_{ij})| \le \max_i (\sum_{j=1}^m |a_{ij}| + \sum_{j=1}^m |b_{ij}|)$$

$$|(A + B)|\infty \le \max_i \sum{j=1}^m |a_{ij}| + \max_i \sum_{j=1}^m |b_{ij}|$$

$$|(A + B)|\infty \le |A|\infty + |B|_\infty$$

Thus, we have shown that $$|(A + B)|\infty \le |A|\infty + |B|_\infty$$

#### 3.(dii)
Show that if A is a real, symmetric matrix, then  $$| | A | | _ { \infty } = | | A | | _ { 1 }$$
##### Answer：
Given a real symmetric matrix $$A$$, we want to show that its infinity norm is equal to its 1-norm.

Recall the definitions of the infinity norm ($$|A|_\infty$$) and the 1-norm ($$|A|_1$$):

$$|A|\infty = \max_i \sum{j=1}^m |a_{ij}|$$
$$|A|1 = \max_j \sum{i=1}^m |a_{ij}|$$

Since $$A$$ is a symmetric matrix, we have $$a_{ij} = a_{ji}$$ for all $$i$$ and $$j$$. Therefore, we can rewrite the 1-norm as:

$$|A|1 = \max_j \sum{i=1}^m |a_{ji}| = \max_j \sum_{i=1}^m |a_{ij}|$$

Now, notice that the expressions for the infinity norm and the 1-norm are identical:

$$|A|\infty = \max_i \sum{j=1}^m |a_{ij}|$$
$$|A|1 = \max_j \sum{i=1}^m |a_{ij}|$$

Since the indices $$i$$ and $$j$$ are arbitrary, we can conclude that for a real symmetric matrix $$A$$:

$$|A|_\infty = |A|_1$$

#### 4.(a)
##### Answer：
```
import numpy as np
import math
import itertools

# All packages here
##############################################################

Nx = 50
T = 1
Nt = 50
time_step = T / Nt
r = 0.03
sigma = 0.3
L = 10
h = L / Nx
E = 4

# All parameters here
##############################################################

mvec = [x for x in range(1, Nx)]
D1 = np.diag(mvec)
square_mvec = [x ** 2 for x in mvec]
D2 = np.diag(square_mvec)
zero_vector1 = np.zeros((Nx - 2, 1))
zero_vector2 = np.transpose(zero_vector1)

B1 = np.identity(Nx - 2)
Upper_triangular1 = np.block([
    [B1[1:, :], zero_vector1],
    [0, zero_vector2]
])
Lower_triangular1 = np.transpose(Upper_triangular1)
Tridiagonal1 = Upper_triangular1 + Lower_triangular1
Tridiagonal2 = Upper_triangular1 - 2 * np.identity(Nx - 1) + Lower_triangular1

Intermediate1 = 0.5 * time_step * r * (np.matrix(D1) @ np.matrix(Tridiagonal1))
Intermediate2 = 0.5 * time_step * sigma**2 * (np.matrix(D2) @ np.matrix(Tridiagonal2))

# Fmatrix = F as in equation (1) above
Fmatrix = (1 - r * time_step) * np.identity(Nx - 1) + Intermediate1

# Bmatrix = B in equation (1) above
Bmatrix = (1 + r * time_step) * np.identity(Nx - 1) - Intermediate2

# A1matrix = 1/2 (I + F) on RHS of equation (1) above
A1matrix = 0.5 * (np.identity(Nx - 1) + Fmatrix)

# A2matrix = 1/2 (I + B) on LHS of equation (1) above
A2matrix = 0.5 * (np.identity(Nx - 1) + Bmatrix)

```
#### 4.(b)

##### Answer：
import numpy as np
import math
import itertools

# Fill in the appropriate parameters and packages
Nx = 100
Nt = 100
E = 10
sigma = 0.2
r = 0.05
h = E / Nx
time_step = 1 / Nt

# Next we solve the above implicit matrix equation
Vmatrix = np.zeros((Nx-1, Nt+1))
column_1_V = [max(E-j*h, 0) for j in range(1, Nx)]
Vmatrix[:, 0] = column_1_V
for i in range(Nt):
    tau = i * time_step
    p1 = 0.5 * time_step * (sigma**2 - r) * E * math.exp(-r * tau)
    q1 = 0.5 * time_step * (sigma**2 - r) * E * math.exp(-r * (tau + time_step))
    vector_initialize = np.zeros((Nx-1, 1))
    vector_initialize[0] = 0.5 * (p1 + q1)
    new_p_q_vector = vector_initialize
    rhs = np.transpose(A1matrix @ Vmatrix[:, i]) + 0.5 * new_p_q_vector.T
    solution_to_equation = np.linalg.solve(A2matrix, rhs)
    Vmatrix[:, i+1] = list(itertools.chain(*np.array(solution_to_equation)))







