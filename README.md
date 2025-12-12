# 🎧 Consumer Insights Analysis: Beats by Dre

## 📌 Project Overview
This project is part of a Consumer Insights Data Analytics Externship. The goal was to analyze customer perception of Beats by Dre earbud products compared to competitors (Sony, Bose, JBL, Apple) to drive product strategy and marketing improvements.

The analysis utilizes **Natural Language Processing (NLP)**, **Sentiment Analysis**, and **Generative AI (Gemini)** to extract actionable insights from over 5,000 customer reviews.

## ❓ Business Problem
In the highly competitive audio market, understanding customer sentiment is crucial for brand positioning. This project aims to:
*   Identify pain points in current Beats products (specifically Beats Studio Buds & Solo Buds).
*   Compare sentiment against key competitors.
*   Provide data-driven strategic recommendations to improve market share.

## 🛠️ Tech Stack
*   **Data Manipulation:** Python, Pandas, NumPy
*   **Visualization:** Matplotlib, Seaborn, Plotly, WordCloud
*   **NLP & AI:** TextBlob (Sentiment Polarity), NLTK, Google Gemini AI API
*   **Statistical Analysis:** Correlation Matrices, Descriptive Statistics

## 📊 Key Findings

### 1. Sentiment Analysis
*   **JBL Tune Buds** received the highest mean sentiment polarity (**0.31**), indicating very positive reception.
*   **Beats Solo Buds** had the lowest mean sentiment (**0.18**), suggesting mixed customer experiences.
*   There is a moderate positive correlation (**0.42**) between customer rating (stars) and sentiment polarity.

### 2. The "Fit" Issue
*   Word cloud analysis and N-gram frequency revealed that "ear" and "fit" were dominant keywords.
*   **Gemini AI analysis** highlighted that while sound quality is praised, many users struggle with the physical fit of Beats earbuds during workouts, leading to lower ratings.

### 3. Competitor Benchmarking
*   **Sony & Sennheiser** lead in consistency (lowest standard deviation in ratings).
*   **Beats** benefits from strong brand recognition and aesthetic appeal (SWOT Analysis strength) but lags in perceived value-for-money compared to JBL.

## 🤖 AI Integration (Gemini)
I utilized the **Google Gemini API** to automatically summarize thousands of reviews into "Pros" and "Cons."
*   *Prompt Engineering:* "Analyze the negative reviews and summarize the key insights."
*   *Result:* Identified specific hardware issues (e.g., lack of charging indicators on cases) that simple keyword matching missed.

## 🚀 Strategic Recommendations
Based on the data, the following strategies were proposed:
1.  **Product Redesign:** Redesign ear tips for better security during physical activity to address the "falling out" complaints.
2.  **Feature Parity:** Add essential features missing in lower-tier models, such as active noise cancellation (ANC) transparency modes, to compete with JBL.
3.  **Marketing Pivot:** Leverage the high "brand coolness" factor in campaigns but pivot messaging to emphasize durability and battery life improvements.

## 📂 Project Structure
*   `code/`: The complete Jupyter Notebook containing code, visualizations, and analysis.
*   `data/`: Dataset used for analysis.

---
*Author: LE Minh Quan*
