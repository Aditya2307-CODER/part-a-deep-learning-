# Part A – Deep Learning

## Fashion Image Classification

**Student:** Aditya Thakur  
**Course:** BBA Fintech and AI  
**Topic:** Deep Learning / Image Classification

### Project Overview

This practical demonstrates how a simple Artificial Neural Network can classify fashion product images using the **Fashion MNIST** dataset.

The project uses **TensorFlow/Keras**, **NumPy**, and **Matplotlib** and is designed as a practical introduction to Deep Learning for BBA AI/ML students.

### Business Scenario

An e-commerce company receives thousands of product images. Instead of manually categorizing every image, a Deep Learning model can predict the product category automatically.

**Input:** Product image  
**Output:** Predicted product category

### Product Categories

- T-shirt/Top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

### Model Architecture

The practical uses a simple neural network:

```text
Input Image (28 × 28)
        ↓
Flatten
        ↓
Dense Layer (64 neurons + ReLU)
        ↓
Output Layer (10 classes + Softmax)
```

### Workflow

1. Import the required libraries.
2. Load the Fashion MNIST dataset.
3. Define the product categories.
4. Visualize sample images.
5. Normalize pixel values from 0–255 to 0–1.
6. Build the neural network.
7. Compile and train the model for 3 epochs.
8. Evaluate the model on unseen test images.
9. Generate predictions for product images.
10. Compare predicted and actual categories.

### Business Applications

The same type of image-classification approach can support:

- Faster product listing
- Reduced repetitive manual work
- More consistent product categorization
- Better product-search experience
- Large-scale image processing

### Important Consideration

Accuracy alone is not enough for business deployment. Incorrect classifications can affect customer experience and product data quality, so human review may still be required for uncertain or high-impact predictions.

### Student Learning Outcomes

After completing the practical, students should understand:

- How images can be used as Deep Learning input
- The role of input, hidden, and output layers
- Basic neural-network training
- Model accuracy and testing
- Image classification predictions
- Business applications and limitations of AI

### Files

- `Deep_Learning_Fashion_Classification_Aditya_Thakur.ipynb` — complete practical notebook
- `README.md` — project documentation

### Submission

The notebook demonstrates Fashion MNIST image classification and includes model training, evaluation, predictions, business interpretation, and student activities.

---

**Author:** Aditya Thakur  
**Course:** BBA Fintech and AI
