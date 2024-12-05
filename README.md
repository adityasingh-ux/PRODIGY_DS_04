# Sentiment Analysis on Social Media Data  

This project focuses on analyzing and visualizing **sentiment patterns** in social media data (primarily tweets) to gain insights into public opinion and attitudes towards specific topics or brands. The analysis leverages Python and popular data science libraries such as **Pandas**, **Seaborn**, and **Matplotlib** to clean, analyze, and visualize the dataset.  

---

## 📂 Dataset  

### **1. `twitter_training.csv`**  
- Contains training data with tweets labeled with sentiments.  
- **Columns**:  
  - `Text`: The tweet text.  
  - `Sentiment`: The sentiment of the tweet (Positive, Negative, Neutral, Irrelevant).  
  - `Platform`: The platform from which the tweet was posted (e.g., Twitter).  

### **2. `twitter_validation.csv`**  
- Validation data with the same format as the training dataset.  

---

## 🎯 Objective  

The primary goals of this analysis are:  
1. **Text Preprocessing**: Clean and preprocess the textual data for sentiment analysis.  
2. **Sentiment Analysis**: Analyze sentiment distributions and extract meaningful insights.  
3. **Data Visualization**: Create informative visualizations to uncover sentiment patterns and trends.  

---

## 🔄 Steps  

### **1. Data Cleaning**  
- Remove missing or irrelevant data.  
- Preprocess the text by:  
  - Removing stop words and special characters.  
  - Tokenizing the text.  

### **2. Sentiment Analysis**  
- Categorize tweets into sentiment categories: **Positive**, **Negative**, **Neutral**, and **Irrelevant**.  
- Compute the **average word count** for each sentiment.  

### **3. Data Visualization**  
Visualizations created include:  
- **Sentiment Distribution Across Platforms**: A countplot showing sentiment frequency across different platforms.  
- **Barplot for Sentiment Distribution**: A bar chart illustrating the proportion of sentiments in the dataset.  
- **Average Word Count by Sentiment**: Box plots displaying average word counts per sentiment category.  
- **Correlation Between Sentiment and Text Length**: Box plots revealing relationships between sentiment and text length.  

---

## 📊 Insights  

1. **Sentiment Distribution**:  
   Sentiments are evenly distributed across platforms, though certain platforms show stronger associations with specific sentiments.  

2. **Word Count Trends**:  
   - **Positive sentiments** tend to have a higher average word count.  
   - **Negative and Irrelevant sentiments** often feature shorter tweets.  

3. **Text Length and Sentiment Correlation**:  
   Sentiments like **Negative** and **Irrelevant** are more likely to have shorter tweet lengths, reflecting concise negative feedback or irrelevant posts.  

---

## 💡 What I Learned  

- Sentiment analysis can provide valuable insights into public emotions and opinions on social media platforms.  
- **Text preprocessing** is a crucial step for handling noisy, unstructured text data in NLP tasks.  
- **Visualizations** make it easier to uncover and communicate trends, such as sentiment distributions and correlations.  

---

## 📈 Conclusion  

This project demonstrates how sentiment analysis can transform social media data into actionable insights. By analyzing and visualizing sentiment distributions and their correlations with text features, this analysis helps reveal public opinions about topics, brands, or events. These insights can inform decision-making in marketing, customer service, and product development.  

---

## 🛠 Technologies Used  

- **Python**  
- **Pandas**  
- **Seaborn**  
- **Matplotlib**  

---
