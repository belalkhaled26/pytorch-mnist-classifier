# PyTorch MNIST Digit Classifier

An end-to-end deep learning pipeline built with PyTorch to classify handwritten digits from the MNIST dataset.

## Key Features
- Fully custom neural network built using `torch.nn.Module`.
- Data normalization and batch loading with `torchvision` and `DataLoader`.
- Efficient evaluation loop using `torch.no_grad()`.

## Model Architecture
- **Input Layer:** 784 nodes ($28 \times 28$ flattened grayscale pixels)
- **Hidden Layer:** 128 nodes with ReLU activation
- **Output Layer:** 10 nodes (representing digit classes 0–9)

## Performance Metrics
- **Epochs:** 5
- **Optimizer:** Adam (`lr=0.001`)
- **Loss Function:** `CrossEntropyLoss`
- **Final Training Loss:** ~0.0283
- **Test Set Accuracy:** **97.85%**

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/belalkhaled26/pytorch-mnist-classifier.git](https://github.com/belalkhaled26/pytorch-mnist-classifier.git)
2.Run task1p2.ipynb directly in Google Colab or locally via Jupyter Notebook.
