# Fake News Detection using Machine Learning

## 📌 Project Overview
This project explores the effectiveness of machine learning models in detecting fake news articles. A logistic regression model was trained on a dataset of 20,000 articles.

## 📂 Dataset
The dataset was obtained from **Kaggle**, containing three files:
- `train.csv`: Used for training the model.
- `test.csv`: Used for evaluating the model.

The dataset labels news articles as **real (1) or fake (0)**.

## 🔍 Challenges & Key Questions
While working on this project, I raised important questions:
1. **Is 20,000 articles enough to generalize to real-world fake news detection?**
2. **What defines 'fake news'?** Does it refer to misinformation, misleading claims, or unverified sources?
3. **Can a machine learning model truly fact-check news?**
4. **How does logistic regression identify fake news?** Is it based on word frequency, text length, or some other pattern?

## 🛠️ Approach
### 1️⃣ **Initial Model: Logistic Regression**
- Used **TF-IDF Vectorization** to convert text into numerical features.
- Trained a **Logistic Regression model** to classify news articles.
- Identified weaknesses, such as reliance on keyword patterns rather than factual validation.

### 2️⃣ **Considering BERT for Improved Contextual Understanding**
- BERT (Bidirectional Encoder Representations from Transformers) understands **sentence structure and meaning** rather than just words.
- Requires GPU acceleration for efficient training.
- More suitable for real-world applications, but **does not inherently fact-check claims**.

## 📌 Key Takeaways
- Traditional models like **Logistic Regression** can detect **textual patterns** in fake news but **struggle with nuanced misinformation**.
- **BERT** can improve **contextual understanding**, but **fact-checking requires external sources**.
- A robust **fact-checking system** needs **external data sources, knowledge graphs, or APIs** to verify claims.

## 📌 How to Run the Project
### 🔹 Clone the Repository
```bash
git clone https://github.comAl-RaoushBasel/Fake-News-Detection.git
cd Fake-News-Detection
```
### 🔹 Install Dependencies
```bash
pip install -r requirements.txt
```
### 🔹 Run the Model

---

## 📸 Suggested Images for LinkedIn Post
1. **Dataset Preview**: A screenshot of the dataset structure.![image](https://github.com/user-attachments/assets/17c6f029-80f3-4d13-8bb8-eef1206bdf7d)

2. **Confusion Matrix**: Show the model’s classification performance. ![image](https://github.com/user-attachments/assets/8653b52f-e997-409b-932b-7ff848ec5ed5)

3. **Word Cloud**: Highlight common words in real vs. fake news. ![image](https://github.com/user-attachments/assets/2083f5b5-f806-452c-90ea-f868f2003392)


---

### ✨ Connect with Me
If you're interested in discussing this project or collaborating, feel free to connect on **[LinkedIn](https://www.linkedin.com/in/basel-al-raoush/)**!
