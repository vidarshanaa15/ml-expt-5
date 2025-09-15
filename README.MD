# Experiment 5:  Perceptron vs Multilayer Perceptron (A/B Experiment) with Hyperparameter Tuning

## 🎯 Objective
To implement and compare the performance of two neural network models:
- Model A: Single-Layer Perceptron Learning Algorithm (PLA)
- Model B: Multilayer Perceptron (MLP) with hidden layers and nonlinear activations
and to select and justify hyperparameters such as activation functions, cost functions, optimizers, learning rates, number of hidden layers, and batch sizes through systematic tuning.

---

## 🧰 Tools & Libraries Used
- **Python 3.10+** – Primary language for implementation
- **NumPy** – Efficient numerical operations and handling of arrays
- **Pandas** – For handling datasets and storing experimental results
- **Scikit-learn** – Provided baseline Perceptron model, data splitting, and evaluation metrics
- **TensorFlow / Keras** – For implementing and training the MLP with flexible hyperparameter tuning
- **Matplotlib** – For performance visualization (loss curves, accuracy plots)

---

## 📁 Folder Structure
```bash
ml-expt-5/
├── README.md                        # Overview, tools, file summary, run instructions
├── datasets/
│   ├── Img                          # Folder containing input images
│   └── english.csv                  # Input image path / Output label
├── Experiment-5/
│   ├── expt-5.ipynb                 # Implementation notebook
├── screenshots/
│   ├── expt-5_4_3.png             
│   ├── expt-5_5_2.png
│   ├── expt-5_6_1.png
│   └── expt-5_7_1.png
├── Assignment5_ML_Vidarshanaa.pdf  # Lab report
├── Assignment5_ML_Vidarshanaa.tex  # Latex report
├── expt5.bib                       # Citations
└── requirements.txt                # Python packages and versions used
```

## 🚀 Instructions to Execute the Code

1. **Clone the Repository**
```bash
   git clone https://github.com/vidarshanaa15/ml-expt-5.git
   cd ml-expt-5
```

2. **Open the Notebooks**
- **Using Google Colab:**
  - Go to Google Colab
  - Click File > Upload Notebook and upload any .ipynb file from the Experiment-5 folder
  - *Or* paste the GitHub URL directly in Colab to open from repo
    
- **Running Locally with Jupyter Notebook:**
  - Install required packages:
  ```bash
  pip install -r requirements.txt
  ```
  - Then run
  ```bash
  pip install notebook
  jupyter notebook
  ```
  - Navigate to the Experiment-5 folder and open a notebook in your browser

## 📈 Model Performance  

### Perceptron Learning Algorithm (PLA)
- **Epochs:** `30`  
- **Learning Rate:** `0.01`  
- **Test Accuracy:** `0.1774`  
- **Precision:** `0.2708`  
- **Recall:** `0.1774`  
- **F1-score:** `0.1576`  

### Multilayer Perceptron (MLP) – Best Configuration
- **Configuration:** `activation=relu, optimizer=adam, lr=0.001, batch_size=32`  
- **Epochs:** `25`  
- **Validation Accuracy:** `0.2878`  
- **Test Accuracy:** `0.2977`  
- **Precision:** `0.3207`  
- **Recall:** `0.2977`  
- **F1-score:** `0.2752`

## 🙌 Credits

This experiment is part of the course **“ICS1512-Machine Learning Algorithms Laboratory”** at **SSN College of Engineering**.
