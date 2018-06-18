# Deep-Learning-for-Sentiment-Analysis
## Natural Language Processing with Deep Learning Techniques

The dataset used for the demonstration is the Ditigal Music reviews from: http://jmcauley.ucsd.edu/data/amazon/ and the pre-trained word embedding is Google News' 300d vector (https://code.google.com/archive/p/word2vec/), I would suggest to go thoroughly with this word2vec vector.<br/>
Please download the dataset and model from those locations. The terms and conditions of the data set license apply.<br/>
The Amazon Review Dataset was published in the following papers:<br/>
* Ups and downs: Modeling the visual evolution of fashion trends with one-class collaborative filtering R. He, J. McAuley WWW, 2016 http://cseweb.ucsd.edu/~jmcauley/pdfs/www16a.pdf<br/>
* Image-based recommendations on styles and substitutes J. McAuley, C. Targett, J. Shi, A. van den Hengel SIGIR, 2015 http://cseweb.ucsd.edu/~jmcauley/pdfs/sigir15.pdf<br/>
In this example we are taking the most positive and most negative reviews from that dataset, and using simple normalization techniques. More complex techniques and larger datasets can be applied to get better results as currently the networks are overfitting in the examples. We will discuss some strategies to mitigate overfitting.<br/>

Consists of a Deep Learning model to do Sentiment Analysis over Amazon reviews data-set.<br/>
We have used 2 models to do the same<br/>
* Bi-Directional LSTM
* Temporal Convolutional Networks<br/>

Alongside we have compared the training accuracy & validation accuracy for both models in order to showcase the best model for this use-case.
<br/>
Pre-requisite for the following is:<br/>
* Python
* Jupyter Notebook
* Basics of Deep Learning
* Models of Deep Learning
* Basics of Matplot

Optional:<br/>
* Understanding of numpy
* Pandas Data Frame
* gensim or word2vec(Google Code)

I would strongly recommend to go through word2vec once, since it'll help you understand few of the steps really well and you'll be able to process what actually is going on.<br/>
Make sure your python is installed and working correctly.<br/>
Install the following before starting the to run the notebook:<br/>
* Jupyter Notebook
* Gensim
* Matplotlib
* pandas
* numpy
* sklearn

You can run the following command to do so:</br>
### pip install jupyter notebook gensim matplotlib pandas numpy sklearn ###
