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

We define generic **regressor**, a vector-valued function which associates an input value to a continuous output and generic **classifier**, a vector-values function whose predicted output is categorical \(discrete\). If they also depend on an internal parameter vector which determines the actual instance of a generic predictor, the approach is called **parametric learning**:

$$
\Large \bar{y} = r(\bar x, \bar \theta) \\
\Large \bar{y} = c(\bar x, \bar \theta) \\
\text {where }\theta \text{ is the generic internal parameter vector}
$$

On the other hand, **non-parametric learning** doesn't make initial assumptions about the family of predictors \(for example, defining a generic parameterized version of r\(...\) and c\(...\)\). A very common non-parametric family is called **instance-based learning** and makes real-time predictions \(without pre-computing parameter values\) based on hypothesis determined only by the training samples \(instance set\).

In unsupervised learning, we normally only have an input set $$X$$ with $$m$$-length vectors, and we define clustering function \(with $$n$$ target clusters\) with the following expression:

$$
\Large k_t = C(\bar x, \bar \theta) \text { where } k_t \in (0,1,2,...,n)
$$







