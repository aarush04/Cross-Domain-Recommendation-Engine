# Cross-Domain Recommendation Engine

Authors
- Aarush Shah, (aarushs2@illinois.edu)
- Jay Sunil Goenka, (jgoenka2@illinois.edu)
- Yash Jain,  (yash7@illinois.edu)
- Yash Mandavia, (yashm4@illinois.edu)

---

Project Overview
The Cross-Domain Recommendation Engine is a personalized storytelling system that bridges the gap between movies and anime. By leveraging advanced Natural Language Processing (NLP) techniques, this engine analyzes thematic, emotional, and narrative details in movies to provide tailored anime recommendations.

Key Features
- Sentiment and semantic analysis for thematic alignment.
- Recommendations based on narrative depth, emotional arcs, and thematic elements.
- Integration of pre-trained models like **Word2Vec**, **KeyBERT**, and **Sentence-BERT** for state-of-the-art performance.

---

## How to Run the Project

Both Jupyter notebooks are identical just for safety. 

1. GoogleNews-vectors-negative300.bin: The Word2Vec model pre-trained on 100 billion words from Google News.
2. movies.csv: Dataset containing movie summaries.
3. anime.csv: Dataset containing anime summaries.

## STEPS TO RUN
1. Upload the necessary files (`GoogleNews-vectors-negative300.bin`, `movies.csv`, and `anime.csv`) in the runtime environment.
2. Open either of the two notebooks in the folder (both are identical).
3. Run the notebook cell by cell to view the desired outputs.

---

## Steps in Notebooks
- Data Preprocessing: Clean and structure datasets by removing inconsistencies and normalizing data.
- Exploratory Data Analysis (EDA): Visualize text distributions and uncover patterns.
- Semantic Similarity Search: Compute similarity scores between movies and anime using embedding vectors.


---

## Technical Requirements
- Python Libraries: `gensim`, `sklearn`, `numpy`, `pandas`, `tabulate`, `transformers`, 'keybert'
- Hardware: Sufficient memory and computational resources for handling large embeddings.
