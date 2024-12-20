# Netflix Reviews Topic Modeling and Sentiment Analysis Project

The goal of this project is to analyze customer reviews of Netflix to gain a deeper understanding of customer sentiment and identify prominent topics discussed in the reviews. This analysis aims to reveal insights about user satisfaction, key issues faced by users, and general attitudes toward Netflix's services. The project is divided into two major components: data preprocessing and topic modeling and sentiment analysis.

### Part 1: Data Preprocessing and Topic Modeling

The dataset was first preprocessed using a combination of text-cleaning techniques from the NLTK (Natural Language Toolkit) library. 

After preprocessing, Latent Dirichlet Allocation (LDA) was used to perform topic modeling. LDA helped identify the most significant themes mentioned by Netflix users.
The resulting topics were then visualized using PyLDAvis, an interactive visualization tool that provided a graphical representation of topics, including their relevance and overlaps. This helped in understanding the different topics discussed in customer reviews, such as technical issues, subscription-related feedback, content preferences, and overall service satisfaction.

### Part 2: Sentiment Analysis Methods Comparison

The second part of the project focused on sentiment analysis of the reviews to determine whether the customer sentiments were positive, neutral, or negative. For this, we applied and compared different sentiment analysis approaches to assess which method yields the most reliable results for our dataset. 