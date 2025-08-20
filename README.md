# Makemore Project

This repository contains my personal implementation of the **Makemore** project, inspired by the video playlist/tutorial series by [Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy).  
The goal of this project is to build a character-level text generation model from scratch, step by step, while experimenting with different neural network architectures.

---

## 📚 About the Project

The **Makemore** series is an educational deep dive into how modern language models are built, starting from the fundamentals and gradually scaling up to more complex architectures.  
In this repository, I have re-implemented the concepts as I followed each video, ensuring that I understand the theory and the code behind it.

This is **my own work** following the tutorials, with added notes, comments, and small modifications where relevant.

---

## 🏗️ Architectures Implemented

Throughout the playlist, the project evolves through multiple architectures:

1. **Bigram Model**  
   - Simple character-level model based only on bigram probabilities.  
   - Serves as a statistical baseline before using neural networks.

2. **Single-Layer Neural Network**  
   - Feedforward neural net for character prediction.  
   - Introduces embeddings and simple training loops.

3. **Multi-Layer Perceptron (MLP)**  
   - Deeper networks with hidden layers and nonlinear activations.  
   - Improved capacity for modeling longer dependencies.

4. **Improved MLPs**  
   - Techniques like BatchNorm, better initialization, and optimizers.  
   - More stable training and better sample quality.

5. **Simple Self-Attention Mechanisms**  
   - First step toward Transformer-like architectures.  
   - Captures longer-range dependencies.

6. **Transformer Block**  
   - Scaled dot-product attention, multi-head attention, residual connections, etc.  
   - This leads to a minimal Transformer architecture.

7. **GPT-like Model**  
   - Final step: a small GPT-style model trained from scratch.  
   - Demonstrates text generation similar to modern LLMs.

---

## 🚀 Features

- Full training code for each architecture  
- Character-level text generation from a training corpus  
- Loss/accuracy plots and generated sample outputs  
- Modular code to easily switch between models  

---

## 📂 Repository Structure

```
.
├── data/               # Training datasets
├── models/             # Implemented architectures
├── notebooks/          # Jupyter notebooks for exploration
├── results/            # Sample generations & training logs
├── utils/              # Helper functions
└── main.py             # Entry point to train and generate
```

---

## 🛠️ Setup & Usage

1. Clone the repo:

```bash
git clone https://github.com/your-username/makemore.git
cd makemore
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run training:

```bash
python main.py --model bigram
```

4. Generate samples:

```bash
python main.py --model transformer --generate
```

---

## ✍️ Notes

- This project is **educational** and follows along with the Makemore video series.  
- I reproduced all steps to deepen my understanding of deep learning fundamentals.  
- Any mistakes, variations, or additional comments in the code are mine.

---

## 🙏 Acknowledgements

- [Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy) for the excellent tutorial series.  
- Open-source deep learning community for resources and inspiration.  
