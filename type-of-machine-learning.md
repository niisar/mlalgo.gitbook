# Type of Machine Learning

## Supervised learning

A Supervised scenario is characterized by the concept of a teacher or supervisor, whose main task is to provide the agent with a precise measure of its error **\(directly comparable with output values\)**.

With actual algorithms, this function is provided by a training set made up of couples **\(input and expected output\)**. Starting from this information, the agent can correct its parameters so as to reduce the magnitude of a global loss function.

After each iteration, if the algorithm is flexible enough and data elements are coherent, the overall accuracy increases and the difference between the predicted and expected value becomes close to zero.

### Common supervised learning applications

* Predictive analysis based on regression or categorical classification
* Spam detection
* Pattern detection
* Natural Language Processing
* Sentiment analysis
* Automatic image classification
* Automatic sequence processing \(for example, music or speech\)

## Unsupervised learning

This approach is based on the absence of any supervisor and therefore of absolute error measures; it's useful when it's necessary to learn how a set of elements can be grouped **\(clustered\)** according to their similarity **\(or distance measure\)**.

### Commons unsupervised applications include:

* Object segmentation \(for example, users, products, movies, songs, and so on\)
* Similarity detection
* Automatic labeling

## Reinforcement learning

Even if there are no actual supervisors, reinforcement learning is also based on feedback provided by the environment.

However, in this case, the information is more qualitative and doesn't help the agent in determining a precise measure of its error. In reinforcement learning, this feedback is usually called reward \(sometimes, a negative one is called penalty\) and it's useful to understand whether a certain action performed in a state is positive or not.

The sequence of most useful actions is a policy that the agent has to learn, so to be able to make always the best decision in terms of the highest immediate and cumulative reward. In other words, an action can also be imperfect, but in terms of a global policy it has to offer the highest total reward.



