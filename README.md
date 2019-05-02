# sgd
Matrix Completion Using Stochastic Gradient Descent

Data sizes have grown exponentially during the last decade, making statistical machine learning methods limited by computing time and underlying algorithms computationally complex in non- trivial ways. As a prevalent task in machine learning, matrix approximation is a common tool in recommendation systems, text mining, and computer vision. It is realistic to assume, in many real datasets, that the partially observed matrix is low-rank. This research implements the stochastic gradient descent (SGD) algorithm on matrix completion problems and tests it on a real-life dataset MovieLens, aiming to predict the unobserved ratings of movies in order to make good recommendations to users on what to watch. The SGD algorithm shows outstanding performance for large-scale problems. It selects an observation uniformly at random and updates the parameters with only !(#) computation. It tries to lower the computation per iteration, at the cost of an increased number of iterations necessary for convergence.

Keywords: machine learning, recommendation systems, matrix completion, stochastic gradient descent.
