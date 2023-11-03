# README


OUTPUT-SCREENSHOTS:

![image](https://github.com/sarthak37/ml/assets/52873771/ac416014-2786-4797-893c-24e13593c35a)



1)This code is training a T5 model to perform English to Hinglish translation and then fine tune on custom dataset. Here’s a step-by-step explanation of what the code is doing:

2)Importing Necessary Libraries: The code starts by importing the necessary libraries from the transformers package1.

3)Loading the Model and Tokenizer: The code then loads the T5 model and its corresponding tokenizer1.

4)Loading the Dataset: The code loads a custom dataset which I uploaded on  Hugging Face.

5)Preparing the Training Data: The code prepares the training data by tokenizing the input and target sentences1.

6)Defining the Training Parameters: The code defines various training parameters such as the source and target languages, the maximum sequence length, and the number of training epochs1.

7)Preprocessing the Data: The code preprocesses the data by tokenizing the input and target sentences, adding the necessary prefixes, and handling padding and truncation1.

8)Training the Model: The code trains the model using the preprocessed data and the defined training parameters1.

9)Saving the Model: After training, the code saves the trained model1.

10)Testing the Model: Finally, the code tests the trained model by translating a sample sentence from English to Hinglish
