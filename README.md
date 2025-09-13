# 📝 NLP\_Project\_TextClassification

## 📌 Overview

This project explores **Vietnamese text classification** using modern NLP techniques.
It includes preprocessing, dataset preparation, and fine-tuning transformer-based models (e.g., PhoBERT, BARTpho) for classification tasks such as **sentiment analysis** and **topic categorization**.

The work is part of the course **SUDO CODE – Week 3: Basic ML Techniques for NLP**.

---

## 📂 Project Structure

```
NLP_Project_TextClassification/
│── 250114-nlp-project-textclassification.ipynb   # Main notebook (coded in Kaggle, exported locally)
│── SUDO_CODE_WEEK_3.pdf                          # Project report (theory, NLP tasks, references)
│── README.md                                     # Project documentation
│── data/                                         # (Optional) Local dataset directory if downloaded
│── models/                                       # (Optional) Fine-tuned model checkpoints
```

---

## 📊 Dataset

I use the **Vietnamese Text Classification Dataset** by [Nguyen Van Anh Tuan (2020)](https://www.kaggle.com/datasets/tuannguyenvananh/vietnamese-text-classification-dataset).

* 10,000+ Vietnamese news samples
* 7 categories: Thể thao (Sports), Chính trị (Politics), Đời sống (Life), Kinh doanh (Business), Pháp luật (Law), Công nghệ (Technology), Giáo dục (Education)

### 🔹 How to download:

1. Log into Kaggle and accept the dataset terms.
2. Download and place it under `data/` in your repo.
3. Or load directly in Kaggle notebook with:

   ```python
   !kaggle datasets download -d tuannguyenvananh/vietnamese-text-classification-dataset
   ```

---

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/NLP_Project_TextClassification.git
cd NLP_Project_TextClassification
pip install --upgrade transformers datasets torch scikit-learn
```

---

## 🚀 Usage

### Run in Kaggle

Simply open `250114-nlp-project-textclassification.ipynb` in Kaggle → attach the dataset → run all cells.

### Run locally

1. Ensure dataset is under `data/`.
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook 250114-nlp-project-textclassification.ipynb
   ```
3. Train and evaluate the model inside the notebook.

---

## 📚 References

* Anh, V. (2018). *Underthesea: Vietnamese NLP Toolkit*. [GitHub](https://github.com/undertheseanlp/underthesea)
* Bhatti, R., et al. (2024). *Prompt Engineering for Large Language Models for Different NLP Tasks*. arXiv:2407.12994
* Doan, V. T., et al. (2024). *Investigating Recent Large Language Models for Vietnamese NLP*. arXiv:2405.12819
* Hoang, et al. (2025). *Fine-tuning LLaMA-3 and Gemma on ViMMRC for Vietnamese MRC*.
* Nguyen, D. Q., Pham, T. V., & Nguyen, D. Q. (2022). *BARTpho: Pre-trained Sequence-to-Sequence Models for Vietnamese*. ACL 2022
* Tuan, N. V. A. (2020). *Vietnamese Text Classification Dataset*. [Kaggle](https://www.kaggle.com/datasets/tuannguyenvananh/vietnamese-text-classification-dataset)

👉 Do you want me to make this **more academic-style (for submission)** or **more practical (like a GitHub repo for others to reuse)**?
