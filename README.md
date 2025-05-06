# HTTP Payload Anomaly Detection using Transformer (Self-Attention)

This project implements an anomaly detection system for HTTP payloads using a Transformer-based encoder-decoder model with self-attention mechanisms. It aims to distinguish between normal and anomalous HTTP requests, which is critical for web security and intrusion detection systems.

## 📂 Files

- `With_Self_Attention_(Transformer)_.ipynb`: Main Jupyter Notebook for training and evaluating the Transformer model.
- `Train_data.csv` and `Test_data.csv`: Datasets containing labeled HTTP payloads (not included here, please add to your local directory).

## 📊 Dataset

The dataset includes HTTP payloads labeled as:
- `0` for normal
- `1` for anomalous

The payloads are converted into sequences using character-level tokenization and padded to uniform lengths.

## 🧠 Model Architecture

- **Encoder-Decoder Transformer**
  - Embedding Layer
  - Positional Encoding
  - Multi-head Self-Attention
  - Feedforward Network
  - Final classification layer for binary classification

## ⚙️ Installation

Make sure you have the following dependencies:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib

🚀 Usage
Clone this repo:
git clone https://github.com/yourusername/http-anomaly-transformer.git
cd http-anomaly-transformer
