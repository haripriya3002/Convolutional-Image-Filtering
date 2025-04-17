# Handwritten Digit Recognition using Convolution

This project demonstrates how a basic **Convolutional Neural Network (CNN)** can be used to recognize a self-drawn handwritten digit (in this case, the number **6**) from a black background image. The project is built from scratch using **TensorFlow/Keras** and works with custom image input.

---

## Objective

Recognize a **user-drawn digit '6'** (white on black background) using a trained CNN and visualize intermediate convolutional layers and predictions.

---

## Input Image

- The input is a self-drawn digit '6'
- Black background (`RGB(0,0,0)`)
- White stroke (`RGB(255,255,255)`)
- Resized to 28x28 pixels for compatibility

---

##  Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- OpenCV / PIL (for image preprocessing)
- Matplotlib

---

##  How to Run

1. Clone the repository
2. Install dependencies:
   - pip install tensorflow matplotlib opencv-python
3. Run the notebook Convolution.ipynb
4. Upload your digit image and test the model.
