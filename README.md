# Sentiment Analysis Using NLP and Machine Learning

## Project Overview
This project performs Sentiment Analysis on movie reviews using Natural Language Processing (NLP) and Machine Learning.

The model classifies reviews as Positive or Negative using the IMDb 50K Movie Reviews dataset.

## Dataset
- IMDb 50K Movie Reviews Dataset
- 50,000 movie reviews
- Positive and Negative sentiments

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Project Workflow
1. Load Dataset
2. Text Preprocessing
   - Lowercase conversion
   - Remove special characters
   - Stopword removal
   - Stemming
3. TF-IDF Vectorization
4. Train-Test Split
5. Model Training using Multinomial Naive Bayes
6. Sentiment Prediction
7. Model Evaluation

## Model Used
Multinomial Naive Bayes

## Results
- Accuracy: Around 85%–90%
- Successfully predicts Positive and Negative reviews

## Sample Prediction

Input:
"This movie was amazing and enjoyable"

Output:
Positive Review

## Repository Contents
- Sentiment_Analysis_IMDb.ipynb → Complete project notebook
- README.md → Project documentation
- requirements.txt → Libraries used

## Future Improvements
- Web application using Streamlit/Flask
- Multiple ML model comparison
- Model deployment
- Interactive dashboard
