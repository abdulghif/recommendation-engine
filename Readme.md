# IBM Watson User Engagement Analysis & Recommendations
The aim of this project is to understand how users interact with articles on IBM Watson's platform and utilize this data to recommend articles that would be most relevant to them.

##  Installations

Try to run this script
```pip install -r requirements.txt```

## Summary:
The project contains the following tasks:
- Exploratory Data Analysis: This stage focuses on dissecting the dataset to unearth trends, patterns, and anomalies. The insights gained here are critical for guiding the rest of the project.
- Rank Based Recommendations:  Here, I start by identifying articles that have garnered the most interactions. These high-engagement articles serve as the initial set of recommendations, particularly useful for new users who have yet to establish their preferences on the platform.
- User-User Based Collaborative Filtering:  In this part, I dig deeper into user behaviors, identifying clusters of users who have interacted with similar sets of articles. Recommendations are then generated based on these user neighborhoods, aiming to offer more personalized suggestions.
- Content Based Recommendations:   Leveraging Natural Language Processing techniques, I analyze the content of each article to create a feature set. This allows the recommendation system to suggest articles that are similar in content to those a user has previously interacted with.
- Matrix Factorization:  In this final stage, I employ machine learning algorithms to deconstruct the user-item interaction matrix. The resulting factors are then used to predict potential future interactions between users and articles, further fine-tuning the recommendation system.

## Data
- user-item-interactions.csv: file contains user interaction.
- articles_community.csv: file contains articles description.  

## Acknowledgments
I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and [IBM](https://dataplatform.cloud.ibm.com/) for providing the data.

## How to Run

1. Install all necessary packages.
2. Load the datasets.
3. Run the Jupyter Notebook containing the analysis and models.