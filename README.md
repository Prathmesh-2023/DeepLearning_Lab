# Deep Learning Lab

A collection of hands-on Jupyter notebooks covering the fundamentals of Neural Networks and Deep Learning, including CNNs, RNNs, LSTMs, Autoencoders, GANs, and practical machine learning applications.

This repository contains implementations, experiments, and visualizations developed as part of the Deep Learning Lab coursework.

## 📚 Practicals

| No. | Practical | Description |
|---|---|---|
| 01 | [Basic Neural Network](Practical_1_BasicNeuralNetwork.ipynb) | TensorFlow tensors and neural network fundamentals |
| 02 | [Linear Regression](Practical_2_linearRegression.ipynb) | Linear regression, prediction, and error evaluation |
| 03 | [Deep Feedforward Neural Network](Practical_3_DeepFeedForwardNeuralNetwork.ipynb) | Deep neural networks for classification |
| 04 | [Regularization & Dropout](Practical_4_Regularization%26Dropout.ipynb) | Preventing overfitting using regularization and dropout |
| 05 | [Hyperparameter Tuning](Practical_5_HyperParameter_Tuning.ipynb) | Optimizers and neural network hyperparameter experimentation |
| 06 | [Handwritten Digit Recognition using CNN](Practical_6_HandWrittenDigitRecognition_usingCNN.ipynb) | CNN-based MNIST digit classification |
| 07 | [Dog Breed Classification](Practical_7_DogBreedClassification.ipynb) | Image classification for dog breeds |
| 08 | [LSTM Stock Prediction](Practical_8_LSTM_StockPrediction.ipynb) | Time-series forecasting using LSTM |
| 09 | [Slot Filling using RNN](Practical_9_SlotFilling_RNN.ipynb) | Sequence labeling using recurrent neural networks |
| 10 | [Credit Card Fraud Detection](Practical_10_CreditCardFraudDetection.ipynb) | Fraud detection using deep learning |
| 11 | [Convolutional Autoencoder](Practical_11_ConvolutionalAutoencoder.ipynb) | Image reconstruction using convolutional autoencoders |
| 12 | [Generative Adversarial Network](Practical_12_GAN.ipynb) | Generating handwritten digits using GANs |
| — | [Market Basket Analysis](MarketBasketAnalysis.ipynb) | Frequent itemset mining and association rules using Apriori |

## 🧠 Topics Covered

- Neural Network Fundamentals
- Linear Regression
- Feedforward Neural Networks
- Backpropagation and Model Training
- Regularization and Dropout
- Hyperparameter Optimization
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Long Short-Term Memory (LSTM)
- Time-Series Forecasting
- Image Classification
- Credit Card Fraud Detection
- Convolutional Autoencoders
- Generative Adversarial Networks (GAN)
- Association Rule Mining

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| TensorFlow / Keras | Deep learning and neural network development |
| NumPy | Numerical computations |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Preprocessing and model evaluation |
| Jupyter Notebook | Interactive development |
| yfinance | Historical stock market data |
| mlxtend | Apriori algorithm and association rules |

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Prathmesh-2023/DeepLearning_Lab.git
cd DeepLearning_Lab
```

### 2. Create a virtual environment

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install --upgrade pip

pip install tensorflow numpy pandas matplotlib seaborn scikit-learn yfinance mlxtend jupyter
```

Use a Python version supported by your installed TensorFlow release.

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any practical notebook and execute the cells sequentially.

## 📂 Dataset Requirements

Some practicals use built-in datasets, while others require additional files or internet access.

| Practical | Dataset |
|---|---|
| CNN Digit Recognition | MNIST |
| Dog Breed Classification | Dog image dataset |
| LSTM Stock Prediction | Historical AAPL stock data via yfinance |
| Credit Card Fraud Detection | creditcard.csv |
| Regularization | Housing.csv |
| Hyperparameter Tuning | California Housing dataset |

**Note:** Download the required external datasets separately and place local CSV files in the working directory expected by the respective notebook.

## 📖 Suggested Learning Path

For a structured learning experience, follow this progression:

1. **Fundamentals:** Neural Networks and Linear Regression.
2. **Deep Learning:** Feedforward Networks, Regularization, and Hyperparameter Tuning.
3. **Computer Vision:** CNNs and Image Classification.
4. **Sequence Learning:** RNNs and LSTMs.
5. **Applied Deep Learning:** Fraud Detection and Stock Prediction.
6. **Generative Models:** Autoencoders and GANs.
7. **Data Mining:** Market Basket Analysis.

## 📁 Repository Structure

```text
DeepLearning_Lab/
│
├── MarketBasketAnalysis.ipynb
│
├── Practical_1_BasicNeuralNetwork.ipynb
├── Practical_2_linearRegression.ipynb
├── Practical_3_DeepFeedForwardNeuralNetwork.ipynb
├── Practical_4_Regularization&Dropout.ipynb
├── Practical_5_HyperParameter_Tuning.ipynb
├── Practical_6_HandWrittenDigitRecognition_usingCNN.ipynb
├── Practical_7_DogBreedClassification.ipynb
├── Practical_8_LSTM_StockPrediction.ipynb
├── Practical_9_SlotFilling_RNN.ipynb
├── Practical_10_CreditCardFraudDetection.ipynb
├── Practical_11_ConvolutionalAutoencoder.ipynb
└── Practical_12_GAN.ipynb
```

## 🎯 Objective

The objective of this repository is to understand deep learning concepts through practical implementations, explore different neural network architectures, and apply them to real-world machine learning problems.

## 👨‍💻 Author

**Prathmesh Durge**

GitHub: [@Prathmesh-2023](https://github.com/Prathmesh-2023)

---

⭐ If you find this repository useful, consider giving it a star!
