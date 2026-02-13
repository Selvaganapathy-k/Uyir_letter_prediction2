📝 Tamil Letter Image Processing

This project focuses on preprocessing and analyzing Tamil handwritten / printed letters using OpenCV and Python.

The goal is to prepare Tamil character images for further tasks such as segmentation, recognition, and OCR model training.

🎯 Project Objective

Preprocess Tamil letter images

Convert images to grayscale

Apply thresholding techniques

Reduce noise

Prepare clean binary images

Support future OCR / deep learning models

🛠 Technologies Used

Python

OpenCV

NumPy

Matplotlib

Jupyter Notebook

📂 Project Structure tamil-letter-processing

├── tamil.ipynb 

├── sample_images
    
├── uyir_cnn_model.h5

├── uyir_label_map.json

├── dateset

└── README.md

⚙️ Image Processing Steps

The notebook includes:

1️⃣ Image loading 2️⃣ Color space conversion (BGR → Grayscale) 3️⃣ Binary thresholding 4️⃣ Adaptive thresholding 5️⃣ Noise removal 6️⃣ Morphological operations 7️⃣ Visualization using Matplotlib

▶️ How to Run 1️⃣ Clone the Repository git clone https://github.com/Selvaganapathy-k/Uyir_letter_prediction2 cd tamil-letter-processing

2️⃣ Create Virtual Environment (Optional but Recommended) python -m venv venv venv\Scripts\activate

3️⃣ Install Dependencies pip install opencv-python numpy matplotlib

4️⃣ Run Notebook jupyter notebook

Open tamil.ipynb.

🚀 Future Work

Line segmentation

Character segmentation

Dataset creation

CNN model training

Tamil OCR system

📌 Applications

Historical manuscript digitization

Palm leaf manuscript processing

Handwritten Tamil OCR

Deep learning dataset preparation

👨‍💻 Author

Selvaganapathy K