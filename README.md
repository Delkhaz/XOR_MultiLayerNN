# XOR_MultiLayerNN
Neural Network that solves XOR problem. 
along with another MultiLayer Network that solves MNIST. 


# Results
We are using data to visualize how the XOR net is behaving i.e examining the decision boundaries the network is using. Initialize the weights in the net randomly to view the decison boundaries before training. Instead of calculating a model loss and accuracy, we are looking which class labels are assigned to each input vector. 

All the grid positions are assigned to a class of 0 or 1, then we seperate the data into two sets :
  * input vectors classifie as 0
  * input vectors classifed as 1
 
apply a boolean slice to select the matching rows from the positions matrix and create two non overlapping matrices of vectors : 0's or 1's. Colors according to class label based on net prediction for each vector in the grid.

![alt text](https://github.com/Delkhaz/XOR_MultiLayerNN/blob/master/results/XOR_decision_boundary.png)




also some mnist classification 
