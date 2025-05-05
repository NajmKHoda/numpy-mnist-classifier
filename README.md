# NumPy MNIST classifier
A NumPy MNIST digit classifier implemented solely using NumPy with cold, hard math.

## Why I made it

Before learning standard AI/ML libraries like PyTorch, I wanted to work with the linear algebra and calculus at the heart of machine learning. This way, I would get a solid mathematical understanding of how machine learning works before looking at higher-level details in PyTorch. I learned important AI algorithms such as:

- Gradient estimation
- Gradient descent
- Backpropagation

## How it was made

1. I watched [3Blue1Brown's amazing series on machine learning](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&si=TlZeMsDixDZc1eZ0).
2. As I watched each video, I took notes on my iPad, noting down important important formulas or visual explanations.
3. I reorganized my notes into a single organized formula sheet with standardized notation for ease of understanding.
4. I created the Google Colab, implemented the formulas, and ran the model on the MNIST dataset---no code examples/tutorials needed.

## Architecture

- **Intermediate activation function:** ReLU
- **Final activation function:** Softmax
- **Gradient descent implementation:** Stochastic gradient descent
- **Weight initialization:** He
- **Layer sizes:** 64 (8 x 8) > 48 > 32 > 10

## Results

### Accuracy: 76.1%

**Cost vs. batch/epoch curve:**

![Sharply declining cost curve](https://github.com/user-attachments/assets/5e27ae43-1154-4eee-8858-7d2099977b82)


**Confusion matrix:**

![Confusion matrix](https://github.com/user-attachments/assets/d46cb0ed-4ce9-481f-9346-17e70f6b81c8)

## Author information

Najm Hoda
Undergraduate Computer Science
University of California, Los Angeles '28
