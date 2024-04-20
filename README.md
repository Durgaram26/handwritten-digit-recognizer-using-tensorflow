# handwritten-digit-recognizer-using-tensorflow
A deep learning model trained to recognize handwritten digits using the MNIST dataset.
Handwritten Digit Recognizer


This project implements a deep learning model to recognize handwritten digits. It utilizes the MNIST dataset for training and testing.



Requirements:
- Python (>=3.6)
- TensorFlow
- NumPy
- Matplotlib
- OpenCV

Installation:
Clone the repository:
git clone https://github.com/Durgaram26/handwritten-digit-recognizer.git
Install the required dependencies:
!pip install -r requirements.txt

Usage:
1. Train the model:
   !python train
2. Test the model:
   !python test
3. Recognize handwritten digits:
   !python recognize.py path/to/your/image.png

Model Architecture:
- Input layer: Flatten layer (784 nodes)
- Hidden layers: Two dense layers with 128 nodes each, ReLU activation function
- Output layer: Dense layer with 100 nodes, Softmax activation function

License:
This project is licensed under the MIT License - see the LICENSE file for details.

