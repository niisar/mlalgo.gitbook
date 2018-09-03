# Multiclass strategies

When the number of output classes is greater than one, there are two main possibilities to manage a classification problem:

* One vs All
* One vs One

## One vs All

 This is probably the most common strategy and is widely adopted by **scikit-learn** for most of its algorithms. If there are $$n$$ output classes, $$n$$ classifiers will be trained in parallel considering there is always a separation between an actual class and the remaining ones. This approach is relatively lightweight \(at most, $$n-1$$ checks are needed to find the right class, so it has an $$O(n)$$ complexity\) and, for this reason, it's normally the default choice and there's no need for further actions.

## One vs One

The alternative to one-vs-all is training a model for each pair of classes. The complexity is no longer linear \(it's $$O(n^2)$$ indeed\) and the right class is determined by a majority vote. In general, this choice is more expensive and should be adopted only when a full dataset comparison is not preferable.

