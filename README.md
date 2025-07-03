# Kendrick Lamar Track Analysis & Popularity Prediction

## Project Overview
I analyzed 305 Kendrick Lamar tracks to understand what makes his songs popular. Using Python and machine learning, I discovered that his solo tracks are significantly more popular than collaborations and built a model to predict track popularity.

## Key Findings
- **Solo tracks are 42% more popular than collaborations** (proven with statistical testing, p < 0.05)
- Most tracks have popularity scores between 50-80, showing consistent fan engagement
- Built a Linear Regression model that predicts popularity with 73% accuracy
- Energy and danceability are the strongest predictors of track popularity

## Dataset
- **305 tracks** spanning from 2009-2024
- **22 features** including audio characteristics (tempo, energy, danceability) and metadata
- Source: Spotify API data for all Kendrick Lamar tracks

## Technologies Used
- Python
- Pandas - data analysis
- Matplotlib - visualizations
- Statsmodels - statistical testing (z-test)
- Scikit-learn - machine learning (Linear Regression)

## Analysis Performed
1. **Exploratory Data Analysis** - distribution of popularity scores
2. **Statistical Testing** - compared solo vs collaboration performance
3. **Data Visualization** - histograms and boxplots
4. **Machine Learning** - built regression model to predict popularity

## How to Run
1. Clone this repository
2. Install requirements: `pip install pandas matplotlib statsmodels scikit-learn`
3. Open and run the Jupyter notebook

## Results
The analysis shows that Kendrick Lamar's solo work consistently outperforms his collaborations, and that certain audio features (especially energy and danceability) are strong indicators of a track's potential popularity.

## Future Improvements
- Add more artists for comparison
- Include lyrical analysis
- Build a web app for real-time predictions