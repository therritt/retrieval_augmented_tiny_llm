# Overview
This Jupyter notebook is designed for the implementation and demonstration of various Retrieval Augmented Generation techniques for a small Large Language Model (LLM). It also contains code to preprocess and search the dataset of documents to be retrieved to augment the LLM.

# Requirements
Python 3.10 or higher
Jupyter Notebook or Colab to run .ipynb files

## Dataset

The dataset used in this project is a Computer Science Question/Answer dataset: https://huggingface.co/datasets/August4293/CS_QA

It is structured as question/answer pairs:
- question:
    - A string that indicates a question being asked to the LLM.
- answer:
    - A string representing an appropriate answer to the question

## Usage

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the `rag_for_small_llm.ipynb` notebook file in your IDE or Google Colab
4. Run the notebook cells in sequential order.