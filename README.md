# Text2Face: Face Generation from Text Description

## Overview

Text2Face is a deep learning-based application that converts textual facial descriptions into corresponding face images. The system utilizes Natural Language Processing (NLP), TF-IDF vectorization, cosine similarity matching, and Generative Adversarial Networks (GANs) to process user input and identify the most relevant facial image from the dataset.

The application provides a graphical user interface (GUI) where users can upload the dataset, train/load the GAN model, enter a text description, and view the predicted face image.

---

## Features

* Upload and process the CelebA face dataset.
* Extract textual features using TF-IDF Vectorization.
* Train or load a pre-trained GAN model.
* Convert user-entered text descriptions into feature vectors.
* Match descriptions using Cosine Similarity.
* Display the most relevant facial image.
* Interactive GUI developed using Tkinter.
* Image preprocessing and visualization using OpenCV.

---

## Technologies Used

* Python
* TensorFlow / Keras
* Generative Adversarial Networks (GAN)
* TF-IDF Vectorization
* OpenCV
* NumPy
* Scikit-Learn
* Tkinter
* CelebA Dataset

---

## System Workflow

1. Upload the CelebA dataset.
2. Load facial images and corresponding text descriptions.
3. Convert text descriptions into TF-IDF feature vectors.
4. Train or load the GAN model.
5. Enter a facial description through the GUI.
6. Convert the input text into a feature vector.
7. Compare the input description with stored descriptions using cosine similarity.
8. Identify the most relevant facial image.
9. Display the predicted face image.

---

## Dataset

This project uses the CelebA Dataset, which contains a large collection of celebrity face images along with associated facial attributes and descriptions.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Text2Face.git
cd Text2Face
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python Text2Face.py
```

---

## How to Use

1. Launch the application.
2. Click **Upload CelebA Dataset**.
3. Click **Generate Fully Trained GAN Model**.
4. Enter a facial description in the text box.
5. Click **Generate Face from Text**.
6. View the generated/predicted face image.

---

## Example Input

```text
young woman with black hair and smiling face
```

## Example Output

The system displays the facial image that best matches the given textual description.

---

## Applications

* AI-Based Face Retrieval
* Human-Computer Interaction
* Digital Character Creation
* Facial Attribute Analysis
* Computer Vision Research
* Educational Deep Learning Projects

---

## Future Enhancements

* Higher-resolution image generation.
* Transformer-based text embeddings.
* Improved GAN architectures.
* Web-based deployment.
* Multiple image generation options.
* Real-time face editing using text prompts.

---

## Author

**Suban Rao**

B.Tech Computer Science Engineering

---
