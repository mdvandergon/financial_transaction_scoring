# financial_transaction_scoring
Using graph embeddings and Tensorflow to predict AML fraud

Right now, I have a Colab that has a pretty basic model using an embedding of the transaction graph. This can run on a decent laptop. As I look through the simulated data, I might enhance the model; I haven't made a fraud-detection model before.

<a target="_blank" href="https://colab.research.google.com/drive/1RrgtwWHPih8V3wceJDG60FcbXwFzD8bI?usp=sharing"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>


### Data

I am using some data from the IBM AMLSim repo, which has several datasets pre-generated and some nice papers: 

https://github.com/IBM/AMLSim

As I familarized myself with this data, I found their wiki helpful.

### Predicted Variables
There are two targets of interest from the data on [Dropbox](https://www.dropbox.com/sh/l3grpumqfgbxqak/AAC8YT4fdn0AYKhyZ5b3Ax16a?dl=0):

1) IS_FRAUD: a binary label
2) ALERT_ID: a categorical label that's more descriptive

