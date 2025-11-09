# Fine-Tuning DistilBERT on AG News Dataset

This project demonstrates how to fine-tune the **DistilBERT** model on the **AG News Dataset** for text classification. The implementation is done in a **Google Colab notebook**, making it easy to run and experiment with.

---

## **📌 Project Overview**
- **Model**: DistilBERT (a smaller, faster, and lighter version of BERT)
- **Dataset**: [AG News Dataset](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset) (120,000 news articles, 4 classes)
- **Task**: Text Classification
- **Environment**: Google Colab (GPU recommended)

---

## **🛠 Setup & Installation**
### **1. Open the Colab Notebook**
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fI7pwnglUwOrhG_SeoFauc_8IJIj3YeE?usp=sharing)

### **2. Runtime Setup**
- Ensure you are using a **GPU runtime** in Colab:
  - Go to **Runtime → Change runtime type → Select GPU**

### **3. Install Dependencies**
Run the following in a Colab cell to install required libraries:
```bash
!pip install transformers datasets torch
