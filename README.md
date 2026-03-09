# AI Advertising Consumer Insights  
**Understanding consumer reactions to AI-generated advertising through sentiment, thematic, and engagement analysis**

## Project Overview

This project analyses how consumers respond to **AI-generated advertising**, using Coca-Cola’s **Masterpiece (2023)** campaign as a case study. The analysis is based on **4,800 YouTube comments** and combines sentiment analysis, topic modelling, thematic analysis, word cloud visualisation, and engagement analysis to understand how audiences perceive AI-created brand content. :contentReference[oaicite:0]{index=0}

The project was developed as part of an MSc dissertation and is presented here as a **Business Analytics / Business Analyst case study** focused on translating unstructured consumer data into actionable strategic insights for marketing and brand decision-making.

---

## Business Problem

As brands increasingly adopt **generative AI** in advertising, they face a key business challenge:

- Will consumers perceive AI-generated content as innovative and engaging?
- Or will they view it as inauthentic, unethical, or damaging to brand trust?

Traditional campaign metrics such as reach, impressions, and click-through rates do not fully capture how audiences interpret AI-generated advertising. Brands need deeper insight into:

- **consumer sentiment**
- **authenticity concerns**
- **trust and credibility**
- **social validation through engagement**
- **strategic risks and opportunities of AI adoption**

This project addresses that challenge by analysing naturally occurring public reactions rather than relying only on surveys or hypothetical experiments. :contentReference[oaicite:1]{index=1}

---

## Project Objective

The objective of this project was to evaluate **consumer reactions to AI-generated advertising** and assess what those reactions imply for:

- perceived usefulness of AI in creative marketing
- authenticity and trust in brand communication
- audience engagement and social validation
- strategic decision-making for future AI-enabled campaigns

---

## Case Study Context

The selected case study is **Coca-Cola’s Masterpiece (2023)**, a highly visible AI-supported advertising campaign that blended classical and modern artworks through generative AI-driven visual storytelling. The campaign attracted both praise for innovation and criticism for perceived inauthenticity, making it a strong case for analysing public reaction to AI in advertising. :contentReference[oaicite:2]{index=2}

---

## Data Source

The dataset consists of **4,800 cleaned YouTube comments** collected from Coca-Cola’s official *Masterpiece* campaign video.

### Data preparation included:
- extracting comments using the YouTube Data API
- removing duplicates and spam
- excluding non-English content
- standardising text for analysis
- preserving engagement metadata such as likes/dislikes where applicable

This approach provided a more natural view of audience behaviour than survey-based responses, enabling stronger ecological validity. :contentReference[oaicite:3]{index=3}

---

## Analytical Approach

This project combines quantitative and qualitative techniques to generate both scale and interpretability.

### 1. Sentiment Analysis
Sentiment polarity was classified using:
- **VADER**
- **TextBlob** (cross-validation)

This was used to quantify the share of:
- positive comments
- negative comments
- neutral comments

### 2. Topic Modelling
**Latent Dirichlet Allocation (LDA)** was used to identify dominant patterns in discussion and uncover recurring topics across the comment dataset. :contentReference[oaicite:4]{index=4}

### 3. Thematic Analysis
Topic modelling outputs were interpreted qualitatively to identify broader consumer meaning structures and recurring themes.

### 4. Word Cloud Analysis
A word cloud of negative comments was used to highlight the most salient critical terms and language patterns.

### 5. Engagement Analysis
Comment likes/dislikes were analysed to understand which reactions were most socially validated by other viewers. This added a behavioural layer beyond sentiment classification alone. :contentReference[oaicite:5]{index=5}

---

## Key Findings

### 1. Consumer reaction was strongly polarised
The analysis found:

- **45% positive**
- **33% negative**
- **22% neutral**

This shows that audience responses to AI-generated advertising were not one-dimensional. Instead, the campaign triggered both admiration and scepticism at scale. :contentReference[oaicite:6]{index=6}

### 2. Positive reactions focused on novelty and spectacle
Supportive comments often praised:
- visual creativity
- technical impressiveness
- “magic” and innovation
- Coca-Cola’s reputation for bold advertising

These reactions suggest that AI can create strong short-term attention and perceived creative value. :contentReference[oaicite:7]{index=7}

### 3. Negative reactions focused on authenticity and ethics
Critical comments frequently described the campaign as:
- “soulless”
- “fake”
- “cheap”
- a replacement for real artists

