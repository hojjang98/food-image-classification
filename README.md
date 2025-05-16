# 🍽️ Food Image Classification

> *"I heard computer vision is trending these days..."*

This project started with that simple thought.  
While studying machine learning, I learned from my professor that the field of computer vision (CV) is rapidly gaining momentum and practical importance.  
Curious and excited, I decided to jump into it and explore image classification through this beginner-friendly project.

## 🎯 Project Goal

- Build a food image classifier using CNN and transfer learning.
- Gain hands-on experience with core CV tasks: preprocessing, augmentation, and evaluation.
- Understand the fundamentals of image classification in a practical, applied context.

## 📁 Dataset

- **Source**: Images were collected through Google Image crawling for educational and non-commercial use only.
- **Categories**: A custom subset of food-related categories including fruits, vegetables, and common dishes.
- **Availability**:  
  Image files are **excluded from this repository** to avoid copyright issues.

> ⚠️ All images used in this project were collected solely for educational purposes and remain stored locally.  
> If you want to build a similar dataset, refer to `food-image-crawling.ipynb`.

## 🔧 Techniques Used

- Convolutional Neural Networks (CNN)
- Transfer Learning (e.g., MobileNetV2)
- Image Augmentation (`ImageDataGenerator`)
- Evaluation: Accuracy, Confusion Matrix, Visual Predictions

## 🧱 Project Structure

```bash
food-image-classification/
├── .gitignore                        # Git ignore rules (e.g., images/, .h5 files)
├── best_model.h5                    # Trained model (excluded from future commits)
├── models/                          # Folder for storing model files
├── food-image-crawling.ipynb        # Web crawler using Selenium
├── food-image-classification(WIP).ipynb  # Main training notebook (CNN + Transfer Learning)
├── .ipynb_checkpoints/              # Jupyter auto-save folder
├── .gitattributes                   # Git LFS / text file settings
├── README.md                        # Project overview
```


## 🚫 Notes on Image Usage

- All crawled image data is used strictly for **non-commercial, educational** purposes.
- To ensure proper copyright respect, these assets are **excluded from version control** using `.gitignore`.
- The dataset is **not redistributed**, but the tools to build it are provided in this repository.

---

Feel free to fork this repo and build your own food image classifier!  
Explore, visualize, model — and don’t forget to clean your data! 🍜🧼
