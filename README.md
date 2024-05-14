# Customer Reviews Analysis Based Recommendation System for Smartphones
# SmartSelect.
## Overview.
The Customer Reviews Analysis Based Recommendation System for Smartphones (and Related) is a project that aims to provide customers with personalised smartphone recommendations based on sentiment analysis of customer reviews. Our algorithm uses a dataset of over 400,000 Amazon.com reviews to generate recommendations categorized by sentiment scores, guaranteeing that consumers receive informed advice based on real customer experiences.

## Workflow
1. **Dataset Collection**: We gathered over 400,000 reviews of unlocked mobile phones sold on Amazon.com in 2017.
2. **Preprocessing and Cleaning**: Handled null values, filled in missing data for Brand Name and Price, and deleted rows with further missing information.
3. **Sentiment Analysis**: Calculated sentiment scores for each review using a formula derived from research.
4. **Recommendation System**: Generated recommendations based on sentiment scores, considering Brand and Price Range.
5. **UI Integration**: Developed a user-friendly interface using Flask, HTML, and CSS to allow users to select Price Range or Brand Name.

## Resource Allocation
- **Front-end**: HTML, CSS, JavaScript (JS)
- **Back-end**: Python, Flask


## How to Run
1. Clone this repository to your local machine.
2. Run the Flask application using `python main.py`.
3. Access the application in your web browser at `http://localhost:5000`.
