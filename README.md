# Disaster_tweets

We investigate the performance of three state-of-the art language models against
an LDA baseline for tweet classification. If tweets are about a disaster, the model
should give positive output, else not. We find that Transformers are far better in
incorporating embeddings than traditional models. The practical relevance of this is
yet to be investigated, but it could be useful for early detection of natural disasters
through social media. We find that the fine-tuned BERTweet model achieves
highest test accuracy and proves to be a potential tool in disaster response.