# 🧠 MNIST Digit Classifier using TensorFlow & Kerasm 

This project implements a simple neural network for handwritten digit classification using the MNIST dataset. The model is built with TensorFlow and Keras, achieving high accuracy in recognizing digits (0-9).


```bash
Epoch 10/10  
1875/1875 ━━━━━━━━━━━━━━━━ 1s 633us/step - accuracy: 0.9973 - loss: 0.0078  
```

##Test Accuracy: 98.52%

## 🚀 Features
- ✅ Loads and preprocesses the MNIST dataset (normalization).
- ✅ Builds a Sequential neural network with a Flatten layer and Dense layers.
- ✅ Uses `ReLU` activation for the hidden layer and `softmax` for the output layer.
- ✅ Compiles the model with Adam optimizer and sparse categorical cross-entropy loss.
- ✅ Trains the model for 10 epochs, achieving ~99.7% accuracy.
- ✅ Predicts and visualizes a sample test image.

## 🛠 Technologies Used
- Python  
- TensorFlow/Keras  
- Matplotlib  

## 📥 Installation
Make sure you have Python installed, then install dependencies:  

```bash
pip install tensorflow matplotlib
```

▶️ Usage
Run the script to train the model and make a prediction:

```bash
bash
Copy
Edit
python mnist_classifier.py
```



Sample MNIST Images

![MnistExamples](https://github.com/user-attachments/assets/06ffadc0-4367-4abe-bb0c-3b03c5d97728)

![Screenshot 2025-02-06 at 6 14 36 PM](https://github.com/user-attachments/assets/3693f641-7ab0-44f1-b187-dbd3bee10426)


