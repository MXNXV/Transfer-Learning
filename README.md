Use transfer learning for large image classification, going through these steps:

- Take at least 100 images per class with at least 3 classes using your phone/camera (e.g. take photos of different types of trees, flowers or animals). Display 5 examples from each class

- Split the images into a training set, a validation set, and a test set.

- Build the input pipeline, including the appropriate preprocessing operations, and add data augmentation.
- Fine-tune a pretrained model of your choice on this dataset (the one you created in part 3). Report classification accuracy and give a few examples of correct/incorrect classification (show a few images that were correctly/incorrectly classified). 
- Train from scratch (without pretraining) a deep neural network that contains convolutional layers on this dataset (the one you created in part 3). Report classification accuracy and give a few examples of correct/incorrect classification (show a few images that were correctly/incorrectly classified). Note: The objective of this question is to illustrate that training deep networks from scratch requires a lot of data so it is ok if your classification accuracy is low.

- Create your own dataset for text classification. It should contain at least 1000 words in total and at least two categories with at least 100 examples per category. You can create it by scraping the web or using some of the documents you have on your computer (do not use anything confidential) or ChatGPT. 
- Split the dataset into training (at least 160examples) and test (at least 40 examples) sets.
  
- Fine tune a pretrained language model capable of generating text (e.g., GPT) that you can take from the Hugging Face Transformers library with the dataset your created (this tutorial could be very helpful: https://huggingface.co/docs/transformers/training). Report the test accuracy. Discuss what could be done to improve accuracy
