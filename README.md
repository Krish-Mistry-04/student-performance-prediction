
# Student Performance Prediction

An end-to-end machine learning project designed to predict student performance based on various academic and demographic factors. This project encompasses data preprocessing, model training, evaluation, and deployment through a user-friendly web interface.

## 📌 Project Overview

This project aims to assist educators and institutions in identifying students who may require additional support by predicting their performance levels. By leveraging machine learning techniques, the system analyzes input data to forecast student outcomes, facilitating proactive educational interventions.

## 🧰 Features

- Comprehensive data preprocessing and feature engineering
- Implementation of multiple machine learning models
- Model evaluation using appropriate metrics
- Interactive web application for user input and prediction display
- Modular code structure for scalability and maintenance

## 📁 Project Structure

```
student-performance-prediction/
├── artifacts/               # Stores intermediate artifacts like processed data and models
├── notebook/                # Jupyter notebooks for exploratory data analysis and prototyping
├── src/                     # Source code for data processing and model training
├── templates/               # HTML templates for the web application
├── app.py                   # Flask application script
├── requirements.txt         # Python dependencies
├── setup.py                 # Project setup configuration
└── README.md                # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Krish-Mistry-04/student-performance-prediction.git
   cd student-performance-prediction
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

Start the Flask web application:
```bash
python app.py
```

Navigate to `http://127.0.0.1:5000/` in your web browser to access the application.

## 🧪 Usage

1. Open the web application in your browser.
2. Input the required student information into the form fields.
3. Submit the form to receive the predicted performance outcome.

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook

## 📈 Model Evaluation

The project evaluates multiple machine learning models to determine the most accurate predictor of student performance. Evaluation metrics include accuracy, precision, recall, and F1-score. Detailed analysis and results are documented within the Jupyter notebooks located in the `notebook/` directory.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## 📬 Contact

For any inquiries or feedback, please contact [Krish Mistry](mailto:krishmistry04@gmail.com).
