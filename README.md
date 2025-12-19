# text-embeddings-rnn-classifier

This project demonstrates the core pipeline for processing text data using Deep Learning. It covers **One-Hot Encoding**, **Word Embeddings**, and building a **Simple RNN** for text classification using Keras and TensorFlow.

## 📂 Project Structure

* `embedding.ipynb`: Implementation of One-Hot encoding and Embedding layers.
* `simplernn.ipynb`: Architecture and training of the Simple RNN model.
* `prediction.ipynb`: Inference logic for making predictions on new sequences.
* `main.py`: Modular Python script for the full training pipeline.
* `requirements.txt`: Project dependencies.

## 🛠️ Technical Stack

* **Framework:** TensorFlow / Keras
* **Preprocessing:** One-Hot Encoding & `pad_sequences`
* **Model Layers:** Embedding, SimpleRNN, Dense
* **Key Hyperparameters:**
* Vocabulary Size: 10,000
* Sentence Length (Padding): 20
* Embedding Dimensions: 100



## 🚀 Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

```

2. **Install dependencies:**
```bash
pip install -r requirements.txt

```


3. **Execution:**
Run `main.py` to train the model or explore the step-by-step logic in the Jupyter Notebooks.

## 🧠 Core Workflow

1. **Tokenization & Padding:** Raw text is converted into integer sequences and padded to a fixed length of 20 to ensure uniform input shape.
2. **Embedding:** Words are mapped to 100-dimensional dense vectors where semantic relationships are captured.
3. **RNN Modeling:** A Simple Recurrent Neural Network processes the sequence to capture temporal dependencies for classification tasks.
