# deep-learning-challenge

# Overview

The purpose of this challenge was to create an algorithm using machine learning and with this algorithm, we should find the accuracy of the information given to us. After the first attempt, we must make the necessary modifications to the algorithm to achieve a minimum accuracy of 75%.

# Results

  - Data Preprocessing
      - The target variable is the 'IS_SUCCESSFUL'
        
        ![Screenshot 2024-04-29 at 5 35 26 PM](https://github.com/Ever30/deep-learning-challenge/assets/149534473/74a68fa9-d6cd-4dc3-b7c2-31ce4fdf87f7)
        
      - The variables that I removed from the input data because they are neither targets nor features were "EIN" and "NAME"

        ![Screenshot 2024-04-29 at 6 15 07 PM](https://github.com/Ever30/deep-learning-challenge/assets/149534473/81f2bef6-f67d-4cd9-940c-d4e74be50bd1)

      - The rest of the variables were taken into consideration for my model. 

  - Compiling, Training, and Evaluating the Model
      - In the first attempt, I used just two layers with 80 and 30 neurons and epochs = 100. At the end of this, I got an accuracy of .7301
      - In the following three attempts I modified different values in my algorithm, but despite that, I wasn't able to achieve an accuracy of 75%.

        - epoch = 100
          
        ![Screenshot 2024-04-29 at 5 54 13 PM](https://github.com/Ever30/deep-learning-challenge/assets/149534473/557b76a1-22f4-4864-82d4-ee64ec8dfe71)
   
        ![1](https://github.com/Ever30/deep-learning-challenge/assets/149534473/9a51dec1-6823-40ed-b92f-29626e4ab43e)


        - epoch = 150
          
        ![Screenshot 2024-04-29 at 5 54 21 PM](https://github.com/Ever30/deep-learning-challenge/assets/149534473/692f2902-a1c5-4762-a184-6d6443066aa4)
   
        ![2](https://github.com/Ever30/deep-learning-challenge/assets/149534473/3cf30ae7-df50-44d2-81b8-fc85d5791790)



        - epoch = 80
          
        ![Screenshot 2024-04-29 at 5 54 28 PM](https://github.com/Ever30/deep-learning-challenge/assets/149534473/a3ca79f4-f58a-4cae-b5ff-7f117a234024)
   
        ![3](https://github.com/Ever30/deep-learning-challenge/assets/149534473/47b6a15b-869f-47d6-b5f8-0576b8225955)



        

# Summary

At the end of all this I can say that although I didn't manage to obtain an accuracy of 75%, the final values were not very far from the desired result. I will recommend using another type of classification model to see if there are other better results. Probably it would be a good idea to try to create a function where the model finds the best number of layers and neurons, like the exercise call "Ins_AutoOptimization".


# Additional Information

- How to save neural network model to Google Drive
  
https://medium.com/@ml_kid/how-to-save-our-model-to-google-drive-and-reuse-it-2c1028058cb2

