# Moral-Role-Prediction

This repository contains dataset and codes for predicting subframes in text. The approach is describe in the following paper.

> [Identifying Morality Frames in Political Tweets using Relational Learning\
> Shamik Roy, Maria Leonor Pacheco and Dan Goldwasser\
> Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing (EMNLP 2021)](https://aclanthology.org/2021.emnlp-main.783.pdf)

## Dataset

The annotated tweet dataset can be found in the _'annotated_dataset'_ folder. The folder contains separate json files for each of the Moral Foundations. Upon parsing the json files a dictionary of the following format can be found.

```
{
tweet_id:
  {
  'annotations': ...,
  'author-label': ..., 
  'dop': ..., 
  'issue': ..., 
  'text': ...
  }
}

tweet_id : Actual tweet id
annotations : Character indexed annotation by each of the annotators
author-label : Political affiliation of the author of the tweet (Republican or Democrat)
dop : Date of Publication
issue : Topic of the tweet
text : tweet text
```

The _'dataset_description.txt'_ file contains more information about the data files. Note that, we cannot release the tweet texts because of Twitter Privacy Policy. The tweet text can be parsed using the tweet_ids provided in the json files. If you need those immediately or require any help in parsing feel free to send an e-mail to roy98@purdue.edu .

## Code
Coming Soon. Please send an e-mail to roy98@purdue.edu for emergency cases. 

## Citation
If you find the dataset and approach helpful in your work, please cite the paper.

```
@inproceedings{roy2021identifying,
  title={Identifying Morality Frames in Political Tweets using Relational Learning},
  author={Roy, Shamik and Pacheco, Mar{\'\i}a Leonor and Goldwasser, Dan},
  booktitle={Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing},
  pages={9939--9958},
  year={2021}
}
```
