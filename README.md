# 📧 Email Spam Detector 🚨

Welcome to the **Email Spam Detector**! 🎉 This project is a machine learning-powered system designed to classify emails as **spam** or **ham** (not spam) with high accuracy. Built with a **Streamlit** web interface, it makes spotting unwanted emails a breeze! 🌟

---

## 🌟 Overview

Tired of sifting through spam emails? 😩 This project uses machine learning to automatically distinguish between spam and legitimate emails. By leveraging **text preprocessing**, **TF-IDF feature extraction**, and a **Naive Bayes classifier**, it delivers reliable predictions through a user-friendly Streamlit app. 📲

---

## 🎯 Features

| **Feature**                     | **Description**                                                                 |
|---------------------------------|--------------------------------------------------------------------------------|
| 🧹 **Text Preprocessing**       | Cleans and prepares email text for analysis (e.g., removing stopwords, punctuation). |
| 📊 **TF-IDF Feature Extraction** | Converts email text into numerical features using Term Frequency-Inverse Document Frequency. |
| 🤖 **Naive Bayes Classifier**   | Classifies emails as spam or ham with high accuracy.                            |
| 📈 **Evaluation Metrics**       | Measures performance with accuracy, precision, recall, and F1-score.           |
| 🌐 **Streamlit Web Interface**  | Interactive app for real-time email classification.                            |
| 💾 **Model Export**            | Saves trained model and vectorizer as `.pkl` files for easy deployment.        |

---

## 📊 Dataset

The dataset contains email metadata and text content, labeled as:
- **Spam**: Unwanted or malicious emails. 🚫
- **Ham**: Legitimate, non-spam emails. ✅

*(Update with dataset link or source if available)*

---

## 🛠️ Getting Started

Follow these steps to set up and run the Email Spam Detector! 🚀

### 📋 Prerequisites
- Python 3.x 🐍
- Git 🌳
- Streamlit 🌐

### 🛠️ Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mohamed-Teba/Mail-Spam-Detector.git
   cd Mail-Spam-Detector
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit App**:
   ```bash
   streamlit run streamlit_app.py
   ```

4. **Access the App**:
   - Open your browser and navigate to `http://localhost:8501` to start classifying emails! 🎉

---

## 📂 Project Structure

| **File/Folder**         | **Description**                                                                 |
|-------------------------|--------------------------------------------------------------------------------|
| `streamlit_app.py`      | Main Streamlit app for the web interface and live predictions.                  |
| `requirements.txt`      | List of required Python packages.                                              |
| `*.pkl`                 | Exported model and TF-IDF vectorizer files.                                    |
| `README.md`             | Project documentation (you're reading it!) 📜                                  |

---

## 🌈 Future Improvements

- 🧠 Enhance the model with advanced algorithms like SVM or neural networks.
- 📥 Add support for real-time email integration (e.g., Gmail API).
- 📊 Include interactive visualization of classification results.
- ⚡ Optimize for large-scale email datasets.

---

## 👤 Author

**Mohamed Teba**  

---

## 🙌 Acknowledgments

- Thanks to the open-source communities behind **Streamlit**, **Scikit-learn**, and other libraries for their amazing tools! 🙏
- Inspired by the need to keep inboxes clean and secure. 💪

---

## 📜 License

This project is licensed under the MIT License.

---

## 📜 Footer
© 2025 GitHub, Inc. All rights reserved.
