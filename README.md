Text2Face: Face Generation from Text Description
Overview

Text2Face is a deep learning-based application that converts textual facial descriptions into corresponding face images. The system utilizes Natural Language Processing (NLP), TF-IDF vectorization, cosine similarity matching, and Generative Adversarial Networks (GANs) to process user input and identify the most relevant facial image from the dataset.

The application provides a graphical user interface (GUI) where users can upload the dataset, train/load the GAN model, enter a text description, and view the predicted face image.

Features
Upload and process the CelebA face dataset.
Extract textual features using TF-IDF Vectorization.
Train or load a pre-trained GAN model.
Convert user-entered text descriptions into feature vectors.
Match descriptions using Cosine Similarity.
Display the most relevant facial image.
Interactive GUI developed using Tkinter.
Image preprocessing and visualization using OpenCV.
Technologies Used
Python
TensorFlow / Keras
Generative Adversarial Networks (GAN)
TF-IDF Vectorization
OpenCV
NumPy
Scikit-Learn
Tkinter
CelebA Dataset
System Workflow
Upload the CelebA dataset.
Load facial images and corresponding text descriptions.
Convert text descriptions into TF-IDF feature vectors.
Train or load the GAN model.
Enter a facial description through the GUI.
Convert the input text into a feature vector.
Compare the input description with stored descriptions using cosine similarity.
Identify the most relevant facial image.
Display the predicted face image.
Dataset

This project uses the CelebA Dataset, which contains a large collection of celebrity face images along with associated facial attributes and descriptions.

Installation
Clone the Repository
git clone https://github.com/your-username/Text2Face.git
cd Text2Face
Install Dependencies
pip install -r requirements.txt
Run the Application
python Text2Face.py
How to Use
Launch the application.
Click Upload CelebA Dataset.
Click Generate Fully Trained GAN Model.
Enter a facial description in the text box.
Click Generate Face from Text.
View the generated/predicted face image.
Example Input
young woman with black hair and smiling face
Example Output

The system displays the facial image that best matches the given textual description.

Applications
AI-Based Face Retrieval
Human-Computer Interaction
Digital Character Creation
Facial Attribute Analysis
Computer Vision Research
Educational Deep Learning Projects
Future Enhancements
Higher-resolution image generation.
Transformer-based text embeddings.
Improved GAN architectures.
Web-based deployment.
Multiple image generation options.
Real-time face editing using text prompts.
Author

Suban Rao

B.Tech Computer Science Engineering
