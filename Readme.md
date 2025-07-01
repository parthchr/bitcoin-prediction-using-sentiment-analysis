# Bitcoin Price Prediction Using LSTM and Sentiment Analysis

## 📌 Project Overview
This project aims to predict Bitcoin price trends by combining **Long Short-Term Memory (LSTM)** neural networks with **sentiment analysis** from Twitter. It integrates deep learning and natural language processing to enhance forecasting accuracy for better investment decisions.

---

## 🎯 Objectives
- Predict Bitcoin price trends using historical and sentiment data.
- Provide a user-friendly application to guide investment decisions.
- Combine deep learning and NLP to interpret trends and public sentiment.

---

## 🧠 Why LSTM Over RNN?
Traditional RNNs struggle with long-term dependencies due to vanishing gradients. LSTMs solve this with specialized gates (input, forget, and output), making them suitable for analyzing time-series financial data.

---

## 📂 Datasets Used
- **Bitcoin Price Data** from Yahoo Finance:
  - Features: `Open`, `High`, `Low`, `Close`, `Adjusted Close`
- **Twitter Sentiment Data** from Kaggle (July 2021 – August 2022):
  - Includes tweet metadata and sentiment scores

---

## 🧹 Data Preprocessing
- Converted date formats
- Removed missing and duplicate entries
- Dropped irrelevant columns (e.g., user_description)
- Normalized and reshaped data for model input

---

## 🖥️ System & User Requirements

### User Requirements
- Predict Bitcoin price
- View market trends

### System Requirements
- Machine Learning model
- Twitter API via Tweepy
- Web interface for displaying insights

---

## 🧱 Model Architecture
- LSTM with dropout layers to prevent overfitting
- Bidirectional LSTM for richer context
- Trained using backpropagation
- Sentiment analysis with TextBlob integrated with historical price data

---

## 🧪 Testing
- **Unit Testing** for individual modules
- **Integration Testing** for complete pipeline
- Actual vs. predicted price visualizations show promising results

---

## 📊 Key Findings
- LSTM model gives reasonable price predictions
- Sentiment data shows limited linear correlation; further feature engineering needed

---

## 🚀 Future Scope
- Expand to other cryptocurrencies like Ethereum and Litecoin
- Integrate transfer learning for better generalization
- Launch tutorials and live sentiment dashboards in the app
- Improve prediction by enhancing sentiment-price fusion



## 🛠️ Tech Stack
- **Languages**: Python, HTML, JavaScript
- **Libraries**: Keras, TensorFlow, Scikit-learn, NumPy, Pandas, TextBlob
- **APIs**: Tweepy (Twitter API)
- **IDE**: Spyder
- **Framework**: Flask/Django for web integration

---

## 📈 Sample Output
> Graphs comparing predicted vs. actual Bitcoin prices  
> Sentiment trend visualization  
> Real-time price and tweet sentiment dashboard (planned)

---

## 📬 Contact
For queries or collaboration, reach out to the project contributors.