# Language Model based on Transformer Architecture

This repository contains the code for creating and training a language model based on the Transformer architecture. The model is designed to generate responses in a chatbot-like manner. It can be trained using the **movie_lines.txt** and **movie_conversations.txt** files located in the **ChatBot_Dataset** directory.

## Dataset

The **ChatBot_Dataset** folder contains the necessary data files for training the language model. The file **movie_lines.txt** consists of individual replicas from different dialogs, and the **movie_conversations.txt** file provides the dialog context by grouping replicas into dialogs using special indexes.

## Model Architecture
The code in the **model.ipynb** notebook presents a language model with two encoders and two decoders. It also includes two head attention mechanisms for improved context understanding. However, you have the flexibility to modify the model's architecture according to your specific needs and capabilities by adjusting the parameters during model creation.

## Model Training
The notebook guides you through the steps of data preprocessing, model creation, training, and inference. By executing the code in the notebook, you can train the language model on the provided movie dialogue dataset.

## Inference
The code also includes an example of how to use the trained model for inference. Once the model is trained, you can input a prompt or a partial sentence, and the model will generate a coherent response based on its learned patterns and context.

Feel free to explore the **model.ipynb** notebook to understand the implementation details and experiment with different parameters, datasets, or modifications to the architecture.

Happy modeling and chatbot conversations!
