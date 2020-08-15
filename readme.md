# Overview
We look at the insects on the [IUCN Red List of Threatened Species](https://www.iucnredlist.org/) and collect data to investigate the prevalence of these insects in academic research contrasted with their popularity with the public. We use Google scholar results as a proxy for prevalence in academia and results from Twitter, Google Search and Google's text corpora as a proxy for prevalence with the public. The raw serialized data dumps have been excluded from this repo as they are too large.

# APIs used
## Google search
We use the [SerpApi](https://serpapi.com/) to scrape Google search and Google scholar results.

## Twitter
We use Twitter's own [API](https://developer.twitter.com/en/docs/twitter-api) to scrape tweets

## Google text corpora
We use the [PhraseFinder API](https://phrasefinder.io/) to get the prevalence of insects in books published since the 1500s.

## Sentiment analysis
We use TextBlob and transformers, two Python packages to get sentiment analysis.


