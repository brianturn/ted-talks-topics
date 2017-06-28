# Uncovering the most common TED Talk topics

## Summary

If you were tasked with presenting a prestigious TED Talk, what would you talk about?

For this natural language processing project, I examined patterns and topics common to TED Talks. In a somewhat tongue-and-cheek response, I presented my findings as “the 25 most common topics to avoid -- if you want to be original.”

After scraping 2300 TED Talk transcripts using BeautifulSoup, I compared topic modelling techniques using Latent Dirichlet Allocation and TF-IDF (Term Frequency-Inverse Document Frequency). 

I completed this project while attending [Metis](https://www.thisismetis.com/), a full-time, data science bootcamp. 

## Repo Contents

The IPython Notebooks are [here](https://github.com/brianturn/ted-talks-topics/tree/master/notebooks).

The PDF is [here](https://github.com/brianturn/ted-talks-topics/blob/master/presentation/turner_presentation_ted.pdf). 

D3 visualizations: [collapsible tree](http://bl.ocks.org/anonymous/21033ce472e9f6699acd7597c47325ec), [word cloud](https://github.com/brianturn/ted-talks-topics/blob/master/viz_ted/word_cloud.png), [sentiment graph](https://github.com/brianturn/ted-talks-topics/blob/master/viz_ted/sentiments_viz.png), and [intertopic distance cluster](https://github.com/brianturn/ted-talks-topics/blob/master/viz_ted/intertopic_distance.png)

## Tools used
- nltk
- sci-kit learn
- BeautifulSoup
- D3.js
- Pandas
