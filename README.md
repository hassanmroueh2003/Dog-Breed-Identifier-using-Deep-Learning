# 🐕 Dog Breed Identifier using Deep Learning

This project uses **TensorFlow** and **transfer learning** to build a deep learning model that classifies dog breeds from images. It was developed as a hands-on learning project, so while the implementation may not be fully optimized, it demonstrates key principles in computer vision and neural network training.

> ⚠️ **Note**: This project was designed as part of a self-learning process. The model and setup may not reflect production-level standards but showcase the use of powerful tools like TensorFlow, TensorFlow Hub, and transfer learning.

---

## 🔍 Project Description

- **Goal**: Predict a dog's breed from an image.
- **Dataset**: [Kaggle Dog Breed Identification Dataset](https://www.kaggle.com/c/dog-breed-identification/data)
- **Approach**:
  - Load and preprocess labeled image data.
  - Apply transfer learning with a pre-trained model from TensorFlow Hub.
  - Train a new classifier layer on top of the pre-trained model.
  - Evaluate predictions visually.

---

## 🚀 Key Features

- 📁 Dataset extraction and preprocessing (images + labels)
- ⚙️ TensorFlow Hub integration with MobileNet/Inception (or similar)
- 📊 GPU training and evaluation
- 🧠 Transfer learning with custom classifier
- 📸 Visualization of predicted vs actual dog breeds

---


### 📁 Expected File Structure (for Google Colab users)

When running this notebook on **Google Colab**, make sure your files are organized like this:

```bash
Dog-Breed-Identifier/
├── dog_breed_prediction_hassan_mroueh.ipynb   # (This Notebook)
├── data/
│   └── Dog Vision/
│       ├── train/                             # Folder containing all training images (JPG)
│       ├── labels.csv                         # CSV file with image IDs and breed labels
│       └── sample_submission.csv              # (Optional) Sample submission file
```

To replicate this in Google Colab:

* Create the folders using `os.makedirs(...)`
* Upload files into their respective locations using `files.upload()`
* Ensure all dataset paths in the notebook match this structure (e.g., `"data/Dog Vision/labels.csv"`)

---

