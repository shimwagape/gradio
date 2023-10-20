# Customer Churn Prediction App
Welcome to the Customer Churn Prediction App! This application allows you to predict whether a customer will churn based on various input features. It uses a machine learning model that has been trained on historical customer data.

## Getting Started
To use this app and make predictions, follow the steps below:

## 1.Clone the Repository
First, clone this repository to your local machine. You can do this by running the following command in your terminal or command prompt:

git clone <https://github.com/shimwagape/gradio.git>
## 2. Navigate to the Project Directory
Change your working directory to the project folder:

cd <project-folder>
## 3. Install Required Dependencies
Make sure you have the required Python packages installed. You can install them using pip:


pip install gradio pandas numpy scikit-learn joblib
## 4. Run the App
You can run the Customer Churn Prediction App by executing the provided Python script. Make sure you are in the project directory:

python <app-script>.py
## 5. Use the App
Once the app is running, you can interact with it through your web browser. It provides a user interface that allows you to input various customer data and get predictions for customer churn.

### Input Features
The following are the input features you can adjust to make predictions:

SeniorCitizen: Select 1 for "Yes" and 0 for "No".
Partner: Choose whether you have a partner ("Yes" or "No").
Dependents: Choose whether you have dependents ("Yes" or "No").
Tenure: Input the number of months you have been with Vodafone.
InternetService: Select your internet service type ("DSL," "Fiber optic," or "No").
OnlineSecurity: Choose your online security status ("Yes," "No," or "No internet service").
OnlineBackup: Choose your online backup status ("Yes," "No," or "No internet service").
DeviceProtection: Choose your device protection status ("Yes," "No," or "No internet service").
TechSupport: Choose your tech support status ("Yes," "No," or "No internet service").
StreamingTV: Choose whether you stream TV ("Yes," "No," or "No internet service").
StreamingMovies: Choose whether you stream movies ("Yes," "No," or "No internet service").
Contract: Select your contract type ("Month-to-month," "One year," or "Two years").
PaperlessBilling: Choose whether you use paperless billing ("Yes" or "No").
PaymentMethod: Select your payment method.
MonthlyCharges: Input your monthly charges.
TotalCharges: Input your total charges.
Making Predictions
After inputting the desired values for these features, click the "Predict" button to get a prediction.
Prediction Output
The prediction will be displayed as "Customer will not Churn" (in green) or "Customer will churn" (in red).
Model Information
The app uses a machine learning model that has been trained to predict customer churn. The model file is located in the models directory and is loaded into the app during runtime.

For any questions or issues, feel free to reach out to the project maintainers. Thank you for using the Customer Churn Prediction App!
## Author
SHIMWA Agape Valentin
### email
savalentin75@gmail.com
