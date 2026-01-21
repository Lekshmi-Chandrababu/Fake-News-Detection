# Fake News Detection 📰

A Machine Learning project that detects whether news headlines are **Fake** or **Real** using Python, Scikit-learn, and Streamlit.

---

## **Project Overview**
Fake news spreads misinformation and can influence opinions. This project uses a **TF-IDF Vectorizer** with a **Machine Learning classifier** to predict whether a news headline is **Real** or **Fake**.  
It also includes a **Streamlit web app** to interact with the model easily.

---

## **Tech Stack**
- **Python** – programming language  
- **Scikit-learn** – Machine Learning library  
- **Streamlit** – for creating interactive web app  
- **TF-IDF Vectorizer** – to convert text into numerical features  

---

## **Project Structure**
Fake-News-Detection/
│
├── app.py # Streamlit app code
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── Fake-News-Detection.ipynb # Jupyter Notebook with code & experiments
├── requirements.txt # Python dependencies

---

## **Installation & How to Run**
1. Clone the repository or download the files  
2. Install dependencies:

```bash
pip install -r requirements.txt
3. Run the Streamlit app:
streamlit run app.py
4. The app interface will open in your browser. Enter a news headline and get the prediction:

REAL ✅ – If news is authentic

FAKE 🚨 – If news is false
