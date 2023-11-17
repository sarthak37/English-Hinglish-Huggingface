# README


OUTPUT-SCREENSHOTS:

![image](https://github.com/sarthak37/English-Hinglish-Huggingface/assets/52873771/3a443892-6869-4908-a9b7-1401f3f15e5b)


![image](https://github.com/sarthak37/English-Hinglish-Huggingface/assets/52873771/55387605-d809-4b51-910b-e51a897db318)


![image](https://github.com/sarthak37/English-Hinglish-Huggingface/assets/52873771/a2982059-7dae-45ad-bd52-9ace24f7e44d)




1)This code is training a T5 model to perform English to Hinglish translation and then fine tune on custom dataset. Here’s a step-by-step explanation of what the code is doing:

2)Importing Necessary Libraries: The code starts by importing the necessary libraries from the transformers package1.

3)Loading the Model and Tokenizer: The code then loads the T5 model and its corresponding tokenizer.

4)Loading the Dataset: The code loads a custom dataset which I uploaded on  Hugging Face.

5)Preparing the Training Data: The code prepares the training data by tokenizing the input and target sentences.

6)Defining the Training Parameters: The code defines various training parameters such as the source and target languages, the maximum sequence length, and the number of training epochs.

7)Preprocessing the Data: The code preprocesses the data by tokenizing the input and target sentences, adding the necessary prefixes, and handling padding and truncation.

8)Training the Model: The code trains the model using the preprocessed data and the defined training parameters.

9)Saving the Model: After training, the code saves the trained model.

10)Testing the Model: Finally, the code tests the trained model by translating a sample sentence from English to Hinglish
