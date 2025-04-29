# Machine Learning Project: Fashion MNIST
**Submission By:**
- Nabeeha Shafiq (22i-2336)  
- Maha Qaiser (22i-2348)  
- Kainat Khalid (22i-2242)

This project investigates how different regularization techniques affect model performance on the Fashion MNIST dataset. We applied dimensionality reduction using PCA and visualized feature distributions using UMAP and t-SNE. The models evaluated include Neural Networks, Logistic Regression, SVM, Random Forest, and Gradient Boosting.

## Dataset
- **Fashion MNIST**: 60,000 training images and 10,000 test images.
- Each image is 28x28 grayscale, categorized into 10 clothing classes.

## Preprocessing
- Normalized pixel values to [0, 1].
- Split the dataset into 70% training, 15% validation, and 15% testing.
- Flattened images into 784-dimensional vectors for non-neural network models.

## Dimensionality Reduction
- **PCA**: Retained 95% and 98% variance to reduce dimensionality.
- **UMAP and t-SNE**: Used for visual exploration of high-dimensional feature clusters.

## Tools & Libraries
- Python, NumPy, Pandas, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn
