# Sentiment Analysis on YouTube Comments

## Project Overview
This project focuses on analyzing YouTube comments to understand public sentiment and identify key themes around **Generative AI**. By leveraging Natural Language Processing (NLP) techniques, we classify comments into positive, neutral, and negative sentiments and uncover recurring topics of discussion. The project also includes insightful visualizations to represent sentiment trends effectively.

---

## Features
- **Sentiment Classification:** Categorizes comments into Positive, Neutral, and Negative using VADER.
- **Topic Modeling:** Extracts dominant themes using Latent Dirichlet Allocation (LDA).
- **Visualization:** Generates pie charts, bar graphs, and word clouds for better interpretability.
- **Data Cleaning:** Preprocesses raw YouTube comments by removing noise, standardizing text, and lemmatizing tokens.

---

## Tools and Technologies
### **Programming Language**
- Python

### **Development Environment**
- Jupyter Notebook

### **Libraries**
- **Data Processing:** Pandas, BeautifulSoup
- **NLP:** NLTK, SpaCy
- **Topic Modeling:** Gensim (LDA)
- **Visualization:** Matplotlib, WordCloud

### **Data Source**
- YouTube comments stored in CSV format.

---

## Project Workflow
1. **Data Collection**
   - Extract comments from YouTube videos discussing generative AI.
   - Consolidate multiple CSV files into a single dataset.
2. **Data Preprocessing**
   - Remove HTML tags, special characters, emojis, and noise.
   - Tokenize and lemmatize text to normalize data.
3. **Sentiment Analysis**
   - Classify sentiments using VADER (Positive, Neutral, Negative).
4. **Topic Modeling**
   - Use LDA to identify key themes and topics within the comments.
5. **Visualization**
   - Generate pie charts for sentiment distribution.
   - Create word clouds to visualize commonly used terms.

---

## Results
- **Sentiment Distribution:**
  - Positive: 46.9%
  - Neutral: 27.5%
  - Negative: 25.6%
- **Key Topics Identified:**
  - Privacy concerns
  - Ethical implications
  - Innovations in AI
- **Visuals:**
  - Pie charts and word clouds representing sentiment trends and themes.

---

## Challenges
- Handling noisy and unstructured text data.
- Accurately classifying short, informal comments.
- Optimizing LDA models for meaningful topic extraction.
- Visualizing large datasets effectively.

---

## Future Work
- **Real-Time Analysis:** Integrate APIs for live comment extraction and tracking.
- **Advanced Models:** Employ BERT or similar neural networks for better sentiment classification.
- **Multilingual Support:** Expand analysis to include non-English comments.
- **Interactive Dashboards:** Develop dashboards for dynamic visualization and exploration.

