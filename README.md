# 📰 Fake News Detection using LSTM and GloVe

This project focuses on detecting fake news articles using deep learning techniques. We use a **Bidirectional LSTM (BiLSTM)** model with **GloVe word embeddings** to classify news as fake or real.

---

## 📁 Dataset

We used the **WELFake Dataset** containing labeled real and fake news articles.

🔗 Dataset Drive Link: [WELFake_Dataset.csv (Google Drive)](https://drive.google.com/file/d/1VfS9VPMdBV0gatEKwn78Gdd8qlRtlp1u/view?usp=drive_link)

> Note: Due to GitHub file size limitations, large files like the dataset and GloVe vectors are **not included** in this repository.

---

## 🔤 Word Embeddings

We use **GloVe (Global Vectors for Word Representation)** - 100d pretrained embeddings.

🔗 GloVe File: [glove.6B.100d.txt (Google Drive)](https://drive.google.com/file/d/1f9f5jFTGzmBhYBzSrJWtpodioUGpSB7q/view?usp=drive_link)

---

## 🧠 Model Architecture

- Input Layer: Tokenized news headlines/text
- Embedding Layer: GloVe 100d embeddings
- BiLSTM Layer
- Dense Layer with dropout
- Output: Binary classification (Fake / Real)

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📓 Notebook

The main code is implemented in:  
📘 `Bi-Lstm.ipynb`

You can run the notebook in **Google Colab** or locally in **Jupyter Notebook**.

---

## 🚫 Files not included in repo

The following files are large (>100MB) and **excluded** from GitHub:

- `WELFake_Dataset.csv` (≈234 MB)
- `glove.6B.100d.txt` (≈331 MB)

To use the project:
1. Download these files from the Google Drive links above
2. Place them in the root folder

---

## 🛠 Requirements

- Python 3.7+
- pandas
- numpy
- nltk
- tensorflow / keras
- sklearn
- matplotlib / seaborn

Install requirements:

```bash
pip install -r requirements.txt
