# Student Academic Performance

## Description
**Project name: Student Academic Performance**
The purpose of this project is to use the neural network structure from the beginning (Neural Networks from Scratch) for predicting the acceptance or rejection of students according to a set of their characteristics during an academic semester.

### the project has 3 main parts:
  1) Neural network implementation (from Scratch):
    -  Quantification of weights and activation threshold
    -  Forward Propagation
    -  Backward Propagation
    -  Combining the previous steps and building the final algorithm
    
  2) Training the Implemented Model:
    - In this part, the implemented algorithm should be trained on the training data
    
  3) Evaluation of the Trained Model:
    -  After tarining step, thw accuracy and loss should be computed to evaluate the performance of the model
### Formulas:
  $$𝑍=𝑊^𝑇 𝑋+𝑏$$
  $$𝐴=𝑠𝑖𝑔𝑚𝑜𝑖𝑑(𝑍)$$
  $$𝐸=-\frac{1}{n}\sum_{i=1}^n (𝑦_𝑖 log(𝑎_𝑖)+(1−𝑦_𝑖)log(1−𝑎_𝑖))$$
  $$\frac{𝜕𝐸}{𝜕𝑊}=\frac{1}{n}𝑋 (𝐴−𝑌)^𝑇$$
  $$\frac{𝜕𝐸}{𝜕b}=\frac{1}{n} \sum_{i=1}^n (𝑎_𝑖−𝑦_𝑖)$$
  $$𝑊=𝑊−𝛼\frac{𝜕𝐸}{𝜕𝑊}$$
  $$𝑏=𝑏−𝛼\frac{𝜕𝐸}{𝜕b}$$

**This project was done as a project of Deep Learning course at University of Guilan in May 2022.**
