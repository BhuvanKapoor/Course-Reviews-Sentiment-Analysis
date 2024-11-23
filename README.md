# Course Reviews Sentiment Analysis

This project performs sentiment analysis on course reviews using two primary approaches:
1. **VADER**: A rule-based sentiment analysis technique.
2. **Transformers**: A transformer-based model (DistilBERT) for fine-grained sentiment analysis.

The project also provides key insights into the data, sentiment distributions, and correlations between ratings and sentiments.

---

## Features

- **Data Preprocessing**: 
  - Cleaning and processing review comments.
- **Sentiment Analysis**:
  - VADER-based compound sentiment score calculation.
  - Transformer-based sentiment classification (positive, negative, neutral).
- **Visualization**:
  - Distribution of review ratings and sentiment scores.
  - Scatter plots to explore correlations.
- **Insights**:
  - Course-wise performance metrics.
  - Summary statistics for ratings and sentiments.

---

## Prerequisites

Ensure you have the following installed:

- Python 3.7+
- Required Python libraries (listed in `requirements.txt`):
  - `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `transformers`, `tqdm`

---

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/course-reviews-sentiment-analysis.git
   cd course-reviews-sentiment-analysis
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure the dataset `(user_courses_review_test_set.csv)` is placed in the data/ folder.

---

## Usage

1. Open the jupyter notebook:
   ```bash
   jupyter notebook sentiment_analysis.ipynb
   ```
2. Follow the instructions in the notebook to perform sentiment analysis and explore the data.

---

## Files

- `sentiment_analysis.ipynb`: Jupyter notebook containing the code for sentiment analysis.
- `requirements.txt`: List of required Python libraries for the project.
- `user_courses_review_test_set.csv`: Sample dataset for sentiment analysis.

---

## Key Insights

1. **Rating Distribution**: 
   - Average rating: 4.64
   - Most common rating: 5
2. **Sentiment Analysis**: 
   - Average sentiment score: 0.46
   - Correlation with ratings: 0.51
3. **Course Performance**: 
   - Best rated course: Advanced Microsoft Excel
   - Most reviewed course: Introduction to Data and Data Science

