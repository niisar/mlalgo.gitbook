# Data formats

In a supervised learning problem, there will always be a dataset, defined as a finite set of real vectors with $$m$$ features each:

$$
\Large X = \{\bar{x_1},\bar{x_2},...,\bar{x_n}\}\text{ where } \bar{x_i} \in \text R^m
$$

Considering that our approach is always probabilistic, we need to consider each as drawn from a statistical multivariate distribution $$D$$. For our purposes, it's also useful to add a very important condition upon the whole dataset $$X$$: we expect all samples to be **independent and identically distributed \(i.i.d\)**. This means all variables belong to the same distribution $$D$$, and considering an arbitrary subset of $$m$$ values, it happens that:

$$
\Large  P(\bar{x_1},\bar{x_2},...,\bar{x_m}) = \prod ^{m} _{i=1} P(\bar{x_i})
$$

The corresponding output values can be both **numerical-continuous** or **categorical**. In the first case, the process is called **regression**, while in the second, it is called **classification**. Examples of numerical outputs are:

$$
\Large X = \{\bar{x_1},\bar{x_2},...,\bar{x_n}\}\text{ where } \bar{x_i} \in \text (0,1) \text { or } \bar{x_i} \in \text R^+
$$

Categorical example are:

$$
\Large X \in \{\text{red, black, white, green} \}\text{ or } \bar{x_i} \in \text \{0,1\}
$$



