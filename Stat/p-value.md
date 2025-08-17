Some words about p-value.

P-value is the probability of obtaining test results at least as extreme as the result actually observed, under the assumption that the null hypothesis is correct.

Consider an observed test-statistic $t$ from unknown distribution $T$. Then the _p_-value $p$ is what the prior probability would be of observing a test-statistic value at least as "extreme" as $t$ if null hypothesis $H_0$ were true. That is:
- $p = \operatorname{P}(T \geq t | H_0)$ for a one-sided right-tail test-statistic distribution.
- $p = \operatorname{P}(T \leq t | H_0)$ for a one-sided left-tail test-statistic distribution.
- $p = 2min[\operatorname{P}(T \geq t | H_0), \operatorname{P}(T \leq t | H_0)]$ for a two-sided test-statistic distribution. If the distribution of $T$ is symmetric about zero, then $p = \operatorname{P}(|T| \geq |t| \ | \ H_0)$.

