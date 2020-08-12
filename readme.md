# Tweets
Contains json data of tweets from every US state governor's Twitter feed from when it was registered until July 30, 2020. The timestamps are keys and the text of the tweets are the values.

# tsv files

## LL_party.tsv
Log likelihood values of every type in the corpus by political party.

## LL_state.tsv
Log likelihood values of every type in the corpus by state.

## Columns
- LL: The log likelihood value of the type.
- F: Number of types per 10,000 tweets in the category
- F2: Number of types per 10,000 tweets in the rest of the corpus

```
alabama
Type            LL      F       F2
montgomery	219.29	15.11   0.23
```

The first item in the "alabama" category in LL_State.tsv is the type "montgomery". It has a log likelihood value of 219.29, occurs in 15.11 out of every 10,000 tweets in the "alabama" category and in 0.23 out of every 10,000 tweets in the rest of the categories combined. 
