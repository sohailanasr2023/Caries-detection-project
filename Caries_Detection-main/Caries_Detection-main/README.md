# Caries_Detection


🦷 Caries Detection Using Deep Learning
This project aims to detect dental caries (tooth decay) in X-ray images using two deep learning models:

A Convolutional Neural Network (CNN) for image classification.

A U-Net model for image segmentation.

These models help in automating the identification of caries, which can support dental professionals in diagnosis.

📁 Project Structure

📂 Caries_Detection/
├── Caries_Detection_CNN.ipynb     # CNN model for classifying X-ray images
├── Caries_Detection_Unet.ipynb    # U-Net model for segmenting caries regions
├── .gitignore                     # Files/folders to be ignored by Git
📌 Features
🧠 CNN Model: Detects presence or absence of caries in X-ray images.

🧠 U-Net Model: Performs pixel-level segmentation to highlight decayed regions.

📊 Accuracy tracking and visualization of model performance.

📸 Handles preprocessing, augmentation, and grayscale image analysis.

🔧 Requirements
Python 3.7+

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

scikit-learn

Install dependencies with:


pip install -r requirements.txt
🚀 How to Run
Clone the repository:


git clone https://github.com/your-username/Caries_Detection.git
Run either notebook:

Caries_Detection_CNN.ipynb to train and evaluate the classification model.

Caries_Detection_Unet.ipynb to train and evaluate the segmentation model.

📊 Dataset
This project uses a dataset of dental X-ray images (grayscale). Please make sure to place your dataset in the correct folder as specified in the notebooks.

Note: Dataset is not included due to privacy/licensing. You may use publicly available dental X-ray datasets or contact for guidance.

🧪 Results
CNN Accuracy: Achieved over 90% accuracy on validation images.

U-Net IOU Score: High-quality segmentation of caries regions.
