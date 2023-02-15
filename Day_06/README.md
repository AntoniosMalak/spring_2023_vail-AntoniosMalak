# Classification Loss Functions

## Topics covered in today's module
* Kullback Leibler Divergence Loss
* Binary Cross-Entropy
* Categorical Cross-Entropy
* Sparse Categorical Cross-Entropy

## Main takeaways from doing today's assignment
How to use classification loss funcations and how does it works.
* Kullback Leibler Divergence Loss
 - KLD Loss is a measure of how a distribution varies from a reference distribution (or a baseline distribution)
* Binary Cross-Entropy
 - BCE is a loss function that is used in binary classification tasks. These are tasks that answer a question with only two choices (yes or no, A or B, 0 or 1, left or righ).
* Categorical Cross-Entropy
  - This is the most common setting for classification problems. Cross-entropy loss increases as the predicted probability strays away from the actual label.
* Sparse Categorical Cross-Entropy
  - Both, Categorical Cross Entropy [CCE] and Sparse Categorical Cross Entropy [SCCE] have the same loss function. The only difference is the format of  yi  (i.e., true labels).
  - If  yi 's are one-hot encoded, we should use CCE. Examples (for a 3-class classification): [1,0,0], [0,1,0], [0,0,1] But if  yi 's are integers, use SCCE. Examples for above 3-class classification problem: [1], [2], [3]

## Challenging, interesting, or exciting aspects of today's assignment
How, Why and When using different losses. What is the difference and Relation between losses?

## Additional resources used 
- [KLD](https://medium.com/@rahulrajdob23/kullback-leibler-divergence-an-intuitive-explanation-ea9fc0e2e20)
- [BCE](https://medium.com/analytics-vidhya/simple-neural-network-with-bceloss-for-binary-classification-for-a-custom-dataset-8d5c69ffffee)
- [CCE](https://medium.com/@neuralthreads/categorical-cross-entropy-loss-the-most-important-loss-function-d3792151d05b)
- [SCCE](https://fmorenovr.medium.com/sparse-categorical-cross-entropy-vs-categorical-cross-entropy-ea01d0392d28)
