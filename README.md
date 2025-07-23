# Somali Social Media Sentiment Analysis on a High-Profile Case

This project analyzes Somali social media discussions surrounding the high-profile case of a police commander allegedly implicated in the murder of businessman Abuukar in the Heliwaa district. By leveraging data science and NLP techniques, the project aims to understand public sentiment, engagement patterns, and the broader societal implications reflected in online discourse.

---

## 📚 Project Overview

* **Context:**
  The case has garnered significant public and media attention in Somalia, raising critical questions about law enforcement accountability, corruption, and public trust in institutions.
* **Objective:**
  To collect, clean, and analyze Somali-language social media comments to reveal sentiment trends, engagement dynamics, and key discussion topics related to the incident.

---

## 🗂️ Dataset

* **Source:** Extracted from public Somali social media platforms using APIs (details anonymized for privacy).
* **Size:** 2,527 comments, 1,705 unique authors, no missing values.
* **Fields:**

  * `author`: Username of the commenter (1,705 unique).
  * `date`: Timestamp in ISO 8601 format.
  * `comment`: The comment text.
  * `like_count`: Number of likes (range: 0–171).
  * `reply_count`: Number of replies (range: 0–27).
  * `comment_length`: Character count for each comment.
* **Format:** CSV file, structured and ready for analysis.

---

## ⚙️ Data Pipeline

1. **Data Extraction:**

   * API-based collection focused on Somali-language content about politics/society.
   * Ensured compliance with ethical and privacy standards.
2. **Data Preparation:**

   * Removed duplicates, ensured no missing data.
   * Verified integrity and cleaned for analysis.
   * Automated scripts for reproducibility.
3. **Sentiment Annotation:**

   * Manual or semi-automated labeling as Positive ('wanaag'), Negative ('xumaan'), or Neutral ('dhexdhexaad').
   * Special attention to Somali language nuances.

---

## 🔍 Exploratory Data Analysis & Visualizations

* **Descriptive Statistics:**

  * Most comments are short (median length ≈ 97 characters), with a small subset of longer, more detailed posts.
* **Engagement Insights:**

  * Majority of comments have zero likes or replies; only a few reach high engagement.
* **Temporal Patterns:**

  * Identified periods of peak activity for targeted community engagement.
* **Trending Content:**

  * Bar plots of top-liked comments and most active users.
* **Text Analysis:**

  * TF-IDF scoring to identify key terms and phrases.
  * Word clouds to visualize dominant topics and sentiment-laden vocabulary.

---

## 💬 Sentiment Analysis

* **Label Distribution:**
  Comments categorized as Positive, Negative, or Neutral.
* **Findings:**

  * Negative sentiments dominate discussions about police conduct and justice.
  * Positive comments are rare, often calling for peace or expressing support for reforms.
  * Neutral statements include news updates or factual reporting.
* **Challenges:**

  * Analysis in Somali language requires nuanced understanding of local idioms and context.

---

## 📈 Key Insights

* Social media users are highly engaged and vocal in response to high-profile incidents, especially involving law enforcement.
* Negative sentiment prevails in public reaction to the case, underscoring distrust in police accountability.
* Engagement peaks correlate with major news updates or legal proceedings.
* Top comments (by likes) are often those calling for justice, transparency, or expressing outrage.

---

## 📝 Conclusion

This project demonstrates the power of data science to uncover public sentiment and engagement dynamics around critical social issues in Somalia. The methodology and analysis can be adapted for similar sociopolitical cases or to support community management and public policy planning.

---

## 🚀 Getting Started

1. **Clone the repository:**
   `git clone https://github.com/yourusername/somali-case-sentiment-analysis.git`
2. **Data & Notebooks:**

   * Data in `combined_data.csv`
   * Jupyter Notebook(s) for all code and visualizations
3. **Requirements:**

   * Python 3.x
   * pandas, numpy, matplotlib, seaborn, scikit-learn, wordcloud

---

## 🤝 Contact

For questions, feedback, or collaborations, please open an issue or contact my linkedin profile (https://www.linkedin.com/in/mohamed-abdullahi-kasim-12b9a732a/)

---

## 📚 References

* [YouTube Video Coverage of the Case (Somali)](https://www.youtube.com/watch?v=APfKrSnF20o&t=21s)
* World Food Programme, FEWS NET, local news reports
