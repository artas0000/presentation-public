# presentation-public

`(slide Machine learning)`

I'm Matsvei Anisovich. Today I would like to talk about machine learning.  
Machine learning is a hot topic in research and industry, with new methodologies developed all the time. 
The speed and complexity of the field makes keeping up with new techniques difficult even for experts — and potentially
overwhelming for beginners.  
A machine learning algorithm, also called model, is a mathematical expression that represents data in the context of a problem, 
often a business problem. The aim is to go from data to insight. For example, if an online retailer wants to anticipate sales for 
the next quarter, they might use a machine learning algorithm that predicts those sales based on past sales and other relevant data.
Similarly, a windmill manufacturer might visually monitor important equipment and feed the video data through algorithms trained to
identify dangerous cracks.  

`(slide Сategories)`

There are two general categories of machine learning: supervised and unsupervised. Let’s distinguish between them.

`(slide Supervised ML)`

We apply supervised ML techniques when we have a piece of data that we want to predict or explain. We do so by using previous data 
of inputs and outputs to predict an output based on a new input. For example, you could use supervised ML techniques to help a 
service business that wants to predict the number of new users who will sign up for the service next month.

`(slide Unsupervised ML)`

By contrast, unsupervised ML looks at ways to relate and group data points without the use of a target variable to predict. In other
words, it evaluates data in terms of traits and uses the traits to form clusters of items that are similar to one another. For example,
you could use unsupervised learning techniques to help a retailer that wants to segment products with similar characteristics — without
having to specify in advance which characteristics to use.

`(slide Machine methods)`

Machine learning has ten methods:
1.	Regression
2.	Classification
3.	Clustering
4.	Dimensionality Reduction
5.	Ensemble Methods
6.	Neural Nets and Deep Learning
7.	Transfer Learning
8.	Reinforcement Learning
9.	Natural Language Processing
10.	Word Embeddings

`(slide Regression)`

Regression methods fall within the category of supervised ML. They help to predict or explain a particular numerical value based on a 
set of prior data, for example predicting the price of a property based on previous pricing data for similar properties.

`(slide Classification)`

Another class of supervised ML, classification methods predict or explain a class value. For example, they can help predict whether or 
not an online customer will buy a product. The output can be yes or no: buyer or not buyer. But classification methods aren’t limited
to two classes. For example, a classification method could help to assess whether a given image contains a car or a truck. In this
case, the output will be 3 different values: 1) the image contains a car, 2) the image contains a truck, or 3) the image contains
neither a car nor a truck.

`(slide Clustering)`

With clustering methods, we get into the category of unsupervised ML because their goal is to group or cluster observations that have 
similar characteristics. Clustering methods don’t use output information for training, but instead let the algorithm define the output.
In clustering methods, we can only use visualizations to inspect the quality of the solution.  
The most popular clustering method is K-Means, where “K” represents the number of clusters that the user chooses to create.
(Note that there are various techniques for choosing the value of K, such as the elbow method.)

`(slide Dimensionality Reduction)`

As the name suggests, we use dimensionality reduction to remove the least important information (sometime redundant columns) from a 
data set. In practice, I often see data sets with hundreds or even thousands of columns (also called features), so reducing the total
number is vital. For instance, images can include thousands of pixels, not all of which matter to your analysis. Or when testing 
microchips within the manufacturing process, you might have thousands of measurements and tests applied to every chip, many of which 
provide redundant information. In these cases, you need dimensionality reduction algorithms to make the data set manageable.

`(slide Ensemble Methods)`

Ensemble methods are techniques that create multiple models and then combine them to produce improved results. Ensemble methods usually
produces more accurate solutions than a single model would. This has been the case in a number of machine learning competitions, where 
the winning solutions used ensemble methods. In the popular Netflix Competition, the winner used an ensemble method to implement a
powerful collaborative filtering algorithm. Another example is KDD 2009 where the winner also used ensemble methods. You can also find 
winners who used these methods in Kaggle competitions, for example here is the interview with the winner of CrowdFlower competition.

`(slide Neural Networks and Deep Learning)`

In contrast to linear and logistic regressions which are considered linear models, the objective of neural networks is to capture 
non-linear patterns in data by adding layers of parameters to the model. In the image below, the simple neural net has three inputs, a 
single hidden layer with five parameters, and an output layer.

`(slide Transfer Learning)`

Transfer Learning refers to re-using part of a previously trained neural net and adapting it to a new but similar task. Specifically, once you train a neural net using data for a task, you can transfer a fraction of the trained layers and combine them with a few new layers that you can train using the data of the new task. By adding a few layers, the new neural net can learn and adapt quickly to the new task.

`(slide Reinforcement Learning)`

The process for the mouse mirrors what we do with Reinforcement Learning (RL) to train a system or a game. Generally speaking, RL is a
machine learning method that helps an agent learn from experience. By recording actions and using a trial-and-error approach in a set
environment, RL can maximize a cumulative reward. Imagine a mouse in a maze trying to find hidden pieces of cheese. In our example,
the mouse is the agent and the maze is the environment. The set of possible actions for the mouse are: move front, back, left or right.
The reward is the cheese.

`(slide Natural Language Processing)`

A huge percentage of the world’s data and knowledge is in some form of human language. Can you imagine being able to read and
comprehend thousands of books, articles and blogs in seconds? Obviously, computers can’t yet fully understand human text but we can
train them to do certain tasks. For example, we can train our phones to autocomplete our text messages or to correct misspelled words. 
We can even teach a machine to have a simple conversation with a human. Natural Language Processing (NLP) is not a machine learning
method, but rather a widely used technique to prepare text for machine learning.

`(slide Word Embeddings)`

TFM and TFIDF are numerical representations of text documents that only consider frequency and weighted frequencies to represent text 
documents. By contrast, word embeddings can capture the context of a word in a document. With the word context, embeddings can quantify
the similarity between words, which in turn allows us to do arithmetic with words.  
Word representations allow finding similarities between words by computing the cosine similarity between the vector representation
of two words. The cosine similarity measures the angle between two vectors.

`(slide Summary)`

I’ve tried to cover the ten most important machine learning methods: from the most basic to the bleeding edge. Studying these methods 
well and fully understanding the basics of each one can serve as a solid starting point for further study of more advanced algorithms
and methods.



