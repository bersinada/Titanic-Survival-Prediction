
# 🚢 Titanic Survival Prediction

An end-to-end machine learning project that predicts passenger survival on the Titanic using Python and scikit-learn.

## 📊 Project Structure

```
Titanic ML/
├── data/
│ └── raw/ # Raw dataset
├── notebooks/ # Jupyter notebooks (EDA, modeling)
├── models/ # Trained models and pipelines
├── src/ # Source code (preprocessing, training)
├── app/ # Streamlit web application
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```

## 🎯 Project Workflow

1. **Exploratory Data Analysis (EDA)**: In-depth analysis and visualization of the dataset
2. **Data Preprocessing**: Handling missing values, feature engineering
3. **Model Development**: Comparison of multiple ML models with hyperparameter tuning
4. **Model Evaluation**: Performance metrics and confusion matrix
5. **Web Application**: Interactive prediction interface with Streamlit

## 📈 Key Findings from EDA

### Most Important Survival Factors:

1. **Gender**: Female survival rate significantly higher than male
2. **Passenger Class**: 1st class passengers had better survival rates
3. **Age**: Children (0-12) had higher survival rates
4. **Family Size**: Passengers with family members survived more than those traveling alone
5. **Embarkation Port**: Cherbourg passengers had highest survival rate (wealthier passengers)

### Missing Data:

- **Age**: ~20% missing
- **Cabin**: ~77% missing
- **Embarked**: <1% missing

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/titanic-survival-prediction.git
cd titanic-survival-prediction

# Install dependencies
pip install -r requirements.txt
```

## 📓 Usage

### Run Jupyter Notebooks

```bash
jupyter notebook
```

Navigate to `notebooks/01_data_exploration.ipynb` to see the EDA.

### Run Streamlit App (Coming Soon)

```bash
streamlit run app/streamlit_app.py
```

## 📊 Model Performance (Coming Soon)

Model performance metrics and comparisons will be available in the notebooks folder.

## 🛠️ Technologies Used

- **Python 3.10+**
- **Pandas & NumPy**: Data manipulation
- **Scikit-learn**: Machine learning
- **Matplotlib & Seaborn**: Data visualization
- **Streamlit**: Web application framework

## 📝 Dataset

The Titanic dataset contains information about passengers including:

- Demographics (age, gender)
- Socio-economic status (passenger class, fare)
- Family information (siblings, parents/children aboard)
- Embarkation details

**Source**: Kaggle Titanic Dataset

## 👤 Author

**Berat Sinan ADA**

- GitHub: [@bersinada](https://github.com/bersinada)
- Linkedin: [Berat Sinan Ada](https://www.linkedin.com/in/berat-sinan-ada-349673219/)

## 📄 License

This project is created for educational purposes.

---

⭐ **Star this repo if you found it helpful!**
