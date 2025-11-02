# Machine-Learning-Freecodecamp
All projects completed as part of freeCodeCamp's Machine Learning with Python certification course. I had fun while learning on freecodecamp personally, it is genuinely a great platform to learn by doing. I have enlisted 4 projects which includes:

## Project 1: Cat-Dog Classifier Model

### Overview
This project implements a **Convolutional Neural Network (CNN)** using TensorFlow and Keras to classify images as either cats or dogs. The model is trained on a dataset provided by freeCodeCamp containing labeled images of cats and dogs.

### Key Features
- **Deep Learning Architecture**: Utilizes CNN layers including Conv2D, MaxPooling2D, Flatten, Dense, and Dropout for robust image classification
- **Image Preprocessing**: Implements data augmentation and normalization techniques using ImageDataGenerator
- **Dataset**: Uses the freeCodeCamp cats and dogs dataset with training, validation, and test splits
- **Performance Optimization**: Configured with batch processing (batch_size=128) and optimized training parameters

### Technical Specifications
- **Framework**: TensorFlow/Keras
- **Model Type**: Convolutional Neural Network (CNN)
- **Input Size**: 150x150 pixel images
- **Training Epochs**: 15
- **Batch Size**: 128
- **Dataset Split**: 
  - Training: 2000 images (2 classes)
  - Validation: 1000 images (2 classes)
  - Testing: 50 images

### Libraries Used
- **TensorFlow/Keras**: For building and training the neural network
- **NumPy**: For numerical computations and array operations
- **Matplotlib**: For data visualization and plotting training metrics
- **SciPy**: For additional scientific computing functions

### Implementation Highlights
- Binary classification approach for distinguishing between cats and dogs
- Image rescaling and normalization (rescaling factor: 1/255)
- Structured data loading with proper directory organization
- Model evaluation on separate test dataset

---

## Other Projects
2. **Book Recommendation Model** - Collaborative filtering system for book recommendations
3. **SMS Text Classifier** - Natural language processing model for spam detection
4. **Linear Regression Health Costs Calculator** - Predictive model for healthcare cost estimation

I worked on these projects on Google Colab notebook (cloud-based version of Jupyter notebook).

### Libraries Used Across Projects
- **Pandas** – for data analysis and manipulation
- **NumPy** – for numerical operations
- **Matplotlib** – for data visualization
- **Seaborn** – for statistical plotting (used in some visualizations)
- **Scikit-learn (sklearn)** – for machine learning algorithms like KNN, train-test split, and model evaluation

## 🏆 Certificate

![Certificate](./certificate.png)