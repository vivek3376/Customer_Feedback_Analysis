# Customer Feedback Analysis using Generative AI

## Project Overview

This project analyzes customer reviews from an e-commerce clothing dataset to identify critical customer feedback and automatically generate personalized customer support responses using a Generative AI model.

The project demonstrates practical data preprocessing, text analysis, rule-based filtering, visualization, and AI-powered response generation using Python.

---

## Problem Statement

Retail companies receive thousands of customer reviews every day. Manually identifying negative reviews and responding to customers is time-consuming.

This project automates the process by:

- Identifying critical customer reviews
- Extracting common complaint keywords
- Generating personalized apology emails using Generative AI

---

## Dataset

**Dataset:** Women's E-Commerce Clothing Reviews

The dataset contains customer reviews, ratings, product information, and recommendation status for women's clothing products.

---

## Features

- Load and explore customer review data
- Handle missing values
- Clean and preprocess review text
- Filter critical reviews (Ratings 1 & 2)
- Extract common complaint keywords using `Counter`
- Visualize complaint insights with Matplotlib
- Generate personalized customer apology emails using OpenRouter (Llama 3.1)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Regular Expressions (`re`)
- Collections (`Counter`)
- OpenRouter API
- Llama 3.1 8B Instruct

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Handle missing values
5. Clean review text
6. Filter critical reviews
7. Extract complaint keywords
8. Visualize customer insights
9. Select the most detailed critical reviews
10. Generate AI-powered customer support emails

---

## Project Structure

```
Customer_Feedback_Analysis/
│
├── Customer_Feedback_Analysis.ipynb
├── README.md
└── Womens Clothing E-Commerce Reviews.csv
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Customer_Feedback_Analysis.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib openai
```

---

## How to Run

1. Open the Jupyter Notebook.
2. Install the required Python libraries.
3. Add your OpenRouter API key:

```python
api_key = "YOUR_OPENROUTER_API_KEY"
```

4. Run all notebook cells from top to bottom.

---

## Output

The project produces:

- Cleaned customer review dataset
- Critical review analysis
- Complaint keyword frequency
- Data visualizations
- AI-generated personalized customer apology emails

---

## Future Improvements

- Perform sentiment analysis using Machine Learning
- Build an interactive dashboard using Power BI or Streamlit
- Add automated email integration
- Improve keyword extraction using NLP techniques

---

## Author

**Vivek Gupta**

B.Sc. Information Technology | Aspiring Data Scientist
