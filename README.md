# ml-dl-deep-dive
#### Study materials for ML and DL 

Hello folks, I’m planning to initiate a series of (long running) ML/Deep Learning sessions here in Bangalore office twice a week, to start with. Since this is an area where we need more in depth knowledge, I think it’s going to be a good investment of our time if we can go deeper into the how and the why of things, while keeping an emphasis on the applicability as well. Besides that, it’d also be a good learning opportunity for me since I need to brush up my old knowledge, and it’s about time that I get myself familiarized with some of the cutting edge algorithms in the field of AI. Current timing is Monday and Friday, 10:15 - 11:15 am, as mornings work out best for me. Below are the high level topics that I intend to cover. It’d probably take around 4 - 6 months to complete all of these materials in sufficient depth. I’m planning to prepare a pdf and a jupyter notebook for each logical section. Do let me know your thoughts on this.

##### Prerequisites:
- Linear Algebra
- Probability
- Optimization

##### Machine Learning:
- ~General concepts (cross validation, grid search etc.)~
- Supervised learning:
 	- ~Naive Bayes~
 	- ~Linear regression~
 	- ~Logistic Regression~
 	- ~Decision Tree, Random Forest~
 	- ~K-nearest Neighbours~
 	- SVM
- Unsupervised learning:
	- ~K-means clustering~
	- ~mean-shift clustering~
	- SVD
	- Bayesian Learning
	- A/B testing
	- Adaptive learning
- Deep Learning
	- Binary/Multi-class classification
	- Basics of Neural Network
	- Backpropagation
	- Ensemble Learning (Random Forest, Adaboost etc.)
	- Convolutional Neural Network
	- Unsupervised Deep Learning (vanishing gradient, PCA, t-SNE etc.)
	- NLP techniques
	- Hidden Markov Models
	- Reinforcement Learning
	- Recurrent Neural Networks
	- Deep Reinforcement Learning
	- GANs and Variational Autoencoders
	- Computer Vision, Recommender systems.


## Sources
We're gonna closely follow these four materials for our journey:

* [CS229: Machine Learning course from stanford](http://cs229.stanford.edu/syllabus.html)
* [fast.ai: Introduction to Machine Learning for Coders](http://course18.fast.ai/ml)
* [lazyprogrammer-udemy](https://deeplearningcourses.com/course_order)
* [deep-learning book by Goodfellow et al](https://www.deeplearningbook.org/)

## Anaconda
We'll be using Python for the duration of the course, so it'd become easier for all of us if we use the same distribution and version as we go. I'd suggest downloading anaconda python-3.7 version from this [official link](https://www.anaconda.com/distribution/). It bundles jupyter notebook, so we should be good.

Once the installation is completed, create a conda environment with the command
> conda create -n py3_ml python=3.6 anaconda

Now, we need to attach the newly created conda env to jupyter
> conda activate py3_ml

> conda install ipykernel

> ipython kernel install --user --name=py3_ml

> conda deactivate

Whenever we're going to use jupyter, please make sure we use this new kernel, `py3_ml`.
