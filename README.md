# Binary Classification: The Perceptron Algorithm 
This Folder provides with the implementation of the Perceptron algorithm for the binary classification of a data set along with the  Perceptron pseudocode.


In this Repository:

➊  README            🢂 you are reading this file

➋  Pseudocode       🢂 a straighfoward and 'text-based" algorithmich design for the Perceptron model

➌  TrainingData     🢂 contains the data-set used in the training-stage of the algorithm 

➍  Testing Data      🢂 contains the data-set used in the training-stage of the algorithm 


➎  Perceptron 🢂 this is the Python Script for the implementation of the Binary Perceptron: 

                                 Training phase :    ...
       FIND      🢂                      
                                 Testing  phase  :    ...
                                 
# Binary Classification and the Perceptron Model                                 
                                 
The Perceptron Model is implemented to define the optimal hyperplane which divides the input dimension into two half-dimensions and it is therefore used in binary classification problems.

This artificial neuron's structure is proposed below:

![a](https://user-images.githubusercontent.com/73316290/113158889-14367500-9234-11eb-8f84-568e4e383a93.png)


Such algorithmich design is the construction of a mathematical function that has been conceived to define a perceptron model, biologically inspired.
At the most basic level, the nodes as per in the diagram above represents the brain neurons that use a trasnfer function to pass information to successor leyers.
Specificallu, the perceptron algorithm is a classification model implemented in ''Machine Supervised Learning'' and it definde by a set of Scores ( these are the W weights)
one for every object feature ( these are the X inputs)  and a threshold ( this is a fix boundary value).
                                                            


The Perceptron mechanism          🡲     The Algorithm computes the SUM 'Σ'  of the weights (W) multiplied by its corresponding feature score (x) 
                                         producing a Score ( activation score) 
                                         
The Classification Rationale      🡲     If this score is greater than or equal to the fix threshold value the algorithm returns 'TRUE'  or '1' 
                                         If this score is greater than or equal to the fix threshold value the algorithm returns 'FALSE' or '0' 


 # The Algorithm Dinamics 

⚪ The model will repeat an epoch until the perceptron has reached the number of epochs available or it has learned the task.

⚪ Within each epoch the algorithm is programmed to iterate through the whole data set. 

⚪ within each iteration the algorithm looks for the *value-error* between the value given by its activation function and the desired output.

⚪ At such point, the if this value-error is different from *0* If error is different from zero then the Algorithm will adjust its weight again.                                           


                                         The Classification process


                                        1- Initialise the weights 
                                        2- Multiply the weights by the imput, Sum this computation.
                                        3- Compare the activation score against the threshold 
                                        4- Update the weights
                                        5- Repeat

