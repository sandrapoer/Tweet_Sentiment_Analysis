# Tweet_Sentiment_Analysis
Fine-tuning XLM-RoBERTa-base for sentiment analysis task on a multilingual tweet dataset

**Project Overview**
This project fine-tuned the multilingual language model XLM-RoBERTa-base for sentiment analysis on a dataset of multilingual tweets. Tweets were classified into positive, neutral, or negative categories, and model performance was evaluated both quantitatively and qualitatively. The dataset (cardiffnlp/tweet_sentiment_multilingual from Hugging Face) was preprocessed and split into training, validation, and test sets. Due to limited resources, training was performed on Google Colab (CPU) with reduced batch sizes and token length. Key metrics such as accuracy (final: 64.5%) were used for evaluation, alongside embedding visualizations via TensorBoard to understand how the model learned sentiment representations over time.

Despite resource constraints, the model demonstrated the ability to generalize across multiple languages and identified key challenges in sentiment detection, including sarcasm, negation, and cultural nuance.

**Key Features**
Fine-tuned xlm-roberta-base on multilingual tweets
Classification into 3 sentiment classes: positive, neutral, negative
Evaluation using accuracy & qualitative analysis
Visualization of embeddings over training epochs (TensorBoard)
Insights into cross-lingual performance and sentiment clustering
