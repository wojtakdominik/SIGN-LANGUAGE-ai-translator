# SIGN-LANGUAGE-ai-translator
AI-based Sign Language Translator
This project implements an AI-based sign language translator using deep learning techniques to recognize sign language gestures from images and video. The goal is to automatically translate sign language gestures into text or spoken language, making communication easier for the hearing-impaired community.

Features
Image Classification: The model can classify sign language gestures from images using a deep learning model (Convolutional Neural Network - CNN).

Video Processing: After building the initial image classification model, the project was extended to support real-time video processing. The model is capable of detecting and translating sign language gestures from video streams or pre-recorded videos, providing continuous translation.

Preprocessing: The dataset is divided into training, validation, and test sets for optimal model performance.

Real-time Translation: The system can be trained to translate American Sign Language (ASL) gestures into text or voice in real time from both images and videos.

Dataset
The dataset used for training the model consists of images representing different American Sign Language (ASL) letters and symbols. The images are organized into directories, each representing a different letter of the ASL alphabet.

The dataset is split into:

Training Set: 75% of the data is used for training the model.

Validation Set: 10% is used for hyperparameter tuning and model validation.

Test Set: 15% is used to evaluate the model's performance after training.

Requirements
Python 3.x

TensorFlow or PyTorch (depending on your preference)

scikit-learn

OpenCV (for video and image processing)

Matplotlib (for plotting)

Installation
Clone the repository:

bash
Kopiuj
Edytuj
git clone https://github.com/yourusername/sign-language-translator.git
Install required libraries:

bash
Kopiuj
Edytuj
pip install -r requirements.txt
Usage
Prepare the dataset: Place the dataset in the appropriate folder, ensuring it is organized by the classes (e.g., ASL letters).

Train the model: Run the training script to train the model on the sign language dataset.

Test the model: After training, you can evaluate the model's performance on the test dataset.

Translate gestures: Use the trained model to predict sign language gestures from both images and videos:

Image-based Translation: The model can classify static images of gestures.

Video-based Translation: The model can be applied to live video streams or video files to continuously recognize and translate sign language gestures frame by frame.

Model Evaluation
The model is evaluated using metrics such as accuracy and confusion matrix to measure its ability to correctly classify the sign language gestures.

Contributing
