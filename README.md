# nlp_predicting-claps-on-medium-articles

Building language-based regression models to predict the number of claps an article received.

Data sourced from https://www.kaggle.com/datasets/aiswaryaramachandran/medium-articles-with-content

In this notebook we will analyze a large dataset of Blog posts scraped from the Medium platform. The goal is to use text and meta data to predict the amount of 'claps' an article might receive. 'Claps' is a metric similar to 'likes', which lets the reader express a positive reaction to the content.
For this purpose, several machine learning models are built and compared. Before any analysis can be done, thorough cleaning of text and meta data is necessary, followed by a quick exploratory analysis.

The task is a typical regression problem, with 'claps' ranging between 0 and (theoretically) infinity.
The models applied can be classified as conventional regression models based on numeric and categorical features, and language models that focus on the texts and headlines themselves, trying to identify context and patterns in the text that might explain which posts are more likely to receive more claps.
In a sense, the 'claps' variable can be seen as a proxy of quality, but also 'virality' of the content.
