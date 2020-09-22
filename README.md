# <a href='https://github.com/1njiku/SB-Capstone2/blob/master/Project-Proposal%20.pdf'>Springboard Capstone</a>

<h2> Introduction </h2>
  Detecting sentiment from a piece of text is a key part of Natural Language Processing (NLP). It is a foundational part of recommender systems which track a user’s affinities and aversions with the aim of matching the user with a product/ service that’s helpful for them.
  
  Most work on sentiment analysis has been done on short-form text data such as those derived from micro-blogging social media sites. Because of the succinct nature of these social media posts, it is perhaps easier to glean points of view than from longer pieces of text. 
  
  Spurred by my penchant for learning new languages, I decided to perform sentiment parsing of long-form text in the form of book reviews. The aim was to see if different models are as capable in situations where the user leaves a more verbose review. Book cataloging websites might benefit from insights gained from this project in order to improve their recommendation system. If longer reviews do result in less reliable recommendations the website might decide to implement a word limit on reviews.

<h2> Data Sources </h2>
<li>List of book reviews rated 1 (negative) or 2 (positive). csv file obtained from <a href='https://www.kaggle.com/rakeshkakati/book-reviews'>Kaggle</a>: 2 columns, about 2,800 rows.</li>
<li>List of book reviews rated 1 to 5 scraped from the book reviews aggregator website Goodreads. csv file obtained from <a href='https://www.kaggle.com/san089/goodreads-dataset
'>Kaggle</a>: 2 columns, about 400 rows.</li>

<h2> Repository Navigation </h2>
<ol>
  <li><a href='https://github.com/1njiku/SB-Capstone2/blob/master/a.EDA_Preprocessing.ipynb'>EDA and Preprocessing</a></li>
  <li><a href='https://github.com/1njiku/SB-Capstone2/blob/master/Capstone%202%20Milestone%20Report%20.pdf'>Milestone Report</a></li>
  <li><a href='https://github.com/1njiku/SB-Capstone2/blob/master/b.%20Bernoulli_Naive_Bayes.ipynb'>Bernoulli Naive Bayes Model</a></li>
  <li><a href='https://github.com/1njiku/SB-Capstone2/blob/master/c.LSTM.ipynb'>Long Short Term Memory (LSTM) Neural Network</a></li>
  <li><a href='https://github.com/1njiku/SB-Capstone2/blob/master/d.RNN.ipynb'>Simple Recurrent Neural Network (simple RNN)</a></li>
  <li><a href='https://github.com/1njiku/SB-Capstone2/blob/master/Capstone%202%20Slides%20.pdf'>TL;DR Slides</a></li>
</ol>

<h2> Results </h2>
The original dataset contained some reviews in other languages including Spanish and Arabic. Preprocessing the text reduced the reviews from a corpus of about 3,000 entries to about 1,000. The LSTM neural network incorporated more layers and had a regularization layer which probably contributed to its superior performance compared to the simple RNN on a small dataset.

The LSTM neural network had the best performance on accuracy and AUC score followed by the Bernoulli Naive Bayes and the simple RNN neural network. 


![](https://github.com/1njiku/1njiku.github.io/blob/master/images/AUC_comp_models.png)
![](https://github.com/1njiku/1njiku.github.io/blob/master/images/accuracy_comp_models.png)


<h2> Conclusions </h2>
Removing non-English text from my dataset resulted in a smaller corpus to train on than I intended therefore it's impossible to make a definitive answer to my original hypothesis. Despite the commendable performance of the LSTM, the simple RNN perhaps could benefit from having a larger training corpus in order to improve performance. 

<h2>Future Scope </h2>
<li> Adding more English language text to train the models</li>



# Greetings Earth-form! I come in peace :space_invader:
<h2> Introduction </h2>
My name is Teresiah (pronounced te-re-see-ah) and I am a recent convert to the world of data. I like to think my conversion began late last year but really I've been tinkering with data (via Excel spreadsheets) since arount 2016 during my previous career as a pharmacist. Since then, I've made the plunge into a full career pivot and will use this space to document my journey. 
Karibuni :smile:
