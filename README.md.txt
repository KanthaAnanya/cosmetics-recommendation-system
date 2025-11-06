## Cosmetics Recommendation System

This is a personalized skincare product recommendation system built using Streamlit and Content-Based Filtering.

## Features
-> Choose product category (e.g., Moisturizer, Sunscreen, Cleanser, Mask, etc.)
-> Filter products based on your skin type
-> Select desired skincare benefits / notable effects
-> Optional brand preference selection
-> Get personalized product recommendations
-> View purchase link for every recommended product
-> Clean and interactive Streamlit UI

## How it Works

This is a Content-Based Recommendation System.

1. The app uses the Notable Effects of each product (e.g., Hydrating, Anti-Aging, Oil Control)
2. Text descriptions are converted into numerical form using TF-IDF Vectorization
3. Cosine Similarity is calculated between product vectors
4. The system recommends products most similar to the one selected by the user

## Dataset Information

Columns used in the dataset:
- product_name
- product_type
- brand
- notable_effects
- skintype
- price
- product_href
- picture_src

Dataset Source: Myntra Skincare Dataset (contains 900+ skincare products)

## Tech Stack

- Python
- Pandas
- Scikit-learn
- Streamlit
- TF-IDF Vectorizer (for content similarity)

## Run the App

Install required libraries if needed:
```bash
pip install streamlit pandas scikit-learn pillow streamlit-option-menu

##Run the Streamlit app:

streamlit run Cosmetics_Recommendation_System_App.py

##The app will open in your browser at:

http://localhost:8501/


## Screenshots
### Home Page
![Home Page](home.PNG)

### Recommendations Page
![Recommendations Page](Recommendations.PNG)

### More Recommendation Results
![More Recommendations](Recommendations2.PNG)

### Contact Page
![Contact Page](Contacts.PNG)


