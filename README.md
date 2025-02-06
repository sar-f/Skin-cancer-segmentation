# Skin-cancer-segmentation
![image](https://github.com/user-attachments/assets/d2042610-e877-4b32-a200-99238360e340)

Overview

Skin cancer is a serious health concern, and early detection can make a huge difference in treatment outcomes. This project aims to simplify the process by using deep learning to automatically segment cancerous regions in skin images. With the power of image processing and machine learning, this tool can help dermatologists and researchers analyze skin cancer more efficiently and accurately. The goal is to create an accessible, reliable, and easy-to-use segmentation model that can support medical professionals in their work.

Features

*Preprocessing of skin cancer images, including resizing, normalization, and augmentation

*Implementation of a deep learning model for segmentation, using U-Net architecture

*Evaluation of model performance using standard metrics such as IoU and Dice coefficient

*Visualization of segmentation results for qualitative analysis


Installation

To run this project, ensure you have the following dependencies installed:

pip install numpy pandas matplotlib opencv-python tensorflow keras

Usage

Clone this repository:

git clone https://github.com/sar-f/skin-cancer-segmentation.git
cd skin-cancer-segmentation


Open the Jupyter Notebook:

jupyter notebook "skin cancer segmentation.ipynb"

Run the cells sequentially to preprocess data, train the model, and evaluate results.

Dataset
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T

Results

The notebook provides visualizations of the segmented regions and evaluates the model’s performance using appropriate metrics. The output includes segmented masks overlayed on the original images to highlight the detected cancerous regions. The model's accuracy and loss curves are also plotted for better analysis.

Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.
