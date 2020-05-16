## KNN(https://kevinzakka.github.io/2016/07/13/k-nearest-neighbor/)

* [Classification in ML](https://www.edureka.co/blog/classification-in-machine-learning/) 
* Difference between target data, testing data and training data
  - **target information** is the information about which class a given sample is known to belong to
  - **training samples** are directly used to calculate the data values.
  - **testing samples** are different samples than the training samples. The algorithm uses the parameters calculated with the training samples to predict the results on the testing samples and then compares the prediction to the target information to see how well the prediction went. It will make use of this information to decide how to re-calculate based upon the training samples.<br> For example the algorithm might hypothesize that features #5 and #11 are enough to predict the results well, and it would calculate parameters based on that, and would use the test samples to see how well it went. Then the algorithm might hypothesize that features #5 and #12 are enough to predict the results well, and it would calculate parameters based on that second hypothesis, and would use the test samples to see how well the second hypothesis went. Whichever of the two hypothesis had worse performance would be dropped, and more hypotheses would be tested, until eventually it would come up with the best hypothesis out of all of the ones it tried.<br>
  How to specify the target value depends upon what the network is to be used for. If it is to be a binary classification algorithm then it should be just 0 and 1. For some types of neural networks, each sample should have a vector of bit values with exactly 1 bit set, with the bit that is set indicating which class the data is. For example, if you had 3 different classes, then [0 0 1] would correspond to class #3. This vector of bit values would be the rows of a 2D array of target information. For other kinds of neural networks, you would just give an integer that is a class number. For other kinds of neural networks, you would give a scalar or perhaps vector of values per sample that did not have to be integer at all.<br>
  The input data would be the array of features, multiple features per sample.<br>
  The output depends upon how the neural network is to be used. Sometimes the output is a single value per sample that is the predicted class number; sometimes the output is a vector of parameter values for each sample.<br>
  For more info go to this link:- https://medium.com/technology-nineleaps/some-key-machine-learning-definitions-b524eb6cb48
* [Mathematical notation for subset of a dataset](https://stats.stackexchange.com/questions/321549/mathematical-notation-for-subset-of-a-dataset-based-on-temporal-conditions)
* [Classification vs Regression](https://medium.com/quick-code/regression-versus-classification-machine-learning-whats-the-difference-345c56dd15f7)
* [Cross validation with different values of K](https://idc9.github.io/stor390/notes/cross_validation/cross_validation.html)
* [Voronoi diagram](https://en.wikipedia.org/wiki/Voronoi_diagram)
* [kd trees](https://en.wikipedia.org/wiki/K-d_tree)
* [Locality-sensitive hashing](https://en.wikipedia.org/wiki/Locality-sensitive_hashing)
