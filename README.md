# WordWizardAI
WordWizardAI is a sophisticated LSTM-based deep learning model designed to predict the next word in a sequence and generate coherent sentences. This project utilizes the Sherlock Holmes dataset, sourced from Kaggle, to train the model on textual data, enabling it to capture language patterns effectively. The project demonstrates the use of an interactive feature where the model predicts and displays the next probable word after user input, simulating real-time predictive text generation.

## Features
### LSTM Model: 
The core of the project is an LSTM (Long Short-Term Memory) model, known for handling sequential data like text, which is ideal for this word prediction task.
The model is structured with three layers :
### Embedding Layer: 
Transforms words into dense vectors of fixed size, which the LSTM layer processes.
### LSTM Layer: 
Captures long-term dependencies and intricate patterns within the dataset.
### Dense Layer: 
Outputs the probability distribution across potential next words.
### Sherlock Holmes Dataset: 
Trained on a large corpus obtained through the Kaggle API, the model learned to understand language constructs from the famous Sherlock Holmes texts.
Supervised Learning: The problem is treated as a multiclass classification task, with Adam as the optimizer and categorical cross-entropy as the loss function.
Interactive User Input: After training, users can provide input, and the model generates the next probable word with a slight delay, enhancing user interaction.
## Model Performance
Achieved an impressive 88% accuracy during training.
Real-time word prediction functionality for interactive engagement with users.




