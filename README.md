# ml-dl-deep-dive

Hello folks, I’m planning to initiate a series of (long running) ML/Deep Learning sessions here in Bangalore office twice a week, to start with. Since this is an area where we need more in depth knowledge, I think it’s going to be a good investment of our time if we can go deeper into the how and the why of things, while keeping an emphasis on the applicability as well. Besides that, it’d also be a good learning opportunity for me since I need to brush up my old knowledge, and it’s about time that I get myself familiarized with some of the cutting edge algorithms in the field of AI. Current timing is Monday and Friday, 10:15 - 11:15 am, as mornings work out best for me. Below are the high level topics that I intend to cover. It’d probably take around 4 - 6 months to complete all of these materials in sufficient depth. I’m planning to prepare a pdf and a jupyter notebook for each logical section. Do let me know your thoughts on this.

#### Prerequisites:
- Linear Algebra
- Probability
- Optimization

#### Machine Learning:
- ~General concepts (cross validation, grid search etc.)~
- **Supervised learning**:
 	- ~Naive Bayes~
 	- ~Linear regression~
 	- ~Logistic Regression~
 	- ~Decision Tree, Random Forest~
 	- ~K-nearest Neighbours~
 	- ~SVM~
- **Unsupervised learning**:
	- ~K-means clustering~
	- ~mean-shift clustering~
	- ~Gaussian Mixture Model~
	- ~Bayesian Learning~
- **Applications in NLP**:
	- SVD
	- TF-IDF
	- Sentiment Analysis
	- Latent Symantic Analysis
	- Article Spinner
- **Deep Learning**:
	- Basics of Neural Network
	- Binary/Multi-class classification
	- Backpropagation
	- Convolutional Neural Network
	- Unsupervised Deep Learning (vanishing gradient, PCA, t-SNE etc.)
	- Hidden Markov Models
	- Reinforcement Learning
	- Recurrent Neural Networks and its applications in NLP

### Sources
We're gonna closely follow these four materials for our journey:

* [CS229: Machine Learning course from stanford](http://cs229.stanford.edu/syllabus.html)
* [fast.ai: Introduction to Machine Learning for Coders](http://course18.fast.ai/ml)
* [lazyprogrammer-udemy](https://deeplearningcourses.com/course_order)
* [Hands-On Machine Learning with Scikit-Learn and Tensor Flow: Concepts, Tools, and Techniques to Build Intelligent System](https://www.amazon.in/Hands-Machine-Learning-Scikit-Learn-Tensor/dp/9352135210/ref=sr_1_1?crid=1DYL86KS3B7IV&keywords=aurelien+geron&qid=1561703909&s=gateway&sprefix=aurelion%2Caps%2C270&sr=8-1)
* [deep-learning book by Goodfellow et al](https://www.deeplearningbook.org/)

If you're planning to get a stronger grasp on the math behind all of this, I'd suggest going through these three courses:

* [MIT 6.041 Probabilistic Systems Analysis and Applied Probability](https://www.youtube.com/watch?v=j9WZyLZCBzs&list=PLUl4u3cNGP60A3XMwZ5sep719_nh95qOe&index=1)
* [MIT 18.06 Linear Algebra](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8)
* [MIT 18.065 Matrix Methods in Data Analysis, Signal Processing, and Machine Learning](https://www.youtube.com/playlist?list=PLUl4u3cNGP63oMNUHXqIUcrkS2PivhN3k)

### Anaconda
We'll be using Python for the duration of the course, so it'd become easier for all of us if we use the same distribution and version as we go. I'd suggest downloading anaconda python-3.7 version from this [official link](https://www.anaconda.com/distribution/). It bundles jupyter notebook, so we should be good.

Once the installation is completed, create a conda environment with the command
> conda create -n py3_ml python=3.6 anaconda

Now, we need to attach the newly created conda env to jupyter
> conda activate py3_ml

> conda install ipykernel

> ipython kernel install --user --name=py3_ml

> conda deactivate

Whenever we're going to use jupyter, please make sure we use this new kernel, `py3_ml`.
