# Debiasing Biased Data

<h3> Introduction </h3>
You've probably seen the news. <a href='https://edition.cnn.com/2020/08/23/tech/algorithms-bias-inequality-intl-gbr/index.html'>Tech</a> <a href='https://edition.cnn.com/2020/09/21/tech/twitter-racial-bias-preview/index.html'>has</a> <a href='https://www.nytimes.com/2019/11/15/technology/algorithmic-ai-bias.html'>a</a> <a href='https://www.wgu.edu/blog/women-tech-addressing-gender-bias2002.html'>bias</a> <a href='https://www.forbes.com/sites/marenbannon/2019/04/10/the-biggest-bias-in-tech-that-no-one-talks-about/'>problem</a>.

It shouldn't surprise you that many of these biases have existed long before everyone thought using algorithms to determine where British children would be placed for further studies was a good idea. What is surprising is the blind trust in these new algorithmic tools to be paragons of fairness given that they're trained using data that our biased systems have produced. Given that pretty much all data should be assumed to have one bias or another, it seems critical for Data Analysts and Data Scientists to be aware of how to include bias correction in their work-flow. 

One very low hanging fruit in bias correction should be to foster collaboration and interaction with subject matter experts from early on in the process. A sociologist will (hopefully) tie in a host of socio-economic factors to why a pupil is underperforming according to algorithm A. This should lead the designers to iteratively improve the algorithm's predictive ability to take into account these factors.

Over the next couple of blog posts, I hope to run a journal club exercise (of one) on a review article published by Maarten Buyl and Tijl De Bie on 6th March 2020 in <a href='https://arxiv.org/pdf/2002.11442.pdf'>arxiv</a> regarding a method for building a less biased predictor. In the article, the authors provide an overview of more technical strategies for bias correction (with a **focus on the second one**) including: 
<li> Preprocessing techniques: modification of training data so as to reduce bias. Resource intensive </li>
<li> Algorithmic fairness.  Reducing the risk of bias affecting the model.</li>
<li> Postprocessing techniques: involves correcting a model's output probabilities given a specific fairness constraint. Can affect model accuracy. </li>



# <a href='https://github.com/1njiku/SB-Capstone2/blob/master/Project-Proposal%20.pdf'>Capstone Project</a>

<h3> Introduction </h3>
  Detecting sentiment from a piece of text is a key part of Natural Language Processing (NLP). It is a foundational part of recommender systems which track a user’s affinities and aversions with the aim of matching the user with a product/ service that’s helpful for them.
  
  Most work on sentiment analysis has been done on short-form text data such as those derived from micro-blogging social media sites. Because of the succinct nature of these social media posts, it is perhaps easier to glean points of view than from longer pieces of text. 
  
  Spurred by my penchant for learning new languages, I decided to perform sentiment parsing of long-form text in the form of book reviews. The aim was to see if different models are as capable in situations where the user leaves a more verbose review. Book cataloging websites might benefit from insights gained from this project in order to improve their recommendation system. If longer reviews do result in less reliable recommendations the website might decide to implement a word limit on reviews.

<h3> Data Sources </h3>
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

<h3> Results </h3>
The original dataset contained some reviews in other languages including Spanish and Arabic. Preprocessing the text reduced the reviews from a corpus of about 3,000 entries to about 1,000. The LSTM neural network incorporated more layers and had a regularization layer which probably contributed to its superior performance compared to the simple RNN on a small dataset.

The LSTM neural network had the best performance on accuracy and AUC score followed by the Bernoulli Naive Bayes and the simple RNN neural network. 


![](https://github.com/1njiku/1njiku.github.io/blob/master/images/AUC_comp_models.png)
![](https://github.com/1njiku/1njiku.github.io/blob/master/images/accuracy_comp_models.png)


<h3> Conclusions </h3>
Removing non-English text from my dataset resulted in a smaller corpus to train on than I intended therefore it's impossible to make a definitive answer to my original hypothesis. Despite the commendable performance of the LSTM, the simple RNN perhaps could benefit from having a larger training corpus in order to improve performance. 

<h3>Future Scope </h3>
<li> Adding more English language text to train the models</li>



# Greetings Earthling! I come in peace :space_invader:
<h3> Introduction </h3>
My name is Teresiah (pronounced te-re-see-ah) and I am a recent convert to the world of data. I like to think my conversion began late last year but really I've been tinkering with data (via Excel spreadsheets) since arount 2016 during my previous career as a pharmacist. Since then, I've made the plunge into a full career pivot and will use this space to document my journey. 
  Karibuni :smile:
