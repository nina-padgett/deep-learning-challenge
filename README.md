Neural Network Model Report

Overview
Alphabet Soup is a nonprofit foundation that is trying to determine which of their applicants
are more likely to succeed. I will apply machine learning and neural networks knowledge to analyze
a dataset of more than 34,000 organizations that Alphabet Soup has previously supported. 

Results
  Data Preprocessing
    - Application Type and Classifications were the model's targets.
    - Is Successful was the model's feature.
    - EIN and Name should be removed from the input data because they are neither targets nor features.

  Compiling, Training and Evaluating the Model
    - I tried defining the model with 4 and 5 node layers. After testing and finding the model's
      accuracy rate declined after adding a 5th layer, I chose to keep it at 4 layers.
      After more testing, I chose 120, 80, 50 and 10 neurons for each layer respectively.
      I chose random numbers for each test and listed them in descending order each time to find
      if they made an impact.
    - I was not able to achieve the target model performance. 
    - I first added the 5th node layer and changed the number of neurons for each node layer. 
      Those changes caused the accuracy rate to decrease. I then removed the 5th layer and added the 
      Name column back into the dataset. This further decreased the accuracy rate. For the last attempt
      at changing the number of neurons for 2 of the layers  

Summary 
My attempts at improving the accuracy rate of the model were not successful as planned. To possibly improve it, I recommend continuing to alter the node layers and number of neurons. Applying a different model may also improve it. 
