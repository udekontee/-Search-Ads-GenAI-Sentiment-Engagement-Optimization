# Search-Ads-GenAI-Sentiment-Engagement-Optimization
Applied NLP and A/B Experimentation to Analyze Ad Copy Performance

# Project Overview
This project examines how Generative AI and NLP can improve Search Ads performance through text sentiment analysis and A/B testing. The goal is to identify what type of ad copy (positive, neutral, or promotional tone) drives higher Click-Through Rates (CTR) and engagement, similar to how Google Ads evaluates creative effectiveness. Using Python, Pandas, NLTK, and statistical testing, this project simulates real-world ad performance data and applies hypothesis testing to validate which ad tone statistically outperforms the others.

# 🎯 Objectives
- Simulate ad campaign data with impressions, clicks, CTR, and sentiment labels.
- Apply Natural Language Processing (NLP) to classify ad tone and text polarity.
- Perform A/B testing (t-test) to compare performance between two ad groups.
- Visualize engagement metrics and identify statistically significant differences.
- Showcase data-driven ad optimization aligned with Search Ads GenAI initiatives.

  # Tech Stack

**Languages:** Python  
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, NLTK, TextBlob, SciPy, TQDM  
**Concepts:** Sentiment Analysis, A/B Testing, Hypothesis Testing, Text Preprocessing, Experimentation Metrics  
**Environment:** Jupyter Notebook

# 📊 Dataset

A **synthetic dataset** is generated using Python, simulating 1,000+ ads with:
- ad_id — unique identifier
- ad_text — ad copy text sample
- Impressions — number of times ad was shown
- clicks — number of clicks
- CTR — Click-Through Rate = clicks / impressions
- sentiment_score — TextBlob sentiment polarity
- ad_group — “Control” (A) vs “Experimental” (B)

# ⚙️ Methodology
1. **Generate Synthetic Ad Data**: Simulate ad texts and CTRs for both groups.
2. **Perform Sentiment Analysis**: Compute sentiment polarity and classify as Positive, Neutral, or Negative.
3. **Conduct A/B Test**:
    - Null Hypothesis (H₀): No difference in mean CTR between A and B.
    - Alternative Hypothesis (H₁): Mean CTR differs between A and B.
4. **Statistical Validation**: Run a two-sample t-test.
5. **Visualization**: Compare CTR distributions, sentiment impact, and confidence intervals.

# 📈 Results & Insights
**Statistical Significance**:
- T-Statistic: –23.34
- P-Value: 0.000000
➡️ The p-value < 0.05 confirms a statistically significant difference between Ad Groups A and B.
- Ad Group B (Experimental) outperformed Ad Group A (Control), demonstrating measurable gains in CTR.

# Interpretation:
Ads with a positive or engaging tone achieved a notable lift in CTR, validating the hypothesis that emotionally positive ad copy performs better.
The boxplot shows Group B’s CTR distribution shifted higher, while the barplot highlights Positive and Neutral sentiments performing above Negative.
These findings reflect how data-driven experimentation and GenAI-enhanced ad copy can directly improve user engagement metrics.

# Key Takeaway:
Statistical analysis confirmed that sentiment intensity correlates with ad engagement, illustrating how GenAI models and A/B testing can guide better ad design decisions and metric optimization.

# 💡 Key Learning Outcomes
- Translating product goals into measurable **North Star Metrics** (CTR, engagement).
- Integrating **Data Science Experimentation** with marketing analytics.
- Applying **GenAI and NLP** for ad optimization research.

# 🧮 Sample Use Case
Google Ads data scientists or marketing analytics teams can adapt this framework to:
- Evaluate the impact of sentiment on ad engagement.
- Identify the best-performing ad tone.
- Scale experimentation using GenAI-based text variation.

  # 📊 Visualizations Recap
- Boxplot: clearly shows a higher CTR distribution for Group B — perfect visual proof of the A/B result.
- Barplot: compares CTR by sentiment tone — Positive and Neutral performing slightly better than Negative.

<img width="574" height="443" alt="image" src="https://github.com/user-attachments/assets/28e53751-b3a1-410a-bb29-e2f6673d9413" />

<img width="602" height="447" alt="image" src="https://github.com/user-attachments/assets/296aa5c2-bd49-4349-ae6a-70f703e1bfc0" />

# Conclusion:
- Ad Group B (the experimental group) outperforms A, proving that the optimized ad copy (perhaps generated or refined with GenAI) leads to higher engagement.




