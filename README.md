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

- ## Compiling, Training, and Evaluating the Model

    - ### neurons, layers, and activation functions. 
    
    - I started out using two hidden layers. Layer 1 with 100 neurons and layer 2 with 30 neurons. 

    ![](/images/n_1.png)

    - From there, I used three layers which had 90, 30, and 10 neurons starting from hidden layer 1 through 3. 

    ![](/images/n_2.png)

    - Finally, I used 3 layers once more but this time 110, 20, and 10 nuerons for hidden layers 1 through 3. 

    ![](/images/n_3.png)

    - Sadly, after testing the three seperate times, all three came back with an accuracy score of under 75% and around the accuracy as shown below. 

    ![](/images/accuracy.png)


## Summary 

The neural netwrokk failed to reach the targeted goal of 75% after three tries with variation in the hidden layers neurons. Because this is the case, we can say that our deep learning model is not outperforming. Instead of deeping learning for this data, we could have instead used a suprived machine learning script to try and get the data accuracy we wanted. Using RandomForestClassifiers and a few decision trees, i think we could have ended with the accuracy score we seeked. We then could have compaired the unsupervised script to our deep learning script to compare the two and maybe go in and make some adjustments to the nuerons in the hidden layers to get an accuracy score of 75% or higher. 

