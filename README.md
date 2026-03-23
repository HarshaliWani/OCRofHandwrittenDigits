# OCR of Handwritten Digits

🎯 Overview
An end-to-end handwritten digit OCR workflow that trains a neural network on MNIST and predicts digits from custom handwritten images.

🚀 Features
- MNIST digit classification with 10 output classes and ~ 97.68% test accuracy.
- Custom image inference pipeline for local files (`digit.png`, `digit2.png`, `digit4.png`) with resize, invert, normalize, and predict steps.

🛠 Tech Stack
Python, TensorFlow/Keras, NumPy, Matplotlib, Pillow, Jupyter Notebook

📈 Results
- Test set performance: accuracy 0.9768, loss 0.1117.
- Training set performance: accuracy 0.9952, loss 0.0541.
- Model artifact saved as `mnist_digit_model.h5` and reused for inference.

📋 Setup
1. Create and activate a Python virtual environment.
2. Install dependencies:

```bash
pip install tensorflow numpy matplotlib pillow jupyter
```

3. Launch Jupyter and open `Untitled2.ipynb`.
4. Run all cells in order to:
	- download/load MNIST,
	- train and evaluate the model,
	- save the model (`mnist_digit_model.h5`),
	- predict custom digits from image files.
5. To test your own handwriting, place a grayscale digit image in the project folder and update the filename in the inference cells.