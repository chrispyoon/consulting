---
layout: default
title: "Introduction"
---

<div class="content-section bg-light">
  <div class="container">
    <h2>Methodology</h2>
    <p>DATA SELEcTION

           For a thorough analysis, this study collected data from blog posts in Korean for two analyses: sentiment analysis (SA) and thematic analysis (TA). The SA focused on blog posts in Korean that mentioned the term "North Korean Defector" (탈북민/t'albungmin). The dataset was collected using the Naver API and translated into English with Google Translator API. 1,200 blog posts that are most likely to discuss "탈북민" were selected, with 120 posts from each year from 2014 to 2023.

HYPOTHEsEs

For the SA, the VADER (Valence Aware Dictionary and sEntiment Reasoner) library was used because VADER comes with a comprehensive lexicon that has been fine-tuned for social media content, including emoticons, slang, and abbreviations. This ensures that the sentiment analysis captures the full range of expressions used in blog posts. The following hypotheses were proposed: 

S1: If the sentiment analysis results show a trend of growing positive sentiment toward North Korean defectors, then these positive sentiments will be significantly associated with higher levels of life satisfaction among defectors.
S2: If the sentiment analysis results show a trend of growing neutral sentiment of North Korean defectors, then these neutral sentiments will have a limited or non-significant impact on the life satisfaction of defectors.
S3: If the sentiment analysis results show a trend of growing negative sentiment toward North Korean defectors, then these negative sentiments will be significantly associated with lower levels of life satisfaction among defectors.

           To classify the blog posts into distinct themes in TA, this study employs a combination of advanced natural language processing (NLP) techniques and machine learning models. The text data was meticulously processed by cleaning and converting it into numerical features through Term Frequency-Inverse Document Frequency (TF-IDF) vectorization. This technique was pivotal in emphasizing the importance of words relative to their context within the dataset.
           For a robust and accurate classification, supervised machine learning models such as Logistic Regression and Support Vector Machines (SVM) were trained. Both models are renowned for their effectiveness in text classification tasks. Logistic Regression provided a baseline for classification, while SVM, known for its robustness in high-dimensional spaces, further enhanced the classification accuracy.
           Beyond these supervised learning methods, Latent Dirichlet Allocation (LDA), an unsupervised machine learning algorithm, was applied to discover latent thematic structures within the text. LDA analyzes word co-occurrence patterns to uncover topics that naturally exist in the data without relying on predefined labels.
           Each blog post was then systematically assigned to the most relevant theme based on the probabilities or associations identified by these models. This multi-faceted approach ensured a comprehensive classification of the blog posts into political, empowering, and discriminating themes.
           By integrating word-based theme determination with sophisticated machine-learning techniques, the analysis provided a nuanced understanding of thematic trends over a decade. The theme distribution was analyzed and visualized across the years to identify shifts and patterns in the focus of the blog posts. The following hypotheses were proposed:

T1: If the empowerment theme explains more than 50% of positive sentiment, it may suggest that conditional inclusion plays a weak role in how North Korean defectors are perceived and accepted in South Korean society.
T2: If non-empowerment themes explain more than 50% of positive sentiment, it may suggest that conditional inclusion plays a significant role in how North Korean defectors are perceived and accepted in South Korean society.

           The life satisfaction percentages given by the survey data for the years 2014 to 2023 were 67.6%, 63.8%, 67.0%, 73.6%, 72.5%, 74.2%, 76.4%, 76.4%, 76.5%, and 77.4%. 
</p>

  </div>
</div>
