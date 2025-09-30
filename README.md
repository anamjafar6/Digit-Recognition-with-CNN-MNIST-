# Handwritten Digit Recognition using CNN (MNIST Dataset)

## Overview
This repository contains a complete machine learning workflow for handwritten digit recognition using the MNIST dataset.  
The project demonstrates dataset exploration, preprocessing, CNN model building, training, evaluation, and interpretation.



## Objectives
- Explore and visualize the MNIST dataset.
- Preprocess data for CNN training.
- Build a CNN with convolutional, pooling, dense, and dropout layers.
- Train and evaluate the model.
- Generate performance metrics including accuracy, confusion matrix, and classification report.



## Dataset
- **Source**: MNIST handwritten digit dataset.
- **Training Set**: 60,000 images of handwritten digits.
- **Testing Set**: 10,000 images.
- **Image Size**: 28x28 grayscale images.
- **Classes**: 10 (digits 0 through 9).



## Project Workflow
1. **Dataset Exploration**
   - Loaded dataset and verified shapes.
   - Visualized sample images.
   - Checked class distribution (balanced dataset).
     
2. **Preprocessing**
   - Normalized pixel values to [0,1].
   - Added channel dimension for CNN.
   - One-hot encoded labels.
   - Created validation split.
     
3. **Model Building**
   - Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Dropout → Dense(Softmax).
     
4. **Compilation**
   - Optimizer: Adam.
   - Loss: Categorical Crossentropy.
   - Metric: Accuracy.
     
5. **Training**
   - Trained on training set with validation monitoring.
     
6. **Evaluation**
   - Test accuracy > 98%.
   - Confusion matrix and classification report generated.
   - Loss and accuracy curves plotted.


## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Results
- Achieved ~99% accuracy on test set.
- Model performs robustly on unseen digits.
- Most misclassifications occur for visually ambiguous digits.



## Author
**Anam Jafar**  
[LinkedIn Profile](https://www.linkedin.com/in/anam-jafar6/)

