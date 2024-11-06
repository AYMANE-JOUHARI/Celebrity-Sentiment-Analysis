# Social Media Sentiment Analysis on Celebrities

## Project Overview
This project analyzes public sentiment towards two Moroccan celebrities, Saad Lamjarred and Simo Life, using data scraped from social media. The project involves:
- Collecting data via web scraping.
- Preprocessing and cleaning text data.
- Applying sentiment analysis models.
- Visualizing sentiment trends.

The goal is to uncover insights about public opinion towards these celebrities by categorizing comments as positive, negative, or neutral.

## Files in the Repository
- `project code.ipynb`: Jupyter notebook for data preprocessing, model training, and sentiment analysis.
- `scraping code.ipynb`: Jupyter notebook for scraping comments from social media posts.
- `SaadLamjarred_LV.csv`: Dataset containing comments and sentiment labels.
- `Integrated Project Report.pdf`: Detailed report of the project methodology, results, and analysis.
- `requirements.txt`: List of required packages to run the project.

## Getting Started

1. **Set Up Environment**: Install the required packages using `requirements.txt`.
   ```bash
   pip install -r requirements.txt
   

2. **Run the Scraping Code**: Open and run `scraping code.ipynb` to collect additional social media comments. Ensure that you have the necessary login credentials and correct WebDriver setup for Selenium.

3. **Run the Analysis Code**: Open and run `project code.ipynb` to perform sentiment analysis. This includes preprocessing, training models, and evaluating results.

## Project Details
The project is organized into several key steps:

1. **Data Collection**: Using Selenium, comments are scraped from social media posts.
2. **Preprocessing**: Data is cleaned, tokenized, and vectorized using TF-IDF.
3. **Model Training**: Various machine learning models (Logistic Regression, Naive Bayes, LDA, QDA) are applied to classify sentiments.
4. **Evaluation and Visualization**: Model performance is evaluated, and results are visualized to understand public sentiment trends.

## Results Summary
The report (`Integrated Project Report.pdf`) includes detailed findings, including accuracy scores for each model and analysis of sentiment trends over time.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Special thanks to our mentors and colleagues who contributed to the success of this project.
