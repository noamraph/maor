# All tweets by Maor Eichler

https://noamraph.github.io/maor

The HTML was generated like this.

I extracted the text from EichlerMaor.pdf, and searched for all the tweet IDs.

Using maor-twitter.ipynb I made a screenshot of each tweet, using pyppeteer (it uses chrome to download the embedded tweet page, and then generates a png from it).

Using imagemagick's mogrify command I converted the png files to webp files, which are much smaller.

In maor-html.ipynb I generated the HTML. I used the twitter API (sign for a developer account and get keys immediately) to get the text and metadata for each tweet.
