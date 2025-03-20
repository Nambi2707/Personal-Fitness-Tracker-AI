# Personal-Fitness-Tracker-AI
Our website provides an AI-powered personal fitness tracker that predicts the number of calories burned during exercise based on user-provided information such as age, gender, BMI, heart rate, body temperature. By leveraging machine learning models, this tool helps individuals monitor their fitness levels and track their progress over time.

🔍Overview

This project is an AI-powered fitness tracking system designed to predict calories burned based on user input. It leverages machine learning models like Random Forest to predict calories burned during physical activities such as walking, running, and other exercises. The system is accessible through a web application, providing an easy-to-use platform for users to track their fitness progress.

🚀 Features

- AI-based calorie burn prediction based on user inputs such as age, BMI, heart rate, body temperature, and exercise duration.
- Utilizes Random Forest Regressor and other machine learning techniques for accurate predictions.
- Web-based application for easy access and interaction.
- Real-time predictions with a user-friendly interface.
- Personalized feedback and insights comparing user data with others.

📂 Folder Structure

/Personal-Fitness-Tracker │── /Datasets # Fitness and exercise datasets used for training │── /Models # Trained AI models (saved files) │── /Notebooks # Jupyter notebooks for model training and testing │── /Screenshots # UI and result images │── app.py # Main application │── requirements.txt # Dependencies │── README.md # Project Overview │── LICENSE # License file │── .gitignore # Files to be ignored in Git

🛠 Technologies Used

- Programming Language: Python 3.12.4
- Machine Learning Libraries: Scikit-learn (Random Forest Regressor)
- Data Processing: Pandas, NumPy
- Web Deployment: Streamlit
- Visualization: Matplotlib, Seaborn
- Miscellaneous: OpenCV (for any potential image processing tasks), SciPy

⚡ How to Run the Project

Clone the repository:


git clone https://github.com/yourusername/Personal-Fitness-Tracker.git
cd Personal-Fitness-Tracker


Install dependencies:


pip install -r requirements.txt


Run the application:


streamlit run app.py


📷 Screenshots

(Add screenshots of the web application interface and model results here)

📜 License

This project is licensed under the MIT License.
