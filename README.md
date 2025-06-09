# UI-streamlit
#  Agricultural Commodity Price Forecasting & Chatbot System

This Streamlit-based web application forecasts prices of various agricultural commodities using ARIMA time series models and integrates a Cohere-powered chatbot for user queries. It also includes data visualizations for supply chain stages, inventory management, and consumer price awareness.



##  Features

- Price Forecasting** using ARIMA for selected commodities
- Commodity Inventory Visualization** across different states
- AI Chatbot Integration** using Cohere API
- Text-to-Speech (TTS)** to read chatbot responses aloud
- Supply Chain Visualization** from farm to consumer
- Bar Charts and Pie Charts** for better data interpretation
- Stylized Streamlit Interface** with custom CSS


# Project Structure
AgriPriceForecast/
│
├── app.py # Main Streamlit application
├── requirements.txt # All required Python libraries
├── updated_daily_price.csv # Dataset for forecasting
├── README.md # Project documentation (this file)
└── assets/ # (Optional) Image or logo assets


##  Requirements
Install the required dependencies using:
pip install -r requirements.txt

# Technologies Used
Python – Core programming language
Streamlit – Web UI development
pandas / numpy – Data manipulation
matplotlib / seaborn – Data visualization
statsmodels – ARIMA model for forecasting
scikit-learn – Data preprocessing
gTTS / pyttsx3 – Text-to-speech engines
Cohere API – Natural language processing (chatbot)
Googletrans – Language detection and translation
Langchain – For prompt templating and chaining (chatbot context)

# How It Works
User selects a commodity and a numerical column (like price).
The app trains an ARIMA model and forecasts future values.
Visualizations are generated for:
Forecast trend
Value distribution
Top 10 values
Inventory by state
A chatbot answers questions related to commodities.
TTS can speak out the response.

# Sample Use Cases
Predicting the future price of Wheat in India
Understanding state-wise inventory for a specific crop\
Asking the chatbot: “What are the factors influencing rice prices?”
Listening to forecasts via TTS for accessibility

# Run Locally
bash
Copy
Edit
streamlit run app.py
Ensure your updated_daily_price.csv file is in the same directory as app.py.
