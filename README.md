# ProbablyTensorFlow

Bayesian Inference is not a complex idea, while there are some complexities, we are actually witnessing a selection bias in that we rarely see simple problems solved in a Bayesian way because simple problems work well with frequentist analysis.  We only turn to Bayesian inference when frequentism fails! As such, Bayesian Inference seems significantly more insurmountable when your introduction has us solving problems which you've never heard of before!

This is an introduction to Bayesian Inference with TensorFlow Probability, looking at simple problems like coin tosses and linear regression to build an intuition and understanding of what's happening. [Colab Link for this notebook](https://colab.research.google.com/github/nayyarv/ProbablyTensorFlow/blob/master/Bayesian_and_TFP_intro.ipynb)

## Disclaimer 

Tensorflow Probability is a new feature and is still under construction. It's very powerful and this notebook only covers the basics of both Bayesian Inference and Tensorflow Probability. There is still a lot of boilerplate which I expect to see less of in future releases. 

Additionally, I'm not the most experienced Tensorflow user, being more accustomed to pytorch (tensorflow feels more functional and pytorch more imperative/OO), so my code is unlikely to be efficent, or even good. I have strived for clarity and understanding, aiming this talk at relative newcomers to stats/programmning. Arguably, TFP is the wrong choice to introduce to beginners, but each of PyMC3 and STAN come with their own baggage too.


# Bayesian Resources

1. [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) is the best introductory text to Bayesian Inference. It's not maths heavy, but is very concept heavy.
2. [My Slide Deck on why you should care about Bayesian Inference](https://docs.google.com/presentation/d/e/2PACX-1vQMBGmSZA2GPuMWNz2Wt9UQAN4rGkU0kpfiTJMN-A4ra4-LRPGQIoDtEVvyTFbe5Ntytcx5D73QlAtv/pub?start=false&loop=false&delayms=3000)
3. [STAN](https://mc-stan.org/docs/2_18/stan-users-guide/index.html) and [PyMC3](https://docs.pymc.io/notebooks/api_quickstart.html) are much gentler introductions to Probabilistic/Bayesian Programming. They're much more mature and PyMC4 will be written with TFP as it's backend instead of theano.

