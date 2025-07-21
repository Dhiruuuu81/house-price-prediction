# 🏠 House Price Predictor

Predict the price of a house based on its area and number of bedrooms using a simple linear regression model in a user-friendly Streamlit interface.

# 📌 Project Overview

This web app uses Streamlit, pandas, and scikit-learn to:
- Display sample housing data
- Train a regression model using that data
- Allow users to input area and bedroom count
- Predict and display the estimated house price (in ₹ Lakhs)

# 🚀 How to Run the App

🖥️ Requirements
Ensure the following Python packages are installed:
pip install streamlit pandas scikit-learn


# ▶️ Running the App
Use the following command in your terminal:
streamlit run app.py


Replace app.py with your actual Python file name if it's different.

# 📊 Sample Dataset
This project comes with a hardcoded sample dataset. You can later replace it with real-world housing data.
| Area (sq ft) | Bedrooms | Price (₹ Lakhs) | 
| 1000 | 2 | 50 | 
| 1500 | 3 | 70 | 
| 2000 | 3 | 90 | 
| 2500 | 4 | 110 | 
| 3000 | 4 | 130 | 



# 🧠 How It Works
- Data Preparation: Loads a sample dataset into a pandas DataFrame.
- Model Training: Trains a LinearRegression model from scikit-learn using:
- Features: Area (sq ft) and Number of Bedrooms
- Target: Price (₹ Lakhs)
- User Input: Users enter desired Area and select number of Bedrooms.
- Prediction: Model outputs the estimated house price in Lakhs.

# 🧪 Example Inputs
| Input | Value | 
| Area | 1200 sq ft | 
| Bedrooms | 3 | 
| Output | ₹ 62.00 Lakhs | 



# 🛠️ Customization Ideas
- Replace sample data with CSV upload or real housing dataset
- Add features like location, amenities, age of property
- Switch model type to RandomForestRegressor or GradientBoosting
- Add charts to visualize trends and prediction confidence

# 📂 File Structure
├── app.py             # Main app file
├── README.md          # This file



# 💡 Tech Used
- Streamlit – Interactive UI
- pandas – Data handling
- scikit-learn – Machine learning

# 🧾 License
This project is open for educational and personal use. Feel free to modify and expand it as needed!

