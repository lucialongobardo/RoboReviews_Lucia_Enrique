###Project - Customer Reviews

###Group Members

Enrique Garcia
Lucía Longobardo




###Task Description
This project focuses on developing a Natural Language Processing (NLP) pipeline to automate the analysis of customer feedback for a retail company. The objectives are:

Classification of Reviews:
Classify customer reviews into three sentiment categories:

Positive
Negative
Neutral

Summarization of Reviews:
Implement a Generative AI model to summarize customer reviews based on their sentiment score (0-5). These summaries provide concise insights into customer opinions.

Clustering and Categorization:
Group reviews into product categories using clustering techniques (e.g., KMeans). If the number of categories is too large, focus on identifying the top-K categories for easier analysis.

Visualization Dashboard:
Create a dynamic, interactive dashboard to visualize key insights, including sentiment distribution, top product categories, and review summaries.





###Dataset Selected

Dataset
We used a subset of the publicly available Amazon Reviews Dataset, consisting of 67,959 reviews across various product categories. The dataset was processed as follows:

Combined three datasets into a single unified dataset (df_combined) for streamlined analysis.
Preprocessed the data by cleaning text, tokenizing, and removing noise to prepare it for modeling.
Dataset Source: Amazon Reviews Dataset 





###Key Features of the Project

1. Preprocessing and Model Training
Text preprocessing, including tokenization, lemmatization, and removal of special characters.
Implementation of a Logistic Regression model using embeddings from DistilBERT to classify reviews into sentiment categories.
2. Model Evaluation
The classification model achieved the following metrics:
Accuracy: 97%
Precision: 89%
Recall: 81%
F1-Score: 85%
3. Clustering of Reviews
Used KMeans clustering to group reviews into thematic categories based on their textual content.
Identified and visualized patterns in customer feedback, helping the company prioritize key product areas.
4. Summarization
Generated concise summaries of reviews using Spacy for extractive summarization.
Summaries allow quick understanding of customer sentiments without reading full reviews.
5. Visualization Dashboard
Designed an interactive visualization dashboard to display:
Sentiment distribution across reviews.
Cluster analysis results.
Key review summaries for each product category.





###Deliverables Contained

Transformer Model in Google Colab. The transformer-based model was implemented and trained using Google Colab for optimal resource utilization.

Code in Jupyter Notebook FINAL

The codebase, including preprocessing, model training, and evaluation, is provided in a Jupyter Notebook for easy replication and exploration.

Presentation PowerPointThe PowerPoint presentation summarizing the project and key insights from our analysis and model performance.

Demo in .jpg to see how the little program for review classifier will work on a company website.

Roadmap for the project in .jpg

Readme file



###Usage Instructions
Clone this repository:

codigo:
bash
Copiar código
git clone https://github.com/eagbdesign/RoboReviews_Lucia_Enrique.git

Run the Jupyter Notebook: Open the notebook in Jupyter and follow the steps for preprocessing, training, and evaluation.

Upload reviews for analysis:

Use the dashboard to upload a file containing customer reviews.
The system will classify, summarize, and cluster the reviews automatically.



###Future Improvements
Refine clustering to reduce noise and improve category clarity.
Enhance the summarization model using abstractive techniques like BART or T5.
Expand the dataset to include more diverse product categories for better generalization.



###Contact
For questions or further details, feel free to contact us:

Enrique Garcia: kikegarciabello@gmail.com
Lucía Longobardo: lucialongobardo@gmail.com

