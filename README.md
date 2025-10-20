# 😄 Simple Sentiment Analysis with TensorFlow & Keras

Sentiment Analysis is a **fun part of NLP** where we teach machines to understand emotions from text! 💬  
Imagine giving a sentence to your computer, and it can tell if it’s **happy, sad, angry, or neutral**. Exciting, right? 😎  

---

## 📂 Dataset
We’re using a simple dataset of sentences labeled with emotions:  
[Click here to view dataset](https://github.com/Elzfe09/SentimentAnalysis-DL/blob/main/train.txt)  

---

## 🛠 Steps

1. **Install Libraries**  
   Make sure you have `TensorFlow` and `Keras` installed.  

2. **Load Dataset**  
   Read the dataset into your Python environment.  

3. **Pre-process Dataset**  
   - Label encode the emotions (convert text labels to numbers).  
   - Clean the text if needed.  

4. **Train Prep**  
   - Tokenize the text (convert words to numbers).  
   - Convert sentences to sequences.  
   - Pad sequences to make them all the same length.  

5. **Build Model** 🏗  
   We use **Sequential API** in Keras — it’s like stacking layers one after another! 📚  
   - **Embedding Layer** → converts words into vectors.  
   - **GlobalAveragePooling1D** → summarizes the text’s info.  
   - **Dense Layer** → final layer for predicting the emotion.  

6. **Compile & Train** ⚡  
   - Define loss, optimizer, and metrics.  
   - Train the model on your dataset until it learns patterns.  

7. **Use the Model** 🎯  
   - Give any text input and see what emotion it predicts!  
   - Example: `"I love sunny days!"` → 😊  

---

## 🔧 Techniques Used
- **TensorFlow** → powerful library for building AI models  
- **Keras** → easy-to-use high-level API for neural networks  
- **Sequential Model** → simple stack of layers for **fast prototyping**  

---

✨ **Tip:** The Sequential model is like a conveyor belt — input goes in one end, passes through layers, and comes out as output, making it very intuitive for beginners!  

