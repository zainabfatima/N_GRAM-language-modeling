 🧠 Language Modelling with N-GRAM

A simple implementation of **N-Gram Language Modeling** using Python, designed to demonstrate how text prediction and probability modeling work using uni-grams, bi-grams, tri-grams, and higher-order N-grams.

 📌 Project Overview

Language models predict the next word in a sentence based on the previous ones. This project:

* Explains and builds N-Gram models from scratch
* Calculates probabilities of word sequences
* Predicts the next word based on the trained model
* Supports uni-gram, bi-gram, tri-gram and beyond

---

🚀 Features

* Preprocessing of input corpus
* Flexible support for n-values in N-grams
* Frequency and probability calculation
* Sentence probability computation
* Next-word prediction
* Written in pure Python, Jupyter Notebook format

---

📁 Project Structure

```bash
Language-modelling-with-NGRAM/
├── NGRAMS_IMPLEMENTATION_PYTHON.ipynb  # Main notebook with full implementation
```

---

## ▶️ How to Run

1. **Clone the repository**:

```bash
git clone https://github.com/moaaz12-web/Language-modelling-with-NGRAM.git
cd Language-modelling-with-NGRAM
```

2. **Install Jupyter (if not installed)**:

```bash
pip install notebook
```

3. **Open the notebook**:

```bash
jupyter notebook NGRAMS_IMPLEMENTATION_PYTHON.ipynb
```

4. **Run each cell** to see:

   * Corpus preprocessing
   * N-gram dictionary creation
   * Probability tables
   * Sentence prediction and probability

🧠 How It Works

* Input: A plain-text corpus
* The text is cleaned (lowercased, punctuation removed)
* N-Grams are generated as combinations of `n` consecutive words
* Frequencies of each N-Gram are counted
* Conditional probabilities are computed
* For a given input sequence, the model predicts the most likely next word

---

📤 Input

* Any custom sentence/corpus provided in code.
* Can be edited directly in the notebook.

```python
text = "The cat sits on the mat. The cat eats the mouse."
```

---

## 📈 Output

* N-gram model showing word pairings
* Frequency tables
* Probability distributions
* Predicted next word(s) based on given inputs
* Example sentence generation

---

📚 Example

```text
Input: "the cat"
Predicted Next Word (Trigram): "sits"
```

---

🔖 Suggested Project Name

**"NGramPredictor"** or **"TextFlow N-Gram Model"**

---

Let me know if you'd like a version in Markdown for direct upload or a visual project banner!

👉 [View the main notebook here](https://github.com/moaaz12-web/Language-modelling-with-NGRAM/blob/main/NGRAMS_IMPLEMENTATION_PYTHON.ipynb)

Links: [Documentation](https://docs.askthecode.ai) · [GitHub](https://github.com/askthecode/documentation) · [Twitter](https://twitter.com/askthecode_ai)
