# Predicting Student Success in Online Learning Environments using Machine Learning

This project applies machine learning techniques to predict students' academic outcomes (final grades and scores) based on historical data from the **Open University Learning Analytics Dataset (OULAD)**. A graphical user interface (GUI) built with Tkinter allows users to load data, train models, and visualize predictions with ease.

---

## 🎯 Features

- 📂 Upload and preview the OULAD dataset
- 🧹 Preprocess data using label encoding and missing value handling
- 🤖 Train and evaluate:
  - Random Forest Classifier & Regressor
  - Gradient Boosting Classifier & Regressor
- 📊 View performance metrics (Accuracy, Precision, Recall, F1 Score, RMSE)
- 📈 Visualize algorithm comparisons with bar charts
- 🔮 Predict student grade and score from new input data

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/student-success-prediction.git
cd student-success-prediction
````

### 2. Install Dependencies

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Then install the required packages:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, install manually:

```bash
pip install pandas numpy matplotlib scikit-learn
```

> Tkinter is usually bundled with Python. If missing, install via your OS package manager (e.g., `sudo apt install python3-tk` on Debian/Ubuntu).

---

## 🚀 How to Run

Start the GUI by executing:

```bash
python Main.py
```

Once the app launches, you can:

* **Upload OULAD Dataset** – Load your dataset file (CSV)
* **Preprocess Dataset** – Clean and encode data, then split for training/testing
* **Run Random Forest** – Train and test the Random Forest model
* **Run Gradient Boosting** – Train and test the Gradient Boosting model
* **Comparison Graph** – View a visual comparison of model performance
* **Predict Grade & Score** – Make predictions using a new dataset
* **Exit** – Close the app

---

## 📁 Project Structure

```
PREDICTING-STUDENT-SUCCESS-IN-ONLINE-LEARNING/
├── Dataset/               # Folder to store your dataset CSV files
│   └── DatasetLink.txt    # Optional text file with dataset source info or links
├── Main.py                # Main Python script with GUI and ML logic
├── README.md              # Project documentation (this file)
└── requirements.txt       # List of Python dependencies
```

---

## 📊 Example Metrics

After training models, the app displays metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* RMSE (Root Mean Squared Error)

These are shown in the GUI and visualized using bar plots.

---

## 🧾 Dataset Info

You can download the dataset from [Open University Learning Analytics Dataset (OULAD)](https://analyse.kmi.open.ac.uk/open_dataset).

Place the dataset CSV file in the `Dataset/` folder or browse to it using the GUI file picker.

---

## 📷 Screenshots

> *(Add screenshots of the GUI interface, performance chart, and predictions output here if desired)*

---


