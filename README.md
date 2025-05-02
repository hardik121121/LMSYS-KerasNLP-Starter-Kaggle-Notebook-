# 🏆 LMSYS: KerasNLP Starter - LLM Classification Fine-Tuning 🧠

🚀 **Competition:** LLM Classification Fine-Tuning
🔍 **Model:** DeBERTaV3 (small)
🧪 **Framework:** KerasNLP
📈 **Public Score:** `1.03643`
🎯 **Best Score:** `1.03643`
🥇 **Rank Achieved:** **41 / 200+ participants**

---

## 🧾 Overview

This notebook demonstrates fine-tuning a DeBERTaV3 model for LLM classification using **KerasNLP**. The competition focused on categorizing large language model outputs accurately across several classes. Despite the intense competition, this solution achieved a **Top 20% rank** on the leaderboard. 🔥

---

## 🧰 Tools & Libraries Used

* 🐍 Python
* ⚙️ TensorFlow + KerasNLP
* 🤗 Transformers (for pretrained models)
* 📊 NumPy, Pandas, Scikit-learn (for preprocessing and metrics)
* 📈 Matplotlib & Seaborn (visualizations)
* 💻 Google Colab + P100 GPU

---

## 🏗️ Approach

1. **Data Loading & Cleaning** 📂

   * Handled imbalanced classes and missing labels.
   * Cleaned and tokenized the text data.

2. **Model Selection** 🔍

   * Chose `DeBERTaV3` small variant for a balance of performance and training efficiency.

3. **Fine-Tuning** 🎯

   * Used KerasNLP’s built-in tokenizer and model.
   * Employed stratified training-validation split to preserve class balance.
   * Trained for optimal epochs using early stopping.

4. **Evaluation** 📊

   * Monitored F1 score across all classes.
   * Achieved **Public LB score of 1.03643**, ranking **41st**!

---

## 📦 Outputs

* 📝 Fine-tuned model weights
* 📁 Submission files (CSV)
* 📃 Logs and notebook outputs

---

## 📚 Learnings

✅ KerasNLP is production-ready and easy to integrate.
✅ DeBERTaV3 shows strong performance even in its smaller variants.
✅ Careful preprocessing and early stopping are crucial for generalization.

---

## 🚀 What's Next?

* Try larger DeBERTa variants for potential boosts 🔋
* Experiment with adversarial training and data augmentation 🧬
* Convert to TensorFlow Lite or ONNX for deployment 💡

---

## 🙌 Acknowledgments

Special thanks to **Addison Howard** and the LMSYS community for the starter notebook and guidance! 💙

---

