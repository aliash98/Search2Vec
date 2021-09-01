# Search2Vec
Influenced by methods introduced in "Scalable Semantic Matching of Queries to Ads in Sponsored Search Advertising" by Mihajlo Grbovic et al., which is also known as "Search2Vec", this code learns the embedding space of search queries and available products (or product categories). The dataset is from "torob.com", which is the biggest product associated search engine in Iran. This data in fact, became available in the datadays.ir competition.

Exploratory Data Analysis (EDA) analysis is available on the Search2Vec.ipynb.

The skip-gram is implemented with Tensorflow, Pandas and NumPy.

Normalized Discounted Cumulative Gain (nDCG) is used to test the model.

