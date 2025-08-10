# Lab 2 - Deep Learning

## 1. Effect of Increasing the Number of Iterations

When the number of **iterations** increases:

* **Accuracy** tends to increase.
* **Error** tends to decrease.

This happens because the model gets more opportunities to adjust its weights and reduce the loss function through repeated training.

---

## 2. Effect of Increasing the Number of Hidden Nodes

### **Q1:** What happens when the number of hidden nodes increases?

* Increasing hidden nodes allows the network to learn more **complex decision boundaries**.
* Initially, **accuracy improves significantly**.
* After a certain point, **gains diminish**.
* Very large hidden layers may lead to **overfitting** (although this might not be obvious in small datasets).

---

### **Q2:** What is the pattern of accuracy when hidden nodes increase?

The general pattern is:

1. **Small layers (1–2 nodes):**

   * Lack capacity to capture patterns.
   * Accuracy is low.

2. **Medium layers (3–20 nodes):**

   * Perform well and capture more complex features.
   * Accuracy improves rapidly.

3. **Large layers (50+ nodes):**

   * Often achieve the highest accuracy.
   * May require **regularization** to avoid overfitting.
   * Accuracy tends to **plateau** and may slightly drop due to overfitting risk.

**Summary Pattern:**
📈 Rapid increase → 📊 Plateau → 📉 Slight drop or saturation.


