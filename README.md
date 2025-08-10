# Lab-2-Deep-Learning
1)When the no of iterations increate the accuracy will be increase and the error will be reduce.

2)
1.What happens when the number of hidden nodes increases?

Increasing the number of hidden nodes allows the network to learn more complex decision boundaries. Initially, accuracy improves significantly. However, after a certain point, gains diminish, and very large layers may lead to overfitting (though not always visible here due to small dataset size).

2.Can you explain the pattern of the accuracy when the hidden nodes increase?

Accuracy typically increases with more hidden units because the model gains greater expressive power. Small layers (1–2) lack capacity to capture patterns. Medium layers (3–20) perform well. Large layers (50) often achieve highest accuracy but require regularization to avoid overfitting. The pattern is usually: rapid increase → plateau → slight drop or saturation.