This suggests that usefulness alone is not enough for audience acceptance. Authenticity and perceived fairness are major decision factors in how AI-generated campaigns are received. :contentReference[oaicite:8]{index=8}

### 4. Five major themes emerged
Thematic analysis identified five dominant patterns in audience discourse:

- **Brand rivalry**
- **Spectacle versus garbage**
- **Christmas nostalgia**
- **Magic versus fake creativity**
- **Corporate exploitation**

Together, these themes show that audiences evaluate AI ads not only on aesthetics, but also through memory, ethics, brand identity, and cultural expectations. :contentReference[oaicite:9]{index=9}

### 5. Engagement validated both admiration and scepticism
Engagement analysis showed that both positive and negative reactions received substantial social endorsement. Neutral comments received far less attention.

This suggests that debate around AI-generated advertising is not fringe or marginal — it is **mainstream, contested, and socially reinforced**. :contentReference[oaicite:10]{index=10}

---

## Business Insights

This project generates several practical insights for businesses and marketing teams considering the use of AI in advertising.

### AI can drive attention, but not automatically trust
Generative AI can create visually impressive campaigns, but strong creative execution does not guarantee audience acceptance if authenticity is questioned.

### Authenticity is a strategic risk factor
Consumers do not evaluate AI-generated advertising only in terms of creativity or usefulness. They also assess:
- whether it feels genuine
- whether it aligns with brand identity
- whether it replaces human creativity unfairly

### Engagement metrics matter beyond reach
Likes, comments, and social endorsement patterns can reveal deeper campaign reception than simple exposure metrics.

### Brand heritage shapes AI acceptance
For established brands, audience reactions are strongly filtered through past brand associations and cultural memory. In this case, Coca-Cola’s heritage advertising influenced how consumers judged its AI-led creative choices. :contentReference[oaicite:11]{index=11}

---

## Strategic Recommendations

Based on the findings, the following business recommendations emerge:

### 1. Balance innovation with authenticity
Brands should use AI to enhance campaigns, but avoid undermining the emotional and human dimensions of storytelling.

### 2. Frame AI as augmentation, not replacement
Campaign messaging should position AI as a creative support tool rather than a substitute for artists or human creativity.

### 3. Monitor engagement quality, not just reach
Campaign evaluation should include:
- comment sentiment
- theme tracking
- engagement validation
- signs of scepticism or backlash

### 4. Consider cultural fit before deploying AI
Brands with strong nostalgic or emotionally rooted identity should be especially careful in how AI is used in consumer-facing campaigns.

### 5. Address ethical concerns proactively
Concerns about labour, fairness, and authenticity are not peripheral. They should be incorporated into campaign planning and risk assessment.

---

## Why This Project Matters for Business Analytics

This project demonstrates how **unstructured consumer data** can be transformed into strategic insight.

It shows how Business Analytics can support decision-making by:
- combining quantitative and qualitative methods
- analysing consumer behaviour beyond basic KPIs
- identifying brand and reputational risks
- supporting evidence-based marketing strategy

This is especially relevant for organisations adopting AI tools without fully understanding their impact on trust, engagement, and consumer perception.

---

## Key Visuals

> Add your visuals in the `/visuals` folder and embed them here.

### Sentiment Distribution
![Sentiment Distribution](visuals/sentiment_distribution.png)

### Topic / Theme Overview
![Topic Themes](visuals/topic_themes.png)

### Engagement Analysis
![Engagement Analysis](visuals/engagement_analysis.png)

### Negative Comment Word Cloud
![Negative Word Cloud](visuals/wordcloud_negative_comments.png)

### Conceptual Framework
![Conceptual Framework](visuals/conceptual_framework.png)

---

## Repository Structure

```text
ai-advertising-consumer-insights/
│
├── README.md
├── docs/
│   ├── executive_summary.md
│   ├── business_problem.md
│   ├── methodology.md
│   ├── key_findings.md
│   ├── business_recommendations.md
│   ├── limitations.md
│   └── my_contribution.md
│
├── visuals/
│   ├── sentiment_distribution.png
│   ├── topic_themes.png
│   ├── engagement_analysis.png
│   ├── wordcloud_negative_comments.png
│   └── conceptual_framework.png
│
├── notebooks/
│   └── analysis_notebook.ipynb
│
├── outputs/
│   ├── sentiment_summary.csv
│   ├── topic_summary.csv
│   └── engagement_summary.csv
│
├── data/
│   └── DATA_NOTE.md
│
└── requirements.txt
