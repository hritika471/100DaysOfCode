## ML Types On The Basis Of Model Training At Production

Hello troubleshooters! this article is a progressive part of the 100days of machine learning wherein in previous three days I have talked about what is ML, Types of ml and some more interesting stuff do check out them too. 
Being a machine learning enthusiast it excites me every freaking time about how we would be deploying the machine model from the production phase to an end user but the question before that pops up is how actually ML models are classified on the basis of training at production level. Basically this classification derives two types in general , one is batch learning and the other one is online learning. In order to simplify this let's dig into the main ideology behind this question inch by inch.

#  BATCH  LEARNING / OFFLINE  LEARNING

In batch learning, the system is incapable of learning incrementally: it must be trained using all the available data. This will generally take a lot of time and computing resources, so it is typically done offline.
If you want a batch learning system to know about new data (such as a new type of spam), you need to train a new version of the system from scratch on the full dataset (not just the new data, but also the old
data), then stop the old system and replace it with the new one.
Fortunately, the whole process of training, evaluating, and launching a Machine Learning system can be automated fairly easily, so even a batch learning system can adapt to change.

## PROBLEM WITH BATCH LEARNING 
There are two main challenges that arise when thinking about applying machine learning to batch manufacturing data. The first is making sure that you’re validating your models correctly, and the second is handling the actual model training using batched data.

### DISADVANTAGES OF BATCH LEARNING 
1. Lots of data 
2. Hardware limitation 
3. Availability  

This article majorly was about just the one type that was batch learning upcoming article would be more focused about online learning. I hope till here i've made things simpler see ya on the next article with some more interesting information to explore within.

**Read till here thanks a bunch:)**