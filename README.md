# Customer_Reviews_Sentiment_Analysis
![1_Yzvu3Fgk-2eZDHmQ1tqgrA](https://user-images.githubusercontent.com/79527973/211901368-85ce29fe-28c4-4e0b-86a2-93fd99cec64f.png)

### Project Scope:
The goal of this project is to perform sentiment analysis on a dataset of reviews using two different techniques in Python: VADER (Valence Aware Dictionary and sEntiment Reasoner) and a Roberta pretrained model from Hugging Face's pipeline. The project will involve the following steps:
1. Data import: The dataset of reviews will be read in from a CSV file using the pandas library.

2. Data exploration: Basic exploratory data analysis will be performed on the dataset to understand the distribution of review scores using matplotlib, seaborn library and display the result by plotting.

3. Text preprocessing: The text of the reviews will be tokenized using nltk library and cleaned using regular expression

4. Sentiment analysis with VADER: The VADER model will be used to predict the polarity scores (neg, neu, pos) of the text using the NLTK library's SentimentIntensityAnalyzer class

5. Sentiment analysis with Roberta: The Roberta pretrained model from HuggingFace pipeline will be fine-tuned on the specific dataset using huggingface library and fine-tuning the architecture using PyTorch library and It will be used to predict the polarity of the text.

6. Results comparison: The results from the two different techniques will be compared and evaluated by visualizing the results using the Matplotlib library or comparing the metrics like accuracy, precision, recall etc.
