# Topic-Modeling-and-Word-Embeddings

This project explores how U.S. Congressional members communicate on Facebook by applying topic modeling and word embedding techniques. Using natural language processing (NLP) methods, the analysis uncovers thematic structures and semantic similarities in over 6,700 posts made by Democrats and Republicans in 2017. The study aims to understand how different political parties discuss issues such as healthcare, immigration, and social welfare.


Congressional Discourse Analysis with Topic Modeling and Word Embeddings

Course
Machine Learning for Social Science, Linköping University

Overview
This project explores how U.S. Congressional members communicate on Facebook by applying topic modeling and word embedding techniques. Using natural language processing (NLP) methods, the analysis uncovers thematic structures and semantic similarities in over 6,700 posts made by Democrats and Republicans in 2017. The study aims to understand how different political parties discuss issues such as healthcare, immigration, and social welfare.

Dataset
Facebook post data from 6752 posts made by U.S. Congress members during 2017. The dataset includes variables such as doc_id, screen_name, party, and message.

Tools & Methods
Language: R
Libraries: quanteda, stm, ggplot2, text2vec, data.table, tidyverse

Main Techniques:
- Tokenization & pre-processing
- Latent Dirichlet Allocation (LDA) for topic modeling
- Word embeddings via GloVe and self-trained models
- Document classification and t-tests for partisan differences
- 
Main Steps
1. Text pre-processing and creation of document-term matrix (DTM)
2. Topic modeling with LDA (K = 50 and K = 3)
3. Labeling and interpreting selected topics (e.g., Tax Reform, Social Welfare, Russian Involvement)
4. T-tests to compare topic prevalence between Democrats and Republicans
5. Word embedding modeling (self-trained and pre-trained)
6. Similarity analysis for political terms and analogies

   
Key Findings

- Republicans focus more on tax reform and healthcare criticism, while Democrats emphasize social welfare and community issues.
- The self-trained word embeddings reflected partisan language use, while pre-trained models captured broader semantic relationships.
- T-tests confirmed statistically significant differences in topic engagement between parties.
Conclusion
This project combines unsupervised learning with political text analysis to reveal thematic and linguistic patterns in political discourse. It highlights the usefulness of computational methods for analyzing large-scale social and political communication data.
