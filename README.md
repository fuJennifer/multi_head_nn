# multi_head_nn
multi_head neural network when taking different labels in different head
Generally, Multi-head Neural Network train data with multi labels, like one dog image with three labels(dog, black color, long hair), in this case, three heads are designed to classify whether it is a dog, what's its color and whether it has long hair. 
However, in this example, one image only has one label, like dog, but there are maybe three labels in whole dataset, like dog, cat, bird. We design a multi head neural network to set three heads, each head is a binary classification, which to classify if it is dog, cat or bird. 
