# HarryPotter_SentimentContribution
Sentiment analysis exists to learn what was said about that topic — was it good or bad? With the growing use of the internet in our daily lives, vast amounts of unstructured text is being published every second of every day, in blog posts, forums, social media, and review sites, to name a few. Sentiment analysis systems can take this unstructured data and automatically add structure to it, capturing the public’s opinion about products, services, brands, politics, etc. This data holds immense value in the fields of marketing analysis, public relations, product reviews, net promoter scoring, product feedback, and customer service

The seven novels we are working with, and are provided by the harrypotter package, include:
philosophers_stone: Harry Potter and the Philosophers Stone (1997)
chamber_of_secrets: Harry Potter and the Chamber of Secrets (1998)
prisoner_of_azkaban: Harry Potter and the Prisoner of Azkaban (1999)
goblet_of_fire: Harry Potter and the Goblet of Fire (2000)
order_of_the_phoenix: Harry Potter and the Order of the Phoenix (2003)
half_blood_prince: Harry Potter and the Half-Blood Prince (2005)
deathly_hallows: Harry Potter and the Deathly Hallows (2007)

To understand how the sentiment changes over the course of each novel? We perform the following:

create an index that breaks up each book by 500 words; this is the approximate number of words on every two pages so this will allow us to assess changes in sentiment even within chapters
join the bing lexicon with inner_join to assess the positive vs. negative sentiment of each word
count up how many positive and negative words there are for every two pages”
spread our data and…
calculate a net sentiment (positive - negative)
plot our data
