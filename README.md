# RAG-System

This project involves creating a RAG systed based on a large language model in a particular domain to combine both the generative/informational power of large language models, along with an ability to retrieve specialised information that would not be in the training data of the LLM.


The colab notebook 'RAG_based_on_Llama3.ipynb' details out the implmentation and serves as a self-contained report. 

The dataset is from kaggle and is a collection 2,225 news articles published by the BBC News, spanning various categories including Sport, Business, Politics, Tech, and Entertainment. Our language of focus is English.


Other architecture:
-> This project uses Llama3 LLM as this is the new state-of-the-art and finetuned and optimized for dialogue/chat bot use cases.

-> It also uses 'BAAI/bge-small-en-v1.5' as sentence embedder. This is trained on English texts. In future, if we plan to increase our focus to other languages, this model supports that. Also the embedding size is 384, not too long as contexts in news is pretty easy to capture. We don't find a lot a varying sentences within a paragraph.
