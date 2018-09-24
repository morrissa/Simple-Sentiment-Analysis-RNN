# Simple-Sentiment-Analysis-RNN
I found an old model of a RNN used for a simple task of doing sentiment analysis on a dataset based on tv show reviews. I believe it's a great reflective exercise to go back and review old code, software, and models you have built, in order to help you understand where some common mistakes or habits in your coding is coming from; in addition to also maybe doing some spit and polish on some old code to give it new life.

I believe the next phase of this code is to maybe slim it down and try it out in Keras, and create a pipeline in which new movie/show reviews can be fed in and scored either positive or negative - just as an experiment.

To provide a summary of the code, and anyone who may want to play with it:

The code makes use of word embeddings, as a big move away from one-hot encoding as the vocab of sentiment or review based data can be huge

It is written in Jupyter notebook and Python, more for the sake of exploration and learning; however it can be turned into a executable python file - once I/you are happy with the result.

Being one of my first models I ever built it taught me how amazing and heartbreaking Tensorflow can be.......

Accuracy of the model is 81.4% however with some more additions within the dataset, as well as some more experimenting with the model architecture it may improve; however as I said I am aiming to make the model a bit less bloated and more slimline as to allow for some automation and maybe a pipeline with some webscraping off of movie and tv show review websites.
