# 📸 Image Preprocessing with OpenCV

This repository contains a Python-based image preprocessing pipeline. It covers essential techniques for preparing images for machine learning and computer vision tasks.
> 📍 **Implemented in Python**  
> 📓 Script: `image_preprocessing.py`

## 📌 **Project Overview**
The goal of this project is to perform **basic preprocessing** steps on a batch of images, making them ready for downstream tasks like classification or detection. The pipeline supports operations such as resizing, normalization, background removal, and grayscale conversion.

## 🗂️ **Dataset**
- The pipeline works on a folder of input images.  
- We can use **any custom image dataset**.  
- Input and output folder paths can be updated inside the script.

## 🧠 **Image Processing Steps**
1. 📏 **Resizing** – All images are resized to **328×280 pixels**  
2. 🧽 **Normalization** – Pixel values are scaled to the **0–255** range  
3. 🚫 **Background Removal** – Removes **white backgrounds**  
4. 🖤 **Grayscale Conversion** – Converts images to **grayscale**

## 🏋️ **How to Use**
```bash
# 1. Clone the repository
git clone https://github.com/your-username/image-preprocessing.git

# 2. Navigate into the project folder
cd image-preprocessing

# 3. Install the required libraries
pip install opencv-python numpy

# 4. Edit the script to set your input and output folder paths
# (Update 'input_folder' and 'output_folder' in image_preprocessing.py)

# 5. Run the script
python image_preprocessing.py

💻 Requirements
- Python 3.x
- OpenCV
- NumPy

📦 Install all dependencies with:
bash
pip install opencv-python numpy

📝 Notes
⚠️ The background removal function assumes a white background.
If our images have a different background color, adjust the threshold value accordingly in the script.

🧠 What I Learned
- Fundamental image preprocessing techniques
- Using OpenCV and NumPy for batch image processing
- Automating workflows for real-world datasets
- Preparing input data for machine learning models

🙏 Acknowledgements
- OpenCV for image manipulation
- NumPy for array operations
- Python community tutorials that inspired the pipeline structure

📁 Project Structure
image-preprocessing/
├── image_preprocessing.py
├── input_folder/
│   ├── image1.jpg
│   └── image2.jpg
├── output_folder/
│   ├── processed_image1.jpg
│   └── processed_image2.jpg
└── README.md

📜 License
MIT License – Feel free to use or modify this project for educational and non-commercial purposes.
