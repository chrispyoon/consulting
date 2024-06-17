---
layout: default
title: Home
---

<!-- Introduction Section -->
<section id="introduction" class="section bg-light">
  <div class="container intro-content">
    <h2>Introduction</h2>
    <p>
      Under the South Korean Constitution, North Korean defectors are granted legal status as South Korean nationals. Despite their legal status, many face significant challenges, including economic struggles, social stigma, and difficulties in cultural adaptation. This study explores whether defectors are genuinely embraced or if their acceptance is conditional on fulfilling certain favorable expectations, such as embodying positive stereotypes.
    </p>
    <p>
      The primary objective of this research is to examine the hypothesis that societal acceptance of North Korean defectors in South Korea is conditional. It investigates whether narratives that are positive and empowering enhance societal acceptance. By analyzing these dynamics, the study aims to contribute to a broader discussion on migration, integration, and human rights, shedding light on the challenges and opportunities faced by North Korean defectors.
    </p>
  </div>
</section>

<!-- Methodology Section -->
<section id="methodology" class="section bg-gray">
  <div class="container">
    <h2>Methodology</h2>
    <p>
      This study collected data from blog posts in Korean for sentiment analysis (SA) and thematic analysis (TA). The SA focused on posts that mentioned "North Korean Defector" (탈북민/t'albungmin), collected using the Naver API. The data was translated into English for analysis.
    </p>
    <p>
      The SA used the VADER library to capture sentiment trends. The TA employed advanced NLP techniques and machine learning models such as Logistic Regression, Support Vector Machines (SVM), and Latent Dirichlet Allocation (LDA) to classify the posts into political, empowering, and discriminating themes.
    </p>
  </div>
</section>

<!-- Results Section -->
<section id="results" class="section bg-light">
  <div class="container">
    <h2>Results</h2>
    <div class="results-left">
      <p>
        The sentiment analysis results show varying percentages of positive sentiment each year, with a noticeable correlation between positive sentiment and life satisfaction among defectors.
      </p>
      <div class="figure-container">
        <figure>
          <img src="/defectorinclusion/assets/images/figure1.png" alt="Figure 1: Sentiment Analysis Results" class="figure-image">
          <figcaption>Figure 1: Sentiment Analysis Results</figcaption>
        </figure>
      </div>
    </div>
    <div class="results-right">
      <p>
        The thematic analysis reveals that the empowerment theme consistently emerged as the most prominent narrative but only explains a portion of the positive sentiment. Non-empowerment themes also play a significant role, indicating the presence of conditional inclusion.
      </p>
      <div class="figure-container">
        <figure>
          <img src="/defectorinclusion/assets/images/figure2.png" alt="Figure 2: Thematic Analysis Results" class="figure-image">
          <figcaption>Figure 2: Thematic Analysis Results</figcaption>
        </figure>
      </div>
    </div>
  </div>
</section>

<!-- Discussion Section -->
<section id="discussion" class="section bg-gray">
  <div class="container">
    <h2>Discussion</h2>
    <p>
      This study underscores the challenges of conditional inclusion, where defectors must conform to societal expectations to gain acceptance.
    </p>
    <p>
      Despite the influence of empowering narratives, the significant role of non-empowerment themes suggests that societal acceptance remains conditional. This highlights the need for a societal framework that embraces defectors unconditionally, recognizing their inherent worth and contributions.
    </p>
  </div>
</section>

<!-- Limits Section -->
<section id="limits" class="section bg-light">
  <div class="container">  
    <h2>Limitations and Future Study</h2>
    <p>
      This study explores how public opinion affects the life satisfaction of North Korean defectors and the conditional inclusion they face in South Korean society. However, it has limitations: reliance on Naver blog posts may not fully capture societal views, and translation from Korean to English could distort sentiment and thematic analysis.
    </p>
    <p>
      Future analyses will use KoBERT for direct Korean text assessment, improving accuracy. The thematic prediction model's low accuracy (less than 30%), discovered late in the research, suggests a need for a larger sample size—potentially over 15,000—to achieve better accuracy.
    </p>
  </div>
</section>

<!-- Acknowledgements Section -->
<section id="acknowledgements" class="section bg-gray">
  <div class="container">
    <h2>Acknowledgements</h2>
    <p>
      I want to express my gratitude to several individuals who greatly supported my research journey. First, thank you to Angela Perkins, the Director of Digital Scholarship Services at Lafayette College, for supporting me with my first machine learning research project. I am also grateful to Associate Professor Caleb Gallemore from the International Affairs Department at Lafayette College for his insights into statistical methods. Yazdan Basir, a Data Engineer at SEI, provided valuable advice on data analysis. I also thank Sidath Chandrasena, DHSS’2023 teaching fellow, and Tanushree Sow Mondal, DHSS'2024, for their persistent feedback. Lastly, I am grateful for the mentorship provided by Professor Seo-Hyun Park of the Government and Law Department and the Asian Studies Program at Lafayette College, who generously shared her expertise and guidance.
    </p>
  </div>
</section>
