## YouTube Comments Analysis

This project analyzes YouTube comments to extract valuable insights using sentiment analysis, emoji frequency analysis, and word cloud generation. The analysis is conducted using Python, leveraging various libraries including pandas, numpy, seaborn, matplotlib, TextBlob, wordcloud, emoji, and plotly.

### Project Setup
1. **Data Loading and Cleaning**:
    - The comments data is loaded from a CSV file.
    - Null values in the `comment_text` column are dropped to ensure data quality.
    - The dataset consists of 691,374 comments after cleaning.

2. **Sentiment Analysis**:
    - Using TextBlob, the polarity of each comment is calculated.
    - Polarity scores are added as a new column to the dataframe.

3. **Word Cloud Generation**:
    - Word clouds are created for positive, negative, and neutral comments.
    - Stopwords are filtered out to focus on significant words.
    - Visual analysis indicates common words in each sentiment category.

4. **Emoji Analysis**:
    - Emojis in comments are extracted and their frequencies are counted.
    - The top 10 most common emojis are identified and visualized using a bar chart.

5. **Combining Multiple CSV Files**:
    - Additional YouTube data from multiple CSV files are combined into a single dataframe.
    - Duplicate entries are removed to ensure data integrity.

### Key Insights
- **Sentiment Distribution**:
    - Positive comments contain words like "awesome" and "best".
    - Negative comments include words like "worst" and "terrible".
    - Neutral comments do not exhibit a clear pattern.
  
- **Emoji Usage**:
    - The most frequently used emojis include 😂, 😍, ❤, and 🔥.
    - Emojis enhance the emotional context of comments.

### Tools and Libraries
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical operations.
- **seaborn & matplotlib**: Data visualization.
- **TextBlob**: Sentiment analysis.
- **wordcloud**: Word cloud generation.
- **emoji**: Emoji extraction and analysis.
- **plotly**: Interactive plotting.

### Conclusion
This project provides a comprehensive analysis of YouTube comments, highlighting sentiment trends and common expressions through emojis and word clouds. It demonstrates the effectiveness of combining various data analysis and visualization tools to gain insights from large datasets.
