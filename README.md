
# Image Denoising with Autoencoder - Kirmizi & Siirt Beans

This repository contains an implementation of an **Autoencoder for Image Denoising**, trained on a dataset of **Kirmizi** and **Skirt pistachios**.  
The project demonstrates how autoencoders can be used to remove noise from images and reconstruct cleaner versions. Also compares two models for performance

---

## 📌 Project Overview
- **Goal**: Apply autoencoder neural networks to denoise images of Kirmizi and Skirt pistachios.
- **Method**: 
  - Add random noise to the original dataset.
  - Train an autoencoder model to reconstruct the original clean images.
  - Evaluate the denoising performance visually and quantitatively.
- **Framework**: Implemented in Python using Jupyter Notebook.
- **Note**: This project is part of my **Final Exam (UAS)**.

---

## 📂 Repository Structure
```

.
├── No2_2702249663.ipynb   # Jupyter Notebook implementation of Autoencoder for image denoising
├── requirements.txt       # Dependencies for running the notebook
├── dataset.zip            # Zipped dataset containing Kirmizi & Siirt pistachio images
└── README.md              # Project documentation

````

---

## ⚙️ Requirements
Make sure you have Python 3.8+ installed. Install dependencies with:

```bash
pip install -r requirements.txt
````

Main libraries used:

* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn
* tensorflow
* keras

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/hansardianta/ImageDenoising-Autoencoder.git
   cd ImageDenoising-Autoencoder
   ```
2. Install the requirements:

   ```bash
   pip install -r requirements.txt
   ```
3. Extract the dataset:

   ```bash
   unzip dataset.zip -d dataset
   ```
4. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook No2_2702249663.ipynb
   ```

---

## 📊 Dataset

* The dataset is provided in this repository as a **compressed file (`dataset.zip`)**.
* After extraction, it contains **images of Kirmizi and Siirt pistachios**.
* Images are preprocessed and augmented with random noise before training.
* Autoencoder learns to map noisy images → clean reconstructed images.

---

## ✨ Results

* The autoencoder successfully removes noise from input images.
* Outputs show a clear improvement in visual quality compared to noisy input.


<img width="873" height="455" alt="image" src="https://github.com/user-attachments/assets/7bb9f890-3307-4794-a768-1d9aaccada98" />


---

## 🎥 Video Explanation

This project is part of my **Final Exam (UAS)**.
If you’d like to see my presentation and explanation of this project, check the video here:
👉 [Project Explanation Video](https://drive.google.com/file/d/15YCGWUgb-UhLw3NUtIAFNBZv5fgmtmwl/view?usp=sharing)

---

