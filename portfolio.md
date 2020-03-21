---
title:
layout: default
permalink: /portfolio/
---

## <u>Course Work</u>


Data Structures, Algorithms, Calculus, Statistics theory, Statistical Methods, Probability,  Machine Learning, Deep Learning, Reinforcement Learning, Artificial Intelligence, Operating Systems,
Databases, Computer Architecture.

## <u>Projects</u>

**1.    Linear Regression for Ames Housing Dataset.**
	Built an explanatory linear model for the data.    
	Performed model selection using backward elimination and lasso regression.   
	Applied box cox tranformation while performing model checking.    
	Used qqplots and residual vs fitted values plot to check for violation of assumptions.
	[code link](https://github.com/bhparijat/Hypothesis-Testing-for-Linear-Models/tree/master/Project)
	    

**2.	Sentiment Analysis of Yelp Reviews(Ongoing):**      
	Performed data cleaning.    
	Built a TF-IDF model to obtain an AUROC score of 0.9.       
	Working on using CNN and LSTM for sentiment analysis task.       
	<u>Framework and platform used:</u> PyTorch, Apache Spark and Google Cloud Platform.         	

**3.    Recommendation System for MovieLens Dataset**<br/>
	Created a recommendation system for 10 million movies of MovieLens dataset by implementing collaborative filtering and matrix factorization.    
	Used nearest neighbor algorithm for the collaborative filtering method and alternating least squares method for matrix factorization.    
	<u>Framework and platform used:</u> Apache Spark and Google Cloud Platform. You may find the [code here](https://github.com/bhparijat/Recommendation-system).     
	
**4.    NYPD Crime Data Analysis**<br/>
	Reverse geocoded 4.8 million addresses using open source GIS database Pelias. Performed webscrapping to map zipcodes to city names and county names.     
	Ananlysed and generated summary statistics and visualizations for the crimes happened in New York between 2014 and 2017.     
	<u>Framework and platform used:</u> Google Cloud Platform, Google Maps Platform, BeautifulSoup, Pandas, Seaborn,Tableau, Pelias. [Code link](https://github.com/bhparijat/NYPD-crime-analysis)   
	<br/>
	
**5.    Monte Carlo Tree Search For Atari Game Pong**<br/>
	My teammate [Ravi](https://www.linkedin.com/in/sudharkj/) and I, created a Monte Carlo Tree Search and deep learning model, to generate a policy for action selection for the atari game Pong.
	We implemented ideas from the famous deep-learning paper
	[Deep Learning for Real-Time Atari Game Play Using Offline Monte-Carlo Tree Search Planning](https://web.eecs.umich.edu/~baveja/Papers/UCTtoCNNsAtariGames-FinalVersion.pdf).
	The optimal policy generated could beat random policy by a significant margin.<u>Framework and platform used:</u> PyTorch, OpenAI gym, OSU pelican cloud.
	[Code link](https://github.com/bhparijat/Monte-Carlo-Tree-Search-For-Pong)
	<br/>
	
**6.    Exploration Map Inpainting**<br/>
	For the deep learning class, I alongwith my friend [Manish Saroya](https://sites.google.com/view/manishsaroya/home?authuser=0), worked on the
	[Darpa Subterranean Challenge](https://www.subtchallenge.com/index.html) to develop a model that could rapidly map complex environments. We created a synthetic map database of 60K images
	consisting of grid-based maps. Our model could learn loop-closures, T-points and fill image holes. For this project, we used ideas from [Partial Convolution Paper](https://arxiv.org/abs/1804.07723) to implement our own UNET structure for image inpainting.<u>Framework and platform used:</u> PyTorch, OSU cloud cluster. You may find a complete report on the
	[project here](https://bhparijat.github.io/assets/report.pdf). [Code link](https://github.com/bhparijat/map-inpainting)
	<br/>
	
**7.    Lottery Scheduling**<br/>
	Implemented lottery scheduling to schedule processes in xv6 environment. Each process when created would be given a ticket. Whenever a process in the ready queue is to be scheduled, a random
	ticket is generated and tickets for the processess in the queue are summed up. As soon as the sum goes beyond the random number, a process is scheduled. <u>Framework and platform:</u> C, xv6,
	OSU server. Here is the [code link](https://github.com/bhparijat/Operating-Systems/tree/master/hw4).<br/> 
	
**8.    Parallel Reinforcement Learning** <br/>
	My teammate [Aashish](http://www.adhikariaashish.com.np/) and I,  implemented reinforcement learning algorithms like value iteration, policy iteration, Q-learning, SARSA and Deep-Q-Network
	using [Ray library](https://github.com/ray-project/ray) to leverage computation power of multiple CPUs. The parallel implementation significantly improved the overall computation time for
	larger environments without affecting the resultant policy. All the implementation was done on Intel Dev Cloud. The code can be found
	[here](https://github.com/bhparijat/Parallel-Reinforcement-Learning).<br/>
	
**9. 	Gesture Recognition** <br/>
	Trained a deep neural network with softmax cross entropy loss and adam optimization for images containing hand gestures. The trained model attained an accuracy of over 91%.
	<u>Framework and platform:</u> Tensorflow and pelican cluster of Oregon State University. The jupyter notebook containing code can be found
	[here](https://github.com/bhparijat/gesture_recognition/blob/master/sign_recognition_using__DNN.ipynb). <br/>
	
**10. 	Apparel Classification**<br/>
	Trained a CNN model on Nvidia GPUs, to classify 10 types of apparel and other clothing wear. Used Adam optimizer and Cross Entropy loss for training to attain a final loss of
	0.0035. [jupyter notebook link](https://github.com/bhparijat/Image-classification-Fashion-MNIST/blob/master/Fashion-MNIST.ipynb)<br/>

**11.	Web crawling**       
	Used BeautifulSoup library to implement a python script that could  scrape reviews of restaurants in San Francisco from Yelp website.
	[Code link](https://github.com/bhparijat/web-scraping)         
	
## <u>Graduate Research</u>

**Monte Carlo Planning** <br/>

My advisor, [Prof. Prasad Tadepalli](http://web.engr.oregonstate.edu/~tadepall/) and I, are working on developing an AI-player algorithm using Monte Carlo Tree Search for the game of [Klondike Solitaire](https://www.solitaire-klondike.com/).