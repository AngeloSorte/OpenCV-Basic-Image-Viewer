# OpenCV Basics with NumPy 📸

This is a simple Computer Vision project built with OpenCV and NumPy on Google Colab.  
It allows you to load, display, and manipulate images directly in your notebook.

## 🚀 Features
- Load images from local upload
- Display images inside Colab using `cv2_imshow`
- Convert images to grayscale
- Resize and flip images
- Apply Gaussian blur

## 📦 Requirements

Install dependencies with:

pip install -r requirements.txt


📂 How to Use

Open the .ipynb notebook on Google Colab.

Upload an image using the Colab file uploader.

Run the provided cells to process and display the image.

📷 Example

from google.colab import files
uploaded = files.upload()

img = cv2.imread('your_image.jpg')
cv2_imshow(img)

📑 License
Free to use for educational and personal projects.
