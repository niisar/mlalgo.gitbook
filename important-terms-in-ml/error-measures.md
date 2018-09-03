# Error measures

In general, when working with a supervised scenario, we define a non-negative error measure $$e_m$$ which takes two arguments \(expected and predicted output\) and allows us to compute a total error value over the whole dataset \(made up of $$n$$ samples\):

$$
\Large \text {Error}_H = \sum^n_{i=1} e_m(\tilde{y_i},y_i) \text { where } e_m \ge 0 \space \forall \space \tilde y_i,y_i
$$

This value is also implicitly dependent on the specific hypothesis $$H$$ through the parameter set, therefore optimizing the error implies finding an optimal hypothesis \(considering the hardness of many optimization problems, this is not the absolute best one, but an acceptable approximation\). In many cases, it's useful to consider the **mean square error \(MSE\)**:

$$
\Large \text {Error}_H = \frac 1 n \sum^n_{i=1} (\tilde{y_i} - y_i)^2
$$



