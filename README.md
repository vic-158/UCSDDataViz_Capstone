# UCSDDataViz_Capstone

## Fake News Finder

![Fake News](https://d18lkz4dllo6v2.cloudfront.net/cumulus_uploads/entry/2018-06-13/Fake%20News%20Cover%20Image.jpg?pw=1200)

Team Left Shark

* Brendan MacNeill
* Holly Bergen
* Jason Winer
* Leslie Yee
* Victor Chen

The internet is full of information, much of it true but just as much fake. Fake news seems to proliferate headlines and is a buzzword for the modern era and to assist people in determining whether a news article is actually real or fake. We propose utilizing our machine learning create a Fake News Finder application whereby a person can determine whether a news article is fake. We will do this in the following ways:

## Datascrape the a combination of following sources:

1. Subreddit r/Onion for fake news
2. Subreddit r/Satire for fake news
3. Kaggle fake news article dataset
4. AP API for real news
5. Reuters API for real news


## Libraries:

These will be aggregated into csv or json files for our model to reference. Next we will train our model using libararies including the following:

* Numpy
* Pandas
* SKLearn
* Seaborn
* BeautifulSoup
* Matplotlib
* PushiftAPI ?
* AWS - Load data into DynamoDB and spin up APIs

## Methodology:
The app will classify articles as fake or real based on headline content and we will include a confusion matrix to demonstrate eror in our results. We will also do a short analysis of most common aspects of fake news including keywords associated with satirical or genuine news.
