# 🧠 Sentiment Analysis Project

This project aims to detect toxic or inappropriate user comments using real-time or simulated review data. It uses NLP (Natural Language Processing) and sentiment analysis to classify and visualize user sentiment.

---

## 📁 Project Structure

This project was completed as a team of 5 members, with each handling a different phase of the NLP pipeline:

### 👤 Member 1 – Data Collection & Simulation
- Collected user reviews from sources like Google Play or Kaggle datasets.
- Simulated real-time review streaming using loops in Google Colab.
- Output: `reviews.csv`

### 👤 Member 2 – Text Preprocessing & Cleaning
- Cleaned the data using NLTK, spaCy, and emoji handling.
- Tasks included: lowercasing, stopword removal, punctuation cleaning, tokenization, and lemmatization.
- Output: `cleaned_reviews.csv`

### 👤 Member 3 – Sentiment Analysis
- Implemented sentiment classification using both rule-based (TextBlob/VADER) and machine learning models.
- Evaluated results using accuracy, precision, recall, F1-score.
- Output: `sentiment_results.csv`

### 👤 Member 4 – Visualization & Dashboard
- Visualized sentiment distribution and trends over time using Seaborn, Matplotlib, and Plotly.
- Optional Streamlit dashboard setup.
- Output: graphs, dashboard UI

### 👤 Member 5 – Integration & Reporting
- Combined all steps into a single Google Colab notebook.
- Wrote final documentation, ethical concerns, and presentation slides.

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NLTK
- spaCy
- TextBlob
- emoji
- Scikit-learn
- Seaborn, Matplotlib, Plotly
- Google Colab
- (Optional) Streamlit for interactive dashboard

---

## 💾 Files in This Repository

| File Name | Description |
|-----------|-------------|
| `reviews.csv` | Raw reviews from Member 1 |
| `cleaned_reviews.csv` | Preprocessed text (output of Member 2) |
| `sentiment_results.csv` | Sentiment labels (output of Member 3) |
| `Final_Integrated_Project.ipynb` | The complete integrated Google Colab notebook |
| `report.pdf` | Final report with results |
| `presentation.pptx` | PPT slides for project demo |
| `README.md` | This file |

---

## ✅ How to Run

1. Open the `.ipynb` file in Google Colab
2. Run all cells in order
3. Review the generated CSVs and visualizations

---

## ⚖️ Ethical Use & Limitations
-
- The model may struggle with sarcasm, slang, or mixed languages.
- This tool is meant for educational use and demonstration purposes only.
- Real-world deployment should include fairness, bias checks, and multilingual support.

---

## 👨‍💻 Team Members

- Nikhil Anand (Member 2 – Text Preprocessing)
- Vaibhav Singh (Member 1 - Data Collection & Simulation)
- Shruti Singh ( Member 3 -Sentiment Analysis)
- Jayant Kumar ( Model Training & Output Generation)
- Utsav Raj ( Streamlit Dashboard)

---

## 📌 License

This project is licensed under the MIT License.
