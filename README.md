# Local-Binary-Convolutional-Neural-Network
This repo contains my implementation of Local Binary Convolutional Neural Network (LBCNN) (https://arxiv.org/abs/1608.06049).

The tested architecture used
    
    512 randomly generated anchor weights (LBC filters),
    10 LBC blocks (20 convolutional layers),
    16 output channels in each LBC block
    384 hidden units in the fully connected layer.
   
 We achieve 79.23% accuracy as the same architecture was refered to get 82.74% in the original article. 
