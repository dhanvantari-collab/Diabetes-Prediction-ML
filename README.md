# Diabetes-Prediction-ML
Diabetes prediction using the PIMA Diabetes Dataset and a linear Support Vector Machine (SVM) classifier in Python.



🩺 Diabetes Prediction Using Machine Learning

📌 Project Overview

This project uses Machine Learning to predict whether a person may have diabetes based on medical measurements. It uses the PIMA Diabetes Dataset and a linear Support Vector Machine (SVM) classifier to classify the input data.

🎯 Objectives

- Analyze the PIMA Diabetes Dataset.
- Preprocess and standardize medical data.
- Train a Support Vector Machine (SVM) model.
- Evaluate the model using accuracy scores.
- Predict diabetes status for an individual input.

🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook
- Google Colab

📂 Project Structure

Diabetes-Prediction-ML/

├── /content/Diabetes_Prediction.ipynb

├── /content/diabetes.csv

└── README.md

📊 Dataset

This project uses the PIMA Diabetes Dataset.

The dataset contains medical measurements, including:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

The "Outcome" column is the target variable:

- "0" – Non-diabetic class
- "1" – Diabetic class

⚙️ Methodology

1. Data Collection

Load the diabetes dataset into a Pandas DataFrame.

2. Data Analysis

- Display the first five records.
- Check dataset dimensions.
- Calculate statistical summaries.
- Examine the distribution of target classes.

3. Data Preprocessing

Separate the input features from the target variable and standardize the features using "StandardScaler".

4. Train-Test Split

Split the dataset into:

- 80% training data
- 20% testing data

Stratified sampling is used to preserve the target-class proportions.

5. Model Training

Train a Support Vector Machine (SVM) classifier with a linear kernel.

6. Model Evaluation

Evaluate the model using accuracy scores on both training and testing data.

7. Prediction

Provide eight input measurements to the trained model to predict the corresponding class.

🚀 Installation and Execution

Step 1: Clone the Repository

git clone https://github.com/dhanvantari-collab/Diabetes-Prediction-ML/edit/main/README.md

Step 2: Install Required Libraries

pip install numpy pandas scikit-learn jupyter

Step 3: Prepare the Dataset

Place "/content/diabetes.csv " in the same folder as the notebook.

Step 4: Update the Dataset Path

In the notebook, replace the Google Colab-specific path with:

diabetes_dataset = pd.read_csv("/content/diabetes.csv")

Step 5: Run the Notebook

jupyter notebook /content/Diabetes_Prediction.ipynb

Run the notebook cells in order to train and evaluate the model.

📈 Results

The notebook calculates the training and testing accuracy of the SVM classifier. Run all cells to obtain the actual results.

Performance may vary depending on the dataset and preprocessing. Accuracy alone does not establish clinical reliability.

🔮 Future Enhancements

- Add a confusion matrix and classification report.
- Evaluate precision, recall, and F1-score.
- Compare SVM with Logistic Regression, Decision Tree, and Random Forest models.
- Develop a simple web application for predictions.
- Improve validation and model evaluation.

⚠️ Disclaimer

This project is intended for educational and research purposes only. Predictions are not a medical diagnosis and should not replace professional medical advice.

👨‍💻 Author

Miss. Dhanvantari S. Pingale 

📄 License

Add an appropriate open-source license if you intend to distribute this project publicly.
