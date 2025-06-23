# **Building a Neural Network from Scratch using NumPy**

## **Overview**

Hi!  I'm **Hamza Imtiaz**, a BSCS student passionate about **machine learning** and **AI**. This project represents one of the most exciting and insightful learning experiences of my journey so far.

In this project, I challenged myself to build a **neural network completely from scratch** using only **NumPy**. No TensorFlow. No PyTorch. Just raw matrix math, logic, and lots of learning.

---

## **Why I Built This**

As I began learning machine learning, I realized I was using libraries like TensorFlow and PyTorch without fully understanding what was happening underneath. So, I set out to answer one simple question:

> 🧠 *"How do neural networks actually work under the hood?"*

To answer this, I explored research papers, books, and tutorials—and implemented every part of this neural network by hand.

---

## **Key Features**

* Built entirely with **NumPy**
* Supports **forward propagation**, **loss calculation**, and **backpropagation**
* Uses **sigmoid** activation
* Trains on **XOR dataset** (a nonlinear problem)
* Demonstrates how neural networks **learn patterns** from data

---

## **How It Works**

### **Data Flow in the Network**

```
Input (2 numbers)
↓
Hidden Layer (4 neurons with sigmoid activation)
↓
Output Layer (1 neuron with sigmoid activation)
```

### **What It's Learning**

* The network takes in two binary inputs (e.g., 0 and 1) and learns to output the correct XOR result.
* It improves through **gradient descent**, adjusting weights to minimize loss.

---

## **XOR Problem Dataset**

```python
X = [[0, 0],
     [0, 1],
     [1, 0],
     [1, 1]]

y = [[0], [1], [1], [0]]
```

This classic problem highlights why simple linear models fail—requiring a hidden layer to learn the pattern.

---

## **Research That Helped Me Understand It**

This project wouldn’t have been possible without the foundational work of AI pioneers. These are the key resources I relied on:

1. 🧠 *Backpropagation*
   Rumelhart, Hinton & Williams (1986)
   [Learning representations by back-propagating errors](https://www.nature.com/articles/323533a0)

2. 🏫 *Artificial Neurons*
   McCulloch & Pitts (1943)
   [A logical calculus of the ideas immanent in nervous activity](https://www.cs.utexas.edu/~nn/web-pubs/htmlbook/pdfs/mcculloch43logical.pdf)

3. ❌ *Linear Model Limitations (XOR Problem)*
   Minsky & Papert (1969)
   [Perceptrons](https://www.worldcat.org/title/perceptrons/oclc/466756257)

4. ⚙️ *Training Deep Networks*
   Glorot & Bengio (2010)
   [Understanding the difficulty of training deep feedforward neural networks](https://arxiv.org/abs/1001.0785)

5. 🔄 *Depth and Complexity*
   Montufar et al. (2014)
   [On the number of linear regions of deep neural networks](https://arxiv.org/abs/1402.1869)

6. 📘 *Textbook*
   Deep Learning, Chapter 6 - [Feedforward Neural Networks](https://www.deeplearningbook.org/)

---

## **Sample Output**

```
Epoch 0 - Loss: 0.3156
...
Epoch 9000 - Loss: 0.0103

Final predictions after training:
[[0.04]
 [0.97]
 [0.98]
 [0.07]]
```

🚀 The network successfully learns the XOR logic function using only NumPy.

---

## **Key Concepts Explained**

| Term                    | Meaning                                                |
| ----------------------- | ------------------------------------------------------ |
| **Neuron**              | A math function that processes inputs and gives output |
| **Layer**               | A group of neurons working together                    |
| **Activation Function** | A function that decides how a neuron fires             |
| **Backpropagation**     | Algorithm to adjust weights based on loss              |
| **Weights & Biases**    | Internal values that the network updates to learn      |
| **Loss**                | Difference between predicted and actual values         |

---

## **How to Run the Code**

```bash
# Clone this project
git clone https://github.com/HamzaImtiaz03/Build-Neural-Network-From-Scratch

# Navigate to folder
cd Build-Neural-Network-From-Scratch

# Run the script
python main.py
```

---

## **What I Learned**

* How **neural networks think and learn**
* The **math behind backpropagation**
* Importance of **activation functions** and **hidden layers**
* What happens **under the hood** in frameworks like PyTorch/TensorFlow

---

## **What’s Next**

* Add support for **ReLU** activation and deeper networks
* Extend to real-world problems like **image classification**
* Compare results with **Keras/PyTorch** implementations

---

## **Let’s Connect!**

If you're a recruiter, mentor, or fellow learner—I'd love to connect and share ideas!

**Hamza Imtiaz**
📧 [GitHub](https://github.com/HamzaImtiaz03)
🎓 BSCS Student | AI & ML Enthusiast
