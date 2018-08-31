# Machine learning and big data

After the first release of Apache Hadoop, which implemented an efficient MapReduce algorithm, the amount of information managed grew exponentially, and several applications of Machine Learning such as mass collaborative filtering became reality.

Imagine an online store with a million users and only one thousand products. Consider a matrix where each user is associated with every product by an implicit or explicit ranking. This matrix will contain 1,000,000 x 1,000 cells, and even if the number of products is very limited, any operation performed on it will be slow and memory-consuming. Instead, using a cluster, together with parallel algorithms, such a problem disappears and operations with higher dimensionality can be carried out in a very short time.

{% hint style="info" %}
Not every machine learning problem is suitable for big data, and not all big datasets are really useful when training models. However, their conjunction in particular situations can drive to extraordinary results by removing many limitations that often affect smaller scenarios.
{% endhint %}



