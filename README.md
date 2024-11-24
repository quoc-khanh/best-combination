# best-combination
I, personally, did several tests. Using several credit scoring datasets, balancing techniques, classifying models, this github is intented to find the best combination of balancing technique and model.

I used the model cWGAN to represent Neural Network-based technique. I am very appreciate the work and gave credit for the author in S0957417421000233.txt

Kaggle is used as it's free and allows five kernels running. 

The problem when working with credit scoring datasets is high imbalance rate, which is usually solved with various techniques, most commonly is SMOTE (Synthetic Minority Over-sampling Technique), but is it really effectively handling our problem? This github did many tests with a wide ranges of data balancing techniques, comfirming their effectiveness as well as find the best balancing techniques ever. The kaggle for this github is in https://www.kaggle.com/code/trnmqkhnh/best-combination.

The structure of this github:

--main

 | --First step
 
 | --Second step
 
 | --Second step with cWGAN

Pipeline:
First we did tests to selection models used in the next step. Code in First step.
Second we did test with a lot of balancing techniques, used the score to compare and find the best combination. Code in Second step and Second step with cWGAN.
Third we have the experimental results in excel in result csv.xlsx, Result.pdf.
