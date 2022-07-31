# Neural Network Analysis

## Overview of Analysis:  

The purpose of this project was to introduce us to the Neural Networks and TensorFlow. Using TensorFlow and Python together, we were able to build a neural network that predicts the success of donations made to charity. 

## Results: 

- ### Data Preprocessing: 

    - I first started out by dropping "EIN" and "NAME" from our DataFrame. 

    ![EIN Name](/images/EIN%20Name.png)

    
    - Next, I used "IS_SUCCESSFUL" to determine if the charity donation was used in an effective manner. This is then considered as the target for the Neural Netwrok. This is also where i define my train, test, and split. 

    ![](/images/IS_SUCCESSFUL.png)

    - The image below then lays out the features of our model: 

    ![](/images/models.png)