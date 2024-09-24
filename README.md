# Streamlit-Work-app
📊🔮 Churn Prediction App 💻🎉

Welcome to the Churn Prediction App project! 🚀 This project is designed to predict customer churn using machine learning based on demographic and behavioral data from the Expresso

Churn dataset. 📂📈

🌟 Project Overview :

In this project, I developed an interactive web application using Streamlit 🌐 to predict whether a customer will churn or stay! The app allows users to input customer details and get

real-time predictions 📊✨ using a Logistic Regression model. 🎯

Key Features 🔑:

🔮 Predict customer churn using Logistic Regression.

💅 Stylish user interface with custom HTML & CSS for an enhanced experience.

🖱️ Easy-to-use input fields for customer details.

📊 Data Source:

This project uses the Expresso Churn dataset, which contains information like:

🌍 Region

⏳ Tenure (How long a customer has been subscribed)

🔁 Frequency of recharge

📞 On-net calls

💰 Revenue, and more!

🛠️ Installation

Prerequisites:

Make sure you have these tools installed before running the project:

🐍 Python 3.x

🌐 Streamlit

📦 Pandas

📚 Scikit-learn

➗ Numpy

Step-by-Step Guide 👣:

📌 Usage :
Once you launch the app, you’ll have two options:

📊 Visualize: Explore the data (coming soon).

🔮 Predict: Enter customer details to predict churn.

Example Inputs 🎯:

🌍 Region: Select a region from the dropdown.

⏳ Tenure: Pick how long the customer has been subscribed.

💰 Montant: Enter the amount the customer spends.

🔄 Frequency: Provide how often they recharge or call.

Other inputs like Revenue, ARPU segment, On-net calls, and more!

Click 🔮 Predict, and the app will show if the customer is likely to churn or stay, with colorful visuals! 🎨

🔧 Data Preprocessing :

The dataset went through several preprocessing steps to prepare it for the model:

🧹 Cleaned data: Dropped irrelevant columns like user_id, ZONE1, ORANGE, etc.

📉 Filled missing values with the median.

🔖 Label encoding for categorical variables such as REGION and TENURE.

🧠 Model

I used a Logistic Regression model 🧑‍🔬 for the churn prediction:

Data was split into training and test sets 📊 using train_test_split.

The model was trained using LogisticRegression from scikit-learn.

Predictions are made based on the probability of churn, with a threshold of 0.7 to classify whether a customer will churn.

🎨 Screenshots :

Here are some visual examples of the app:

🌟 App Interface:

🔮 Churn Prediction:

🚀 Future Improvements :

Here’s what I plan to add in future versions of the app:

📊 Data visualization for customer behavior analysis.

⚡ Implement additional machine learning models for comparison (e.g., Random Forest, SVM).

🔍 Feature importance analysis to better understand the data.

🎉 Conclusion :

This app helps companies like Expresso understand whether their customers are likely to churn. By entering customer details, businesses can make data-driven decisions 🧠 based on real-

time predictions. 📈

📧 Contact :

Feel free to reach out if you have any questions or suggestions:

GitHub: Your GitHub Profile 🖥️

Email: oueslatioumayma157@gmail.com 📩
