# 📰 Fake News Detection Web App

A **Machine Learning–powered Fake News Detection application** built using **Python, Scikit-learn, and Streamlit**. The app allows users to enter news text and instantly predicts whether the news is **Real** or **Fake**.

---

## 🚀 Live Demo

Deployed on **Streamlit Cloud**

> 🔗 *https://fake-new0.streamlit.app/*

---

## 📌 Features

* 🔍 Detects **Fake vs Real News** using ML
* 🧠 Trained using **Natural Language Processing (NLP)** techniques
* ⚡ Fast and lightweight **Streamlit UI**
* ☁️ Cloud deployed (Streamlit Community Cloud)

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **Backend / ML:** Python, Scikit-learn
* **Data Processing:** NumPy, Pandas
* **Visualization:** Altair
* **Model Serialization:** Joblib

---

## 📂 Project Structure

```text
fake-news/
|   app.ipynb             #colab
│── app.py                # Main Streamlit application
│── model.pkl / model.joblib  # Trained ML model
│── vectorizer.jb         # Text vectorizer
|-- lr_model.jb            
│── requirements.txt      # Dependencies
│── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup (Local)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/surya323-ma/Fake-news.git
cd Fake-news
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the App

```bash
streamlit run app.py
```

---

## 🧠 How It Works

1. User enters news text
2. Text is preprocessed (tokenization, vectorization)
3. ML model predicts authenticity
4. Result displayed as **Fake ❌** or **Real ✅**

---

## 📊 Model Details

* Algorithm: *(e.g., Logistic Regression / Naive Bayes / Random Forest)*
* Feature Extraction: TF-IDF Vectorizer
* Training Data: Fake & Real news datasets

---

## 🧪 Sample Input

```text
Breaking News: Scientists discover a new planet capable of supporting life.
```

### Output

```
Prediction: REAL NEWS ✅
```

---

## ☁️ Deployment (Streamlit Cloud)
the application is successfully deployed on Streamlit Community Cloud 🎉
🔗 Live App URL: https://fake-new0.streamlit.app/

1. Push code to GitHub
2. Go to [https://streamlit.io/cloud](https://streamlit.io/cloud)
3. Select repository
4. Set `app.py` as entry point
5. Deploy 🚀

---

## ❗ Common Issues

* Ensure **model files** are committed to GitHub
* Use **Python 3.10+ compatible dependencies**
* Keep `requirements.txt` minimal

---

## 👤 Author

**Surya Omar**
🎓 Machine Learning & Python Developer

* GitHub: [https://github.com/surya323-ma](https://github.com/surya323-ma)

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

