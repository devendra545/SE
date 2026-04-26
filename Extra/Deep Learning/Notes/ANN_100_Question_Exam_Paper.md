# Deep Learning Exam Paper: Artificial Neural Networks Only

## Instructions

- Total questions: 100
- Scope: Artificial Neural Networks, perceptrons, MLPs, activations, forward pass, loss functions, gradient descent, backpropagation, optimization, regularization, and evaluation.
- Excluded topics: code, CNNs, RNNs, Transformers, GANs, reinforcement learning, and other deep learning architectures.

## Section A: Very Short Answer Questions

1. Define an artificial neuron.
2. What is the role of weights in an ANN?
3. What is the role of bias in a neuron?
4. State the main limitation of the MP neuron.
5. Why is the perceptron considered a learning model?
6. What is meant by a linearly separable problem?
7. Why can a single perceptron not solve XOR?
8. What is an activation function?
9. Why do ANNs need non-linear activation functions?
10. What is the difference between input layer, hidden layer, and output layer?
11. What is a forward pass?
12. What is a loss function?
13. What does gradient descent try to minimize?
14. What is learning rate?
15. What happens if the learning rate is too high?
16. What happens if the learning rate is too low?
17. Define epoch.
18. Define batch size.
19. Define mini-batch gradient descent.
20. What is backpropagation?

## Section B: Short Answer Questions

21. Compare the MP neuron and the perceptron.
22. Explain why weights represent feature importance.
23. Explain the importance of bias using a simple decision boundary example.
24. Describe the perceptron learning rule conceptually.
25. What does it mean for a model to learn from data?
26. Explain the difference between a hard threshold activation and a differentiable activation.
27. Why is differentiability important for training modern ANNs?
28. Explain the sigmoid activation function and mention one limitation.
29. Explain the tanh activation function and mention one limitation.
30. Explain ReLU and why it is widely used.
31. What is the dying ReLU problem?
32. How does Leaky ReLU reduce the dying ReLU problem?
33. When is sigmoid commonly used in the output layer?
34. When is softmax commonly used in the output layer?
35. When is a linear output layer used?
36. Explain mean squared error loss.
37. Explain cross-entropy loss.
38. Why is cross-entropy suitable for classification?
39. What is the difference between prediction and loss?
40. Explain how a hidden layer helps solve non-linear problems.

## Section C: Conceptual Understanding

41. Why is an ANN called a composition of functions?
42. Explain how multiple layers allow feature transformation.
43. Why does adding more neurons increase model capacity?
44. Why can too many neurons cause overfitting?
45. What is underfitting in an ANN?
46. What is overfitting in an ANN?
47. How can training loss and validation loss reveal overfitting?
48. Why is data normalization useful before training an ANN?
49. What problems can unscaled input features cause?
50. Explain the difference between parameters and hyperparameters.
51. Give examples of ANN parameters.
52. Give examples of ANN hyperparameters.
53. What is the purpose of weight initialization?
54. Why should all weights not be initialized to the same value?
55. What is vanishing gradient?
56. What is exploding gradient?
57. Why are sigmoid and tanh more prone to vanishing gradients in deep networks?
58. Explain why ReLU helps reduce vanishing gradient issues.
59. What is the purpose of regularization?
60. Explain L1 regularization conceptually.

## Section D: Training and Optimization

61. Explain L2 regularization conceptually.
62. What is dropout?
63. Why does dropout reduce overfitting?
64. What is early stopping?
65. How does early stopping act as regularization?
66. Compare batch gradient descent, stochastic gradient descent, and mini-batch gradient descent.
67. Why is mini-batch gradient descent commonly preferred?
68. What is momentum in optimization?
69. How does momentum help gradient descent?
70. What is an adaptive optimizer?
71. Explain the intuition behind Adam optimizer.
72. What is a local minimum?
73. What is a global minimum?
74. What is a saddle point?
75. Why can saddle points slow down ANN training?
76. What is a loss landscape?
77. Why is ANN optimization usually non-convex?
78. Explain the role of the chain rule in backpropagation.
79. Why does backpropagation compute gradients layer by layer?
80. What does it mean to update weights using gradients?

## Section E: Applied ANN Reasoning

81. Given a binary classification problem, which output activation and loss function would you choose? Justify.
82. Given a multiclass classification problem, which output activation and loss function would you choose? Justify.
83. Given a regression problem, which output activation and loss function would you choose? Justify.
84. A model has high training accuracy but low validation accuracy. What is likely happening?
85. A model has low training accuracy and low validation accuracy. What is likely happening?
86. A model's loss fluctuates heavily during training. Mention two possible causes.
87. A model's training is extremely slow. Mention three possible reasons.
88. A model predicts nearly the same output for all inputs. Mention possible causes.
89. Why might increasing the number of hidden layers improve performance?
90. Why might increasing the number of hidden layers harm performance?
91. How would you decide the number of neurons in a hidden layer?
92. Why is validation data important?
93. Why should test data not be used during training or model selection?
94. Explain accuracy, precision, recall, and F1-score in classification.
95. Why can accuracy be misleading for imbalanced datasets?
96. What is a confusion matrix?
97. What is the difference between binary and multiclass classification in an ANN output layer?
98. Explain how an MLP can solve the XOR problem.
99. State the universal approximation idea in simple words.
100. Design a simple ANN architecture for a tabular classification problem and justify the input layer, hidden layers, activation functions, output layer, and loss function.
