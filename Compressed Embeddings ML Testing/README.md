
# Batching Embedding Testing

## Overview

This Jupyter notebook demonstrates a process for generating text embeddings using OpenAI's embedding model. The notebook includes reading data from a CSV file, batching requests to the OpenAI API, and writing the results to a new CSV file.

## Steps

1. **Import Libraries**: 
    - Import necessary libraries including `csv`, `os`, `openai`, `random`, `numpy`, `pandas`, `matplotlib`, `seaborn`, and `sklearn`.

2. **Set API Key**:
    - Set your OpenAI API key in a .env file to initialize the OpenAI client.

3. **Define Input and Output Files**:
    - Specify the input and output CSV file paths.

4. **Define Batch Size**:
    - Set the batch size for embedding requests.

5. **Embed Text Batch Function**:
    - Define a function to embed a batch of texts using OpenAI's embedding model.

6. **Main Function**:
    - Read the CSV file.
    - Randomize the rows and select the first 1000.
    - Process addresses in batches.
    - Generate embeddings for each batch and combine them with the original CSV data.
    - Write the combined data to a new CSV file.

7. **Execution**:
    - Execute the main function to process the CSV file and generate embeddings.

## Requirements

- openai
- python-dotenv
- numpy
- pandas
- matplotlib
- seaborn
- sklearn

You can install the required packages using the following command:

```
pip install openai python-dotenv numpy pandas matplotlib seaborn sklearn
```

## Setting Up the .env File 

Create a '.env' file in the same directory as the Jupyter notebook and add the following:
```
OPENAI_API_KEY = Your API Key
```

All the CSV files used in the Jupyter notebook are included in this folder.
