# Project Execution Guide
This project implements a dual-phase cardiovascular intelligence system for:
* ECG-based Myocardial Infarction detection
* Long-term CHD risk and survival prediction
* Streamlit-based integrated frontend

---

## Clone the Repository

```bash
git clone https://github.com/sriijk/Integrated-ECG-MI-and-CHD-Risk-Survival-Prediction.git
cd Integrated-ECG-MI-and-CHD-Risk-Survival-Prediction
```

---

## Dataset Links

**ECG Classification Dataset (PTB-XL):** https://physionet.org/content/ptb-xl/1.0.3/

**CHD Survival Prediction Dataset (Framingham Heart Study):** https://www.kaggle.com/datasets/aasheesh200/framingham-heart-study-dataset

---

## Installation

1. Create a virtual environment (recommended):
    ```bash
    python -m venv venv
    ```
2. Activate the environment:
    **Windows:**
    ```bash
    venv\Scripts\activate
    ```

    **macOS/Linux:**
    ```bash
    source venv/bin/activate
    ```

3. Install required dependencies:
    ```
    pip install -r requirements.txt
    ```

---

## How to Run the Project

### 1. ECG-Based Myocardial Infarction Detection
Open Jupyter Notebook and run:

```bash
IMPROVED_CNN_BiLSTM_MultiHead_Attention.ipynb
```

### 2. Cardiovascular Risk & Survival Prediction
Open Jupyter Notebook and run:

```bash
final_pred.ipynb
```

### 3. Run the Frontend Application
From the project root directory:

```bash
cd frontend
streamlit run main_copy.py
```

The application will open in your browser at: "http://localhost:8501"

---