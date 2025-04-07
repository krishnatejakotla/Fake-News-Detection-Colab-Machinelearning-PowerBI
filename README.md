# 📰 Fake News Detection using Colab ML & Power BI

This project combines **Machine Learning** (via Google Colab) and **Data Visualization** (via Power BI) to detect fake news and analyze patterns between real and fake news articles using natural language features.

---

## 📌 Project Overview

- **Model**: Logistic Regression using TF-IDF vectorization
- **Tooling**: Python (Google Colab), Power BI, Pandas, Scikit-learn
- **Data**: Combined Fake and Real News dataset with 44,954 articles
- **Output**: A predictive ML model and a Power BI dashboard for visual insights

---

## 🛠️ Features

### 🔬 Machine Learning (Colab)
- Preprocessing of news articles (title, text)
- TF-IDF Vectorization
- Model training using Logistic Regression
- Prediction on unseen data
- Model saved as `.pkl` for reuse

### 📊 Power BI Dashboard
- Visual comparison of Fake vs Real news
- Top topics by frequency & authenticity
- Timeline analysis of publishing patterns
- Word cloud keyword analysis by label
- Summary page with insights

---

## 📂 Dataset Access  
The full `Combined_FakeNews.csv` file (100MB+) used in this project is too large to host directly on GitHub.  
You can access and download the dataset from Google Drive here:

🔗 [Download Combined_FakeNews.csv](https://drive.google.com/file/d/1bj_7iHd2qXgfK6U9Gy9QVNugACiN8UdW/view?usp=drive_link)

---

## 📁 Files in Repository

| File | Description |
|------|-------------|
| `collabnews.ipynb` | Google Colab ML notebook used for training the model |
| `Fake News Detection Dashboard PowerBI.pbix` | Power BI Dashboard |
| `.gitattributes` | Git LFS tracking info (auto-generated) |
| `README.md` | You're here! |

---

## 🧠 Insights Extracted

- About **52%** of the news was real, and **48%** fake.
- Fake news often used attention-grabbing terms like "BREAKING", "VIDEO", "SHOCKING".
- Real news used more neutral and location-specific language.
- Fake news saw a significant increase after mid-2016, possibly tied to global political events.

---

## 💼 Author

**Krishna Teja Reddy Kotla**

- 📧 Email: krishnatejareddy.kotla@gmail.com  
- 🔗 [LinkedIn](https://www.linkedin.com/in/krishnatejakotla)

---

## 🧠 Keywords

`Machine Learning` • `Fake News Detection` • `Colab` • `Python` • `TF-IDF` • `Logistic Regression` • `Power BI` • `Dashboard` • `Data Analysis` • `Natural Language Processing`

---

## 📌 License

This project is open-source and free to use for educational and portfolio purposes.
