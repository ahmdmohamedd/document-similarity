# Document Similarity Model

This project implements a document similarity model using TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity in Python. It allows users to compare the similarity of multiple text documents within a specified folder.

## Features

- Reads multiple text documents from a specified folder.
- Calculates document similarity using TF-IDF vectorization.
- Computes cosine similarity scores to quantify document similarity.
- Displays a similarity matrix for easy comparison of documents.

## Requirements

To run this project, you will need:

- Python 3.x
- Libraries:
  - pandas
  - scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas scikit-learn
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/document-similarity.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd document-similarity
   ```

3. Place your text documents (with `.txt` extension) in a designated folder.

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook document_similarity_model.ipynb
   ```

5. In the notebook, set the `folder_path` variable to the path of the folder containing your documents.

6. Run the cells to read the documents and calculate their similarity.

## Example

If your folder structure looks like this:

```
/path/to/your/documents/
    ├── document1.txt
    ├── document2.txt
    ├── document3.txt
```

Set the `folder_path` in the notebook to `'/path/to/your/documents/'`.

## Acknowledgements

- [scikit-learn](https://scikit-learn.org/stable/) for machine learning and data mining tools.
- [pandas](https://pandas.pydata.org/) for data manipulation and analysis.
```
