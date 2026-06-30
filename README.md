# 🛒 Amazon Reviews Sentiment Analysis using Natural Language Processing (NLP)

## 📌 Project Overview

Customer reviews contain valuable information about product quality, customer satisfaction, and common issues. Manually analyzing thousands of reviews is time-consuming and inefficient.

This project builds an **end-to-end Natural Language Processing (NLP) pipeline** to analyze Amazon product reviews. It performs text preprocessing, sentiment analysis, topic modeling, clustering, and visualization to extract meaningful insights from customer feedback.

The project demonstrates practical applications of NLP techniques using Python and popular machine learning libraries.

---

# 🎯 Objectives

- Analyze customer sentiments from Amazon product reviews.
- Clean and preprocess raw text data.
- Convert text into machine-readable format.
- Discover hidden topics discussed by customers.
- Group similar reviews using clustering.
- Visualize high-dimensional text data using t-SNE.
- Generate business insights from customer feedback.

---

# 📂 Dataset

The dataset contains Amazon customer reviews with information such as:

- Review Text
- Rating
- Product Information (if available)

For sentiment analysis:

- ⭐⭐⭐⭐⭐ & ⭐⭐⭐⭐ → Positive
- ⭐⭐⭐ → Neutral
- ⭐⭐ & ⭐ → Negative

---

# 🛠️ Technologies Used

| Category | Libraries |
|----------|-----------|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, WordCloud |
| NLP | NLTK |
| Machine Learning | Scikit-learn |
| Topic Modeling | Gensim |
| Dimensionality Reduction | t-SNE |

---

# 📋 Project Workflow

```
Amazon Reviews
        │
        ▼
Data Cleaning
        │
        ▼
Text Preprocessing
        │
        ▼
Tokenization
        │
        ▼
Stopword Removal
        │
        ▼
Lemmatization
        │
        ▼
Sentiment Analysis
        │
        ▼
Topic Modeling (LDA)
        │
        ▼
K-Means Clustering
        │
        ▼
t-SNE Visualization
        │
        ▼
Business Insights
```

---

# 🔍 NLP Pipeline

### 1. Data Cleaning

- Removed missing values
- Selected relevant columns
- Removed duplicate records
- Created sentiment labels

---

### 2. Text Preprocessing

The following preprocessing steps were performed:

- Convert text to lowercase
- Remove punctuation
- Remove numbers
- Remove special characters
- Tokenization
- Stopword Removal
- Lemmatization

This improves text quality before analysis.

---

### 3. Exploratory Data Analysis

Performed exploratory analysis to understand:

- Sentiment distribution
- Most frequent words
- Word Clouds
- Review statistics

---

### 4. Topic Modeling (LDA)

Latent Dirichlet Allocation (LDA) was used to discover hidden topics within customer reviews.

Example topics identified:

- Battery
- Display
- Delivery
- Packaging
- Price
- Product Quality

This helps understand what customers discuss most frequently.

---

### 5. K-Means Clustering

Customer reviews were grouped into clusters based on textual similarity.

The clustering helps identify groups of reviews discussing similar themes without using predefined labels.

---

### 6. t-SNE Visualization

Since text vectors exist in high-dimensional space, **t-SNE (t-Distributed Stochastic Neighbor Embedding)** was used to reduce dimensions from hundreds of features to two dimensions.

This visualization helps:

- Understand cluster separation
- Explore review similarity
- Identify hidden patterns in customer feedback

---

# 📊 Visualizations

The project includes visualizations such as:

- Sentiment Distribution
- Word Frequency
- Word Clouds
- Topic Visualization
- Cluster Visualization
- t-SNE 2D Projection

---

# 💡 Key Insights

- Majority of reviews were positive.
- Topic modeling identified major customer concerns and product strengths.
- Similar reviews naturally formed clusters.
- t-SNE clearly visualized customer review groups.
- NLP techniques transformed unstructured text into meaningful business insights.

---

# 📁 Project Structure

```
Amazon-Review-Sentiment-Analysis/

│── Amazon_Review_NLP.ipynb
│── README.md
│── requirements.txt
│── images/
│      ├── sentiment_distribution.png
│      ├── wordcloud.png
│      ├── lda_topics.png
│      ├── clustering.png
│      └── tsne_visualization.png
│── dataset_link.txt
```
---

# 📈 Skills Demonstrated

- Natural Language Processing
- Text Preprocessing
- Sentiment Analysis
- Topic Modeling (LDA)
- Unsupervised Learning
- K-Means Clustering
- Dimensionality Reduction
- Data Visualization
- Feature Engineering
- Python Programming

---

# 🎯 Business Impact

This project can help organizations:

- Monitor customer satisfaction
- Detect common complaints
- Identify product improvement areas
- Analyze customer opinions at scale
- Support data-driven business decisions

---

# 👨‍💻 Author

**Aditi Vashisht**

Pharmacist transitioning into Data Science

Skills:
- Python
- SQL
- Machine Learning
- Natural Language Processing
- Data Analysis
- Data Visualization

---

# ⭐ If you found this project useful, consider giving it a Star!
