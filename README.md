# 📧 Email Spam Classifier

A Machine Learning project that classifies emails (or SMS messages) as **Spam** or **Ham (Not Spam)**.  
This project includes a **Jupyter Notebook** for data exploration and model training, and a **Flask web application** for deployment.

## 🚀 Features
- Preprocesses raw text messages (cleaning, tokenization, stopword removal, vectorization).
- Trained a supervised ML model (Naive Bayes) for spam detection.
- Saves and loads trained models using **Pickle** (`model.pkl`, `vectorizer.pkl`).
- Flask web app for real-time spam detection.
- Ready for deployment with **requirements.txt**, **setup.sh**, and **Procfile**.

## 📂 Project Structure
```

├── app.py                 # Flask app for web interface
├── sms-spam-detection.ipynb # Jupyter notebook for training & EDA
├── model.pkl              # Trained ML model
├── vectorizer.pkl         # TF-IDF/Count Vectorizer
├── spam.csv               # Dataset
├── requirements.txt       # Dependencies
├── setup.sh               # Setup script
├── Procfile               # Deployment config


## 📊 Dataset
- Dataset: [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)  
- Contains ~5,500 labelled messages (Spam / Ham).  

## ⚙️ Tech Stack
- **Python 3**
- **Pandas, NumPy, Scikit-learn**
- **NLTK**
- **Flask**
- **Jupyter Notebook**

## 📈 Model Performance
- Algorithm: **Multinomial Naive Bayes**  
- Achieved **97% accuracy**, high precision and recall for spam detection.  
(Add updated metrics if you rerun training!)


## ▶️ How to Run

### 1. Clone the repo
```bash
git clone https://github.com/vishalkumar172923/Email-Spam-Classifier.git
cd Email-Spam-Classifier


### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Flask app

```bash
python app.py
```
App will be available at: `http://127.0.0.1:5000/`



## 📌 Future Improvements

* Add support for email datasets with subject + body.
* Try advanced models (SVM, Random Forest, Deep Learning).
* Build a modern frontend UI for the classifier.

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

```

---

👉 Vishal, do you want me to also **add badges (accuracy, GitHub stars, Python version, etc.)** to make it look more professional, or keep it clean and simple?
```

