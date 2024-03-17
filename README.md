# Next-Word-Prediction-Analyzing-the-Shakespearean-Sonnets-Dataset

# Instructions:
Here's the list of tasks performed in the provided code:

1. **Importing Libraries**: Importing necessary libraries such as NumPy, Matplotlib, and TensorFlow.
2. **Downloading Data**: Downloading the Shakespeare Sonnets Dataset using the `gdown` library.
3. **Reading Data**: Reading the downloaded data file and converting it to lowercase.
4. **Tokenizing the Text**: Using the Tokenizer class from Keras to tokenize the text corpus and determine the total number of unique words.
5. **Generating n-gram Sequences**: Implementing a function to generate n-gram sequences from the tokenized corpus.
6. **Padding Sequences**: Implementing a function to pad the generated n-gram sequences to the maximum sequence length.
7. **Splitting Data into Features and Labels**: Creating a function to split the padded n-gram sequences into features and one-hot encoded labels.
8. **Creating the Model**: Implementing a function to create a text generation model using Keras with an embedding layer, bidirectional LSTM layer, and dense output layer.
9. **Training the Model**: Training the created model on the features and labels data.

Each task contributes to the overall process of building a model to predict the next word in a text sequence based on Shakespeare's sonnets dataset.

# Screenshorts:
![accuracy](https://github.com/ArsalMirza007/Next-Word-Prediction-Analyzing-the-Shakespearean-Sonnets-Dataset/assets/121928372/15307a2e-d378-4709-a773-b7434cde9cd6)
![loss](https://github.com/ArsalMirza007/Next-Word-Prediction-Analyzing-the-Shakespearean-Sonnets-Dataset/assets/121928372/43a996e8-9f67-4e09-9e4c-aded38d09234)
![Screenshot (45)](https://github.com/ArsalMirza007/Next-Word-Prediction-Analyzing-the-Shakespearean-Sonnets-Dataset/assets/121928372/3d574f2a-e630-4154-bf21-65b70629a0d1)
