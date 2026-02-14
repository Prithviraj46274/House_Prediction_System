This is a simple Streamlit web application that predicts house prices based on house size using Linear Regression.
The app generates synthetic house data, trains a machine learning model, and provides real-time price predictions with visualization.


Process :
1.Generates synthetic house size and price data
2.Trains a Linear Regression model using scikit-learn
3.Takes house size input from the user
4.Predicts the estimated house price
5.Displays an interactive scatter plot with the predicted value highlighted

How to run :

1. Clone the repository: 
git clone https://github.com/your-username/house-price-prediction-streamlit.git , 
cd house-price-prediction-streamlit

2. Install dependencies: 
pip install streamlit numpy pandas scikit-learn plotly

3. Run the Streamlit app: 
streamlit run app.py
