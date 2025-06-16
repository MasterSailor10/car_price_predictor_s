🚗 Car Price Predictor

🔗 Repository: MasterSailor10/car_price_predictor_s

🚀 Overview

The Car Price Predictor is a machine learning-based web application that estimates the price of a used car based on various features such as brand, model, year of manufacture, fuel type, and kilometers driven. The application is built using Flask for the backend and Linear Regression for prediction.

🛠️ Features

✔️ Accurate Car Price Prediction based on historical data. ✔️ Machine Learning Model trained using Linear Regression. ✔️ Flask Web Application with an easy-to-use interface. ✔️ Interactive UI for entering car details. ✔️ Live Deployment on Render for real-time usage.

📂 Project Structure

car_price_predictor_s/ │── templates/ # HTML templates for the web app
│── app.py # Flask web application
│── Cleaned Car.csv # Preprocessed dataset
│── LinearRegressionModel.pkl # Trained ML model
│── requirements.txt # Python dependencies
│── .gitignore # Ignored files
│── README.md # Project documentation

⚙️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/MasterSailor10/car_price_predictor_s.git cd car_price_predictor_s

2️⃣ Create & Activate Virtual Environment (Optional but Recommended)

python -m venv venv source venv/bin/activate # On macOS/Linux venv\Scripts\activate # On Windows

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run the Application

python app.py Visit http://127.0.0.1:5000/ in your browser to access the web app.

🎯 How It Works

1️⃣ Enter Car Details – Provide specifications like year, fuel type, kilometers driven, and brand.

2️⃣ Predict Price – The model estimates the resale value based on the input.

3️⃣ Get Insights – Users can make informed decisions while buying or selling a car.

🔍 Machine Learning Model

Algorithm Used: Linear Regression Dataset: Cleaned car price dataset (Cleaned Car.csv). Pretrained Model: Stored as LinearRegressionModel.pkl.

🔗 Live Deployment

The application is deployed on Render. Try it out here: https://car-price-predictor-ss.onrender.com

🤝 Contribution

Contributions are welcome! Feel free to fork this repository, create feature branches, and submit pull requests.

📜 License

This project is licensed under the MIT License – free to use and modify.

📬 Contact 👤 Siddhartha Singh 📧 10mastergaming10@gmail.com 🔗 https://www.linkedin.com/in/siddhartha1010/
