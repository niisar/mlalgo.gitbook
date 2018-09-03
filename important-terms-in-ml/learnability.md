# Learnability

A parametric model can be split into two parts: a static structure and a dynamic set of parameters. The former is determined by choice of a specific algorithm and is normally immutable \(except in the cases when the model provides some re-modeling functionalities\), while the latter is the objective of our optimization. Considering $$n$$ unbounded parameters, they generate an $$n$$-dimensional space  where each point, together with the immutable part of the estimator function, represents a learning hypothesis $$H$$ \(associated with a specific set of parameters\):

$$
\Large H = \{\theta_1, \theta_2, ..., \theta_n\}
$$



