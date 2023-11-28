Animal classification using facial images with score-level fusion
------------------------------------------------------------------

This project demonstrates image classification using Convolutional Neural Networks (CNN) and the VGG16 pre-trained model. The code includes data augmentation, model training, evaluation, and fusion of predictions from CNN and VGG16.

-------------
Requirements:
-------------

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Install the required packages using the following command:

pip install -r requirements.txt

---------
Data Sets:
---------
This project uses a dataset located at 'D:\\anc\\CV\\HiT_demo_20100820\\dataset'. The dataset is divided into training and validation sets using ImageDataGenerator.

------
Usage :
-------
1. Clone the repository:

   git clone https://github.com/Vidya-msdsm/animal classification.git

2. Navigate to the project directory:
   
   cd your-repository

3. Install the required packages:

   pip install -r requirements.txt

4. Run the main script:

   python main.py
  

   This script performs the following steps:
   - Loads and preprocesses the dataset using ImageDataGenerator.
   - Builds a custom CNN model and trains it on the training set.
   - Evaluates the CNN model on the validation set and displays class-wise images.
   - Loads the VGG16 pre-trained model and fine-tunes it for the classification task.
   - Evaluates the VGG16 model on the validation set and displays class-wise images.
   - Combines predictions from CNN and VGG16 using score-level fusion (averaging).
   - Evaluates the final model and visualizes the confusion matrix.


---
