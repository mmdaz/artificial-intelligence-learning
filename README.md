# In the name of God
 ## Artificial-intelligence-learning

  ### Summary of Hands-on-machine-Gueron book.

    There is a pdf version of this book in this repository and in books folder.

  lets start : 

  #### Chapter I : The machine learning landscape.
    An intuduction for Machine Learning : 
        Machine learning is the field of study that gives the computers
        the ability to learn without being explictly programmed.
    
    In fact we have a problem and training data and our machine learning programm
    learn from training data to solve and predict for new data.
        read the spam email example of page 17
    
    
    Machine learning is great for:
        * Problenms for each existing solutions reqiure long list of rules (spam email problem)
        * Complex problems for which there is no good solution at all using traditional approach.
        * A ML system can adapt to new data.(Fluctuiting environments)
        * Getting insights from a big data.
    
    Types of ML Systems:
        * Whether or not they are trained with human supervision:
            + Supervised Learning
            + Unsupervised Learning
            + Semisupervised Learning
            + Reinforcement Learning
                . Supervised Learning:
                    We have labled data to train.
                    It's tipical task is classification of data (see Figure 1-5)
                    for example : we have a set of features of a car (mileage, age, brand, etc)
                    and their prices and we want to predict price of other cars.
                . Unsupervised Learning:
                    We have unlabed data.
                    Tasks:
                        1.Demonsionality reduction : simplify data without losing data.
                        for example : since a car's mileage may be correlated with its age and we can merge them in to 
                        feature and then feed into supervised learning algorithm.
                        This is called feature extraction.
                        
                        2.Anomaly detection : say us that a new instance is normal(usual) or not.(see Figure 1-10)
                . Semisupervised Learning:
                    It is combination of unsupervised and supervised learning.
                    For example google photos service that it automatically recognizes that a same person A shows up in 
                    photos 1, 2, 4.
                    and system set just one lable per person to tell you who is he/she.
                