# Research Project - The size of kernels in a convolutional neural network and its effects on overfitting
**Abstract:**
Convolutional neural networks have a multitude of factors, or hyperparameters, that can be set when creating the architecture. One of them is the kernel sizes used within the network. This study examined the effects the kernel size has on overfitting, a common problem encountered by many machine learning researchers. It was hypothesized that the size of kernels would affect the amount of overfitting. A python program was created in Visual Studio Code using the Tensorflow, scikit-learn, NumPy, and Matplotlib libraries. A single factor analysis of variance (ANOVA) test was performed to determine statistical significant difference and Tukey’s Range Test was performed as a post hoc analysis to determine where the statistical significant difference was between the means of accuracy or loss for each of the groups. This study found that there was a statistically significant difference between the mean accuracy of 5x5 kernel size and 7x7 kernel size as well as the 3x3 kernel size and 5x5 kernel size. The 5x5 kernel size resulted in the greatest mean accuracy. There was a statistically significant difference between the mean loss of the 3x3 and 7x7 kernel sizes as well as the 5x5 and 7x7 kernel sizes. The 7x7 kernel size resulted in the greatest mean loss. The 3x3 kernel size did not achieve the same performance as the 5x5 kernel size because it may not have been able to pick up significant details needed to classify the handwritten digits. Furthermore, the 7x7 kernel size did not achieve the same performance as the 5x5 kernel size because of computational time needed to fine-tune its parameters and potential overfitting to the noise of the data.
