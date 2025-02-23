## Preaching_research
We are researching Hungarian preaching that has been broadcast on public media platforms, specifically on TV.

## data
  The sermons of five churches (Catholic, Calvinist, Lutheran, Baptist, and Methodist) were sourced from [nava.hu](https://nava.hu/), and processed using NLP methods. Currently, we have 121 sermons, which we are reviewing for content analysis. These sermons were delivered between May 22, 2016, and October 20, 2024.  

## Research discribe
The focus of this research is on public political words and phrases appearing in these sermons. We created a "Public Politics Dictionary" with the help of ChatGPT. After applying data-cleaning methods, this dictionary contains 263 words. We performed a Poisson regression analysis on the training and test datasets, where the normalization factor was the length of the document. Additionally, we conducted various time series analyses to explore which factors influence the number of public political phrases. Sentiment analysis was also applied using a dictionary-based method. The Hungarian sentiment dictionary was sourced from https://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm. Furthermore, we carried out a time series analysis of the "fear" sentiment elements, comparing them to the frequency of public political phrases.
