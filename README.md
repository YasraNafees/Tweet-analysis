# Tweet Analysis Web App

A simple web application built using **Gradio** and **Scikit-learn** that predicts the sentiment (Positive or Negative) of a given text input using a machine learning model.

Gradio app screenshot((https://github.com/user-attachments/assets/f91a3eed-4e7a-4015-a573-5b8ff3fd81b9)
465f-a09f-d4bfd99d5cb5)


---

## 🚀 Demo

[Live App on Hugging Face Spaces](https://nafees456-tweet-analysis.hf.space/?__theme=system&deep_link=iv_oUHmAJMw)  
*Click the link above to try it out!*

---

## 📂 Project Structure


---

## 💡 How It Works

1. User enters text in the Gradio interface.
2. Text is transformed into a numerical vector using the TF-IDF vectorizer.
3. The model predicts the sentiment of the text.
4. Output is displayed as **Positive** or **Negative**.

---

## 🧠 Model Details

- **Model Type**: Logistic Regression 
- **Training Data**: Preprocessed text labeled with sentiment
- **Libraries Used**:
  - `scikit-learn`
  - `joblib` & `pickle`
  - `gradio`

---

## ⚙️ Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/sentiment-analysis.git
cd sentiment-analysis


