# Newspaper-Topic-Modeling-Analysis
## Overview
This project focuses on the preprocessing, exploratory data analysis, and topic modeling of a large corpus containing newspaper articles from sources like the Wall Street Journal and the New York Times for the year 2017. It demonstrates the application of Natural Language Processing (NLP) techniques to uncover underlying themes within a vast collection of text data, aiming to assist journalists in enhancing their reporting by providing deeper insights into the content.

## Objectives
To preprocess and clean a corpus of newspaper articles for analysis.
To perform exploratory data analysis through summaries and visualizations.
To construct a topic model to identify and understand prevalent topics within the corpus.

## Methodology
1. **Corpus Creation:**
Articles were sourced from the Factiva Global News database, processed, and segmented based on specific keywords to construct the corpus.
2. **Refinement:** 
Articles were scrutinized for formatting and accurate extraction, with metadata separated from content.
3. **Preprocessing:** Included tokenization, removal of punctuation, stopwords, and stemming.
4. **Feature Extraction:** Creation of a document-term matrix and visualization through word clouds.
5. **Topic Modeling (LDA):** Employing the genism library for Latent Dirichlet Allocation (LDA) model creation, further processed for topic identification.
Results Evaluation: Using pyLDAvis for visualization and metrics like perplexity and coherence scores for model assessment.

## Key Findings
The optimal model featured 5 topics, balancing model complexity and performance, identified through coherence scores and perplexity evaluation.
Visualizations and word frequency distributions provided insights into the dominant themes within the data, highlighting topics related to political figures, international incidents, and social issues.

## Conclusion
The study emphasizes the importance of preprocessing and exploratory data analysis in journalism, allowing for the discovery of significant themes and topics. It illustrates the potential of topic modeling in offering valuable insights, thereby enabling journalists to produce more informed and impactful stories.

## Future Directions
Future research could focus on refining the preprocessing phase, exploring additional analytical techniques, or applying the methodology to different datasets for comparative analysis.

## Contributors
* Samarasimha Reddy
* Vengal Rao Pachava
* Corwin Bennett  
* For inquiries, please contact psamarasimha.reddy06@gmail.com.
