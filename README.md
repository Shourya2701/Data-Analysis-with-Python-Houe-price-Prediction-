# Data-Analysis-with-Python

![1](https://user-images.githubusercontent.com/52822987/138602656-eaa4e9c6-cfeb-469e-87be-97f636d98d18.jpg)

# HOUSE PRICE PREDICTION

![Housing-price-prediction](https://user-images.githubusercontent.com/52822987/138602683-3053a749-5ee0-4125-a525-825050fee85c.png)

Given here is the example of how machine learning algorithms used to analyse and predict the rates of various houses. 

 # Procedure:
  
![1_W0V1hhp8jstY4orD1_hD9Q](https://user-images.githubusercontent.com/52822987/138603812-a73f86b7-768f-4d46-ab3a-d0710bd95e7b.jpeg)

 
In this repository, following steps are followed:

1. Data normalization
   ![Normalization-Formula](https://user-images.githubusercontent.com/52822987/138602805-1a140be3-a263-4fb2-9380-c8cdfaf5de21.jpg)

  Above formula is used to normalize the data, In our case of house price prediction, data is normalized using scikit learn library which in turn uses above formula to complete.

2. Train and Test split
   <img width="722" alt="3tHZF" src="https://user-images.githubusercontent.com/52822987/138602886-60f717e1-2c88-44d5-8c4f-30d90ecef4b2.png">
   
   We don't use whole data for training purpose only. To check the accuracy we used to split the data into training,testing and validation set. Again sklearn provides useful function to do so.

3. Create a neural network model
   
   ![download](https://user-images.githubusercontent.com/52822987/138602966-df707f05-b302-4ea7-bcee-3a857b547cf7.png)

    Neural network is created as shown above pictorically in the model.

4. Train the model to fit the dataset
   ![download (1)](https://user-images.githubusercontent.com/52822987/138603371-1672ebb2-e4ed-4f69-b105-41aabbbded27.png)
   Training the model to different dataset to have high accuracy. A machine learning training model is a process in which a machine learning (ML) algorithm is fed with      sufficient training data to learn from.

5. Evaluate the model
    ![evaluatingmlmodels](https://user-images.githubusercontent.com/52822987/138603665-e0d9ca09-5a0f-4c49-a103-ebdd4ecc6ded.png)

    Model is evaluated based on classification metrics
    # Classification metrics
      When performing classification predictions, there's four types of outcomes that could occur.

      True positives are when you predict an observation belongs to a class and it actually does belong to that class.
      True negatives are when you predict an observation does not belong to a class and it actually does not belong to that class.
      False positives occur when you predict an observation belongs to a class when in reality it does not.
      False negatives occur when you predict an observation does not belong to a class when in fact it does.
    
6. Visualize the predictions
   
   ![0_XT_vRCVjy0CYQY1i_](https://user-images.githubusercontent.com/52822987/138603725-b8cdd39c-3101-4fe4-8fd8-1556bd651e5c.png)

   This step is pictorial representation of outcome.
   
