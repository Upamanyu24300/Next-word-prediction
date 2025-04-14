# 🧠 Next Word Prediction using GRU

This project implements a **Next Word Prediction** model using **Gated Recurrent Units (GRU)** — a type of Recurrent Neural Network (RNN). It is trained on Shakespeare's *Hamlet* and is capable of predicting the most probable next word given a sequence of text.

---

## 🚀 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
</p>

---

## 📁 Project Structure

```
📆 Next-word-prediction
🔜 app.py                 # Streamlit web app for prediction
🔜 experiments.ipynb      # Jupyter notebook for training and evaluation
🔜 hamlet.txt             # Dataset: Shakespeare's Hamlet
🔜 next_word_lstm.h5      # Trained GRU model
🔜 tokenizer.pickle       # Tokenizer for text preprocessing
🔜 requirements.txt       # Required dependencies
🔜 README.md              # Project documentation
```

---

## 🧠 Model Overview

- **Architecture**: Embedding layer → GRU layer → Dense softmax output.
- **Data**: Shakespeare's *Hamlet*, formatted and tokenized.
- **Output**: Predicts the next likely word for a given input sequence.

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Upamanyu24300/Next-word-prediction.git
cd Next-word-prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```bash
streamlit run app.py
```

The app will open in your default web browser. You can type in a sentence and the model will suggest the next word!

---

## 📊 Sample Prediction

> **Input:** "To be or not to"  
> **Predicted next word:** *be*

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

Steps:

1. Fork this repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [Streamlit](https://streamlit.io/)
- Shakespeare’s public domain text from [Project Gutenberg](https://www.gutenberg.org/)

---

⭐ If you like this project, give it a star on GitHub!  
📬 For queries or collaborations, feel free to reach out.

