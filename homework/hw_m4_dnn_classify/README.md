# Identifying M4 cluster members w/ Dense Neural Networks

_NOTE_: I don't include the data here to keep things small.  Please get the data from the [class repo](https://github.com/uo-phys/sci-comp-spring23).

Demonstrate the use of a densely connected neural network, like the one we trained on the MNIST data set, for classifying stars in the M4 cluster using Gaia's measurements of stars' locations on the sky (right ascension and declination).  This is basically a repeat of what we covered in class, but this time I want you to even out the training set to include roughly equal numbers of M4 members and non-members.

1. What training and validation accuracies are you able to achieve?

2. Is your trained model confident that any of the stars in your test set are part of M4?

3. What did your model learn?  Can you come up with a useful way to probe your model and visualize the results to answer this question?

4. Do you think more sophisticated models could do better with this classification task using only sky positions?  Use the properties of the training set to make your argument.

**510 students:**

Make use of other features observed by Gaia to improve your classifier.  Be sure to use the data model documentation to understand what each feature is, and explain why you think it would be useful for identifying cluster members.  What training and validation accuracies can you achieve?  Does your trained model find any stars it believes are confidently in M4 that weren't in the M4 catalog?