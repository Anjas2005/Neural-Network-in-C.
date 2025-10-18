# 🧠 Simple Neural Network in C ⚙️

<div align="center">
  <img src="https://media.giphy.com/media/l2JIm1br3ewcfx2Xm/giphy.gif" alt="Neural Network Animation" width="400"/>
</div>

<div align="center">

[![Language C](https://img.shields.io/badge/Language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![made-with-love](https://img.shields.io/badge/Made%20with-Love-red.svg)](https://github.com/Anjas2005)

</div>

> A lightweight, from-scratch implementation of a feedforward neural network in pure C. This project demonstrates the fundamental principles of neural networks by teaching a simple model to solve the classic **XOR** problem.

---

## ✨ Features

* **Pure C:** Built with only standard C libraries (`stdlib.h`, `stdio.h`, `math.h`). No heavy dependencies!
* **Feedforward Architecture:** A simple and classic neural network structure with an input layer, a hidden layer, and an output layer.
* **Backpropagation Algorithm:** Learns from its mistakes by propagating errors backward through the network to adjust weights and biases.
* **Sigmoid Activation:** Uses the sigmoid function to introduce non-linearity, allowing it to learn complex patterns.
* **Stochastic Training:** Shuffles the training data for each epoch to prevent the model from getting stuck in local minima and improve generalization.

---

## 🚀 How to Get Started

You can compile and run this project with any standard C compiler like GCC.

### Prerequisites

* A C compiler (e.g., [GCC](https://gcc.gnu.org/))

### Compilation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/Anjas2005/Neural-Network-in-C.git](https://github.com/Anjas2005/Neural-Network-in-C.git)
    cd Neural-Network-in-C
    ```

2.  Compile the C code. The `-lm` flag is necessary to link the math library.
    ```bash
    gcc main.c -o neural_network -lm
    ```

### Execution

Run the compiled executable from your terminal:
```bash
./neural_network
```

---
