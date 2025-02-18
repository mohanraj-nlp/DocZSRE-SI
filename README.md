# DocZSRE-SI
Code for Document-Level Zero-Shot Relation Extraction with Entity Side Information (DocZSRE-SI)
## Dependencies

Python 3.10

This project utilizes the following libraries:

- **Pytorch**: A powerful deep learning library used for building and training neural networks.
- **Transformers**: A library by Hugging Face, providing state-of-the-art pre-trained models for Natural Language Processing (NLP).
- **Langchain**: A framework for building applications with LLMs (Large Language Models).
- **Numpy**: A package for scientific computing with Python, widely used for handling large, multi-dimensional arrays and matrices.
## Instruction

Follow these steps to get the project up and running:

1. Clone this repository to your local machine using the following command.
2. To install the required dependencies, run the following command:
  ```bash
  pip install -r requirements.txt
  ```
3. Create Folder for the Dataset:
  - DocRED: Download the dataset (https://github.com/thunlp/DocRED)
  - REDocRED: Download the dataset (https://github.com/tonytan48/Re-DocRED)
  - MEN-Dataset: Download the dataset (https://github.com/mohanraj-nlp/MEN-Dataset)
    - The provided repository only provides 200 Articles. The remaining 200 has yet to be published by author.

4. For Generating Side-Information Module (Execute following order):
    - Run Jupyter Notebook: **Run Description Generation**
      - Open the Jupyter Notebook.
      - Execute all cells to generate the required descriptions.

    - Run Jupyter Notebook: **Run Description Generation**
      - After completing the first notebook, open the second Jupyter Notebook.
      - Execute all cells to finalize the description generation process.

5. For Zero-Shot Relation Extraction Module:
    - Run: `[DocRED] Zero-Shot Relation Extraction Module.ipynb`
      - For DocRED Dataset Only.
      - Execute the Evaluation Section in Jupyter Notebook.

    - Run: `[RE-DocRED] Zero-Shot Relation Extraction Module.ipynb`
      - For RE-DocRED Dataset Only.
      - Execute the Evaluation Section in Jupyter Notebook.

    - Run: `[MEN-Dataset] Zero-Shot Relation Extraction Module.ipynb`
      - For MEN-Dataset Dataset Only.
      - Execute the Evaluation Section in Jupyter Notebook.