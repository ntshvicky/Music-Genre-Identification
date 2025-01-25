# 🎵 Music Genre Identification Using Deep Learning

This project focuses on building a **Music Genre Identification System** using **Deep Learning**. The goal is to classify audio files into their respective genres based on their features. The system is trained on a dataset of songs categorized by genre and achieves high accuracy in identifying genres for unseen audio files.

---

## 📂 Dataset
The dataset used for this project is the **GTZAN Music Genre Dataset**, which contains 10 genres:
- **Genres**: Blues, Classical, Country, Disco, Hiphop, Jazz, Metal, Pop, Reggae, and Rock.
- Each genre folder contains 100 `.au` files of 30 seconds each.

The dataset can be downloaded from [this link](https://www.dropbox.com/s/4jw31k5mlzcmgis/genres.tar.gz?dl=0).

---

## 💡 Project Highlights

### 1. **Audio Preprocessing**:
   - Extract **Mel-spectrograms** from audio files as features.
   - Applied **data augmentation** to improve generalization by:
     - Adding noise
     - Time stretching
     - Pitch shifting

### 2. **Deep Learning Model**:
   - Built a **Convolutional Neural Network (CNN)** to classify audio genres.
   - Implemented regularization techniques like Dropout and L2 to prevent overfitting.

### 3. **Performance**:
   - Achieved **90% validation accuracy**.
   - Trained for up to **500 epochs** with early stopping and learning rate scheduling.

---


## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/ntshvicky/Music-Genre-Identification.git
cd Music-Genre-Identification
```