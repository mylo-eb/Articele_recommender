# Author: Milad(Mylo) Ebtedaei

Sometimes individuals seek out articles or documents that share similar content with those they have already read, indicating an interest in exploring related content. Using unsupervised learning techniques, it is feasible to extract insights from articles and offer new suggestions to readers based on similarity to their previous interests.

## Article recommender system
Our aim is to offer recommendations for articles that are comparable in meaning and structure to those that have already been read. Our motivation for developing this recommender system stems from our shared passion for reading, including academic literature. With advancements in technology and the proliferation of social media, numerous articles and blog posts are published every day, making it convenient for people to access information from diverse sources. This has led to a surge in the number of individuals seeking to acquire knowledge and broaden their understanding of the world. Companies such as Medium depend on user engagement to generate revenue through their articles and blogs. When a reader discovers an insightful blog, they may be interested in perusing similar documents. If readers are unable to locate comparable articles, they tend to lose interest and disengage. Providing recommendations to users based on the articles they have read can entice them to read more and even subscribe to services that provide valuable and stimulating content.

## Dataset Information
Our dataset comprises approximately 3,000 articles that have been made publicly available on CI&T's communication platform. These articles come in various formats, such as HTML and Video. The dataset includes two files, namely "shared_articles.csv" and "users_interactions.csv", which provide detailed information on the relationships between the articles and readers, offering valuable insights. There are numerous features that can be utilized for content-based and collaborative filtering, including userCountry (the user's country) and userAgent (web browser), which can be leveraged to filter content for users and suggest articles. However, the most crucial feature is the "text", which enables us to identify common words and recommend articles based on similarity scores with other articles. 

## Requirements
- numpy
- scikit-learn
- scipy
- matplotlib
- panda
- KMeans
- NLTK
- tqdm

## Future Scope
There are instances where a reader may lose interest in an article due to the information presented being too complicated or difficult to comprehend. This can cause a drop in interest, particularly when subsequent articles are dissimilar to those previously read. To maintain user engagement, it is important to recommend articles that are similar to those the user has already read. Developing technology that can recommend articles to readers can help to sustain their interest and encourage them to read more articles.
