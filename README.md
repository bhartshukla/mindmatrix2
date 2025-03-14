# Mental Health Monitoring System (MHMS)

 📌 Overview
The **Mental Health Monitoring System (MHMS)** is an AI-driven tool designed to analyze a user's mental health condition based on their textual responses. It evaluates **happiness level, confidence level, and satisfaction level** by utilizing **sentiment analysis** and predefined **word sets**. The system provides personalized insights and suggestions to help users track their mental well-being over time.

✨ Features
- Sentiment Analysis**: Uses NLTK's `SentimentIntensityAnalyzer` to detect emotions from user responses.
- **Confidence & Satisfaction Detection**: Analyzes predefined word sets to assess confidence and satisfaction levels.
- **Randomized Questions**: Asks users different questions in each session for unbiased evaluation.
- **User-Friendly UI**: Built with Streamlit for a smooth and interactive experience.
- **Mental Health Score**: Generates an overall score and provides suggestions based on the user's responses.
- **Future Integration**: Can be expanded with ML models for advanced mental health analysis.

📦 Tech Stack
- **Python** (Backend logic)
- **Streamlit** (Web-based UI)
- **NLTK** (Sentiment Analysis)
- **Pandas** (Data processing)
- **Matplotlib/Seaborn** (Data visualization, if needed)

🚀 Installation & Setup
 Prerequisites
Ensure you have Python installed (3.8+ recommended). Install the required libraries using:
```sh
pip install streamlit nltk pandas
```

Run the Application
```sh
streamlit run app.py
```

 🛠 How It Works
1. The user responds to randomly generated mental health-related questions.
2. The system analyzes responses based on predefined word sets and sentiment scores.
3. Results are displayed with insights on **happiness, confidence, and satisfaction levels**.
4. The user receives suggestions to improve their mental well-being.

📌 Folder Structure
```
mental-health-monitoring/
│── app.py                  # Main Streamlit app
│── utils.py                # Helper functions (word sets, analysis functions)
│── requirements.txt        # Required dependencies
│── README.md               # Project Documentation
```

 📖 Future Enhancements
- Machine Learning Model**: Train a custom model for more accurate mental health detection.
- User Dashboard**: Track daily trends over time.
- Integration with Wearables**: Collect additional health data for better insights.
- Multilingual Support**: Analyze responses in multiple languages.

 📜 License
This project is open-source and available under the **MIT License**.

 🤝 Contributing
Want to contribute? Feel free to fork this repository and submit a pull request! 🚀

---
Developed by **Bhart Shukla** 🚀

