# NLP FROM SCRATCH 🖥️:
In this repository I will try to create every basic fundamental algorithm used in nlp from scratch to build my solid foundational skills in NLP .

For Example:
1. Gradient Descent
2. Linear Regression
3. Neural Network
4. Recurrent Neural Networks
5. Backpropagation
6. and even LSTM's or Transformers

Which are currently dominating the Market with products like:

* ChatGPT
* Gemini
* Claude

And many more ...

# ⚙️ Environment Setup Guide (Windows, macOS, Linux)

This guide will help you set up a clean Python environment with the required libraries for data science and machine learning projects.

---

## 📦 Required Packages

- `pandas`  
- `numpy`  
- `scikit-learn`  
- `matplotlib`

You can use either **Conda** or a standard **Python virtual environment (venv)**.

---

## 🐍 Option 1: Using Conda (Recommended)

### ✅ Step-by-Step Instructions

```bash
# Step 1: Create a new conda environment named "nlp"
conda create -n nlp python=3.10 -y

# Step 2: Activate the environment
# Windows
conda activate nlp

# macOS/Linux
source activate nlp

# Step 3: Install required libraries
conda install pandas numpy scikit-learn matplotlib jupyter -y

```

## 🖊️ Option 2: Using Python Virtual Environment (venv)

```bash
# Step 1: Create a virtual environment named "nlp"
python3 -m venv nlp

# Step 2: Activate the environment
# Windows (Command Prompt)
nlp\Scripts\activate

# macOS/Linux
source nlp/bin/activate

# Step 3: Upgrade pip
pip install --upgrade pip

# Step 4: Install required packages
pip install pandas numpy scikit-learn matplotlib jupyter


```

