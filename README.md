# email-spam-classifier-new
An end-to-end machine learning project that detects whether an Email or SMS message is Spam or Not Spam.
Built with Python, Streamlit, NLP techniques, and Machine Learning, and ready for deployment on Heroku or Streamlit Cloud
This project provides a simple and interactive Spam Classifier Web App where users can type or paste a message and get instant prediction as Spam or Not Spam. The app uses Natural Language Processing (NLP) for text preprocessing and TF-IDF for feature extraction, combined with a machine learning model trained on a labeled dataset.
End to end code for the email spam classifier project

- Features
1.  Real-time Spam/Not Spam detection
2. Clean and modern UI with Streamlit
   
- Advanced text preprocessing:

1. Lowercasing

2. Tokenization

3. Stopword Removal

4. Punctuation Removal

5. Stemming using Porter Stemmer

- Displays:

1.Transformed text

2.Vectorized input shape

- Prediction probabilities
✔ Pre-trained ML model using TF-IDF + Classifier
✔ Deployment-ready for Heroku or Streamlit Cloud
✔ Includes FAQ section, usage tips, and examples
- Dependencies

1.Install all dependencies from requirements.txt:

a. streamlit
b. nltk
c.scikit-learn
  
- Additional:

1. nltk datasets: punkt, stopwords (auto-downloaded in app)

2. pickle (built-in for model loading)

3. Technologies & Skills Used

- Language: Python

- Framework: Streamlit

- NLP Techniques:

1. Tokenization

2.Stopword Removal

3.Stemming

4. TF-IDF Vectorization

- Machine Learning:

Scikit-learn (model training & evaluation)

- Deployment:

Heroku (Procfile & setup.sh)

Streamlit Sharing (alternative)

- Others: Git, GitHub, HTML/CSS customization in Streamlit
  
-How to Run Locally
 Clone the Repository
 git clone https://github.com/<your-username>/spam_detection.git
 cd spam_detection
- Install Requirements
  pip install -r requirements.txt
  Run the App
  streamlit run app.py

Thanks for Exploring Email-spam-detection

