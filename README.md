# Forest-Fire-Detection-using-DL

# Forest Fire Detection using Deep Learning

## Week 1: Dataset Exploration and Visualization

### Project Overview
This project focuses on detecting forest fires using deep learning. The dataset used is **The Wildfire Dataset**, which contains labeled images for training a deep learning model.

### Dataset Information
- **Source:** Downloaded from Kaggle using `kagglehub`
- **Size:** ~9.94GB
- **Classes:**
  - `fire`
  - `nofire`
- **Dataset Split:**
  - Training set
  - Validation set
  - Test set

### Code Breakdown
1. **Dataset Download:**
   - Uses `kagglehub` to fetch the dataset.
   - Extracts the files to a local directory.

2. **Checking GPU Availability:**
   - Ensures TensorFlow detects GPU for faster processing.

3. **Dataset Structure & Classes:**
   - Loads dataset paths for train, validation, and test sets.
   - Lists the two available classes.

4. **Data Visualization:**
   - Displays **5 sample images** from both `fire` and `nofire` classes.

### Prerequisites
- Python 3.10
- TensorFlow
- NumPy
- Matplotlib
- KaggleHub

### How to Run
1. Install dependencies:
   
   pip install tensorflow matplotlib numpy kagglehub
2. Run the script:

python week1_dataset_exploration.py

### Next Steps

Implement data preprocessing and augmentation.

Design a Convolutional Neural Network (CNN) for classification.

Train and evaluate the model.
